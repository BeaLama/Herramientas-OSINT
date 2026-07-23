# DNSDumpster

## Descripción

**DNSDumpster** es una herramienta OSINT que permite obtener información pública sobre la configuración **DNS** de un dominio. Facilita la identificación de subdominios, direcciones IP, servidores de correo y otros registros DNS sin necesidad de realizar consultas manuales.

Es muy utilizada durante las fases iniciales de una investigación o auditoría para conocer la infraestructura visible de una organización.

---

# ¿Cómo funciona?

DNSDumpster recopila información de diferentes fuentes públicas y realiza consultas DNS para generar un informe del dominio analizado.

El proceso consiste en:

1. Introducir un dominio.
2. Consultar registros DNS públicos.
3. Identificar subdominios y hosts.
4. Relacionar la información encontrada.
5. Generar un informe y un mapa de la infraestructura.

---

# Información disponible

DNSDumpster puede mostrar:

- Registros **A**
- Registros **AAAA**
- Registros **MX**
- Registros **NS**
- Registros **TXT**
- Subdominios
- Direcciones IP
- Servidores de correo
- Servidores DNS
- Información del proveedor de alojamiento (Hosting)

---

# Usos en OSINT

- Descubrir subdominios.
- Identificar servidores DNS.
- Analizar servidores de correo.
- Obtener direcciones IP públicas.
- Conocer la infraestructura visible de un dominio.
- Preparar investigaciones posteriores con otras herramientas.

---

# Cómo utilizarlo

1. Acceder a DNSDumpster.
2. Introducir el nombre del dominio.
3. Resolver el CAPTCHA (si se solicita).
4. Analizar los resultados obtenidos.

---

# Resultados

La herramienta suele organizar la información en varias secciones:

## Hosts

Lista de servidores y subdominios asociados al dominio.

---

## Servidores DNS (NS)

Muestra los servidores responsables de resolver el dominio.

---

## Servidores de correo (MX)

Identifica los servidores utilizados para el envío y recepción de correo electrónico.

---

## Registros TXT

Permite visualizar registros relacionados con:

- SPF
- DKIM
- DMARC
- Verificaciones de servicios

---

## Mapa de infraestructura

DNSDumpster genera un diagrama que representa gráficamente la relación entre:

- Dominio
- Subdominios
- Servidores DNS
- Servidores MX
- Direcciones IP

Este mapa facilita la comprensión de la infraestructura pública.

---

# Casos de uso

**Descubrimiento de subdominios**

Identificar servicios publicados bajo un dominio.

**Análisis DNS**

Comprobar la configuración DNS pública.

**Investigación de correo electrónico**

Localizar los servidores MX utilizados por una organización.

**Inventario de infraestructura**

Obtener una visión general de los activos visibles en Internet.

---

# Integración con otras herramientas

DNSDumpster puede complementarse con:

- Shodan
- Censys
- SecurityTrails
- crt.sh
- VirusTotal
- Amass
- SpiderFoot
- Maltego

---

# Ventajas

- Interfaz sencilla.
- No requiere instalación.
- Genera mapas de infraestructura.
- Muestra información DNS relevante.
- Útil para investigaciones preliminares.

---

# Limitaciones

- Solo muestra información pública.
- Puede no encontrar todos los subdominios.
- Algunas consultas están limitadas para evitar abusos.
- Depende de la información disponible en los registros DNS.

---

# Buenas prácticas

- Verificar los resultados con otras herramientas.
- Analizar también los certificados SSL mediante crt.sh.
- Documentar los registros encontrados.
- Revisar periódicamente la información, ya que puede cambiar con el tiempo.

---

# Caso práctico

**Objetivo:** Analizar la infraestructura pública de un dominio.

Dominio:

```text
empresa.com
```

Resultado esperado:

- Servidores DNS.
- Servidores de correo.
- Subdominios.
- Direcciones IP.
- Registros DNS.
- Mapa de la infraestructura.

---

# Resumen

DNSDumpster es una herramienta OSINT especializada en el análisis de registros DNS. Permite obtener rápidamente una visión general de la infraestructura pública de un dominio, identificar subdominios y servidores asociados, y generar un mapa visual que facilita el análisis de la información recopilada.