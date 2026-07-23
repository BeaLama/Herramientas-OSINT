# Caso práctico - Análisis de un dominio con VirusTotal

## Objetivo

Analizar la reputación de un dominio utilizando VirusTotal para identificar posibles amenazas y obtener información relevante durante una investigación OSINT.

## Herramienta utilizada

- VirusTotal

## Escenario

Se analizará el siguiente dominio:

```text
ubuntu.com
```

---

## Paso 1. Acceder a VirusTotal

Abre VirusTotal y selecciona la pestaña **Domains**.

![Página principal](imagenes/threatintelligence/01_inicio.png)

---

## Paso 2. Introducir el dominio

Escribe el dominio que deseas analizar.

```text
ubuntu.com
```

![Búsqueda del dominio](imagenes/threatintelligence/02_busqueda.png)

---

## Paso 3. Analizar los resultados

VirusTotal mostrará un informe con la información recopilada por distintos motores de seguridad.

Entre los datos disponibles pueden encontrarse:

- Reputación del dominio.
- Detecciones de antivirus.
- Resolución DNS.
- Direcciones IP relacionadas.
- Certificados SSL.
- URLs asociadas.
- Últimos análisis realizados.

![Resultados](imagenes/threatintelligence/03_resultados.png)

---

## Paso 4. Revisar la información relacionada

Consulta las pestañas adicionales para obtener más contexto sobre el dominio.

Es posible analizar:

- Direcciones IP.
- Certificados digitales.
- Comunicaciones.
- Relaciones con otros dominios.
- Historial de resoluciones.

![Relaciones](imagenes/threatintelligence/04_relaciones.png)

---

## Resultados obtenidos

Durante el análisis pueden obtenerse datos como:

- Reputación del dominio.
- Detecciones por motores antivirus.
- Direcciones IP asociadas.
- Certificados SSL.
- Dominios relacionados.
- Historial DNS.
- URLs analizadas.

---

## Conclusiones

VirusTotal permite centralizar información procedente de múltiples motores antivirus y fuentes de inteligencia de amenazas, facilitando el análisis de dominios, direcciones IP, URLs y archivos. Su utilización ayuda a identificar indicadores de compromiso (IOC), evaluar la reputación de un activo y complementar investigaciones OSINT relacionadas con la ciberseguridad.