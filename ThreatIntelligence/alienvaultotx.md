# AlienVault OTX

## Descripción

**AlienVault OTX (Open Threat Exchange)** es una plataforma colaborativa de **Threat Intelligence** desarrollada por **AT&T Cybersecurity** que permite compartir y consultar indicadores de compromiso (IOC) relacionados con amenazas informáticas.

Es una de las mayores comunidades abiertas de inteligencia sobre amenazas y es utilizada por analistas SOC, equipos CERT, investigadores OSINT y profesionales de ciberseguridad para identificar campañas maliciosas y obtener contexto sobre indicadores.

---

# ¿Cómo funciona?

AlienVault OTX recopila información aportada por investigadores, empresas y organizaciones de todo el mundo.

Los usuarios pueden publicar **Pulses**, que son conjuntos de indicadores relacionados con una amenaza concreta. La plataforma correlaciona estos datos y permite consultar rápidamente si un indicador está asociado a actividades maliciosas.

---

# Funciones principales

AlienVault OTX permite:

- Consultar indicadores de compromiso (IOC).
- Buscar amenazas conocidas.
- Analizar dominios e IPs.
- Consultar hashes.
- Analizar URLs.
- Compartir inteligencia mediante Pulses.
- Acceder mediante API.

---

# Información disponible

Dependiendo del indicador consultado, puede mostrar:

- Direcciones IP.
- Dominios.
- URLs.
- Hashes MD5, SHA1 y SHA256.
- Archivos maliciosos.
- Campañas.
- Malware asociado.
- Pulses relacionados.
- Descripción de la amenaza.

---

# Indicadores compatibles

OTX permite consultar:

- Direcciones IP.
- Dominios.
- URLs.
- Hashes.
- Nombres de malware.
- IOC relacionados con campañas.

---

# Usos en Threat Intelligence

AlienVault OTX resulta útil para:

- Investigar amenazas.
- Analizar IOC.
- Detectar campañas maliciosas.
- Complementar investigaciones OSINT.
- Validar alertas de seguridad.
- Compartir inteligencia con otros investigadores.

---

# Casos de uso

## Respuesta ante incidentes

Comprobar si una IP, dominio o hash está relacionado con campañas conocidas.

---

## Threat Hunting

Buscar indicadores asociados a malware o ataques recientes.

---

## Investigación OSINT

Relacionar un dominio o dirección IP con amenazas previamente documentadas.

---

## SOC

Enriquecer alertas procedentes de SIEM o EDR mediante información adicional.

---

# Integración con otras herramientas

AlienVault OTX suele utilizarse junto con:

- AbuseIPDB
- VirusTotal
- URLScan
- Hybrid Analysis
- GreyNoise
- Shodan
- Censys

La combinación de estas herramientas permite obtener una visión mucho más completa sobre una amenaza.

---

# API

AlienVault OTX dispone de una API REST que permite:

- Consultar IOC automáticamente.
- Obtener información sobre Pulses.
- Integrar inteligencia en herramientas SIEM.
- Automatizar investigaciones.

El acceso requiere una clave API gratuita.

---

# Ventajas

- Gratuito.
- Gran comunidad de usuarios.
- Amplia base de indicadores.
- API disponible.
- Actualización constante.
- Muy útil para Threat Intelligence.

---

# Limitaciones

- Parte de la información depende de las aportaciones de la comunidad.
- Algunos IOC pueden quedar obsoletos con el tiempo.
- Es recomendable validar siempre la información con otras fuentes.

---

# Buenas prácticas

- Contrastar los IOC con otras plataformas de Threat Intelligence.
- Revisar la fecha de publicación de los Pulses.
- Analizar el contexto de cada amenaza.
- No considerar un único IOC como evidencia suficiente.

---

# Caso práctico

**Objetivo:** Analizar un dominio sospechoso.

Consulta:

```text
malicious-example.com
```

Información esperada:

- Pulses relacionados.
- IOC asociados.
- Malware vinculado.
- Direcciones IP.
- URLs.
- Descripción de la amenaza.
- Historial de actividad.

---

# Resumen

AlienVault OTX es una de las plataformas de Threat Intelligence más completas para compartir y consultar indicadores de compromiso. Gracias a su gran comunidad y a su amplia base de datos de amenazas, permite enriquecer investigaciones OSINT, validar IOC y mejorar los procesos de detección y respuesta ante incidentes de ciberseguridad.