# ADS-B Exchange

## Descripción

**ADS-B Exchange** es una plataforma de seguimiento de aeronaves en tiempo real que recopila y muestra información transmitida mediante el sistema **ADS-B (Automatic Dependent Surveillance–Broadcast)**. A diferencia de otros servicios similares, no filtra la mayoría de las aeronaves, lo que la convierte en una herramienta muy valiosa para investigaciones **GEOINT** y **OSINT**.

La plataforma es utilizada por investigadores, periodistas, analistas de inteligencia y aficionados a la aviación para monitorizar vuelos civiles, privados, militares y gubernamentales.

---

# ¿Cómo funciona?

Las aeronaves equipadas con un transpondedor ADS-B transmiten periódicamente información sobre su posición y estado.

ADS-B Exchange recibe estas señales mediante una red mundial de receptores terrestres y datos satelitales, mostrando la información sobre un mapa interactivo.

Los datos se actualizan en tiempo real, permitiendo seguir el recorrido de una aeronave durante todo el vuelo.

---

# Información disponible

Dependiendo de la aeronave, la plataforma puede mostrar:

- Número de vuelo.
- Matrícula.
- Modelo de aeronave.
- Fabricante.
- Altitud.
- Velocidad.
- Rumbo.
- Posición GPS.
- Aeropuerto de origen.
- Aeropuerto de destino.
- Hora estimada de llegada.
- Historial de vuelo.

---

# Funciones principales

ADS-B Exchange permite:

- Seguir vuelos en tiempo real.
- Buscar aeronaves por matrícula.
- Consultar vuelos mediante número de vuelo.
- Visualizar rutas de vuelo.
- Analizar trayectorias.
- Consultar información técnica de la aeronave.
- Revisar el historial de movimientos (según disponibilidad).

---

# Métodos de búsqueda

La plataforma permite realizar búsquedas por:

- Matrícula.
- Número de vuelo.
- Modelo de aeronave.
- Aeropuerto.
- Ubicación geográfica.

---

# Usos en GEOINT

ADS-B Exchange puede utilizarse para:

- Verificar la presencia de aeronaves durante un evento.
- Analizar rutas aéreas.
- Investigar vuelos privados o corporativos.
- Monitorizar aeronaves militares (cuando transmiten ADS-B).
- Confirmar la ubicación de un avión en un momento determinado.
- Complementar investigaciones geoespaciales.

---

# Casos de uso

## Investigación periodística

Verificar los desplazamientos de una aeronave relacionada con un acontecimiento de interés.

---

## Verificación de imágenes

Comprobar si un avión visible en una fotografía o vídeo se encontraba realmente en esa zona y a esa hora.

---

## Investigación corporativa

Analizar los desplazamientos de aeronaves pertenecientes a empresas u organizaciones.

---

## GEOINT

Relacionar movimientos aéreos con otros eventos investigados mediante herramientas cartográficas.

---

# Integración con otras herramientas

ADS-B Exchange suele utilizarse junto con:

- Google Maps
- Google Earth
- OpenStreetMap
- Sentinel Hub
- SunCalc
- Windy
- MarineTraffic

La combinación de estas herramientas permite obtener un contexto geográfico mucho más completo durante una investigación.

---

# API

ADS-B Exchange dispone de una API que permite acceder a información sobre vuelos y aeronaves para automatizar consultas e integrar los datos en aplicaciones o scripts.

Algunas funciones avanzadas pueden requerir registro o suscripción.

---

# Ventajas

- Información prácticamente en tiempo real.
- Cobertura mundial.
- Amplia información sobre aeronaves.
- No filtra gran parte de las aeronaves visibles.
- Muy útil para investigaciones GEOINT.

---

# Limitaciones

- Solo muestra aeronaves que transmiten ADS-B.
- La cobertura depende de la red de receptores.
- Algunas funciones avanzadas pueden ser de pago.
- Determinados vuelos pueden ocultar o limitar parte de su información.

---

# Buenas prácticas

- Contrastar la información con otras fuentes cuando sea necesario.
- Utilizar imágenes satelitales para complementar el análisis.
- Documentar la hora y la posición de las aeronaves observadas.
- Tener en cuenta posibles retrasos o pérdidas de señal.

---

# Caso práctico

**Objetivo:** Verificar el paso de una aeronave sobre una determinada zona.

Consulta:

```text
Matrícula: EC-XXX
```

Información esperada:

- Posición en tiempo real.
- Altitud.
- Velocidad.
- Rumbo.
- Ruta seguida.
- Origen y destino.
- Historial del vuelo.

---

# Resumen

ADS-B Exchange es una de las herramientas GEOINT más importantes para el seguimiento de aeronaves. Gracias a la información transmitida mediante el sistema ADS-B, permite analizar vuelos en tiempo real, estudiar rutas aéreas y verificar la presencia de aeronaves durante una investigación, convirtiéndose en un recurso imprescindible para analistas OSINT, periodistas e investigadores de inteligencia.