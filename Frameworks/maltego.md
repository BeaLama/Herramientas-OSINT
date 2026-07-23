# Maltego

## Descripción

**Maltego** es una plataforma de análisis OSINT y visualización de información desarrollada por **Paterva**. Permite recopilar, relacionar y representar gráficamente datos procedentes de múltiples fuentes abiertas mediante grafos interactivos.

Es una de las herramientas más utilizadas por analistas de inteligencia, investigadores OSINT, equipos de ciberseguridad y fuerzas de seguridad para descubrir relaciones entre personas, organizaciones, dominios, direcciones IP, correos electrónicos y otros activos digitales.

---

# ¿Cómo funciona?

Maltego trabaja mediante **entidades** (*Entities*) y **Transforms**.

Las entidades representan elementos de una investigación, como:

- Personas.
- Empresas.
- Dominios.
- Direcciones IP.
- Correos electrónicos.
- Teléfonos.
- Redes sociales.
- URLs.

Los **Transforms** consultan fuentes OSINT y generan automáticamente nuevas entidades relacionadas con la información inicial.

De esta forma, el investigador puede ampliar progresivamente la información obtenida y visualizar todas las relaciones mediante un grafo.

---

# Funciones principales

Maltego permite:

- Relacionar información visualmente.
- Descubrir subdominios.
- Analizar infraestructura.
- Investigar personas.
- Correlacionar direcciones IP.
- Buscar correos electrónicos.
- Analizar organizaciones.
- Integrarse con múltiples servicios OSINT.

---

# Información disponible

Dependiendo del objetivo analizado, Maltego puede obtener:

- Dominios.
- Subdominios.
- Direcciones IP.
- Correos electrónicos.
- Empresas.
- Personas.
- Redes sociales.
- DNS.
- Certificados.
- URLs.
- Teléfonos.
- Información WHOIS.

---

# Entidades

Maltego trabaja con numerosos tipos de entidades, entre ellas:

- Person
- Company
- Domain
- Website
- Email Address
- Phone Number
- IP Address
- DNS Name
- URL
- Location
- Document

Cada entidad puede relacionarse automáticamente con otras mediante los Transforms.

---

# Transforms

Los **Transforms** son el núcleo de Maltego.

Permiten consultar distintas fuentes OSINT para descubrir nueva información relacionada con una entidad.

Ejemplos:

- Obtener los subdominios de un dominio.
- Buscar direcciones IP asociadas.
- Obtener registros WHOIS.
- Buscar perfiles en redes sociales.
- Consultar certificados digitales.
- Analizar relaciones entre empresas.

---

# Usos en OSINT

Maltego puede utilizarse para:

- Investigación de personas.
- Investigación corporativa.
- Análisis de dominios.
- Descubrimiento de infraestructura.
- Correlación de información.
- Investigación de incidentes.
- Threat Intelligence.
- Análisis de redes.

---

# Casos de uso

## Investigación de una empresa

Descubrir dominios, correos electrónicos, subdominios e infraestructura relacionada.

---

## Investigación de una persona

Relacionar perfiles públicos, correos electrónicos, organizaciones y redes sociales.

---

## Reconocimiento

Obtener una visión completa de los activos públicos de un objetivo.

---

## Threat Intelligence

Relacionar indicadores de compromiso obtenidos durante una investigación.

---

# Integración con otras herramientas

Maltego puede trabajar junto con:

- Shodan
- Censys
- VirusTotal
- SecurityTrails
- SpiderFoot
- Recon-ng
- Amass
- theHarvester
- Hunter
- Intelligence X
- Have I Been Pwned
- AlienVault OTX

---

# Instalación

Maltego está disponible para:

- Windows.
- Linux.
- macOS.

Es necesario crear una cuenta para utilizar la versión Community.

---

# Automatización

Además de la interfaz gráfica, Maltego permite:

- Ejecutar Transforms personalizados.
- Integrar APIs externas.
- Automatizar investigaciones.
- Exportar grafos.
- Compartir proyectos.

---

# Ventajas

- Excelente visualización de relaciones.
- Gran cantidad de Transforms.
- Compatible con múltiples fuentes OSINT.
- Muy utilizado profesionalmente.
- Fácil correlación de información.
- Exportación de resultados.

---

# Limitaciones

- Curva de aprendizaje elevada.
- Algunas funciones requieren licencias comerciales.
- Determinados Transforms necesitan claves API.
- El rendimiento puede disminuir en investigaciones muy grandes.

---

# Buenas prácticas

- Definir claramente el objetivo de la investigación antes de comenzar.
- Ejecutar únicamente los Transforms necesarios.
- Verificar siempre la información obtenida.
- Complementar los resultados con otras herramientas OSINT.
- Documentar las relaciones encontradas durante el análisis.

---

# Caso práctico

**Objetivo:** Analizar una organización.

Entidad inicial:

```text
empresa.com
```

Información esperada:

- Subdominios.
- Direcciones IP.
- Correos electrónicos.
- Certificados.
- Registros DNS.
- Empresas relacionadas.
- Infraestructura pública.
- Relaciones entre activos.

Toda la información obtenida se representa automáticamente mediante un grafo interactivo.

---

# Resumen

Maltego es una de las plataformas OSINT más potentes para la recopilación, correlación y visualización de información. Gracias a su sistema de entidades y Transforms, permite descubrir relaciones entre personas, organizaciones, dominios y otros activos digitales de forma intuitiva, convirtiéndose en una herramienta imprescindible para analistas OSINT, investigadores digitales y profesionales de la ciberseguridad.