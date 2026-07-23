# Recon-ng

## Descripción

**Recon-ng** es un framework de reconocimiento y recopilación de información (**OSINT**) desarrollado en Python. Proporciona una consola interactiva similar a la de Metasploit, permitiendo automatizar la obtención de información sobre dominios, organizaciones, personas e infraestructuras mediante módulos especializados.

Es una herramienta muy utilizada por analistas OSINT, pentesters y equipos de ciberseguridad durante la fase de reconocimiento.

---

# ¿Cómo funciona?

Recon-ng utiliza una arquitectura basada en módulos. Cada módulo realiza una tarea específica, como consultar una API, buscar subdominios o recopilar direcciones de correo electrónico.

Los resultados obtenidos se almacenan en una base de datos interna, lo que permite reutilizar la información en módulos posteriores y correlacionar fácilmente los datos recopilados.

---

# Funciones principales

Recon-ng permite:

- Descubrir subdominios.
- Buscar correos electrónicos.
- Analizar dominios.
- Consultar registros WHOIS.
- Enumerar hosts.
- Buscar información sobre empresas.
- Automatizar investigaciones.
- Exportar resultados.

---

# Información disponible

Dependiendo del módulo utilizado, puede obtener:

- Dominios.
- Subdominios.
- Direcciones IP.
- Correos electrónicos.
- Empresas.
- Contactos.
- Servidores DNS.
- Información WHOIS.
- Hosts.
- Certificados digitales.

---

# Espacios de trabajo (Workspaces)

Recon-ng organiza cada investigación mediante **Workspaces**.

Cada Workspace almacena:

- Objetivos.
- Resultados.
- Configuración.
- Historial de consultas.

Esto permite mantener separadas distintas investigaciones.

---

# Módulos

Los módulos se clasifican por categorías, entre ellas:

- Reconocimiento de dominios.
- Correos electrónicos.
- DNS.
- Empresas.
- Contactos.
- Geolocalización.
- Infraestructura.
- APIs externas.

Cada módulo puede configurarse con diferentes opciones antes de ejecutarse.

---

# Uso básico

Crear un Workspace:

```bash
workspaces create investigacion
```

Mostrar módulos disponibles:

```bash
marketplace search
```

Cargar un módulo:

```bash
modules load recon/domains-hosts/bing_domain_web
```

Ejecutar el módulo:

```bash
run
```

---

# Usos en OSINT

Recon-ng resulta útil para:

- Investigación de organizaciones.
- Reconocimiento de dominios.
- Descubrimiento de subdominios.
- Obtención de correos electrónicos.
- Automatización de consultas.
- Correlación de información.

---

# Casos de uso

## Investigación corporativa

Obtener información pública relacionada con una empresa y sus dominios.

---

## Pentesting

Recopilar información antes de realizar una auditoría de seguridad.

---

## Threat Intelligence

Relacionar dominios, IPs y otros indicadores de compromiso.

---

## Automatización

Ejecutar múltiples módulos para obtener información desde distintas fuentes sin realizar consultas manuales.

---

# Integración con otras herramientas

Recon-ng puede utilizarse junto con:

- theHarvester
- Amass
- BBOT
- SpiderFoot
- Shodan
- Censys
- VirusTotal
- Hunter
- Intelligence X
- SecurityTrails
- Maltego

---

# Instalación

Recon-ng puede instalarse mediante Git:

```bash
git clone https://github.com/lanmaster53/recon-ng.git
```

También está disponible en distribuciones orientadas a ciberseguridad como Kali Linux.

---

# APIs

Muchos módulos utilizan APIs externas para ampliar la información obtenida.

Entre ellas:

- Shodan.
- VirusTotal.
- Hunter.
- SecurityTrails.
- Bing.
- Google.
- GitHub.

Para algunos servicios es necesario configurar una clave API.

---

# Ventajas

- Código abierto.
- Arquitectura modular.
- Automatización de tareas.
- Consola intuitiva.
- Base de datos integrada.
- Compatible con numerosas APIs.

---

# Limitaciones

- Algunos módulos requieren claves API.
- La cantidad de información depende de las fuentes consultadas.
- Requiere conocimientos básicos de línea de comandos.
- Algunos módulos pueden quedar desactualizados con el tiempo.

---

# Buenas prácticas

- Crear un Workspace para cada investigación.
- Configurar correctamente las APIs antes de comenzar.
- Ejecutar únicamente los módulos necesarios.
- Contrastar los resultados con otras herramientas OSINT.
- Documentar la información obtenida.

---

# Caso práctico

**Objetivo:** Obtener información pública sobre un dominio.

Dominio:

```text
empresa.com
```

Información esperada:

- Subdominios.
- Direcciones IP.
- Correos electrónicos.
- Hosts.
- DNS.
- Información WHOIS.
- Relaciones con otros activos.

Toda la información queda almacenada en el Workspace para poder continuar la investigación con otros módulos.

---

# Resumen

Recon-ng es uno de los frameworks OSINT más completos para automatizar la recopilación de información durante la fase de reconocimiento. Gracias a su arquitectura modular, su base de datos integrada y su compatibilidad con múltiples APIs, permite realizar investigaciones estructuradas sobre dominios, organizaciones y activos digitales de forma eficiente y organizada.