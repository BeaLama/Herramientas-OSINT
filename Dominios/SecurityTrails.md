# SecurityTrails

## Descripción

**SecurityTrails** es una plataforma OSINT especializada en el análisis de **dominios, DNS, direcciones IP y activos de Internet**. Destaca por ofrecer información histórica, permitiendo conocer cómo ha evolucionado la infraestructura de un dominio a lo largo del tiempo.

Es una herramienta muy utilizada en investigaciones OSINT, auditorías de seguridad y gestión de activos digitales.

---

# ¿Cómo funciona?

SecurityTrails recopila información de múltiples fuentes públicas y realiza un seguimiento continuo de los cambios en la infraestructura de Internet.

El proceso consiste en:

1. Recopilar registros DNS.
2. Indexar dominios y subdominios.
3. Registrar cambios históricos.
4. Relacionar dominios, IPs y certificados.
5. Presentar la información mediante un buscador y una API.

---

# Información disponible

SecurityTrails puede mostrar:

- Dominios.
- Subdominios.
- Registros DNS.
- Historial DNS.
- Direcciones IP.
- Servidores DNS (NS).
- Servidores de correo (MX).
- Registros TXT.
- Información WHOIS.
- Proveedor de alojamiento (Hosting).
- ASN (Sistema Autónomo).

---

# Usos en OSINT

- Descubrir subdominios.
- Analizar cambios históricos en DNS.
- Identificar direcciones IP antiguas.
- Investigar infraestructura pública.
- Correlacionar dominios e IPs.
- Realizar inventarios de activos.

---

# Tipos de búsqueda

## Dominio

Permite consultar toda la información disponible de un dominio.

Ejemplo:

```text
empresa.com
```

---

## Subdominios

Lista los subdominios conocidos asociados al dominio.

---

## Historial DNS

Muestra cómo han cambiado los registros DNS con el tiempo.

---

## WHOIS

Presenta información relacionada con el registro del dominio.

---

# Información DNS

SecurityTrails permite consultar:

- Registros A
- Registros AAAA
- Registros MX
- Registros NS
- Registros TXT
- Registros CNAME
- Registros SOA

---

# Casos de uso

**Descubrimiento de subdominios**

Identificar servicios públicos asociados a un dominio.

**Historial DNS**

Analizar cambios en la infraestructura a lo largo del tiempo.

**Investigación de IPs**

Conocer qué direcciones IP ha utilizado un dominio.

**Inventario de activos**

Obtener una visión general de la infraestructura pública.

---

# API

SecurityTrails ofrece una API que permite:

- Consultar dominios.
- Obtener subdominios.
- Acceder al historial DNS.
- Buscar información WHOIS.
- Exportar resultados en formato JSON.

Es necesario disponer de una clave API.

---

# Integración con otras herramientas

SecurityTrails puede combinarse con:

- Shodan
- Censys
- DNSDumpster
- crt.sh
- VirusTotal
- Maltego
- SpiderFoot
- Recon-ng
- Amass

---

# Ventajas

- Excelente historial DNS.
- Gran cantidad de subdominios indexados.
- Información WHOIS integrada.
- API para automatización.
- Interfaz intuitiva.

---

# Limitaciones

- Algunas funciones requieren una suscripción.
- Solo muestra información pública.
- Los datos históricos dependen de la información recopilada por la plataforma.

---

# Buenas prácticas

- Comparar los resultados con otras herramientas OSINT.
- Revisar tanto los registros actuales como el historial DNS.
- Documentar los cambios encontrados.
- Utilizar la API para automatizar investigaciones recurrentes.

---

# Caso práctico

**Objetivo:** Analizar la infraestructura pública de un dominio.

Dominio:

```text
empresa.com
```

Información esperada:

- Subdominios.
- Historial DNS.
- Direcciones IP.
- Servidores DNS.
- Registros MX.
- Información WHOIS.
- ASN y proveedor de alojamiento.

---

# Resumen

SecurityTrails es una herramienta OSINT muy completa para el análisis de dominios y DNS. Su principal fortaleza es el acceso al **historial de registros DNS**, lo que permite estudiar la evolución de una infraestructura y descubrir activos públicos relacionados con una organización.