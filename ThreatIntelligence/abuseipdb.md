# AbuseIPDB

## Descripción

**AbuseIPDB** es una plataforma colaborativa de **Threat Intelligence** que recopila y comparte reportes sobre direcciones IP involucradas en actividades maliciosas, como ataques, escaneos, spam o intentos de acceso no autorizado.

Es una herramienta muy utilizada por analistas de ciberseguridad, equipos SOC, investigadores OSINT y administradores de sistemas para evaluar la reputación de una dirección IP.

---

# ¿Cómo funciona?

AbuseIPDB permite consultar una dirección IP para conocer si ha sido reportada por otros usuarios como origen de actividades maliciosas.

La plataforma recopila miles de reportes enviados por empresas, investigadores y particulares, asignando una puntuación de confianza basada en el número y la calidad de los reportes recibidos.

---

# Funciones principales

AbuseIPDB permite:

- Consultar la reputación de una IP.
- Ver reportes de abuso.
- Obtener información ASN.
- Consultar el país de origen.
- Reportar direcciones IP maliciosas.
- Acceder mediante API.

---

# Información disponible

Dependiendo de la dirección IP consultada, puede mostrar:

- Dirección IP.
- Nivel de confianza (Abuse Confidence Score).
- Número de reportes.
- Fecha del último reporte.
- País.
- ASN.
- ISP.
- Categorías de abuso.
- Historial de actividad.

---

# Métodos de búsqueda

La plataforma permite consultar:

- Direcciones IPv4.
- Direcciones IPv6.

Las búsquedas pueden realizarse desde la web o mediante su API.

---

# Usos en Threat Intelligence

AbuseIPDB resulta útil para:

- Analizar direcciones IP sospechosas.
- Investigar ataques.
- Verificar indicadores de compromiso (IOC).
- Detectar servidores comprometidos.
- Complementar investigaciones OSINT.
- Validar alertas de seguridad.

---

# Casos de uso

## Respuesta ante incidentes

Comprobar si una IP detectada en los registros ha sido utilizada previamente en actividades maliciosas.

---

## Investigación OSINT

Relacionar una dirección IP con campañas conocidas o reportes públicos.

---

## Análisis de logs

Evaluar la reputación de las IP que acceden a un servidor o aplicación.

---

## Threat Hunting

Priorizar la investigación de direcciones IP con un alto nivel de confianza de abuso.

---

# Integración con otras herramientas

AbuseIPDB suele utilizarse junto con:

- AlienVault OTX
- VirusTotal
- URLScan
- Hybrid Analysis
- GreyNoise
- Shodan
- Censys

La combinación de estas herramientas proporciona un contexto mucho más completo sobre una dirección IP.

---

# API

AbuseIPDB dispone de una API REST que permite:

- Consultar IPs automáticamente.
- Reportar direcciones maliciosas.
- Integrar resultados en herramientas SIEM.
- Automatizar investigaciones.

Algunas funciones requieren una clave API.

---

# Ventajas

- Gran base de datos colaborativa.
- Información actualizada.
- API sencilla de utilizar.
- Puntuación de confianza.
- Muy útil para investigaciones de seguridad.

---

# Limitaciones

- La información depende de los reportes enviados por la comunidad.
- Una IP puede aparecer reportada por actividades puntuales o antiguas.
- Algunas funciones avanzadas requieren una cuenta.

---

# Buenas prácticas

- No basar una decisión únicamente en el nivel de reputación.
- Contrastar la información con otras plataformas de Threat Intelligence.
- Revisar la fecha de los últimos reportes.
- Analizar el contexto antes de clasificar una IP como maliciosa.

---

# Caso práctico

**Objetivo:** Verificar la reputación de una dirección IP.

Consulta:

```text
185.220.101.1
```

Información esperada:

- Nivel de confianza.
- Número de reportes.
- País.
- ASN.
- ISP.
- Tipos de abuso registrados.
- Fecha del último reporte.

---

# Resumen

AbuseIPDB es una de las plataformas de Threat Intelligence más utilizadas para evaluar la reputación de direcciones IP. Gracias a su sistema colaborativo de reportes y a su API, permite identificar rápidamente posibles indicadores de compromiso y complementar investigaciones OSINT, análisis forenses y procesos de respuesta ante incidentes.