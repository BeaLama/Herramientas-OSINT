# ExifTool

## Descripción

**ExifTool** es una herramienta de línea de comandos desarrollada por **Phil Harvey** que permite leer, modificar y eliminar metadatos de una gran variedad de archivos. Es una de las herramientas más utilizadas en **OSINT**, análisis forense y ciberseguridad para extraer información oculta de imágenes, documentos, vídeos y archivos de audio.

Gracias a su amplio soporte de formatos, es considerada el estándar para el análisis de metadatos.

---

# ¿Cómo funciona?

ExifTool analiza los metadatos almacenados dentro de un archivo y muestra toda la información disponible.

Además de consultar los datos, permite modificarlos, eliminarlos o exportarlos para su posterior análisis.

Puede utilizarse desde la terminal o integrarse en scripts y procesos automatizados.

---

# Funciones principales

ExifTool permite:

- Leer metadatos.
- Modificar metadatos.
- Eliminar metadatos.
- Exportar información.
- Analizar múltiples archivos.
- Procesar directorios completos.

---

# Información disponible

Dependiendo del archivo, puede mostrar:

- Fecha de creación.
- Fecha de modificación.
- Modelo de cámara.
- Fabricante.
- Configuración de la cámara.
- Coordenadas GPS.
- Autor.
- Software utilizado.
- Resolución.
- Información EXIF, IPTC y XMP.

---

# Formatos compatibles

ExifTool admite cientos de formatos, entre ellos:

- JPG.
- PNG.
- TIFF.
- RAW.
- PDF.
- DOCX.
- MP4.
- MOV.
- MP3.
- WAV.

---

# Uso básico

Mostrar todos los metadatos:

```bash
exiftool imagen.jpg
```

Analizar varios archivos:

```bash
exiftool carpeta/*
```

Eliminar metadatos:

```bash
exiftool -all= imagen.jpg
```

---

# Usos en OSINT

ExifTool resulta útil para:

- Analizar fotografías.
- Obtener coordenadas GPS.
- Identificar dispositivos.
- Verificar fechas.
- Analizar documentos.
- Detectar software utilizado para crear un archivo.

---

# Casos de uso

## Investigación de imágenes

Extraer información EXIF para conocer cuándo y con qué dispositivo fue tomada una fotografía.

---

## Análisis forense

Examinar metadatos de documentos y archivos multimedia durante una investigación.

---

## Verificación

Comprobar si los metadatos coinciden con la información declarada por el autor.

---

## Privacidad

Eliminar metadatos antes de compartir imágenes o documentos.

---

# Integración con otras herramientas

ExifTool suele utilizarse junto con:

- FOCA
- MediaInfo
- PDFInfo
- Google Maps
- Google Earth

La combinación de estas herramientas permite realizar un análisis completo de archivos y su contexto geográfico.

---

# Instalación

ExifTool está disponible para:

- Windows.
- Linux.
- macOS.

También suele incluirse en distribuciones orientadas a ciberseguridad como Kali Linux.

---

# Ventajas

- Gratuito y de código abierto.
- Compatible con cientos de formatos.
- Muy rápido.
- Gran cantidad de información disponible.
- Amplias opciones de automatización.

---

# Limitaciones

- Se utiliza desde la línea de comandos.
- Algunos archivos pueden no contener metadatos.
- La información puede haber sido modificada o eliminada previamente.

---

# Buenas prácticas

- Analizar siempre una copia del archivo original.
- Verificar la coherencia de las fechas y coordenadas.
- Complementar el análisis con otras herramientas OSINT.
- Conservar los metadatos originales como evidencia cuando sea necesario.

---

# Caso práctico

**Objetivo:** Analizar una fotografía.

Comando:

```bash
exiftool fotografia.jpg
```

Información esperada:

- Fecha de captura.
- Modelo de cámara.
- Coordenadas GPS.
- Resolución.
- Software utilizado.
- Información EXIF completa.

---

# Resumen

ExifTool es la herramienta de referencia para el análisis de metadatos en investigaciones OSINT y forenses. Gracias a su compatibilidad con cientos de formatos y a su capacidad para leer, modificar y eliminar metadatos, constituye un recurso imprescindible para obtener información oculta en archivos digitales y verificar su autenticidad.