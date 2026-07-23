# SpiderFoot

## Descripción

**SpiderFoot** es una herramienta de automatización **OSINT** de código abierto diseñada para recopilar información sobre personas, dominios, direcciones IP, correos electrónicos y organizaciones a partir de cientos de fuentes públicas.

Su principal objetivo es automatizar el proceso de reconocimiento, reduciendo el tiempo necesario para obtener información y facilitando la correlación de los datos recopilados. Es ampliamente utilizada por analistas OSINT, pentesters, investigadores digitales y equipos de respuesta ante incidentes.

---

# ¿Cómo funciona?

SpiderFoot utiliza un sistema basado en **módulos** que consultan diferentes fuentes OSINT y servicios externos.

El usuario define un objetivo (por ejemplo, un dominio o una dirección IP) y selecciona los módulos que desea ejecutar. Cada módulo recopila información específica y puede generar nuevos datos que serán procesados automáticamente por otros módulos.

Los resultados se almacenan y se presentan mediante tablas, gráficos y relaciones entre entidades.

---

# Funciones principales

SpiderFoot permite:

- Descubrir subdominios.
- Buscar direcciones IP.
- Obtener registros DNS.
- Localizar correos electrónicos.
- Analizar certificados TLS.
- Buscar filtraciones de datos.
- Identificar tecnologías web.
- Correlacionar información automáticamente.

---

# Información disponible

Dependiendo del objetivo analizado, SpiderFoot puede obtener:

- Dominios.
- Subdominios.
- Direcciones IP.
- Registros DNS.
- Correos electrónicos.
- Certificados digitales.
- URLs.
- Tecnologías utilizadas.
- Redes sociales.
- Filtraciones de datos.
- Información WHOIS.
- ASN.

---

# Objetivos de análisis

SpiderFoot admite diferentes tipos de objetivos, entre ellos:

- Dominios.
- Direcciones IP.
- URLs.
- Direcciones de correo.
- Nombres de usuario.
- Empresas.
- Personas.
- Hashes.

---

# Módulos

SpiderFoot incorpora cientos de módulos especializados que consultan distintas fuentes OSINT.

Algunos módulos permiten:

- Consultar motores de búsqueda.
- Analizar DNS.
- Buscar certificados.
- Consultar APIs públicas.
- Analizar redes sociales.
- Buscar información en filtraciones de datos.
- Obtener información WHOIS.

Muchos módulos requieren una clave API para acceder a determinados servicios.

---

# Uso básico

Iniciar SpiderFoot:

```bash
python3 sf.py
```

Acceder a la interfaz web desde el navegador y crear un nuevo análisis indicando:

- Objetivo.
- Tipo de objetivo.
- Módulos a ejecutar.

Una vez iniciado el escaneo, SpiderFoot recopilará la información automáticamente.

---

# Usos en OSINT

SpiderFoot resulta especialmente útil para:

- Investigación de organizaciones.
- Descubrimiento de infraestructura.
- Reconocimiento de dominios.
- Investigación de personas.
- Auditorías de seguridad.
- Threat Intelligence.
- Automatización de investigaciones.

---

# Casos de uso

## Reconocimiento

Obtener una visión completa de la infraestructura pública de una organización.

---

## Investigación corporativa

Descubrir dominios, subdominios, correos y tecnologías utilizadas por una empresa.

---

## Pentesting

Recopilar información antes de realizar pruebas de seguridad.

---

## Threat Intelligence

Relacionar indicadores de compromiso procedentes de diferentes fuentes.

---

# Integración con otras herramientas

SpiderFoot puede complementarse con:

- Maltego
- Amass
- Recon-ng
- BBOT
- theHarvester
- Shodan
- Censys
- VirusTotal
- Hunter
- SecurityTrails
- Intelligence X

---

# Instalación

SpiderFoot puede instalarse mediante Git:

```bash
git clone https://github.com/smicallef/spiderfoot.git
```

También está disponible en Docker y en diversas distribuciones orientadas a ciberseguridad.

---

# Automatización

SpiderFoot permite:

- Ejecutar análisis automáticos.
- Programar investigaciones.
- Integrarse mediante API.
- Exportar resultados.
- Generar informes.
- Procesar múltiples objetivos.

---

# Ventajas

- Código abierto.
- Gran cantidad de módulos.
- Interfaz web intuitiva.
- Automatización avanzada.
- Compatible con numerosas APIs.
- Exportación de resultados.

---

# Limitaciones

- Algunos módulos requieren claves API.
- Los análisis completos pueden tardar varios minutos.
- La cantidad de información depende de las fuentes consultadas.
- Algunas funciones avanzadas están disponibles únicamente en SpiderFoot HX (versión comercial).

---

# Buenas prácticas

- Definir claramente el objetivo antes de iniciar el análisis.
- Ejecutar únicamente los módulos necesarios para reducir el tiempo de escaneo.
- Verificar la información obtenida con otras herramientas OSINT.
- Mantener actualizadas las claves API utilizadas.
- Documentar todos los resultados obtenidos.

---

# Caso práctico

**Objetivo:** Analizar un dominio corporativo.

Dominio:

```text
empresa.com
```

Información esperada:

- Subdominios.
- Direcciones IP.
- Registros DNS.
- Correos electrónicos.
- Certificados TLS.
- Tecnologías detectadas.
- Filtraciones conocidas.
- Información WHOIS.
- Relaciones entre activos.

SpiderFoot mostrará toda la información en una interfaz gráfica con tablas y relaciones entre los distintos elementos descubiertos.

---

# Resumen

SpiderFoot es uno de los frameworks de automatización OSINT más completos disponibles. Gracias a su arquitectura modular, su interfaz web y su capacidad para consultar cientos de fuentes públicas, permite realizar investigaciones rápidas y estructuradas sobre dominios, personas, organizaciones e infraestructuras, convirtiéndose en una herramienta imprescindible para analistas OSINT y profesionales de la ciberseguridad.