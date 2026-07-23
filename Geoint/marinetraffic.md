# MarineTraffic

## Descripción

**MarineTraffic** es una plataforma de seguimiento marítimo que permite monitorizar la posición de buques y embarcaciones en tiempo real mediante el sistema **AIS (Automatic Identification System)**. Es una de las herramientas más utilizadas en investigaciones **GEOINT** y **OSINT** relacionadas con el tráfico marítimo.

Gracias a su amplia cobertura mundial, permite conocer la ubicación, el recorrido y las características de miles de embarcaciones comerciales, pesqueras, recreativas y, en algunos casos, gubernamentales.

---

# ¿Cómo funciona?

Los buques equipados con un transpondedor **AIS** transmiten periódicamente información sobre su posición, velocidad y rumbo.

MarineTraffic recopila estas señales mediante una red global de estaciones receptoras terrestres y satélites, mostrando los datos en un mapa interactivo prácticamente en tiempo real.

---

# Funciones principales

MarineTraffic permite:

- Seguir embarcaciones en tiempo real.
- Buscar barcos por nombre o número IMO.
- Consultar rutas marítimas.
- Analizar el historial de navegación.
- Localizar puertos.
- Consultar llegadas y salidas.
- Obtener información técnica de los buques.

---

# Información disponible

Dependiendo de la embarcación, puede mostrar:

- Nombre del buque.
- Número IMO.
- Número MMSI.
- Bandera.
- Tipo de embarcación.
- Posición GPS.
- Velocidad.
- Rumbo.
- Puerto de origen.
- Puerto de destino.
- Hora estimada de llegada (ETA).
- Historial de navegación.

---

# Métodos de búsqueda

La plataforma permite buscar embarcaciones mediante:

- Nombre del barco.
- Número IMO.
- Número MMSI.
- Puerto.
- Zona geográfica.

---

# Usos en GEOINT

MarineTraffic puede utilizarse para:

- Monitorizar el tráfico marítimo.
- Investigar rutas comerciales.
- Verificar la presencia de un buque en una ubicación.
- Analizar movimientos de embarcaciones.
- Estudiar operaciones portuarias.
- Complementar investigaciones geoespaciales.

---

# Casos de uso

## Investigación periodística

Comprobar la ruta seguida por un buque durante un acontecimiento de interés.

---

## Verificación de imágenes

Confirmar si una embarcación estaba presente en una zona cuando se tomó una fotografía o un vídeo.

---

## Investigación corporativa

Analizar el movimiento de barcos pertenecientes a una empresa naviera.

---

## GEOINT

Relacionar movimientos marítimos con imágenes satelitales, condiciones meteorológicas u otros eventos.

---

# Integración con otras herramientas

MarineTraffic suele utilizarse junto con:

- Google Maps
- Google Earth
- OpenStreetMap
- Sentinel Hub
- Windy
- ADS-B Exchange
- SunCalc

La combinación de estas herramientas permite obtener un contexto geográfico mucho más completo.

---

# API

MarineTraffic dispone de una API que permite consultar información sobre buques, puertos y posiciones para automatizar investigaciones e integrarla con otras aplicaciones.

El acceso a determinadas funciones requiere una suscripción.

---

# Ventajas

- Cobertura mundial.
- Información prácticamente en tiempo real.
- Amplia base de datos de embarcaciones.
- Historial de navegación.
- Muy útil para investigaciones GEOINT.

---

# Limitaciones

- Solo muestra embarcaciones que transmiten AIS.
- Algunas funciones avanzadas son de pago.
- La cobertura depende de la disponibilidad de receptores AIS.
- Determinados buques pueden limitar o desactivar la transmisión de datos.

---

# Buenas prácticas

- Contrastar la información con otras fuentes cuando sea necesario.
- Revisar el historial de navegación para identificar patrones.
- Complementar el análisis con imágenes satelitales y datos meteorológicos.
- Documentar la fecha y hora de las observaciones.

---

# Caso práctico

**Objetivo:** Analizar el recorrido de un buque.

Consulta:

```text
Nombre: EVER GIVEN
```

Información esperada:

- Posición actual.
- Velocidad.
- Rumbo.
- Puerto de origen.
- Puerto de destino.
- Historial de navegación.
- Características del buque.

---

# Resumen

MarineTraffic es una herramienta esencial para el análisis del tráfico marítimo en investigaciones GEOINT y OSINT. Gracias a la información proporcionada por el sistema AIS, permite seguir embarcaciones en tiempo real, estudiar sus rutas y verificar movimientos marítimos, siendo un recurso muy valioso para analistas, periodistas e investigadores.