# GreyNoise

## Descripción

**GreyNoise** es una plataforma de **Threat Intelligence** especializada en analizar el ruido de Internet (*Internet Noise*), identificando direcciones IP que realizan escaneos masivos, búsquedas automatizadas o actividades de reconocimiento sin estar necesariamente dirigidas a un objetivo concreto.

Su principal utilidad es ayudar a distinguir entre tráfico malicioso dirigido y el tráfico habitual generado por escáneres automáticos que recorren continuamente Internet.

---

# ¿Cómo funciona?

GreyNoise monitoriza millones de direcciones IP mediante sensores distribuidos globalmente.

La plataforma analiza el comportamiento de cada IP y la clasifica según la actividad observada, permitiendo saber si forma parte de campañas automatizadas, escaneos de Internet o ataques dirigidos.

---

# Funciones principales

GreyNoise permite:

- Consultar la reputación de una IP.
- Identificar escaneos de Internet.
- Detectar actividad automatizada.
- Clasificar direcciones IP.
- Consultar contexto sobre amenazas.
- Acceder mediante API.

---

# Información disponible

Dependiendo de la dirección IP consultada, puede mostrar:

- Dirección IP.
- Clasificación de la IP.
- Tipo de actividad.
- País.
- ASN.
- Organización.
- Protocolos utilizados.
- Puertos analizados.
- Última actividad observada.
- Nivel de confianza.

---

# Clasificaciones

GreyNoise clasifica las direcciones IP en diferentes categorías, como:

- **Benign:** actividad legítima conocida.
- **Malicious:** actividad maliciosa detectada.
- **Unknown:** sin información suficiente.
- **Internet Scanner:** escaneos automatizados de Internet.

Estas clasificaciones ayudan a priorizar el análisis durante una investigación.

---

# Usos en Threat Intelligence

GreyNoise resulta útil para:

- Analizar direcciones IP sospechosas.
- Filtrar ruido de Internet.
- Investigar intentos de escaneo.
- Priorizar alertas de seguridad.
- Complementar investigaciones OSINT.
- Mejorar procesos de Threat Hunting.

---

# Casos de uso

## Respuesta ante incidentes

Determinar si una IP detectada corresponde a un escáner automatizado o a un ataque dirigido.

---

## Threat Hunting

Reducir falsos positivos eliminando el tráfico generado por escaneos habituales de Internet.

---

## Investigación OSINT

Obtener contexto adicional sobre una dirección IP antes de profundizar en el análisis.

---

## SOC

Priorizar las alertas procedentes de sistemas SIEM y EDR según la clasificación de la IP.

---

# Integración con otras herramientas

GreyNoise suele utilizarse junto con:

- AlienVault OTX
- AbuseIPDB
- VirusTotal
- URLScan
- Hybrid Analysis
- Shodan
- Censys

La combinación de estas herramientas proporciona un contexto mucho más completo sobre una dirección IP.

---

# API

GreyNoise ofrece una API REST que permite:

- Consultar IPs automáticamente.
- Integrar información en SIEM y SOAR.
- Automatizar investigaciones.
- Enriquecer indicadores de compromiso.

El acceso a determinadas funciones requiere una clave API.

---

# Ventajas

- Excelente contexto sobre direcciones IP.
- Reduce falsos positivos.
- Información actualizada.
- API disponible.
- Muy útil para Threat Hunting y SOC.

---

# Limitaciones

- Centrada principalmente en direcciones IP.
- Algunas funciones avanzadas requieren suscripción.
- No sustituye a otras plataformas de Threat Intelligence.

---

# Buenas prácticas

- Complementar la información con otras herramientas de Threat Intelligence.
- Revisar la fecha de la última actividad registrada.
- Analizar el contexto antes de clasificar una IP como maliciosa.
- Utilizar GreyNoise para diferenciar ataques reales del ruido habitual de Internet.

---

# Caso práctico

**Objetivo:** Analizar una dirección IP detectada en un firewall.

Consulta:

```text
45.155.205.233
```

Información esperada:

- Clasificación de la IP.
- Tipo de actividad.
- País.
- ASN.
- Puertos analizados.
- Última actividad.
- Contexto de la amenaza.

---

# Resumen

GreyNoise es una plataforma especializada en diferenciar el tráfico malicioso dirigido del ruido habitual generado por escáneres automatizados de Internet. Gracias a su capacidad para contextualizar direcciones IP y reducir falsos positivos, constituye una herramienta imprescindible para analistas SOC, equipos de Threat Intelligence e investigadores OSINT.