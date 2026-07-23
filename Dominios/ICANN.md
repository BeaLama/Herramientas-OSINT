# ICANN Lookup

## Descripción

**ICANN Lookup** es el servicio oficial de la **Internet Corporation for Assigned Names and Numbers (ICANN)** que permite consultar información pública sobre nombres de dominio registrados. Es una herramienta fundamental en **OSINT** para obtener datos relacionados con el registro y la administración de un dominio.

A diferencia de otras herramientas, ICANN proporciona información procedente del registro oficial del dominio.

---

# ¿Cómo funciona?

Cuando un dominio es registrado, el registrador envía la información correspondiente a los registros administrados por la ICANN.

ICANN Lookup consulta estos datos y muestra la información pública disponible.

Proceso:

1. Introducir un dominio.
2. Consultar el registro oficial.
3. Mostrar la información pública disponible.
4. Presentar los datos del registrador y del estado del dominio.

---

# Información disponible

Dependiendo del dominio y de la configuración de privacidad, ICANN puede mostrar:

- Nombre del dominio.
- Estado del dominio.
- Registrador.
- Fechas de creación y expiración.
- Servidores DNS (Nameservers).
- Estado DNSSEC.
- Código EPP del dominio.
- Información de contacto (si es pública).

---

# Usos en OSINT

- Verificar la existencia de un dominio.
- Identificar el registrador.
- Consultar fechas de registro.
- Analizar el estado del dominio.
- Obtener los servidores DNS asociados.
- Comprobar la protección DNSSEC.

---

# Información del dominio

## Dominio

Nombre registrado.

Ejemplo:

```text
empresa.com
```

---

## Registrador

Empresa responsable del registro del dominio.

---

## Fecha de creación

Indica cuándo fue registrado por primera vez.

---

## Fecha de expiración

Muestra cuándo finaliza el periodo de registro si no se renueva.

---

## Nameservers

Lista de servidores DNS responsables de resolver el dominio.

---

## Estado del dominio

Algunos estados comunes son:

| Estado | Descripción |
|---------|-------------|
| `ok` | Dominio activo. |
| `clientTransferProhibited` | No puede transferirse sin autorización. |
| `clientUpdateProhibited` | No se permiten modificaciones. |
| `clientDeleteProhibited` | Protegido frente a eliminación. |

---

## DNSSEC

Indica si el dominio utiliza **DNS Security Extensions**, un mecanismo que ayuda a proteger la integridad de las respuestas DNS.

---

# Casos de uso

**Verificación de un dominio**

Comprobar si un dominio está registrado y cuál es su estado.

**Análisis temporal**

Determinar la antigüedad de un dominio mediante su fecha de creación.

**Identificación del registrador**

Conocer qué empresa gestiona el registro del dominio.

**Análisis DNS**

Consultar los servidores DNS oficiales.

---

# Integración con otras herramientas

ICANN Lookup suele utilizarse junto con:

- WHOIS
- DNSDumpster
- SecurityTrails
- crt.sh
- Shodan
- Censys
- VirusTotal
- ViewDNS

---

# Ventajas

- Fuente oficial de información.
- Datos fiables sobre el registro del dominio.
- No requiere instalación.
- Fácil de utilizar.
- Útil para verificar información obtenida con otras herramientas.

---

# Limitaciones

- Parte de la información puede estar protegida por servicios de privacidad.
- No muestra subdominios.
- No proporciona información sobre puertos o servicios.
- Solo ofrece datos relacionados con el registro del dominio.

---

# Buenas prácticas

- Complementar la información con herramientas DNS.
- Verificar los certificados mediante crt.sh.
- Analizar la infraestructura con Shodan o Censys.
- Documentar las fechas de registro y expiración del dominio.

---

# Caso práctico

**Objetivo:** Obtener información básica sobre un dominio.

Dominio:

```text
empresa.com
```

Información esperada:

- Registrador.
- Fecha de creación.
- Fecha de expiración.
- Servidores DNS.
- Estado del dominio.
- Estado de DNSSEC.

---

# Resumen

ICANN Lookup es una herramienta esencial para obtener información oficial sobre el registro de un dominio. Permite verificar datos como el registrador, las fechas de creación y expiración, los servidores DNS y el estado del dominio, siendo un excelente punto de partida en cualquier investigación OSINT relacionada con nombres de dominio.