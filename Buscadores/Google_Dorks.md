# Google Dorks

## Descripción

**Google Dorking** (también conocido como **Google Hacking**) consiste en utilizar operadores avanzados de Google para localizar información pública de forma más precisa. Es una técnica ampliamente utilizada en **OSINT (Open Source Intelligence)** para encontrar documentos, directorios, perfiles y otros recursos disponibles en Internet.

> **Importante:** Google Dorking debe utilizarse únicamente sobre información pública y con fines legítimos como investigación, auditoría, formación o análisis de seguridad.

---

# ¿Cómo funciona?

Google indexa millones de páginas web. Mediante operadores de búsqueda es posible limitar y filtrar los resultados para encontrar información específica de forma más eficiente.

Ejemplo:

```text
site:empresa.com filetype:pdf
```

Busca únicamente archivos PDF dentro del dominio `empresa.com`.

---

# Operadores más utilizados

| Operador | Función |
|----------|---------|
| `site:` | Limita la búsqueda a un dominio. |
| `filetype:` | Busca un tipo de archivo. |
| `intitle:` | Busca palabras en el título. |
| `allintitle:` | Todas las palabras deben estar en el título. |
| `inurl:` | Busca palabras en la URL. |
| `allinurl:` | Todas las palabras deben aparecer en la URL. |
| `intext:` | Busca palabras dentro del contenido. |
| `allintext:` | Todas las palabras deben estar en el contenido. |
| `related:` | Sitios similares. |
| `cache:` | Muestra la versión en caché (si está disponible). |
| `"texto"` | Busca una frase exacta. |
| `OR` | Busca una opción u otra. |
| `-palabra` | Excluye una palabra. |
| `*` | Comodín. |

---

# Ejemplos básicos

Buscar una frase exacta:

```text
"Open Source Intelligence"
```

Buscar dentro de un sitio web:

```text
site:empresa.com
```

Buscar archivos PDF:

```text
site:empresa.com filetype:pdf
```

Buscar documentos Word:

```text
site:empresa.com filetype:docx
```

Buscar hojas de cálculo:

```text
site:empresa.com filetype:xlsx
```

Buscar presentaciones:

```text
site:empresa.com filetype:pptx
```

---

# Búsqueda de personas

Buscar un perfil:

```text
"Juan Pérez"
```

Buscar perfiles en LinkedIn:

```text
site:linkedin.com/in "Juan Pérez"
```

Buscar perfiles en GitHub:

```text
site:github.com "Juan Pérez"
```

---

# Búsqueda de empresas

Buscar una empresa:

```text
"Empresa S.A."
```

Buscar documentos públicos:

```text
site:empresa.com filetype:pdf
```

Buscar noticias:

```text
site:empresa.com noticia
```

---

# Búsqueda de documentación

PDF:

```text
filetype:pdf ciberseguridad
```

Word:

```text
filetype:docx auditoría
```

Excel:

```text
filetype:xlsx inventario
```

PowerPoint:

```text
filetype:pptx formación
```

---

# Combinación de operadores

Ejemplo:

```text
site:empresa.com filetype:pdf "seguridad"
```

Busca archivos PDF que contengan la palabra **seguridad** dentro del dominio indicado.

Otro ejemplo:

```text
site:gov.es filetype:pdf ciberseguridad
```

---

# Usos en OSINT

- Localizar documentos públicos.
- Encontrar perfiles profesionales.
- Buscar empresas.
- Investigar dominios.
- Buscar noticias.
- Localizar manuales técnicos.
- Encontrar publicaciones académicas.

---

# Buenas prácticas

- Utilizar varios operadores combinados.
- Revisar varias páginas de resultados.
- Contrastar la información con otras fuentes.
- Documentar las consultas realizadas.
- Mantener un enfoque ético y respetar la normativa aplicable.

---

# Limitaciones

- Solo permite buscar contenido indexado por Google.
- Algunas páginas bloquean la indexación.
- Los resultados pueden variar según la ubicación o el idioma.
- No toda la información pública aparece en el índice.

---

# Casos prácticos

**Buscar documentos PDF de una organización:**

```text
site:empresa.com filetype:pdf
```

**Buscar publicaciones de una universidad:**

```text
site:universidad.edu filetype:pdf investigación
```

**Buscar perfiles profesionales:**

```text
site:linkedin.com/in "Nombre Apellido"
```

**Buscar repositorios públicos:**

```text
site:github.com "Nombre Proyecto"
```

---

# Consejos

- Empieza con búsquedas simples y añade operadores progresivamente.
- Combina Google Dorks con otras herramientas OSINT como Bing, DuckDuckGo o Yandex.
- Guarda las búsquedas más útiles para reutilizarlas en futuras investigaciones.

---

# Resumen

Google Dorking es una técnica que aprovecha los operadores avanzados de Google para realizar búsquedas más precisas sobre información pública. Utilizado de forma responsable, permite localizar documentos, perfiles, publicaciones y otros recursos de gran utilidad en investigaciones OSINT.