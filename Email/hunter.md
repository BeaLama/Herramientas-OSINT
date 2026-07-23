# Hunter

## Descripción

**Hunter** es una plataforma OSINT especializada en la búsqueda, identificación y verificación de direcciones de correo electrónico asociadas a personas y organizaciones. Es una herramienta ampliamente utilizada por investigadores, analistas de seguridad y profesionales de la inteligencia para descubrir información pública relacionada con dominios corporativos.

Hunter recopila datos de múltiples fuentes abiertas y permite conocer las direcciones de correo utilizadas por una empresa, así como verificar si una dirección concreta es válida.

---

# ¿Cómo funciona?

Hunter recopila información procedente de páginas web, documentos públicos y otras fuentes abiertas para identificar direcciones de correo electrónico asociadas a un dominio.

Cuando el usuario realiza una búsqueda, la plataforma analiza la información disponible y genera un informe con las direcciones encontradas, su nivel de confianza y las fuentes donde han sido localizadas.

---

# Funciones principales

Hunter ofrece varias herramientas especializadas:

- Domain Search.
- Email Finder.
- Email Verifier.
- Author Finder.
- Bulk Tasks.
- API para automatización.

---

# Información disponible

Dependiendo del tipo de búsqueda, Hunter puede mostrar:

- Dirección de correo electrónico.
- Nombre de la persona.
- Empresa.
- Cargo.
- Departamento.
- Nivel de confianza.
- Fuentes donde aparece el correo.
- Patrón de direcciones utilizado por la organización.

---

# Usos en OSINT

Hunter resulta útil para:

- Identificar correos corporativos.
- Investigar organizaciones.
- Verificar direcciones de correo.
- Descubrir empleados públicos.
- Analizar la estructura de una empresa.
- Complementar investigaciones de identidad.

---

# Herramientas principales

## Domain Search

Permite obtener todas las direcciones de correo público asociadas a un dominio.

Ejemplo:

```text
empresa.com
```

---

## Email Finder

Busca la dirección de correo de una persona a partir de su nombre y empresa.

Ejemplo:

```text
Nombre: Juan Pérez
Empresa: empresa.com
```

---

## Email Verifier

Comprueba si una dirección de correo electrónico parece válida y puede recibir mensajes.

Ejemplo:

```text
juan.perez@empresa.com
```

---

## Author Finder

Permite localizar autores de artículos y publicaciones junto con sus direcciones de correo cuando están disponibles.

---

# Casos de uso

## Investigación corporativa

Identificar empleados públicos y direcciones de correo asociadas a una empresa.

---

## Auditorías de seguridad

Comprobar qué información sobre una organización está expuesta públicamente.

---

## Reconocimiento

Obtener direcciones de correo que posteriormente puedan verificarse con otras herramientas OSINT.

---

## Respuesta ante incidentes

Relacionar direcciones de correo con personas o departamentos durante una investigación.

---

# Integración con otras herramientas

Hunter suele utilizarse junto con:

- EmailRep
- Have I Been Pwned
- DeHashed
- Intelligence X
- SpiderFoot
- Maltego
- Recon-ng
- theHarvester

---

# API

Hunter dispone de una API que permite automatizar consultas como:

- Búsqueda de dominios.
- Verificación de correos.
- Localización de direcciones.
- Procesamiento masivo de consultas.

Es necesario disponer de una clave API.

---

# Ventajas

- Interfaz sencilla.
- Resultados rápidos.
- Alta precisión.
- API disponible.
- Permite verificar direcciones de correo.

---

# Limitaciones

- La versión gratuita tiene un número limitado de consultas.
- Solo muestra información procedente de fuentes públicas.
- No garantiza que todos los correos encontrados estén activos.

---

# Buenas prácticas

- Contrastar los resultados con otras herramientas OSINT.
- Verificar siempre los correos antes de utilizarlos.
- Documentar las fuentes de donde procede la información.
- Utilizar la API para automatizar investigaciones recurrentes.

---

# Caso práctico

**Objetivo:** Obtener los correos públicos de una empresa.

Dominio:

```text
empresa.com
```

Información esperada:

- Direcciones de correo.
- Nombre de los empleados.
- Cargo.
- Nivel de confianza.
- Fuentes donde aparece cada dirección.
- Patrón de correo utilizado por la organización.

---

# Resumen

Hunter es una de las herramientas más utilizadas para localizar y verificar direcciones de correo electrónico en investigaciones OSINT. Gracias a sus funciones de búsqueda por dominio, localización de personas y verificación de direcciones, permite obtener rápidamente información pública sobre empleados y organizaciones, siendo un excelente complemento para herramientas como EmailRep, Have I Been Pwned o DeHashed.