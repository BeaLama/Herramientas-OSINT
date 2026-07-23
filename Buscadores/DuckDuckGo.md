# DuckDuckGo

## Descripción

DuckDuckGo es un motor de búsqueda centrado en la **privacidad del usuario**. A diferencia de otros buscadores, no crea perfiles de usuario ni personaliza los resultados en función del historial de búsqueda. Es una herramienta útil en investigaciones **OSINT** porque ofrece resultados más neutrales y reduce el sesgo por personalización.

---

# ¿Cómo funciona?

DuckDuckGo obtiene resultados de diversas fuentes, entre ellas:

- Su propio rastreador (DuckDuckBot).
- Bing.
- Wikipedia.
- Stack Overflow.
- Otras fuentes públicas.

Su funcionamiento se basa en:

1. Rastreo de páginas web.
2. Indexación de información.
3. Clasificación de resultados.
4. Presentación sin personalización del usuario.

---

# Usos en OSINT

- Buscar información pública.
- Contrastar resultados con Google y Bing.
- Investigar personas y empresas.
- Localizar documentación pública.
- Buscar contenido técnico.
- Evitar resultados personalizados.

---

# Características principales

- No almacena el historial de búsqueda.
- No rastrea al usuario.
- No utiliza perfiles publicitarios.
- Resultados menos influenciados por búsquedas anteriores.
- Interfaz sencilla y rápida.

---

# Operadores de búsqueda

DuckDuckGo admite muchos operadores similares a otros buscadores.

| Operador | Función |
|----------|---------|
| `"texto"` | Busca una frase exacta. |
| `site:` | Limita la búsqueda a un dominio. |
| `filetype:` | Busca un tipo de archivo. |
| `intitle:` | Busca palabras en el título. |
| `-palabra` | Excluye una palabra. |
| `OR` | Busca una opción u otra. |

### Ejemplos

```text
site:empresa.com

site:empresa.com filetype:pdf

"Juan Pérez"

site:github.com API

intitle:login
```

---

# Bangs (!)

Una de las funciones más conocidas de DuckDuckGo son los **Bangs**, que permiten realizar búsquedas directamente en otros sitios web.

Ejemplos:

```text
!g OpenAI
```

Busca en Google.

```text
!w OSINT
```

Busca en Wikipedia.

```text
!yt Ciberseguridad
```

Busca en YouTube.

```text
!gh ChatGPT
```

Busca en GitHub.

```text
!r OSINT
```

Busca en Reddit.

Existen miles de Bangs disponibles para acceder rápidamente a diferentes servicios.

---

# Casos de uso en OSINT

- Buscar documentación técnica.
- Localizar perfiles públicos.
- Encontrar proyectos en GitHub.
- Buscar publicaciones en Reddit.
- Consultar artículos de Wikipedia.
- Comparar resultados con otros buscadores.

---

# Ventajas

- Mayor privacidad.
- Resultados poco personalizados.
- Compatible con numerosos operadores.
- Función Bang para búsquedas rápidas.
- Interfaz ligera y rápida.

---

# Limitaciones

- Índice propio más reducido.
- Algunos resultados dependen de fuentes externas.
- Menor cobertura que Google en ciertos idiomas.

---

# Buenas prácticas

- Utilizar Bangs para acelerar búsquedas.
- Comparar resultados con Google y Bing.
- Emplear operadores avanzados para búsquedas precisas.
- Verificar siempre la información obtenida.

---

# Herramientas relacionadas

- DuckDuckGo Browser
- Duck.ai (IA integrada)
- DuckDuckGo Email Protection
- DuckDuckGo Privacy Essentials

---

# Caso práctico

**Buscar documentos PDF en un dominio:**

```text
site:empresa.com filetype:pdf
```

**Buscar un repositorio en GitHub:**

```text
!gh osint-framework
```

**Buscar una definición en Wikipedia:**

```text
!w Open Source Intelligence
```

---

# Resumen

DuckDuckGo es un buscador orientado a la privacidad que resulta especialmente útil en investigaciones OSINT por ofrecer resultados menos personalizados y permitir búsquedas rápidas mediante los **Bangs**, facilitando el acceso directo a miles de sitios web y servicios especializados.