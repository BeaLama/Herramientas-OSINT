# PDFInfo

## Descripción

**PDFInfo** es una herramienta de línea de comandos incluida en el paquete **Poppler** (anteriormente Xpdf) que permite obtener información técnica y metadatos de documentos PDF. Es ampliamente utilizada en **OSINT**, informática forense y auditorías de seguridad para analizar documentos sin modificar su contenido.

Su objetivo es mostrar de forma rápida los metadatos y las características principales de un archivo PDF.

---

# ¿Cómo funciona?

PDFInfo analiza la estructura interna del documento y extrae los metadatos disponibles.

La herramienta muestra información técnica del archivo, como el autor, el título, la fecha de creación, el software utilizado o el número de páginas, entre otros datos.

---

# Funciones principales

PDFInfo permite:

- Analizar documentos PDF.
- Mostrar metadatos.
- Obtener información técnica.
- Verificar el cifrado.
- Consultar permisos del documento.
- Procesar archivos desde la terminal.

---

# Información disponible

Dependiendo del documento, puede mostrar:

- Título.
- Autor.
- Asunto.
- Palabras clave.
- Fecha de creación.
- Fecha de modificación.
- Software utilizado.
- Número de páginas.
- Tamaño del archivo.
- Versión del PDF.
- Estado del cifrado.

---

# Uso básico

Analizar un documento:

```bash
pdfinfo documento.pdf
```

Mostrar información de un PDF protegido:

```bash
pdfinfo -upw contraseña documento.pdf
```

---

# Usos en OSINT

PDFInfo resulta útil para:

- Analizar documentos públicos.
- Obtener metadatos.
- Identificar autores.
- Verificar fechas.
- Detectar software utilizado.
- Complementar investigaciones documentales.

---

# Casos de uso

## Investigación documental

Analizar informes o documentos publicados por una organización.

---

## Auditoría de seguridad

Detectar metadatos que puedan revelar información sensible.

---

## Análisis forense

Examinar documentos PDF como evidencia digital.

---

## Verificación

Comprobar si las fechas y los metadatos coinciden con la información declarada.

---

# Integración con otras herramientas

PDFInfo suele utilizarse junto con:

- ExifTool
- FOCA
- MediaInfo
- theHarvester
- Maltego

La combinación de estas herramientas permite realizar un análisis más completo de documentos y metadatos.

---

# Instalación

PDFInfo está disponible para:

- Windows.
- Linux.
- macOS.

En la mayoría de distribuciones Linux forma parte del paquete **Poppler**.

---

# Ventajas

- Gratuito y de código abierto.
- Muy rápido.
- Fácil de utilizar.
- No modifica el documento.
- Compatible con la mayoría de archivos PDF.

---

# Limitaciones

- Solo funciona con documentos PDF.
- La información depende de los metadatos existentes.
- No recupera metadatos eliminados.

---

# Buenas prácticas

- Analizar siempre una copia del documento original.
- Contrastar la información obtenida con otras herramientas.
- Revisar especialmente autor, fechas y software utilizado.
- Documentar los metadatos relevantes durante la investigación.

---

# Caso práctico

**Objetivo:** Analizar un documento PDF.

Comando:

```bash
pdfinfo informe.pdf
```

Información esperada:

- Autor.
- Título.
- Fecha de creación.
- Fecha de modificación.
- Número de páginas.
- Software utilizado.
- Versión del PDF.
- Estado del cifrado.

---

# Resumen

PDFInfo es una herramienta sencilla pero muy útil para el análisis de documentos PDF en investigaciones OSINT y forenses. Gracias a su capacidad para extraer metadatos y características técnicas, permite obtener información relevante sobre el origen, la creación y las propiedades de un documento sin alterar su contenido.