# ViewDNS

## Descripción

**ViewDNS.info** es una plataforma OSINT que reúne diversas herramientas para analizar **dominios, direcciones IP, registros DNS y servicios de Internet**. Permite realizar múltiples consultas desde una única interfaz, siendo muy útil en investigaciones preliminares y auditorías de infraestructura.

---

# ¿Cómo funciona?

ViewDNS consulta diferentes bases de datos y servicios públicos para obtener información sobre un dominio o una dirección IP.

El proceso consiste en:

1. Introducir un dominio o una IP.
2. Seleccionar la herramienta de consulta.
3. Obtener la información correspondiente.
4. Analizar y correlacionar los resultados.

---

# Información disponible

ViewDNS ofrece herramientas para consultar:

- Información WHOIS.
- Registros DNS.
- Direcciones IP.
- Servidores DNS (NS).
- Servidores MX.
- ASN.
- Geolocalización aproximada.
- Historial de IPs.
- Historial WHOIS.
- Dominios alojados en una misma IP (Reverse IP Lookup).
- Reverse DNS.

---

# Usos en OSINT

- Investigar dominios.
- Analizar registros DNS.
- Descubrir dominios relacionados.
- Identificar la infraestructura de alojamiento.
- Obtener información sobre una dirección IP.
- Corroborar datos obtenidos con otras herramientas.

---

# Herramientas principales

## WHOIS Lookup

Consulta la información pública de registro de un dominio.

---

## DNS Report

Muestra los registros DNS del dominio.

Incluye:

- A
- AAAA
- MX
- NS
- TXT
- SOA

---

## Reverse IP Lookup

Permite descubrir otros dominios que resuelven a una misma dirección IP.

---

## Reverse DNS Lookup

Obtiene el nombre de host asociado a una dirección IP.

---

## IP Location

Muestra información aproximada sobre:

- País.
- Ciudad.
- ISP.
- ASN.

---

## Ping

Comprueba si un host responde a solicitudes ICMP.

---

## Traceroute

Muestra la ruta aproximada seguida por los paquetes hasta un destino.

---

## Port Scanner

Permite consultar qué puertos públicos responden en un host (según la funcionalidad disponible en la plataforma).

---

# Casos de uso

**Investigación de un dominio**

Obtener información WHOIS y registros DNS.

**Análisis de infraestructura**

Identificar otros dominios alojados en la misma dirección IP.

**Investigación de IPs**

Consultar geolocalización, ASN y nombre de host.

**Correlación de activos**

Relacionar dominios, IPs y servicios públicos.

---

# Integración con otras herramientas

ViewDNS suele utilizarse junto con:

- SecurityTrails
- DNSDumpster
- Shodan
- Censys
- crt.sh
- VirusTotal
- Maltego
- SpiderFoot

---

# Ventajas

- Gran cantidad de herramientas en una única plataforma.
- No requiere instalación.
- Interfaz sencilla.
- Información útil para investigaciones iniciales.
- Acceso rápido a consultas comunes.

---

# Limitaciones

- Algunas funciones ofrecen información limitada en la versión gratuita.
- Solo muestra datos públicos.
- La información histórica puede no estar disponible para todos los dominios.

---

# Buenas prácticas

- Verificar la información con otras herramientas OSINT.
- Utilizar Reverse IP para identificar activos relacionados.
- Complementar el análisis con certificados SSL mediante crt.sh.
- Documentar todas las consultas realizadas.

---

# Caso práctico

**Objetivo:** Analizar un dominio.

Dominio:

```text
empresa.com
```

Información esperada:

- WHOIS.
- Registros DNS.
- Direcciones IP.
- Reverse IP.
- Reverse DNS.
- ASN.
- Geolocalización aproximada.

---

# Resumen

ViewDNS es una plataforma muy útil para investigaciones OSINT relacionadas con dominios e infraestructura de Internet. Gracias a su colección de herramientas integradas, permite obtener rápidamente información sobre registros DNS, direcciones IP, servicios asociados y dominios relacionados, facilitando la correlación de datos durante una investigación.