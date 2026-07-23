# theHarvester

## Descripción

**theHarvester** es una herramienta de **OSINT** especializada en la recopilación de información pública sobre dominios, organizaciones y personas. Está orientada principalmente al descubrimiento de direcciones de correo electrónico, subdominios, hosts, direcciones IP y otra información útil durante la fase de reconocimiento.

Es una de las herramientas más utilizadas por analistas de seguridad y pentesters debido a su sencillez, rapidez y compatibilidad con numerosas fuentes OSINT.

---

# ¿Cómo funciona?

theHarvester consulta diferentes motores de búsqueda, servicios OSINT y APIs públicas para recopilar información relacionada con un dominio o una organización.

La herramienta automatiza el proceso de búsqueda y presenta los resultados de forma estructurada, facilitando el análisis de la información obtenida.

Dependiendo de la fuente utilizada, puede descubrir información que no es fácilmente localizable mediante búsquedas manuales.

---

# Funciones principales

theHarvester permite:

- Buscar direcciones de correo electrónico.
- Descubrir subdominios.
- Enumerar hosts.
- Obtener direcciones IP.
- Consultar registros DNS.
- Buscar empleados públicos.
- Recopilar información desde múltiples fuentes.

---

# Información disponible

Dependiendo del objetivo analizado y de las fuentes utilizadas, puede obtener:

- Correos electrónicos.
- Subdominios.
- Hosts.
- Direcciones IP.
- Registros DNS.
- URLs.
- Servidores.
- ASN.
- Información pública relacionada con el dominio.

---

# Fuentes compatibles

theHarvester puede consultar numerosas fuentes, entre ellas:

- Google.
- Bing.
- DuckDuckGo.
- Yahoo.
- Baidu.
- Shodan.
- Censys.
- Hunter.
- SecurityTrails.
- crt.sh.
- DNSDumpster.
- VirusTotal.

Algunas fuentes requieren una clave API para acceder a todas sus funciones.

---

# Uso básico

Buscar información utilizando todas las fuentes disponibles:

```bash
theHarvester -d empresa.com -b all
```

Buscar únicamente con Bing:

```bash
theHarvester -d empresa.com -b bing
```

Guardar los resultados en un archivo HTML:

```bash
theHarvester -d empresa.com -b all -f informe
```

---

# Usos en OSINT

theHarvester resulta especialmente útil para:

- Investigación de organizaciones.
- Descubrimiento de correos electrónicos.
- Enumeración de subdominios.
- Reconocimiento de infraestructura.
- Auditorías de seguridad.
- Preparación de pruebas de penetración.

---

# Casos de uso

## Reconocimiento

Obtener información pública antes de realizar una auditoría de seguridad.

---

## Investigación corporativa

Descubrir empleados, direcciones de correo y activos públicos asociados a una empresa.

---

## Pentesting

Identificar posibles objetivos para una auditoría autorizada.

---

## OSINT

Complementar investigaciones con información procedente de diferentes motores de búsqueda y servicios públicos.

---

# Integración con otras herramientas

theHarvester suele utilizarse junto con:

- Amass
- SpiderFoot
- Recon-ng
- BBOT
- Maltego
- Hunter
- Shodan
- Censys
- SecurityTrails
- VirusTotal

La combinación de estas herramientas permite obtener una visión mucho más completa del objetivo.

---

# Instalación

En distribuciones como Kali Linux suele venir preinstalado.

También puede instalarse desde GitHub:

```bash
git clone https://github.com/laramies/theHarvester.git
```

O mediante `pip`:

```bash
pip install theHarvester
```

---

# Automatización

theHarvester permite:

- Automatizar búsquedas desde scripts.
- Exportar resultados.
- Integrarse en flujos de reconocimiento.
- Consultar múltiples fuentes de forma simultánea.

---

# Ventajas

- Código abierto.
- Fácil de utilizar.
- Muy rápido.
- Compatible con numerosas fuentes OSINT.
- Exportación de resultados.
- Muy utilizado en auditorías de seguridad.

---

# Limitaciones

- Algunas fuentes requieren claves API.
- La cantidad de información depende de la disponibilidad pública.
- Algunos motores limitan el número de consultas.
- No garantiza encontrar toda la información existente.

---

# Buenas prácticas

- Utilizar varias fuentes para obtener mejores resultados.
- Complementar la información con otras herramientas OSINT.
- Verificar los datos obtenidos antes de utilizarlos.
- Respetar los límites de uso de las APIs.
- Documentar toda la información recopilada durante la investigación.

---

# Caso práctico

**Objetivo:** Obtener información pública sobre un dominio.

Consulta:

```bash
theHarvester -d empresa.com -b all
```

Información esperada:

- Direcciones de correo electrónico.
- Subdominios.
- Hosts.
- Direcciones IP.
- Registros DNS.
- Información procedente de diferentes motores de búsqueda.

Los resultados pueden exportarse posteriormente para su análisis o integrarse con otras herramientas OSINT.

---

# Resumen

theHarvester es una de las herramientas clásicas de reconocimiento dentro del ecosistema OSINT. Gracias a su capacidad para consultar múltiples fuentes públicas y recopilar información sobre dominios, correos electrónicos, subdominios e infraestructura, constituye una herramienta imprescindible para la fase de reconocimiento en auditorías de seguridad, investigaciones digitales y pruebas de penetración.