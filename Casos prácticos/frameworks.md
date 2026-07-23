# Caso práctico - Reconocimiento de un dominio con Maltego

## Objetivo

Obtener información pública y visualizar las relaciones existentes entre un dominio y su infraestructura utilizando Maltego.

## Herramienta utilizada

- Maltego

## Escenario

Se analizará el siguiente dominio:

```text
ubuntu.com
```

---

## Paso 1. Crear un nuevo gráfico

Abre Maltego y crea un gráfico vacío para comenzar la investigación.

![Nuevo gráfico](imagenes/frameworks/01_nuevo_grafo.png)

---

## Paso 2. Añadir la entidad

Inserta una entidad de tipo **Domain** e introduce el dominio.

```text
ubuntu.com
```

![Entidad de dominio](imagenes/frameworks/02_dominio.png)

---

## Paso 3. Ejecutar las transformaciones

Haz clic con el botón derecho sobre el dominio y ejecuta las transformaciones disponibles para obtener información pública.

![Transformaciones](imagenes/frameworks/03_transformaciones.png)

---

## Paso 4. Analizar los resultados

Maltego generará automáticamente un grafo con las entidades relacionadas.

Entre la información obtenida pueden aparecer:

- Direcciones IP.
- Registros DNS.
- Servidores NS.
- Certificados.
- Dominios relacionados.
- Información WHOIS.

![Resultados](imagenes/frameworks/04_resultados.png)

---

## Resultados obtenidos

Durante el análisis pueden identificarse:

- Dominio principal.
- Infraestructura asociada.
- Direcciones IP públicas.
- Servidores DNS.
- Certificados digitales.
- Relaciones entre entidades.

---

## Conclusiones

Maltego permite automatizar la recopilación y correlación de información procedente de múltiples fuentes OSINT. Su principal ventaja es la representación gráfica de las relaciones entre entidades, facilitando el análisis de infraestructuras y la identificación de conexiones que podrían pasar desapercibidas en una investigación manual.