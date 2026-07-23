# Censys

## Descripción

Censys es un motor de búsqueda especializado en la **infraestructura de Internet**. Recopila información pública sobre direcciones IP, dominios, certificados digitales y servicios expuestos, siendo una herramienta muy utilizada en **OSINT**, análisis de seguridad y gestión de activos.

A diferencia de Shodan, Censys pone un fuerte énfasis en el análisis de certificados **SSL/TLS** y en la relación entre dominios, hosts y servicios.

---

# ¿Cómo funciona?

Censys realiza escaneos continuos de Internet mediante:

1. Descubrimiento de hosts públicos.
2. Análisis de puertos abiertos.
3. Recopilación de banners de servicios.
4. Análisis de certificados SSL/TLS.
5. Indexación de la información para su consulta.

---

# Información disponible

Censys puede mostrar:

- Dirección IP.
- Dominios asociados.
- Certificados SSL/TLS.
- Puertos abiertos.
- Servicios detectados.
- Software identificado.
- Protocolos utilizados.
- Proveedor de alojamiento (Hosting).
- Sistema Autónomo (ASN).

---

# Usos en OSINT

- Investigación de dominios.
- Identificación de activos públicos.
- Descubrimiento de subdominios.
- Análisis de certificados digitales.
- Correlación entre IPs y dominios.
- Inventario de infraestructura.

---

# Tipos de búsqueda

## Hosts

Permite consultar información sobre una dirección IP o un host.

Ejemplo:

```text
198.51.100.10
```

---

## Certificados

Busca certificados SSL/TLS públicos.

Ejemplo:

```text
empresa.com
```

---

## Dominios

Obtiene información relacionada con un dominio y sus servicios.

---

# Filtros de búsqueda

| Filtro | Descripción |
|---------|-------------|
| `services.port:` | Filtra por puerto. |
| `services.service_name:` | Filtra por servicio. |
| `location.country:` | Filtra por país. |
| `autonomous_system.name:` | Filtra por proveedor o ASN. |
| `dns.names:` | Busca por nombre de dominio. |
| `services.tls.certificates.leaf_data.subject.common_name:` | Busca por nombre común (CN) del certificado. |

---

# Ejemplos

Buscar un dominio:

```text
dns.names:empresa.com
```

Buscar servidores HTTPS:

```text
services.port:443
```

Buscar equipos en España:

```text
location.country:Spain
```

Buscar servidores Apache:

```text
services.software.product:Apache
```

Buscar certificados de un dominio:

```text
services.tls.certificates.leaf_data.subject.common_name:empresa.com
```

---

# Casos de uso

**Análisis de certificados**

Comprobar qué certificados están asociados a una organización.

**Descubrimiento de activos**

Identificar servidores públicos relacionados con un dominio.

**Inventario de infraestructura**

Conocer los servicios y tecnologías expuestos a Internet.

**Correlación de información**

Relacionar dominios, IPs y certificados para obtener una visión más completa de la infraestructura.

---

# API

Censys ofrece una API que permite:

- Consultar hosts.
- Buscar certificados.
- Automatizar búsquedas.
- Exportar resultados en formato JSON.

Es necesario disponer de una cuenta y credenciales API.

---

# Integración con otras herramientas

Censys puede combinarse con:

- Shodan
- VirusTotal
- SecurityTrails
- DNSDumpster
- Maltego
- SpiderFoot
- Recon-ng
- Amass

---

# Ventajas

- Excelente análisis de certificados SSL/TLS.
- Información detallada sobre hosts y servicios.
- Potentes filtros de búsqueda.
- API para automatización.
- Actualización periódica de los datos.

---

# Limitaciones

- Algunas funciones requieren una suscripción.
- Solo muestra información accesible públicamente.
- Los datos dependen de la frecuencia de los escaneos.

---

# Buenas prácticas

- Verificar la fecha del último escaneo.
- Corroborar los resultados con otras herramientas OSINT.
- Documentar las consultas realizadas.
- Utilizar la información únicamente con fines legítimos y autorizados.

---

# Caso práctico

**Objetivo:** Analizar los certificados asociados a un dominio.

Consulta:

```text
dns.names:empresa.com
```

Resultado esperado:

- Certificados SSL/TLS.
- Direcciones IP relacionadas.
- Puertos abiertos.
- Servicios detectados.
- Información del proveedor de alojamiento.

---

# Resumen

Censys es una herramienta esencial para investigaciones OSINT centradas en la infraestructura de Internet. Destaca por su capacidad para analizar certificados digitales, identificar servicios públicos y relacionar dominios, direcciones IP y tecnologías utilizadas por una organización.