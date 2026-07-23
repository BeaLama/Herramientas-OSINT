# Bing

## Descripción

Bing es el motor de búsqueda desarrollado por Microsoft. Es una alternativa a Google y resulta muy útil en investigaciones **OSINT (Open Source Intelligence)** gracias a su capacidad para indexar sitios web, documentos, imágenes y vídeos.

---

# ¿Cómo funciona?

Bing basa su funcionamiento en tres etapas:

1. **Rastreo (Crawling):** Bingbot recorre Internet en busca de nuevas páginas.
2. **Indexación (Indexing):** La información encontrada se almacena en el índice de Bing.
3. **Clasificación (Ranking):** Los resultados se ordenan según su relevancia.

---

# Usos en OSINT

- Buscar información pública.
- Localizar documentos.
- Encontrar perfiles en redes sociales.
- Buscar empresas.
- Investigar dominios.
- Localizar imágenes y vídeos.
- Contrastar resultados con otros buscadores.

---

# Operadores básicos

| Operador | Función |
|----------|---------|
| `"texto"` | Busca una frase exacta. |
| `-palabra` | Excluye una palabra. |
| `OR` | Busca una opción u otra. |
| `()` | Agrupa términos. |

### Ejemplos

```text
"Juan Pérez"

seguridad -firewall

OpenAI OR Microsoft
```

---

# Operadores avanzados

| Operador | Descripción |
|----------|-------------|
| `site:` | Busca dentro de un dominio. |
| `filetype:` | Busca archivos específicos. |
| `intitle:` | Busca en el título. |
| `inurl:` | Busca en la URL. |
| `contains:` | Busca páginas que enlazan a un tipo de archivo. |
| `ip:` | Busca sitios asociados a una IP (soporte limitado). |

### Ejemplos

```text
site:empresa.com

site:empresa.com filetype:pdf

intitle:login

inurl:admin

contains:pdf seguridad
```

---

# Búsqueda de documentos

Bing destaca por encontrar documentos públicos como:

- PDF
- DOCX
- XLSX
- PPTX

Ejemplos:

```text
site:empresa.com filetype:pdf

site:empresa.com filetype:xlsx

site:empresa.com filetype:docx
```

---

# Búsqueda de imágenes

Bing Images permite:

- Buscar imágenes similares.
- Filtrar por tamaño, color y tipo.
- Buscar por licencia.
- Realizar búsqueda inversa mediante imágenes.

---

# Búsqueda de vídeos

Bing Video permite:

- Buscar vídeos por duración.
- Filtrar por resolución.
- Buscar emisiones en directo.
- Localizar contenido publicado en distintas plataformas.

---

# Ventajas

- Excelente búsqueda de documentos.
- Muy buena búsqueda de imágenes y vídeos.
- Interfaz sencilla.
- Integración con Microsoft.
- Complementa los resultados de otros buscadores.

---

# Limitaciones

- Índice menor que Google.
- Algunos operadores tienen soporte limitado.
- Menor cantidad de resultados en ciertos idiomas.

---

# Buenas prácticas

- Combinar Bing con otros motores de búsqueda.
- Utilizar operadores para afinar los resultados.
- Verificar siempre la información encontrada.
- Guardar las fuentes consultadas.

---

# Casos prácticos

**Buscar documentos PDF:**

```text
site:empresa.com filetype:pdf
```

**Buscar perfiles de LinkedIn:**

```text
site:linkedin.com/in "Nombre Apellido"
```

**Buscar paneles de administración públicos:**

```text
intitle:login

inurl:admin
```

---

# Herramientas complementarias

- Bing Images
- Bing Video
- Bing Maps
- Microsoft Copilot

---

# Resumen

Bing es un motor de búsqueda muy útil para OSINT, especialmente para localizar documentos, imágenes y contenido multimedia. Aunque su índice es menor que el de Google, ofrece resultados diferentes que pueden aportar información valiosa en una investigación.