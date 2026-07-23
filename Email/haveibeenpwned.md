# Have I Been Pwned

## Descripción

**Have I Been Pwned (HIBP)** es un servicio de inteligencia desarrollado por **Troy Hunt** que permite comprobar si una dirección de correo electrónico o una contraseña ha aparecido en alguna filtración de datos conocida. Es una de las herramientas más utilizadas en **OSINT**, auditorías de seguridad y respuesta ante incidentes.

La plataforma recopila información procedente de brechas de seguridad verificadas y ofrece una forma sencilla de conocer si una cuenta ha sido comprometida en el pasado.

---

# ¿Cómo funciona?

HIBP recopila bases de datos procedentes de filtraciones públicas y las indexa para facilitar su consulta.

Cuando un usuario introduce una dirección de correo electrónico, la plataforma busca coincidencias y muestra en qué brechas de seguridad ha aparecido esa cuenta.

Además, mediante el servicio **Pwned Passwords**, es posible comprobar si una contraseña ha sido expuesta en filtraciones sin revelar la contraseña completa gracias al modelo **k-Anonymity**.

---

# Información disponible

Dependiendo de la consulta, HIBP puede mostrar:

- Dirección de correo electrónico.
- Brechas de seguridad donde aparece.
- Fecha de la filtración.
- Empresa o servicio afectado.
- Tipo de datos comprometidos.
- Número de cuentas afectadas.
- Estado de la filtración.

---

# Usos en OSINT

- Verificar si un correo ha sido comprometido.
- Investigar filtraciones de datos.
- Analizar la exposición de una organización.
- Comprobar la seguridad de credenciales.
- Obtener contexto durante una investigación.

---

# Tipos de búsqueda

## Correo electrónico

Permite consultar si una dirección de correo aparece en alguna filtración.

Ejemplo:

```text
usuario@empresa.com
```

---

## Contraseñas

HIBP dispone de **Pwned Passwords**, un servicio para comprobar si una contraseña ha sido expuesta anteriormente.

La consulta se realiza sin enviar la contraseña completa, preservando la privacidad del usuario.

---

# Información sobre una filtración

Cada brecha suele incluir:

- Nombre del servicio afectado.
- Fecha del incidente.
- Fecha de publicación.
- Tipo de información expuesta.
- Número de cuentas afectadas.
- Descripción de la brecha.

---

# Casos de uso

## Investigación de personas

Determinar si una dirección de correo ha aparecido en filtraciones conocidas.

---

## Auditorías de seguridad

Evaluar el nivel de exposición de los empleados de una organización.

---

## Respuesta ante incidentes

Comprobar rápidamente si una cuenta comprometida ya había aparecido en filtraciones anteriores.

---

## Concienciación en ciberseguridad

Ayudar a los usuarios a conocer el riesgo asociado a sus credenciales y fomentar el uso de contraseñas seguras.

---

# Integración con otras herramientas

HIBP suele utilizarse junto con:

- Hunter
- EmailRep
- DeHashed
- Intelligence X
- VirusTotal
- SpiderFoot
- Maltego
- Recon-ng

---

# API

Have I Been Pwned ofrece una API que permite:

- Consultar correos electrónicos.
- Obtener información sobre filtraciones.
- Automatizar comprobaciones.
- Integrar los resultados en herramientas de seguridad.

El acceso requiere una clave API.

---

# Ventajas

- Base de datos muy amplia.
- Información verificada.
- API disponible.
- Fácil de utilizar.
- Excelente para auditorías de seguridad.

---

# Limitaciones

- Solo muestra filtraciones conocidas.
- No indica si una cuenta está comprometida en la actualidad.
- Algunas funciones requieren una API de pago.

---

# Buenas prácticas

- Cambiar inmediatamente la contraseña si aparece en una filtración.
- Utilizar contraseñas únicas para cada servicio.
- Activar la autenticación multifactor (MFA).
- Revisar periódicamente las cuentas importantes.
- Complementar la investigación con otras herramientas OSINT.

---

# Caso práctico

**Objetivo:** Comprobar si una cuenta ha sido comprometida.

Consulta:

```text
usuario@empresa.com
```

Información esperada:

- Filtraciones donde aparece.
- Fecha de cada brecha.
- Servicio afectado.
- Tipo de datos expuestos.
- Descripción del incidente.

---

# Resumen

Have I Been Pwned es una de las herramientas más importantes para comprobar la exposición de direcciones de correo y contraseñas en filtraciones de datos. Gracias a su amplia base de datos y a su API, constituye un recurso esencial para investigaciones OSINT, auditorías de seguridad y respuesta ante incidentes, permitiendo identificar rápidamente credenciales comprometidas y evaluar el riesgo asociado a una cuenta.