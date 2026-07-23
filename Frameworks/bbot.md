# BBOT

## Descripción

**BBOT (Bighuge BLS OSINT Tool)** es un framework de reconocimiento y automatización OSINT de código abierto diseñado para descubrir activos e infraestructura de una organización. Utiliza una arquitectura modular que permite recopilar información desde múltiples fuentes y correlacionar automáticamente los resultados.

Es una herramienta muy utilizada en fases de reconocimiento de auditorías de seguridad y pentesting, ya que automatiza gran parte del proceso de recopilación de información.

---

# ¿Cómo funciona?

BBOT ejecuta diferentes módulos que consultan fuentes OSINT, APIs públicas y servicios de reconocimiento para obtener información relacionada con un objetivo.

Durante el análisis, la herramienta relaciona automáticamente los datos obtenidos y puede lanzar nuevos módulos a medida que descubre información adicional.

Esto permite ampliar el alcance de la investigación de forma progresiva.

---

# Funciones principales

BBOT ofrece múltiples capacidades de reconocimiento, entre ellas:

- Descubrimiento de subdominios.
- Enumeración DNS.
- Resolución de direcciones IP.
- Análisis de certificados TLS.
- Búsqueda de URLs.
- Descubrimiento de servicios.
- Correlación automática de información.
- Exportación de resultados.

---

# Información disponible

Dependiendo del objetivo analizado, BBOT puede obtener:

- Dominios.
- Subdominios.
- Direcciones IP.
- Registros DNS.
- Certificados digitales.
- URLs.
- Puertos abiertos.
- Tecnologías utilizadas.
- ASN.
- Información WHOIS.

---

# Usos en OSINT

BBOT resulta especialmente útil para:

- Reconocimiento de organizaciones.
- Descubrimiento de activos expuestos.
- Enumeración de subdominios.
- Análisis de infraestructura.
- Automatización de investigaciones.
- Preparación de auditorías de seguridad.

---

# Módulos

BBOT utiliza una arquitectura basada en módulos que pueden ejecutarse de forma individual o combinada.

Algunos módulos permiten:

- Consultar motores de búsqueda.
- Analizar DNS.
- Obtener certificados.
- Consultar APIs OSINT.
- Analizar servicios web.
- Descubrir nuevos objetivos automáticamente.

---

# Uso básico

Escaneo sencillo de un dominio:

```bash
bbot -t empresa.com
```

Especificar módulos concretos:

```bash
bbot -t empresa.com -m subdomain-enum
```

Exportar resultados:

```bash
bbot -t empresa.com -o resultados/
```

---

# Casos de uso

## Reconocimiento

Obtener una visión general de la infraestructura pública de una organización.

---

## Pentesting

Descubrir activos expuestos antes de realizar pruebas de seguridad.

---

## Investigación OSINT

Relacionar dominios, IPs y servicios asociados a un objetivo.

---

## Inventario de activos

Detectar sistemas olvidados o poco documentados.

---

# Integración con otras herramientas

BBOT suele utilizarse junto con:

- Amass
- SpiderFoot
- Recon-ng
- theHarvester
- Shodan
- Censys
- SecurityTrails
- DNSDumpster
- VirusTotal
- Maltego

---

# Instalación

BBOT puede instalarse mediante **pip**:

```bash
pip install bbot
```

También es posible instalar la versión más reciente desde su repositorio oficial.

---

# Automatización

Una de las principales ventajas de BBOT es su capacidad para automatizar investigaciones.

Permite:

- Ejecutar múltiples módulos simultáneamente.
- Integrarse en scripts.
- Exportar resultados en diferentes formatos.
- Automatizar tareas repetitivas.
- Procesar varios objetivos de forma secuencial.

---

# Ventajas

- Código abierto.
- Arquitectura modular.
- Automatización avanzada.
- Fácil integración con otras herramientas.
- Descubrimiento automático de nuevos activos.
- Exportación de resultados.

---

# Limitaciones

- Requiere conocimientos básicos de terminal.
- Algunas funciones utilizan APIs externas.
- Los análisis completos pueden tardar varios minutos.
- La cantidad de información obtenida depende de las fuentes disponibles.

---

# Buenas prácticas

- Ejecutar primero un reconocimiento básico.
- Complementar los resultados con otras herramientas OSINT.
- Documentar todos los activos descubiertos.
- Actualizar periódicamente los módulos.
- Respetar siempre el alcance autorizado de la investigación.

---

# Caso práctico

**Objetivo:** Analizar la infraestructura pública de una empresa.

Consulta:

```bash
bbot -t empresa.com
```

Información esperada:

- Subdominios.
- Direcciones IP.
- DNS.
- Certificados TLS.
- URLs.
- Tecnologías detectadas.
- Relaciones entre activos.

---

# Resumen

BBOT es un framework moderno de automatización OSINT orientado al reconocimiento y descubrimiento de activos en Internet. Gracias a su arquitectura modular y a su capacidad para correlacionar información obtenida desde múltiples fuentes, constituye una herramienta muy útil para analistas OSINT, pentesters y equipos de ciberseguridad que necesitan automatizar investigaciones sobre dominios e infraestructuras públicas.