# crt.sh

## Descripción

**crt.sh** es un buscador de **Certificate Transparency Logs (CT Logs)** que permite consultar certificados digitales SSL/TLS emitidos para dominios públicos. Es una herramienta muy utilizada en **OSINT** para descubrir subdominios, analizar certificados y obtener información sobre la infraestructura de una organización.

---

# ¿Cómo funciona?

Cada vez que una Autoridad de Certificación (CA) emite un certificado SSL/TLS, este se registra en un **Certificate Transparency Log**.

crt.sh recopila estos registros y permite buscarlos de forma pública.

Proceso:

1. Se emite un certificado SSL/TLS.
2. El certificado se registra en un CT Log.
3. crt.sh indexa esa información.
4. El usuario puede realizar búsquedas por dominio.

---

# Información disponible

Para cada certificado se puede consultar:

- Dominio principal.
- Subdominios.
- Nombre común (Common Name - CN).
- Subject Alternative Names (SAN).
- Autoridad Certificadora (CA).
- Número de serie.
- Fecha de emisión.
- Fecha de expiración.
- Estado del certificado.

---

# Usos en OSINT

- Descubrir subdominios.
- Analizar certificados SSL/TLS.
- Identificar cambios en la infraestructura.
- Relacionar dominios y certificados.
- Verificar certificados públicos.

---

# Cómo buscar

Buscar un dominio:

```text
empresa.com
```

Buscar todos los subdominios:

```text
%.empresa.com
```

El carácter `%` actúa como comodín y permite localizar certificados emitidos para subdominios.

---

# Ejemplos

Buscar certificados de un dominio:

```text
empresa.com
```

Buscar todos los subdominios:

```text
%.empresa.com
```

Buscar un subdominio específico:

```text
vpn.empresa.com
```

---

# Interpretación de resultados

Cada resultado muestra información como:

- ID del certificado.
- Nombre del dominio.
- Subdominios incluidos.
- Fecha de emisión.
- Fecha de expiración.
- Autoridad certificadora.
- Estado del certificado.

---

# Casos de uso

**Descubrimiento de subdominios**

Identificar subdominios publicados mediante certificados SSL/TLS.

**Análisis de infraestructura**

Conocer qué dominios utilizan certificados emitidos por una misma autoridad certificadora.

**Auditoría de certificados**

Verificar fechas de emisión y caducidad.

**Investigación histórica**

Consultar certificados emitidos anteriormente para un dominio.

---

# Integración con otras herramientas

crt.sh suele utilizarse junto con:

- Shodan
- Censys
- SecurityTrails
- Amass
- Subfinder
- SpiderFoot
- Maltego
- Recon-ng

---

# Ventajas

- Acceso gratuito.
- No requiere registro.
- Excelente para descubrir subdominios.
- Basado en registros públicos.
- Resultados rápidos y fáciles de interpretar.

---

# Limitaciones

- Solo muestra información procedente de certificados públicos.
- No todos los subdominios disponen de certificados SSL/TLS.
- La aparición de un dominio en un certificado no garantiza que el servicio siga activo.

---

# Buenas prácticas

- Combinar los resultados con herramientas DNS y de infraestructura.
- Verificar si los subdominios continúan siendo accesibles.
- Documentar las fechas de emisión y expiración de los certificados.
- Corroborar la información con otras fuentes OSINT.

---

# Caso práctico

**Objetivo:** Descubrir subdominios de una organización.

Consulta:

```text
%.empresa.com
```

Resultado esperado:

- Dominio principal.
- Subdominios encontrados.
- Certificados asociados.
- Fechas de emisión.
- Autoridad certificadora.

---

# Resumen

crt.sh es una herramienta esencial para investigaciones OSINT relacionadas con certificados SSL/TLS. Su principal utilidad es el descubrimiento de subdominios y el análisis de certificados públicos, proporcionando información valiosa sobre la infraestructura visible de una organización sin necesidad de realizar escaneos activos.