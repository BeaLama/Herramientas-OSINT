# Hybrid Analysis

## Descripción

**Hybrid Analysis** es una plataforma de **Threat Intelligence** y análisis de malware desarrollada por **CrowdStrike**. Permite analizar archivos y URLs sospechosas en un entorno controlado (*sandbox*) para detectar comportamientos maliciosos y obtener información detallada sobre amenazas.

Es una herramienta ampliamente utilizada por analistas SOC, investigadores OSINT, equipos CERT y profesionales de ciberseguridad para estudiar muestras de malware y verificar archivos sospechosos.

---

# ¿Cómo funciona?

Hybrid Analysis ejecuta archivos o URLs en un entorno aislado (*sandbox*) donde monitoriza todas sus acciones.

Durante el análisis registra el comportamiento del archivo, como conexiones de red, procesos creados, modificaciones del sistema, acceso al registro de Windows y otras actividades potencialmente maliciosas.

Al finalizar, genera un informe detallado con los resultados.

---

# Funciones principales

Hybrid Analysis permite:

- Analizar archivos sospechosos.
- Analizar URLs.
- Ejecutar muestras en sandbox.
- Detectar malware.
- Consultar informes públicos.
- Acceder mediante API.

---

# Información disponible

Dependiendo del análisis, puede mostrar:

- Hashes (MD5, SHA1 y SHA256).
- Nivel de riesgo.
- Familia de malware.
- Procesos ejecutados.
- Conexiones de red.
- Dominios e IPs contactadas.
- Archivos creados o modificados.
- Indicadores de compromiso (IOC).
- Reglas YARA y MITRE ATT&CK (cuando estén disponibles).

---

# Métodos de análisis

La plataforma permite analizar:

- Archivos ejecutables.
- Documentos.
- Scripts.
- Archivos comprimidos.
- URLs.
- Hashes.

---

# Usos en Threat Intelligence

Hybrid Analysis resulta útil para:

- Analizar malware.
- Verificar archivos sospechosos.
- Investigar URLs maliciosas.
- Obtener IOC.
- Complementar investigaciones OSINT.
- Apoyar la respuesta ante incidentes.

---

# Casos de uso

## Respuesta ante incidentes

Analizar un archivo recibido por correo electrónico para determinar si es malicioso.

---

## Threat Hunting

Extraer indicadores de compromiso para detectar amenazas similares en la red.

---

## Investigación OSINT

Consultar informes públicos sobre malware conocido.

---

## Análisis forense

Estudiar el comportamiento de una muestra sin ejecutarla en un sistema real.

---

# Integración con otras herramientas

Hybrid Analysis suele utilizarse junto con:

- VirusTotal
- AlienVault OTX
- AbuseIPDB
- GreyNoise
- URLScan
- Shodan
- Censys

La combinación de estas herramientas proporciona una visión mucho más completa de una amenaza.

---

# API

Hybrid Analysis dispone de una API REST que permite:

- Enviar archivos automáticamente.
- Consultar informes.
- Obtener IOC.
- Integrar resultados en plataformas SIEM y SOAR.

El acceso requiere una clave API.

---

# Ventajas

- Sandbox avanzado.
- Informes muy detallados.
- API disponible.
- Amplia base de muestras públicas.
- Muy útil para análisis de malware.

---

# Limitaciones

- Algunas funciones requieren una cuenta.
- Los análisis pueden tardar varios minutos.
- No todas las muestras están disponibles públicamente.
- Determinadas funciones avanzadas requieren suscripción.

---

# Buenas prácticas

- Analizar siempre archivos sospechosos en un entorno aislado.
- Contrastar los resultados con otras plataformas de Threat Intelligence.
- Revisar cuidadosamente los IOC obtenidos.
- No descargar ni ejecutar muestras maliciosas fuera de un entorno controlado.

---

# Caso práctico

**Objetivo:** Analizar un archivo sospechoso.

Archivo:

```text
invoice.pdf.exe
```

Información esperada:

- Nivel de riesgo.
- Comportamiento del archivo.
- Procesos ejecutados.
- Conexiones de red.
- Hashes.
- IOC.
- Posible familia de malware.

---

# Resumen

Hybrid Analysis es una plataforma de análisis dinámico de malware que permite estudiar el comportamiento de archivos y URLs en un entorno seguro. Gracias a sus informes detallados, la extracción de indicadores de compromiso y su integración con otras plataformas de Threat Intelligence, constituye una herramienta imprescindible para analistas de ciberseguridad, investigadores OSINT y equipos de respuesta ante incidentes.