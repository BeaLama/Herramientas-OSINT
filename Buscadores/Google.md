# Google

## Descripción

Google Search es el motor de búsqueda más utilizado del mundo y una de las herramientas más importantes en investigaciones **OSINT (Open Source Intelligence)**. Permite localizar información pública mediante palabras clave y operadores de búsqueda avanzados.

---

# ¿Cómo funciona?

Google realiza tres procesos principales:

1. **Rastreo (Crawling)**: Googlebot recorre Internet descubriendo nuevas páginas.
2. **Indexación (Indexing)**: almacena la información encontrada en su índice.
3. **Clasificación (Ranking)**: ordena los resultados según su relevancia.

---

# Usos en OSINT

- Localizar personas.
- Buscar empresas.
- Encontrar documentos públicos.
- Descubrir subdominios.
- Buscar archivos expuestos.
- Investigar redes sociales.
- Encontrar noticias antiguas.
- Ver páginas almacenadas en caché.

---

# Operadores básicos

| Operador | Función |
|----------|---------|
| `"texto"` | Busca la frase exacta. |
| `-palabra` | Excluye una palabra. |
| `OR` | Busca una opción u otra. |
| `*` | Comodín. |
| `()` | Agrupa búsquedas. |

### Ejemplos

```text
"Juan Pérez"

"OpenAI" OR "ChatGPT"

seguridad -firewall
```

---

# Operadores avanzados

| Operador | Descripción |
|----------|-------------|
| `site:` | Limita la búsqueda a un dominio. |
| `filetype:` | Busca tipos de archivos. |
| `intitle:` | Busca palabras en el título. |
| `inurl:` | Busca palabras en la URL. |
| `related:` | Sitios similares. |
| `cache:` | Versión almacenada (si está disponible). |

### Ejemplos

```text
site:example.com

site:example.com filetype:pdf

site:github.com "API"

intitle:index.of

inurl:admin
```

---

# Google Dorking

Google Dorking consiste en combinar operadores para localizar información pública de forma más precisa.

Ejemplos:

```text
site:empresa.com filetype:pdf

site:empresa.com filetype:xlsx

site:github.com "API_KEY"

site:linkedin.com/in "Ingeniero"

site:gov.es filetype:pdf

intitle:"index of"

inurl:login
```

---

# Servicios útiles para OSINT

## Google Images

Permite buscar imágenes similares o realizar búsquedas inversas.

---

## Google Lens

Reconoce objetos, texto, lugares y productos en imágenes.

---

## Google Maps

Permite investigar:

- Empresas
- Direcciones
- Coordenadas
- Street View
- Horarios

---

## Google Earth

Permite visualizar imágenes satelitales e históricas.

---

## Google Scholar

Buscador de artículos científicos y publicaciones académicas.

---

## Google News

Permite localizar noticias actuales e históricas.

---

# Ventajas

- Gran cobertura de Internet.
- Búsquedas muy rápidas.
- Gran cantidad de operadores.
- Integración con otros servicios de Google.
- Excelente para investigaciones OSINT.

---

# Limitaciones

- No indexa toda la web.
- Algunos resultados dependen de la ubicación.
- La personalización puede modificar los resultados.
- Parte del contenido requiere autenticación y no aparece en el índice.

---

# Buenas prácticas

- Utilizar operadores de búsqueda.
- Contrastar la información obtenida.
- Combinar Google con otras herramientas OSINT.
- Guardar las fuentes consultadas.
- Documentar la fecha de la búsqueda.

---

# Herramientas complementarias

- Google Images
- Google Lens
- Google Maps
- Google Earth
- Google Scholar
- Google News
- Google Alerts

---

# Caso práctico

**Objetivo:** Buscar documentos PDF publicados por un dominio.

```text
site:empresa.com filetype:pdf
```

**Objetivo:** Buscar perfiles de LinkedIn.

```text
site:linkedin.com/in "Nombre Apellido"
```

**Objetivo:** Buscar repositorios públicos.

```text
site:github.com "empresa"
```

---

# Resumen

Google es la herramienta OSINT más utilizada gracias a su enorme índice de información pública y al uso de operadores avanzados que permiten localizar documentos, personas, empresas y recursos específicos de forma rápida y eficiente.