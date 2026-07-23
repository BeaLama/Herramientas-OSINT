# Intelligence X

## Descripción

**Intelligence X (IntelX)** es una plataforma de **OSINT** y **Threat Intelligence** que indexa información pública procedente de múltiples fuentes, permitiendo buscar correos electrónicos, dominios, direcciones IP, documentos, URLs, criptomonedas, filtraciones de datos y otros indicadores de interés.

Es una de las herramientas más completas para investigaciones digitales, ya que centraliza información de diferentes servicios en una única plataforma y facilita la correlación de datos entre distintas fuentes.

---

# ¿Cómo funciona?

Intelligence X recopila e indexa información procedente de Internet, bases de datos públicas, filtraciones conocidas y otros recursos abiertos.

El usuario puede realizar búsquedas utilizando diferentes indicadores (*Indicators of Compromise* o IOCs), obteniendo resultados relacionados con dichos elementos.

La plataforma permite además filtrar los resultados por tipo de contenido, fecha o fuente para facilitar el análisis.

---

# Tipos de búsqueda

Intelligence X permite realizar consultas utilizando:

- Direcciones de correo electrónico.
- Dominios.
- Direcciones IP.
- URLs.
- Nombres de usuario.
- Nombres de personas.
- Hashes.
- Direcciones Bitcoin.
- Archivos y documentos.
- Certificados digitales.
- Teléfonos (cuando existen registros públicos).

---

# Información disponible

Dependiendo de la búsqueda realizada, Intelligence X puede mostrar:

- Correos electrónicos.
- Dominios.
- Direcciones IP.
- URLs.
- Documentos públicos.
- Archivos PDF.
- Filtraciones de datos.
- Hashes.
- Certificados TLS.
- Información DNS.
- Metadatos.
- Historial de contenido.

---

# Usos en OSINT

Intelligence X puede utilizarse para:

- Investigar personas.
- Analizar organizaciones.
- Buscar documentos públicos.
- Localizar filtraciones de datos.
- Analizar dominios.
- Correlacionar información entre diferentes fuentes.
- Investigar indicadores de compromiso (IOCs).
- Verificar información obtenida mediante otras herramientas.

---

# Funciones principales

## Búsqueda por correo electrónico

Permite localizar información pública asociada a una dirección de correo.

Ejemplo:

```text
usuario@empresa.com
```

---

## Búsqueda por dominio

Obtiene información relacionada con un dominio.

Ejemplo:

```text
empresa.com
```

---

## Búsqueda por dirección IP

Permite localizar referencias públicas relacionadas con una IP.

Ejemplo:

```text
203.0.113.10
```

---

## Búsqueda de documentos

Indexa documentos disponibles públicamente como:

- PDF
- DOCX
- XLSX
- PPTX
- TXT

---

## Filtraciones de datos

Permite localizar información procedente de brechas de seguridad conocidas cuando está disponible.

---

# Casos de uso

## Investigación de personas

Buscar correos electrónicos, documentos o perfiles públicos asociados a una persona.

---

## Investigación corporativa

Analizar dominios, documentos publicados y posibles filtraciones relacionadas con una organización.

---

## Respuesta ante incidentes

Correlacionar indicadores obtenidos durante una investigación de seguridad.

---

## Threat Intelligence

Buscar IOCs relacionados con campañas maliciosas o incidentes de seguridad.

---

# Integración con otras herramientas

Intelligence X suele utilizarse junto con:

- Hunter
- EmailRep
- Have I Been Pwned
- DeHashed
- VirusTotal
- Shodan
- Censys
- SpiderFoot
- Maltego
- Recon-ng

---

# API

La plataforma ofrece una API que permite automatizar consultas e integrarlas con otras herramientas de análisis.

Entre sus funciones destacan:

- Consultas automáticas.
- Búsqueda de IOCs.
- Integración con plataformas SIEM.
- Automatización de investigaciones OSINT.

El acceso a determinadas funciones requiere una suscripción.

---

# Ventajas

- Gran cantidad de información indexada.
- Múltiples tipos de búsqueda.
- Interfaz intuitiva.
- API disponible.
- Excelente para correlacionar información.

---

# Limitaciones

- Algunas funciones avanzadas requieren suscripción.
- Parte del contenido puede estar restringido.
- No toda la información indexada está actualizada en tiempo real.

---

# Buenas prácticas

- Contrastar siempre los resultados con otras fuentes.
- Documentar las evidencias obtenidas.
- Utilizar filtros para reducir falsos positivos.
- Respetar la legislación vigente sobre protección de datos.
- Utilizar la plataforma únicamente con fines legítimos.

---

# Caso práctico

**Objetivo:** Investigar un dominio corporativo.

Consulta:

```text
empresa.com
```

Información esperada:

- Correos electrónicos relacionados.
- Documentos públicos.
- Certificados digitales.
- Subdominios.
- Direcciones IP.
- Posibles filtraciones.
- Referencias públicas.
- Información histórica del dominio.

---

# Resumen

Intelligence X es una de las plataformas más completas para investigaciones OSINT y Threat Intelligence. Gracias a su capacidad para indexar correos electrónicos, dominios, documentos, direcciones IP, filtraciones de datos e indicadores de compromiso, constituye una herramienta imprescindible para analistas de seguridad, investigadores digitales y profesionales de la inteligencia que necesitan correlacionar información procedente de múltiples fuentes abiertas.