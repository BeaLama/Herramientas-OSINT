# FOCA

## Descripción

**FOCA (Fingerprinting Organizations with Collected Archives)** es una herramienta desarrollada por **INCIBE** y **ElevenPaths** para la recopilación y análisis de metadatos en documentos públicos. Está orientada al reconocimiento de organizaciones, permitiendo descubrir información sensible publicada de forma involuntaria.

Es una herramienta muy utilizada en **OSINT**, auditorías de seguridad y pruebas de penetración para identificar infraestructura, usuarios y tecnologías empleadas por una empresa.

---

# ¿Cómo funciona?

FOCA busca documentos públicos asociados a un dominio utilizando diferentes motores de búsqueda y repositorios.

Una vez descargados, extrae automáticamente sus metadatos para identificar información relevante sobre la organización, como usuarios, software utilizado, servidores o rutas internas.

---

# Funciones principales

FOCA permite:

- Buscar documentos públicos.
- Extraer metadatos.
- Analizar dominios.
- Obtener información DNS.
- Consultar registros WHOIS.
- Identificar tecnologías.
- Generar informes.

---

# Información disponible

Dependiendo de los documentos encontrados, puede obtener:

- Autores.
- Nombres de usuario.
- Correos electrónicos.
- Software utilizado.
- Sistema operativo.
- Rutas internas.
- Servidores.
- Dominios.
- Direcciones IP.
- Información DNS.

---

# Documentos compatibles

FOCA puede analizar numerosos formatos, entre ellos:

- PDF.
- DOC.
- DOCX.
- XLS.
- XLSX.
- PPT.
- PPTX.
- ODT.

---

# Usos en OSINT

FOCA resulta útil para:

- Investigar organizaciones.
- Analizar documentos públicos.
- Identificar empleados.
- Descubrir infraestructura interna.
- Detectar fugas de información.
- Preparar auditorías de seguridad.

---

# Casos de uso

## Investigación corporativa

Analizar documentos publicados por una empresa para obtener información técnica y organizativa.

---

## Auditoría de seguridad

Detectar metadatos sensibles que puedan facilitar un ataque de reconocimiento.

---

## Pentesting

Recopilar información previa sobre una organización antes de una auditoría autorizada.

---

## OSINT

Relacionar información obtenida en documentos con otros datos públicos.

---

# Integración con otras herramientas

FOCA suele utilizarse junto con:

- ExifTool
- MediaInfo
- PDFInfo
- theHarvester
- SpiderFoot
- Maltego
- Recon-ng

La combinación de estas herramientas permite realizar un análisis mucho más completo de una organización.

---

# Instalación

FOCA está disponible para **Windows** y puede descargarse gratuitamente desde el sitio oficial de **INCIBE**.

---

# Ventajas

- Gratuita.
- Interfaz gráfica sencilla.
- Excelente análisis de documentos.
- Automatiza la extracción de metadatos.
- Muy útil en auditorías de seguridad.

---

# Limitaciones

- Disponible principalmente para Windows.
- Depende de la existencia de documentos públicos.
- Algunos metadatos pueden haber sido eliminados antes de la publicación.

---

# Buenas prácticas

- Analizar documentos de diferentes formatos.
- Verificar la información obtenida con otras fuentes OSINT.
- Revisar especialmente autores, rutas internas y software utilizado.
- Documentar todos los hallazgos relevantes.

---

# Caso práctico

**Objetivo:** Analizar los documentos públicos de una empresa.

Dominio:

```text
empresa.com
```

Información esperada:

- Documentos publicados.
- Autores.
- Software utilizado.
- Usuarios.
- Rutas internas.
- Información DNS.
- Posibles tecnologías empleadas.

---

# Resumen

FOCA es una herramienta especializada en el análisis de metadatos de documentos públicos y el reconocimiento de organizaciones. Gracias a su capacidad para descubrir información sensible oculta en archivos publicados en Internet, constituye un recurso muy valioso para analistas OSINT, auditores de seguridad y profesionales de la ciberseguridad.