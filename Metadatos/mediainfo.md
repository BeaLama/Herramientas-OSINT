# MediaInfo

## Descripción

**MediaInfo** es una herramienta gratuita y de código abierto que permite analizar archivos multimedia para obtener información técnica y metadatos. Es ampliamente utilizada en **OSINT**, informática forense y análisis multimedia para identificar las características de vídeos, audios e imágenes.

Su objetivo es mostrar de forma detallada toda la información disponible sobre un archivo sin modificar su contenido.

---

# ¿Cómo funciona?

MediaInfo analiza la estructura interna del archivo y extrae los metadatos almacenados.

Los resultados pueden visualizarse desde una interfaz gráfica o mediante la línea de comandos, facilitando su integración en procesos automatizados.

---

# Funciones principales

MediaInfo permite:

- Analizar archivos multimedia.
- Mostrar metadatos.
- Identificar códecs.
- Obtener información técnica.
- Exportar resultados.
- Procesar múltiples archivos.

---

# Información disponible

Dependiendo del archivo, puede mostrar:

- Formato.
- Tamaño.
- Duración.
- Resolución.
- Velocidad de fotogramas (FPS).
- Códec de vídeo.
- Códec de audio.
- Fecha de creación.
- Software utilizado.
- Metadatos disponibles.

---

# Formatos compatibles

MediaInfo admite una gran variedad de formatos, entre ellos:

- MP4.
- AVI.
- MKV.
- MOV.
- MP3.
- WAV.
- FLAC.
- JPG.
- PNG.
- TIFF.

---

# Uso básico

Analizar un archivo:

```bash
mediainfo video.mp4
```

Exportar los resultados:

```bash
mediainfo --Output=HTML video.mp4
```

---

# Usos en OSINT

MediaInfo resulta útil para:

- Analizar vídeos.
- Examinar archivos de audio.
- Verificar metadatos.
- Identificar software de edición.
- Comparar archivos multimedia.
- Apoyar investigaciones forenses.

---

# Casos de uso

## Investigación de vídeos

Obtener información técnica para verificar la autenticidad de un archivo.

---

## Análisis forense

Examinar archivos multimedia como evidencia digital.

---

## Verificación

Comprobar si un vídeo ha sido codificado o modificado mediante determinado software.

---

## Investigación OSINT

Complementar el análisis de imágenes y vídeos con información técnica.

---

# Integración con otras herramientas

MediaInfo suele utilizarse junto con:

- ExifTool
- FOCA
- PDFInfo
- Google Earth
- Google Maps

La combinación de estas herramientas permite realizar un análisis más completo de los archivos digitales.

---

# Instalación

MediaInfo está disponible para:

- Windows.
- Linux.
- macOS.

También existe una versión portátil y una interfaz de línea de comandos.

---

# Ventajas

- Gratuito y de código abierto.
- Compatible con numerosos formatos.
- Muy sencillo de utilizar.
- Interfaz gráfica y línea de comandos.
- Exportación de resultados.

---

# Limitaciones

- Solo analiza información técnica y metadatos.
- Algunos archivos contienen muy pocos metadatos.
- No recupera información eliminada.

---

# Buenas prácticas

- Analizar siempre el archivo original.
- Comparar los metadatos con otras evidencias.
- Complementar el análisis con ExifTool cuando sea posible.
- Documentar toda la información obtenida.

---

# Caso práctico

**Objetivo:** Analizar un vídeo.

Comando:

```bash
mediainfo video.mp4
```

Información esperada:

- Formato.
- Duración.
- Resolución.
- Códec de vídeo.
- Códec de audio.
- Software utilizado.
- Metadatos disponibles.

---

# Resumen

MediaInfo es una herramienta esencial para el análisis técnico de archivos multimedia. Gracias a su capacidad para mostrar metadatos y características de vídeos, audios e imágenes, constituye un excelente recurso para investigaciones OSINT, análisis forense y verificación de archivos digitales.