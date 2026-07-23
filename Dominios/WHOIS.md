# WHOIS

## Descripción

**WHOIS** es un protocolo y servicio de consulta que permite obtener información pública sobre el registro de un dominio o una dirección IP. Es una de las herramientas más utilizadas en **OSINT** para conocer datos relacionados con la propiedad, el registrador y la configuración de un dominio.

---

# ¿Cómo funciona?

Cuando un dominio es registrado, cierta información se almacena en bases de datos gestionadas por los registradores y registros de dominios.

Una consulta WHOIS recupera los datos públicos disponibles sobre ese registro.

Proceso:

1. Introducir un dominio o una IP.
2. Consultar la base de datos WHOIS correspondiente.
3. Mostrar la información pública disponible.

---

# Información disponible

Dependiendo del dominio y de la política de privacidad, WHOIS puede mostrar:

- Nombre del dominio.
- Registrador.
- Fecha de creación.
- Fecha de actualización.
- Fecha de expiración.
- Estado del dominio.
- Servidores DNS (Nameservers).
- Estado DNSSEC.
- Información de contacto (si es pública).

---

# Usos en OSINT

- Verificar la existencia de un dominio.
- Identificar el registrador.
- Consultar fechas de registro y expiración.
- Analizar los servidores DNS.
- Obtener información básica de un dominio.
- Correlacionar datos con otras herramientas OSINT.

---

# Campos más importantes

## Domain Name

Nombre del dominio registrado.

Ejemplo:

```text
empresa.com
```

---

## Registrar

Empresa encargada del registro del dominio.

---

## Creation Date

Fecha en la que se registró el dominio.

---

## Updated Date

Última fecha de modificación del registro.

---

## Expiration Date

Fecha de expiración del dominio.

---

## Name Servers

Servidores DNS responsables de resolver el dominio.

Ejemplo:

```text
ns1.example.com
ns2.example.com
```

---

## Domain Status

Estado actual del dominio.

Algunos estados comunes:

| Estado | Descripción |
|---------|-------------|
| `ok` | Dominio activo. |
| `clientTransferProhibited` | Protegido frente a transferencias. |
| `clientUpdateProhibited` | No se permiten modificaciones. |
| `clientDeleteProhibited` | Protegido frente a su eliminación. |

---

## DNSSEC

Indica si el dominio utiliza **DNS Security Extensions** para proteger la autenticidad de las respuestas DNS.

---

# Herramientas para consultas WHOIS

- ICANN Lookup
- Whois.com
- ViewDNS
- SecurityTrails
- WhoisXML API
- Herramienta `whois` en Linux

---

# Uso desde la línea de comandos

En sistemas Linux y macOS es posible realizar consultas mediante:

```bash
whois empresa.com
```

El comando devuelve la información pública disponible del dominio.

---

# Casos de uso

**Verificación de un dominio**

Comprobar si un dominio está registrado.

**Análisis temporal**

Conocer cuándo fue registrado y cuándo expira.

**Investigación de infraestructura**

Identificar los servidores DNS y el registrador.

**Correlación de información**

Relacionar los datos obtenidos con herramientas como Shodan, Censys o SecurityTrails.

---

# Integración con otras herramientas

WHOIS suele utilizarse junto con:

- ICANN Lookup
- DNSDumpster
- SecurityTrails
- crt.sh
- Shodan
- Censys
- VirusTotal
- ViewDNS

---

# Ventajas

- Información oficial del registro del dominio.
- Fácil de utilizar.
- Disponible desde múltiples plataformas.
- Útil para investigaciones iniciales.

---

# Limitaciones

- Parte de la información puede estar protegida por servicios de privacidad (WHOIS Privacy).
- No proporciona información sobre servicios o puertos.
- No muestra subdominios.
- La información disponible depende del registrador y de la normativa aplicable.

---

# Buenas prácticas

- Verificar la información con otras herramientas.
- Documentar las fechas de registro y expiración.
- Analizar también los registros DNS y los certificados SSL.
- Tener en cuenta que algunos datos pueden estar ocultos por motivos de privacidad.

---

# Caso práctico

**Objetivo:** Obtener información básica sobre un dominio.

Consulta:

```bash
whois empresa.com
```

Información esperada:

- Registrador.
- Fecha de creación.
- Fecha de actualización.
- Fecha de expiración.
- Servidores DNS.
- Estado del dominio.
- Estado de DNSSEC.

---

# Resumen

WHOIS es una herramienta fundamental en cualquier investigación OSINT relacionada con dominios. Permite obtener información pública sobre el registro de un dominio, como el registrador, las fechas de creación y expiración, los servidores DNS y el estado del dominio, siendo el punto de partida para el análisis de la infraestructura de Internet.