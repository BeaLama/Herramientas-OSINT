# VirusTotal

## Descripción

**VirusTotal** es una plataforma de análisis que permite comprobar archivos, direcciones IP, dominios, URLs y *hashes* utilizando decenas de motores antivirus y fuentes de **Threat Intelligence**. Es una herramienta ampliamente utilizada en **OSINT**, respuesta ante incidentes y análisis de malware.

---

# ¿Cómo funciona?

VirusTotal recopila información de múltiples proveedores de seguridad y la presenta en un único informe.

El proceso consiste en:

1. Enviar un archivo, URL, dominio, IP o hash.
2. Analizarlo con múltiples motores de seguridad.
3. Correlacionar la información obtenida.
4. Mostrar un informe con los resultados.

---

# Tipos de búsqueda

VirusTotal permite analizar:

- Archivos.
- URLs.
- Dominios.
- Direcciones IP.
- Hashes (MD5, SHA1 y SHA256).

---

# Información disponible

Dependiendo del tipo de consulta, VirusTotal puede mostrar:

- Detecciones antivirus.
- Reputación.
- Dominios relacionados.
- Subdominios.
- Direcciones IP.
- Certificados SSL/TLS.
- Registros DNS.
- WHOIS.
- URLs asociadas.
- Archivos relacionados.
- Comentarios de la comunidad.

---

# Usos en OSINT

- Analizar dominios.
- Investigar direcciones IP.
- Consultar certificados SSL.
- Analizar URLs.
- Verificar hashes de archivos.
- Correlacionar indicadores de compromiso (IOCs).

---

# Análisis de dominios

Permite consultar:

- Registros DNS.
- WHOIS.
- Certificados.
- Subdominios.
- Resoluciones históricas.
- URLs relacionadas.

Ejemplo:

```text
empresa.com
```

---

# Análisis de direcciones IP

Información disponible:

- Geolocalización aproximada.
- ASN.
- Puertos observados.
- Dominios relacionados.
- Reputación.

---

# Análisis de URLs

Permite comprobar si una dirección web ha sido clasificada como maliciosa por alguno de los motores de seguridad.

Ejemplo:

```text
https://www.ejemplo.com
```

---

# Análisis de archivos

Se pueden subir archivos para obtener:

- Resultado de múltiples motores antivirus.
- Hashes.
- Tipo de archivo.
- Tamaño.
- Información básica del análisis.

---

# Análisis mediante hashes

VirusTotal admite búsquedas por:

- MD5
- SHA1
- SHA256

Ejemplo:

```text
44d88612fea8a8f36de82e1278abb02f
```

---

# API

VirusTotal ofrece una API para:

- Consultar dominios.
- Analizar URLs.
- Buscar hashes.
- Consultar IPs.
- Automatizar investigaciones.

El uso requiere una clave API.

---

# Integración con otras herramientas

VirusTotal puede combinarse con:

- Shodan
- Censys
- SecurityTrails
- DNSDumpster
- Maltego
- SpiderFoot
- MISP
- TheHive

---

# Ventajas

- Gran cantidad de motores antivirus.
- Amplia información de Threat Intelligence.
- Interfaz sencilla.
- API disponible.
- Excelente para correlacionar indicadores.

---

# Limitaciones

- No sustituye un análisis manual.
- Algunas funciones avanzadas requieren suscripción.
- La ausencia de detecciones no garantiza que un archivo o URL sea seguro.

---

# Buenas prácticas

- Contrastar los resultados con otras fuentes.
- Analizar tanto dominios como IPs y URLs relacionadas.
- Utilizar hashes para identificar archivos conocidos.
- Documentar los indicadores encontrados.

---

# Caso práctico

**Objetivo:** Analizar un dominio.

Consulta:

```text
empresa.com
```

Información esperada:

- Reputación.
- Registros DNS.
- Subdominios.
- Certificados SSL.
- Direcciones IP relacionadas.
- URLs observadas.

---

# Resumen

VirusTotal es una herramienta imprescindible en investigaciones OSINT y de ciberseguridad. Permite analizar archivos, dominios, URLs, direcciones IP y hashes utilizando múltiples fuentes de inteligencia, facilitando la identificación y correlación de indicadores públicos de seguridad.