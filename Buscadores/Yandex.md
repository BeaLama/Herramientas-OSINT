# Yandex

## Descripción

Yandex es el motor de búsqueda desarrollado por la empresa rusa **Yandex**. Es especialmente conocido en el ámbito OSINT por su potente **búsqueda inversa de imágenes**, capaz de encontrar imágenes similares, diferentes resoluciones y posibles coincidencias faciales o de objetos.

---

# ¿Cómo funciona?

Yandex realiza tres procesos principales:

1. **Rastreo (Crawling):** YandexBot explora sitios web.
2. **Indexación (Indexing):** Almacena la información en su índice.
3. **Clasificación (Ranking):** Ordena los resultados según distintos factores de relevancia.

---

# Usos en OSINT

- Buscar información pública.
- Localizar personas y empresas.
- Buscar imágenes similares.
- Identificar lugares y objetos.
- Buscar documentos públicos.
- Contrastar resultados con otros buscadores.

---

# Características principales

- Gran cobertura de sitios de Europa del Este y Asia.
- Excelente búsqueda inversa de imágenes.
- Búsqueda por texto, imágenes, vídeos y mapas.
- Resultados diferentes a Google y Bing.

---

# Operadores de búsqueda

| Operador | Función |
|----------|---------|
| `"texto"` | Busca una frase exacta. |
| `site:` | Limita la búsqueda a un dominio. |
| `filetype:` | Busca archivos específicos. |
| `host:` | Busca dentro de un host concreto. |
| `mime:` | Filtra por tipo de archivo. |
| `url:` | Busca texto dentro de una URL. |
| `-palabra` | Excluye una palabra. |

### Ejemplos

```text
site:empresa.com

site:empresa.com filetype:pdf

"Juan Pérez"

host:example.com

mime:pdf seguridad
```

---

# Búsqueda inversa de imágenes

Una de las funciones más útiles de Yandex para OSINT.

Permite:

- Encontrar imágenes similares.
- Localizar versiones en mayor resolución.
- Buscar imágenes recortadas.
- Identificar lugares.
- Reconocer objetos.
- Encontrar posibles coincidencias de rostros.
- Descubrir el origen de una imagen.

---

# Casos de uso en OSINT

- Verificar fotografías.
- Identificar perfiles falsos.
- Localizar la fuente original de una imagen.
- Buscar imágenes reutilizadas.
- Analizar fotografías de eventos.

---

# Servicios útiles

## Yandex Images

Búsqueda y análisis de imágenes.

---

## Yandex Maps

Mapas y fotografías de calles en determinadas regiones.

---

## Yandex Translate

Traductor útil para investigaciones internacionales.

---

## Yandex Video

Búsqueda de contenido multimedia.

---

# Ventajas

- Excelente búsqueda inversa de imágenes.
- Buenos resultados para contenido de Europa del Este.
- Resultados diferentes a Google.
- Útil para verificar fotografías.

---

# Limitaciones

- Menor cobertura en algunos idiomas occidentales.
- Parte de los resultados pueden estar orientados a regiones específicas.
- Algunas funciones pueden variar según el país.

---

# Buenas prácticas

- Utilizar Yandex junto con Google Images y Bing Images.
- Verificar siempre las coincidencias encontradas.
- Comparar resultados entre distintos buscadores.
- Guardar las fuentes originales.

---

# Herramientas complementarias

- Yandex Images
- Yandex Maps
- Yandex Translate
- Yandex Video

---

# Caso práctico

**Buscar documentos PDF:**

```text
site:empresa.com filetype:pdf
```

**Buscar una imagen similar:**

1. Acceder a **Yandex Images**.
2. Subir una imagen o pegar su URL.
3. Analizar las coincidencias y el posible origen.

**Buscar información sobre un dominio:**

```text
site:empresa.com
```

---

# Resumen

Yandex es un motor de búsqueda muy valioso para OSINT, especialmente por su capacidad de **búsqueda inversa de imágenes**, que facilita la verificación de fotografías, la identificación de objetos y la localización de imágenes publicadas en diferentes sitios web. Es una excelente herramienta complementaria a Google y Bing.