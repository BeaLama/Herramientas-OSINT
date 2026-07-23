# Shodan

## Descripción

Shodan es un motor de búsqueda especializado en **dispositivos y servicios conectados a Internet**. A diferencia de Google, que indexa páginas web, Shodan recopila información sobre servidores, cámaras, routers, dispositivos IoT y otros servicios expuestos públicamente.

Es una de las herramientas más utilizadas en **OSINT**, auditorías de seguridad e inventario de activos.

---

# ¿Cómo funciona?

Shodan escanea continuamente Internet y:

1. Detecta direcciones IP públicas.
2. Analiza los puertos abiertos.
3. Obtiene el *banner* del servicio.
4. Identifica el software y su versión.
5. Guarda la información en su base de datos.

---

# Información que muestra

Dependiendo del servicio encontrado, Shodan puede mostrar:

- Dirección IP.
- Puertos abiertos.
- Nombre del host.
- Sistema operativo (cuando es detectable).
- Software y versión.
- Certificados SSL/TLS.
- Ubicación aproximada.
- Organización o proveedor de Internet (ISP).
- Fecha del último escaneo.

---

# Usos en OSINT

- Inventario de activos expuestos.
- Identificación de tecnologías utilizadas.
- Descubrimiento de servidores públicos.
- Investigación de dominios e IPs.
- Análisis de certificados SSL.
- Verificación de servicios accesibles desde Internet.

---

# Filtros de búsqueda

| Filtro | Descripción |
|---------|-------------|
| `hostname:` | Busca por nombre de host. |
| `org:` | Filtra por organización. |
| `country:` | Filtra por país. |
| `city:` | Filtra por ciudad. |
| `port:` | Filtra por puerto. |
| `net:` | Busca por rango de IP. |
| `os:` | Filtra por sistema operativo detectado. |
| `product:` | Busca un software concreto. |
| `ssl:` | Busca información del certificado SSL. |

---

# Ejemplos

Buscar un dominio:

```text
hostname:empresa.com
```

Buscar servicios HTTPS:

```text
port:443
```

Buscar servidores web Apache:

```text
product:Apache
```

Buscar equipos en España:

```text
country:ES
```

Buscar un rango de IP:

```text
net:192.0.2.0/24
```

Buscar una organización:

```text
org:"Empresa S.A."
```

---

# Casos de uso

**Inventario de activos**

Comprobar qué servicios públicos pertenecen a una organización.

**Identificación de tecnologías**

Detectar qué servidores web o servicios están publicados.

**Análisis de certificados**

Consultar información sobre certificados SSL visibles públicamente.

**Investigación de infraestructura**

Relacionar dominios, IPs y servicios accesibles.

---

# API

Shodan dispone de una API que permite:

- Buscar dispositivos.
- Consultar información de una IP.
- Obtener datos en formato JSON.
- Automatizar investigaciones.

Se requiere una clave API para utilizarla.

---

# Integración con otras herramientas

Shodan puede complementarse con:

- Censys
- VirusTotal
- SecurityTrails
- DNSDumpster
- Maltego
- SpiderFoot
- Recon-ng

---

# Ventajas

- Gran base de datos de servicios expuestos.
- Actualización periódica de los escaneos.
- Filtros de búsqueda muy completos.
- API para automatización.
- Interfaz sencilla de utilizar.

---

# Limitaciones

- Solo muestra información accesible públicamente.
- Algunos datos pueden no estar completamente actualizados.
- Determinadas funciones requieren una cuenta de pago.
- No sustituye a un análisis técnico directo del sistema.

---

# Buenas prácticas

- Verificar la fecha del último escaneo.
- Contrastar la información con otras fuentes OSINT.
- Documentar las consultas realizadas.
- Utilizar la información únicamente con fines legítimos y autorizados.

---

# Caso práctico

**Objetivo:** Identificar los servicios públicos asociados a un dominio.

Consulta:

```text
hostname:empresa.com
```

Resultado esperado:

- Direcciones IP relacionadas.
- Puertos abiertos.
- Software detectado.
- Certificados SSL.
- Información del proveedor de red.

---

# Resumen

Shodan es una herramienta fundamental para investigaciones OSINT relacionadas con infraestructura de Internet. Permite identificar servicios públicos, tecnologías utilizadas y activos expuestos, facilitando el análisis de dominios e IPs sin necesidad de interactuar directamente con los sistemas analizados.