# Amass

## Descripción

**OWASP Amass** es una herramienta de reconocimiento y enumeración de activos desarrollada por la **OWASP Foundation**. Está especializada en el descubrimiento de subdominios, infraestructura de red y relaciones entre activos públicos de una organización.

Es una de las herramientas más utilizadas durante la fase de **reconocimiento (Reconnaissance)** en auditorías de seguridad, pentesting e investigaciones OSINT, ya que combina técnicas de enumeración pasiva y activa para obtener la mayor cantidad posible de información.

---

# ¿Cómo funciona?

Amass consulta múltiples fuentes públicas de información y realiza diferentes técnicas de enumeración para descubrir activos asociados a un dominio.

Entre ellas se encuentran:

- Consultas DNS.
- Certificados TLS.
- Motores de búsqueda.
- Bases de datos OSINT.
- APIs públicas.
- ASN (Autonomous System Number).
- Registros WHOIS.

Posteriormente relaciona toda la información obtenida para generar un mapa de la infraestructura.

---

# Funciones principales

Amass dispone de varios modos de funcionamiento:

- Enumeración pasiva.
- Enumeración activa.
- Descubrimiento de subdominios.
- Mapeo de infraestructura.
- Visualización de relaciones.
- Exportación de resultados.

---

# Información disponible

Dependiendo del dominio analizado, Amass puede obtener:

- Subdominios.
- Direcciones IP.
- Servidores DNS.
- Registros MX.
- ASN.
- Bloques de red.
- Certificados TLS.
- Servidores web.
- Relaciones entre activos.

---

# Usos en OSINT

Amass resulta especialmente útil para:

- Descubrir subdominios.
- Analizar la infraestructura de una organización.
- Obtener información DNS.
- Relacionar activos públicos.
- Complementar investigaciones de reconocimiento.
- Preparar auditorías de seguridad.

---

# Modos de funcionamiento

## Enumeración pasiva

Consulta únicamente fuentes OSINT sin interactuar directamente con el dominio objetivo.

Ejemplo:

```bash
amass enum -passive -d empresa.com
```

---

## Enumeración activa

Realiza consultas DNS adicionales para ampliar los resultados.

Ejemplo:

```bash
amass enum -active -d empresa.com
```

---

## Descubrimiento de subdominios

Obtiene todos los subdominios públicos encontrados para un dominio.

Ejemplo:

```bash
amass enum -d empresa.com
```

---

## Visualización

Los resultados pueden exportarse para crear mapas de relaciones entre activos.

---

# Casos de uso

## Reconocimiento

Descubrir todos los activos públicos pertenecientes a una organización.

---

## Pentesting

Obtener una visión completa de la superficie de ataque antes de realizar pruebas de seguridad.

---

## Investigación OSINT

Relacionar dominios, direcciones IP y servidores asociados a una empresa.

---

## Gestión de activos

Detectar infraestructuras públicas olvidadas o mal documentadas.

---

# Integración con otras herramientas

Amass suele combinarse con:

- theHarvester
- SpiderFoot
- BBOT
- Recon-ng
- Maltego
- Shodan
- Censys
- SecurityTrails
- DNSDumpster
- crt.sh

---

# Instalación

En sistemas Linux puede instalarse mediante Go:

```bash
go install github.com/owasp-amass/amass/v4/...@master
```

También está disponible en diversas distribuciones orientadas a ciberseguridad, como Kali Linux.

---

# API y automatización

Amass permite:

- Exportar resultados en distintos formatos.
- Automatizar análisis mediante scripts.
- Integrarse con otras herramientas de reconocimiento.
- Procesar grandes cantidades de dominios.

---

# Ventajas

- Código abierto.
- Muy preciso.
- Gran número de fuentes OSINT.
- Excelente descubrimiento de subdominios.
- Compatible con automatización.
- Muy utilizado en auditorías profesionales.

---

# Limitaciones

- Algunas fuentes requieren claves API.
- Los análisis completos pueden tardar varios minutos.
- El modo activo genera tráfico hacia el objetivo.
- Requiere conocimientos básicos de línea de comandos.

---

# Buenas prácticas

- Comenzar con una enumeración pasiva.
- Verificar los resultados con otras herramientas.
- Documentar todos los activos encontrados.
- Mantener actualizadas las APIs utilizadas.
- Ejecutar análisis periódicos para detectar nuevos activos.

---

# Caso práctico

**Objetivo:** Descubrir la infraestructura pública de una organización.

Consulta:

```bash
amass enum -d empresa.com
```

Información esperada:

- Subdominios.
- Direcciones IP.
- Servidores DNS.
- ASN.
- Certificados.
- Registros DNS.
- Relaciones entre activos.

---

# Resumen

OWASP Amass es una de las herramientas de reconocimiento más potentes del ecosistema OSINT y la ciberseguridad. Gracias a su capacidad para descubrir subdominios, analizar infraestructura y correlacionar información procedente de múltiples fuentes públicas, constituye una herramienta imprescindible para auditorías de seguridad, pentesting e investigaciones de inteligencia sobre organizaciones y activos en Internet.