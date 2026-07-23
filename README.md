# 🕵️ Manual Completo de Herramientas OSINT

> Una guía técnica y práctica sobre herramientas de **Open Source Intelligence (OSINT)**, organizada por categorías y con documentación individual para cada herramienta.

![OSINT](https://img.shields.io/badge/OSINT-Documentation-blue)
![Markdown](https://img.shields.io/badge/Markdown-100%25-success)
![License](https://img.shields.io/badge/License-MIT-green)

---

![osint](/img/OSINT.png)

---
# Índice

- [¿Qué es este proyecto?](#qué-es-este-proyecto)
- [Objetivos](#objetivos)
- [¿Qué es OSINT?](#qué-es-osint)
- [Estructura del repositorio](#estructura-del-repositorio)
- [Categorías](#categorías)
- [Cómo utilizar este manual](#cómo-utilizar-este-manual)
- [Metodología](#metodología)
- [Convenciones](#convenciones)
- [Buenas prácticas](#buenas-prácticas)
- [Aspectos legales y éticos](#aspectos-legales-y-éticos)
- [Requisitos](#requisitos)
- [Contribuciones](#contribuciones)
- [Licencia](#licencia)

---

# ¿Qué es este proyecto?

Este repositorio reúne documentación técnica sobre las principales herramientas utilizadas en investigaciones **OSINT (Open Source Intelligence)**.

Cada herramienta dispone de su propio documento en formato Markdown donde se explica detalladamente:

- Qué es.
- Cómo funciona.
- Para qué sirve.
- Instalación.
- Configuración.
- Casos de uso.
- Ejemplos prácticos.
- Automatización.
- APIs (cuando existan).
- Integración con otras herramientas.
- Buenas prácticas.
- Limitaciones.

El objetivo es disponer de una documentación completa, homogénea y fácil de consultar.

---

# Objetivos

Este proyecto pretende:

- Centralizar documentación OSINT.
- Servir como material de estudio.
- Facilitar la formación.
- Documentar herramientas profesionales.
- Mantener una estructura uniforme.
- Crear una referencia técnica de consulta rápida.

---

# ¿Qué es OSINT?

**OSINT (Open Source Intelligence)** consiste en recopilar, analizar y correlacionar información obtenida de fuentes públicas.

Las fuentes pueden incluir:

- Sitios web
- Redes sociales
- Documentación pública
- Bases de datos abiertas
- Certificados digitales
- Motores de búsqueda
- Registros DNS
- Repositorios públicos
- Imágenes
- Vídeos
- Metadatos
- Información geográfica

OSINT **no implica acceder a sistemas protegidos ni vulnerar mecanismos de seguridad**. Se basa exclusivamente en información disponible públicamente.

---

# Estructura del repositorio

```
OSINT-Manual/
│
├── README.md
├── indice.md
├── categorias.md
│
├── Buscadores/
├── Redes_Sociales/
├── Dominios/
├── GEOINT/
├── Personas/
├── Empresas/
├── Imágenes/
├── Metadatos/
├── Frameworks/
├── Automatización/
├── APIs/
├── Threat_Intelligence/
├── Cloud/
├── Repositorios/
└── Recursos/
```

Cada herramienta tiene su propio documento independiente.

Ejemplo:

```
Dominios/

Shodan.md
Censys.md
VirusTotal.md
DNSDumpster.md
SecurityTrails.md
crt.sh.md
Whois.md
ICANN.md
```

---

# Categorías

## 🌐 Buscadores

- [Google](Buscadores/google.md)
- [Bing](Buscadores/bing.md)
- [DuckDuckGo](Buscadores/duckduckgo.md)
- [Yandex](Buscadores/yandex.md)
- [Google Dorks](Buscadores/googledorks.md)

---

## 🌍 Dominios

- [WHOIS](Dominios/WHOIS.md)
- [ICANN](Dominios/ICANN.md)
- [SecurityTrails](Dominios/SecurityTrails.md)
- [DNSDumpster](Dominios/DNSDumpster.md)
- [ViewDNS](Dominios/ViewDNS.md)
- [crt.sh](Dominios/crt.sh.md)
- [Shodan](Dominios/Shodan.md)
- [Censys](Dominios/Censys.md)
- [VirusTotal](Dominios/VirusTotal.md)

---

## 👤 Personas

- [LinkedIn](Personas/linkedin.md)
- [Instagram](Personas/instagram.md)
- [TikTok](Personas/tiktok.md)
- [ORCID](Personas/orcid.md)
- [ResearchGate](Personas/researchgate.md)

---

## 📧 Email

- [Hunter](Email/hunter.md)
- [EmailRep](Email/emailrep.md)
- [Have I Been Pwned](Email/haveibeenpwned.md)
- [DeHashed](Email/dehashed.md)
- [Intelligence X](Email/intelligencex.md)

---

## 🌎 GEOINT

- [Google Maps](Geoint/googlemaps.md)
- [Google Earth](Geoint/googleearth.md)
- [OpenStreetMap](Geoint/openstreetmap.md)
- [Sentinel Hub](Geoint/sentinelhub.md)
- [ADS-B Exchange](Geoint/adsbexchange.md)
- [MarineTraffic](Geoint/marinetraffic.md)
- [SunCalc](Geoint/suncalc.md)
- [Windy](Geoint/windy.md)

---

## 📷 Imágenes

- [Google Lens](Imagenes/googlelens.md)
- [TinEye](Imagenes/tineye.md)
- [Yandex Images](Imagenes/yandeximages.md)
- [Bing Visual Search](Imagenes/bingvisualsearch.md)

---

## 📄 Metadatos

- [ExifTool](Metadatos/exiftool.md)
- [FOCA](Metadatos/foca.md)
- [MediaInfo](Metadatos/mediainfo.md)
- [PDFInfo](Metadatos/pdfinfo.md)

---

## 🛡 Threat Intelligence

- [AlienVault OTX](ThreatIntelligence/alienvaultotx.md)
- [AbuseIPDB](ThreatIntelligence/abuseipdb.md)
- [URLScan](ThreatIntelligence/urlscan.md)
- [Hybrid Analysis](ThreatIntelligence/hybridanalysis.md)
- [GreyNoise](ThreatIntelligence/greynoise.md)

---

## ⚙ Frameworks

- [Maltego](Frameworks/maltego.md)
- [SpiderFoot](Frameworks/spiderfoot.md)
- [Recon-ng](Frameworks/reconng.md)
- [Amass](Frameworks/amass.md)
- [theHarvester](Frameworks/theharvester.md)
- [BBOT](Frameworks/bbot.md)

---

## 📚 Casos prácticos

- [Índice de casos prácticos](Casos prácticos/casospracticos.md)

---

# Cómo utilizar este manual

Se recomienda seguir el siguiente orden:

1. Introducción a OSINT.
2. Motores de búsqueda.
3. Google Dorks.
4. Dominios.
5. Personas.
6. Redes sociales.
7. GEOINT.
8. Imágenes.
9. Metadatos.
10. Frameworks.

Cada documento puede consultarse de forma independiente.

---

# Metodología

Todos los documentos siguen la misma estructura:

1. Introducción
2. Historia
3. Funcionamiento
4. Instalación
5. Configuración
6. Interfaz
7. Características
8. Sintaxis
9. Ejemplos
10. Automatización
11. APIs
12. Integraciones
13. Buenas prácticas
14. Limitaciones
15. Errores frecuentes
16. Glosario
17. Referencias

Esto facilita la navegación y el aprendizaje.

---

# Convenciones

Se emplean las siguientes convenciones:

| Símbolo | Significado |
|----------|-------------|
| ℹ️ | Información |
| ⚠️ | Advertencia |
| 💡 | Consejo |
| 🛠 | Configuración |
| 📌 | Nota importante |
| 📖 | Referencia |

---

# Aspectos legales y éticos

Este proyecto tiene fines exclusivamente:

- Educativos.
- Formativos.
- Investigación.
- Auditoría.
- Concienciación.

No promueve actividades ilícitas, acceso no autorizado a sistemas ni vulneración de la privacidad. El uso de la información contenida en este repositorio es responsabilidad del usuario.

---

# Requisitos

Para aprovechar al máximo este manual se recomienda tener conocimientos básicos de:

- Redes
- DNS
- HTTP/HTTPS
- Linux
- Windows
- JSON
- APIs REST
- Python (opcional)

---

# Contribuciones

Las contribuciones son bienvenidas.

Si deseas colaborar:

1. Haz un Fork.
2. Crea una rama.
3. Añade o mejora documentación.
4. Envía un Pull Request.

Se recomienda mantener el mismo formato utilizado en el resto del proyecto.

---

# Licencia

Este proyecto se distribuye bajo la licencia **MIT**, salvo que se indique lo contrario en algún documento específico.

---

# Aviso

Las herramientas descritas pertenecen a sus respectivos propietarios y marcas registradas. Este proyecto es independiente y tiene un propósito exclusivamente educativo y de documentación.

---

**Última actualización:** Julio de 2026
