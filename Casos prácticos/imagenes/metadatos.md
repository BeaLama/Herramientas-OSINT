# Caso práctico - Análisis de metadatos con ExifTool

## Objetivo

Extraer y analizar los metadatos de una imagen utilizando ExifTool para obtener información relevante durante una investigación OSINT.

## Herramienta utilizada

- ExifTool

## Escenario

Se analizará el siguiente archivo:

```text
fotografia.jpg
```

---

## Paso 1. Abrir la terminal

Accede al directorio donde se encuentra la imagen que se desea analizar.

![Terminal](imagenes/metadatos/01_terminal.png)

---

## Paso 2. Ejecutar ExifTool

Ejecuta el siguiente comando:

```bash
exiftool fotografia.jpg
```

![Ejecución de ExifTool](imagenes/metadatos/02_comando.png)

---

## Paso 3. Analizar los metadatos

Examina la información obtenida.

Entre los datos disponibles pueden encontrarse:

- Fecha y hora de captura.
- Modelo de cámara.
- Fabricante.
- Resolución.
- Software utilizado.
- Coordenadas GPS (si existen).

![Metadatos obtenidos](imagenes/metadatos/03_resultados.png)

---

## Paso 4. Interpretar la información

Determina qué datos pueden ser útiles para la investigación.

Por ejemplo:

- Identificar el dispositivo utilizado.
- Conocer la fecha de creación.
- Localizar el lugar donde fue tomada la fotografía mediante las coordenadas GPS.
- Detectar si la imagen ha sido modificada con algún software de edición.

![Análisis de los datos](imagenes/metadatos/04_analisis.png)

---

## Resultados obtenidos

Durante el análisis pueden obtenerse datos como:

- Nombre del archivo.
- Fecha y hora de creación.
- Modelo y fabricante de la cámara.
- Dimensiones de la imagen.
- Coordenadas GPS.
- Software de edición.
- Información EXIF, IPTC y XMP.

---

## Conclusiones

ExifTool permite extraer de forma rápida una gran cantidad de metadatos almacenados en archivos multimedia. Esta información puede aportar evidencias relevantes durante una investigación OSINT, como la ubicación donde fue tomada una fotografía, el dispositivo utilizado o si el archivo ha sido modificado antes de su publicación.