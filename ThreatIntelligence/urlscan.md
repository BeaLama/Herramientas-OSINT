# URLScan

## Descripción

**URLScan.io** es una plataforma de **Threat Intelligence** que permite analizar páginas web y URLs en un entorno seguro para obtener información sobre su contenido, comportamiento y posibles amenazas. Es ampliamente utilizada por analistas SOC, investigadores OSINT y profesionales de ciberseguridad para investigar sitios web sospechosos.

La herramienta captura el contenido de una página web, analiza las conexiones realizadas y genera un informe detallado con todos los recursos cargados durante la visita.

---

# ¿Cómo funciona?

URLScan visita automáticamente la URL indicada utilizando un navegador aislado (*sandbox*).

Durante el análisis registra todas las peticiones realizadas, los dominios contactados, las direcciones IP, los certificados SSL, las tecnologías utilizadas y otros elementos relacionados con la página.

Al finalizar genera un informe completo que puede compartirse mediante un enlace.

---

# Funciones principales

URLScan permite:

- Analizar URLs.
- Capturar páginas web.
- Identificar dominios relacionados.
- Detectar tecnologías web.
- Consultar certificados SSL.
- Obtener capturas de pantalla.
- Acceder mediante API.

---

# Información disponible

Dependiendo de la URL analizada, puede mostrar:

- Captura de pantalla.
- Dirección IP.
- Dominio.
- Certificado SSL.
- Tecnologías utilizadas.
- Recursos cargados.
- Solicitudes HTTP.
- Archivos JavaScript.
- Cookies.
- Indicadores de compromiso (IOC).

---

# Métodos de búsqueda

La plataforma permite consultar:

- URLs.
- Dominios.
- Direcciones IP.
- Hashes de capturas.
- Informes públicos.

---

# Usos en Threat Intelligence

URLScan resulta útil para:

- Analizar páginas sospechosas.
- Investigar campañas de phishing.
- Detectar infraestructura maliciosa.
- Obtener IOC.
- Complementar investigaciones OSINT.
- Verificar sitios web.

---

# Casos de uso

## Respuesta ante incidentes

Analizar un enlace recibido por correo electrónico antes de acceder a él.

---

## Investigación OSINT

Obtener información sobre la infraestructura utilizada por un sitio web.

---

## Threat Hunting

Relacionar dominios, IPs y recursos utilizados en campañas maliciosas.

---

## Análisis de phishing

Identificar páginas fraudulentas y recopilar evidencias.

---

# Integración con otras herramientas

URLScan suele utilizarse junto con:

- VirusTotal
- AlienVault OTX
- AbuseIPDB
- Hybrid Analysis
- GreyNoise
- Shodan
- Censys

La combinación de estas herramientas proporciona un análisis mucho más completo de una amenaza.

---

# API

URLScan dispone de una API REST que permite:

- Enviar URLs para su análisis.
- Consultar informes automáticamente.
- Obtener capturas de pantalla.
- Integrar resultados en plataformas SIEM y SOAR.

El acceso a determinadas funciones requiere una clave API.

---

# Ventajas

- Gratuito para consultas básicas.
- Capturas completas de la página.
- Información muy detallada.
- API disponible.
- Muy útil para investigar phishing y sitios maliciosos.

---

# Limitaciones

- Algunos análisis pueden ser públicos.
- Determinadas funciones requieren una cuenta.
- No todas las URLs pueden analizarse si presentan restricciones.

---

# Buenas prácticas

- Analizar enlaces sospechosos antes de abrirlos.
- Revisar los dominios e IPs asociados.
- Contrastar los resultados con otras plataformas de Threat Intelligence.
- Documentar los IOC obtenidos durante la investigación.

---

# Caso práctico

**Objetivo:** Analizar una URL sospechosa.

Consulta:

```text
https://example-login.com
```

Información esperada:

- Captura de pantalla.
- Dirección IP.
- Certificado SSL.
- Tecnologías utilizadas.
- Recursos cargados.
- Dominios relacionados.
- Indicadores de compromiso.

---

# Resumen

URLScan es una plataforma muy completa para analizar páginas web y URLs de forma segura. Gracias a sus informes detallados, capturas de pantalla e información sobre la infraestructura utilizada, constituye una herramienta fundamental para investigaciones OSINT, análisis de phishing y procesos de Threat Intelligence.