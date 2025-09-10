<!--
README-CATÁLOGO • Artefactos para elegir
Usa placeholders:
- TU_USUARIO  -> tu user de GitHub (p.ej., triptalabs)
- TU_REPO     -> un repo cualquiera (p.ej., firmware-vacuum-oven)
- TU_ORG      -> si aplicara
- COLOR_HEX   -> sin "#", p.ej. 0e75b6

Quita lo que no uses. Cada bloque trae variantes.
-->

# Catálogo de Artefactos para READMEs

## 0) Mini-guía (cómo probar rápido)
- Reemplaza `TU_USUARIO` y `TU_REPO` globalmente.
- Mantén **pocas** secciones activas a la vez (menos ruido, más señal).
- Recuerda: muchas imágenes pasan por proxy → **caché** (no te asustes si tarda en actualizar).

---

## 1) Encabezados / Portada

<!-- Variante A: simple alineado a la izquierda -->
# Nombre del Proyecto
Descripción en una línea: qué hace, para quién y por qué importa.

<!-- Variante B: centrado con subtítulo -->
<div align="center">
  <h1>Nombre del Proyecto</h1>
  <p><em>Pitch breve y contundente</em></p>
</div>

<!-- Variante C: banner (sube tu imagen al repo o usa una URL) -->
<p align="center">
  <img src="https://raw.githubusercontent.com/TU_USUARIO/TU_REPO/main/docs/banner.png" alt="Banner" width="800">
</p>

---

## 2) Badges — Contadores & “social proof”

<!-- Estilos: flat | flat-square | plastic | for-the-badge -->

<!-- Visitas (Komarev) -->
![Visitas](https://komarev.com/ghpvc/?username=TU_USUARIO&label=Visitas&color=COLOR_HEX&style=flat)

<!-- Stars / Forks / Watchers -->
![Stars](https://img.shields.io/github/stars/TU_USUARIO/TU_REPO?style=flat)
![Forks](https://img.shields.io/github/forks/TU_USUARIO/TU_REPO?style=flat)
![Watchers](https://img.shields.io/github/watchers/TU_USUARIO/TU_REPO?style=flat)

<!-- Followers (perfil) -->
![Followers](https://img.shields.io/github/followers/TU_USUARIO?style=flat)

<!-- Último commit / Issues / PRs -->
![Last Commit](https://img.shields.io/github/last-commit/TU_USUARIO/TU_REPO?style=flat)
![Open Issues](https://img.shields.io/github/issues/TU_USUARIO/TU_REPO?style=flat)
![Open PRs](https://img.shields.io/github/issues-pr/TU_USUARIO/TU_REPO?style=flat)

<!-- Licencia / Release / Descargas -->
![License](https://img.shields.io/github/license/TU_USUARIO/TU_REPO?style=flat)
![Release](https://img.shields.io/github/v/release/TU_USUARIO/TU_REPO?display_name=tag&style=flat)
![Downloads](https://img.shields.io/github/downloads/TU_USUARIO/TU_REPO/total?style=flat)

<!-- Redes / Contacto -->
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Contactar-blue?style=flat&logo=linkedin)](https://www.linkedin.com/)
[![Web](https://img.shields.io/badge/Web-Visitar-0e75b6?style=flat&logo=vercel)](https://example.com)
[![Email](https://img.shields.io/badge/Email-Enviar-8A2BE2?style=flat&logo=gmail)](mailto:contacto@example.com)

<!-- Badges "for-the-badge" más llamativos -->
![Build](https://img.shields.io/github/actions/workflow/status/TU_USUARIO/TU_REPO/ci.yml?label=CI&style=for-the-badge)
![Coverage](https://img.shields.io/codecov/c/github/TU_USUARIO/TU_REPO?style=for-the-badge)

---

## 3) Badges — Stack técnico (varias estéticas)

<!-- Opción A: Shields con logos -->
![C](https://img.shields.io/badge/C-Systems-COLOR_HEX?style=flat&logo=c)
![C++](https://img.shields.io/badge/C%2B%2B-Embedded-COLOR_HEX?style=flat&logo=c%2B%2B)
![ESP-IDF](https://img.shields.io/badge/ESP--IDF-Firmware-COLOR_HEX?style=flat&logo=espressif)
![FreeRTOS](https://img.shields.io/badge/FreeRTOS-RTOS-COLOR_HEX?style=flat)
![LVGL](https://img.shields.io/badge/LVGL-UI-COLOR_HEX?style=flat)
![RS485/Modbus](https://img.shields.io/badge/RS485%2FModbus-Fieldbus-COLOR_HEX?style=flat)
![TypeScript](https://img.shields.io/badge/TypeScript-Frontend-COLOR_HEX?style=flat&logo=typescript)
![React](https://img.shields.io/badge/React-UI-COLOR_HEX?style=flat&logo=react)
![TailwindCSS](https://img.shields.io/badge/TailwindCSS-Style-COLOR_HEX?style=flat&logo=tailwindcss)
![Supabase](https://img.shields.io/badge/Supabase-DB-COLOR_HEX?style=flat&logo=supabase)
![Python](https://img.shields.io/badge/Python-Scripting-COLOR_HEX?style=flat&logo=python)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-CI-COLOR_HEX?style=flat&logo=githubactions)

<!-- Opción B: Devicon (SVGs limpios) -->
<p>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/c/c-original.svg" height="32" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/cplusplus/cplusplus-original.svg" height="32" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" height="32" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/react/react-original.svg" height="32" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" height="32" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/tailwindcss/tailwindcss-plain.svg" height="32" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/espressif/espressif-original.svg" height="32" />
</p>

<!-- Opción C: Emojis minimalistas -->
`🧠 C/C++` · `🔌 ESP-IDF` · `⏱ FreeRTOS` · `🎛 LVGL` · `📡 RS485/Modbus` · `⚛️ React` · `🌀 Tailwind` · `🗃 Supabase` · `🐍 Python`

---

## 4) Estado del proyecto & Calidad

<!-- CI (GitHub Actions) -->
![CI](https://img.shields.io/github/actions/workflow/status/TU_USUARIO/TU_REPO/ci.yml?label=CI&style=flat)

<!-- Codecov (coverage) -->
![Coverage](https://img.shields.io/codecov/c/github/TU_USUARIO/TU_REPO?style=flat)

<!-- SonarCloud (Quality Gate) -->
![Quality Gate](https://img.shields.io/sonar/quality_gate/TU_ORG:TU_REPO?server=https%3A%2F%2Fsonarcloud.io&style=flat)

<!-- Linter / Formatter genéricos -->
![Lint](https://img.shields.io/badge/Lint-passing-brightgreen?style=flat)
![Format](https://img.shields.io/badge/Format-Prettier-informational?style=flat&logo=prettier)

---

## 5) Paquetes, builds, tamaños

<!-- npm versión / downloads -->
![npm](https://img.shields.io/npm/v/TU_PAQUETE?style=flat)
![npm dls](https://img.shields.io/npm/dm/TU_PAQUETE?style=flat)

<!-- PyPI versión / downloads (si aplica) -->
![PyPI](https://img.shields.io/pypi/v/TU_PAQUETE?style=flat)

<!-- Bundlephobia (tamaño del bundle) -->
![Size](https://img.shields.io/bundlephobia/minzip/TU_PAQUETE?style=flat)

<!-- Docker pulls / image size -->
![Docker Pulls](https://img.shields.io/docker/pulls/TU_USUARIO/TU_IMAGEN?style=flat)
![Image Size](https://img.shields.io/docker/image-size/TU_USUARIO/TU_IMAGEN/latest?style=flat)

---

## 6) Documentación

[![Docs](https://img.shields.io/badge/Docs-Read%20the%20Docs-0e75b6?style=flat&logo=readthedocs)](https://readthedocs.org/)
[![Storybook](https://img.shields.io/badge/Storybook-UI-ff4785?style=flat&logo=storybook)](https://storybook.js.org/)
[![Swagger](https://img.shields.io/badge/OpenAPI-Swagger-85EA2D?style=flat&logo=swagger)](https://swagger.io/)

---

## 7) Gráficas / Estadísticas (tarjetas populares)

<!-- GitHub Readme Stats (anuraghazra) -->
<picture>
  <img alt="Stats" height="150"
    src="https://github-readme-stats.vercel.app/api?username=TU_USUARIO&show_icons=true&include_all_commits=true&rank_icon=github&theme=transparent&hide_border=true" />
</picture>
<picture>
  <img alt="Top Langs" height="150"
    src="https://github-readme-stats.vercel.app/api/top-langs/?username=TU_USUARIO&layout=compact&langs_count=8&theme=transparent&hide_border=true" />
</picture>

<!-- Streak (DenverCoder1) -->
<img alt="Streak"
  src="https://streak-stats.demolab.com?user=TU_USUARIO&theme=transparent&hide_border=true" />

<!-- Activity Graph -->
<img alt="Activity Graph"
  src="https://github-readme-activity-graph.vercel.app/graph?username=TU_USUARIO&theme=github-compact&hide_border=true" />

<!-- Pin cards (para repos específicos) -->
<a href="https://github.com/TU_USUARIO/TU_REPO">
  <img alt="Repo pin"
    src="https://github-readme-stats.vercel.app/api/pin/?username=TU_USUARIO&repo=TU_REPO&theme=transparent&hide_border=true" />
</a>

<!-- Métricas avanzadas (lowlighter/github-profile-metrics) -> requiere workflow propio que genere metrics.svg -->
<!-- Una vez configurado el action, enlaza el SVG resultante: -->
<!-- <img src="https://raw.githubusercontent.com/TU_USUARIO/TU_USUARIO/main/metrics.svg" alt="Metrics"> -->

<!-- Snake (contrib animation) -> requiere workflow Platane/snk -->
<!-- <img src="https://raw.githubusercontent.com/TU_USUARIO/TU_USUARIO/output/github-contribution-grid-snake.svg" alt="Snake"> -->

> Nota: estas tarjetas dependen de servicios externos y caché. Útiles para overview, no para auditoría fina.

---

## 8) Bloques “callout” / Plegables / Tabs

> **Nota**: Usa callouts para advertencias o ideas clave.  
> Sugerencia: *“Problema → Solución → Impacto”* en 2–3 líneas.

<details>
<summary>Detalles técnicos (click para expandir)</summary>

- Arquitectura: breve explicación por capas.
- Dependencias críticas.
- Limitaciones y trade-offs.

</details>

<!-- Tabs con HTML nativo (simple) -->
<table>
<tr>
<td>

**Caso de uso A**
- Paso 1
- Paso 2

</td>
<td>

**Caso de uso B**
- Paso 1
- Paso 2

</td>
</tr>
</table>

---

## 9) Tablas comparativas (con iconos)

| Feature                | Estado      | Notas                          |
|-----------------------|------------:|--------------------------------|
| PID Horno             | ✅          | Autotune + NVS                 |
| OTA desde microSD     | ✅          | Fallback seguro                |
| Chart en UI (LVGL)    | 🟡          | Backlog → optimización         |
| App móvil             | ❌          | No en este milestone           |

---

## 10) Snippets “copiar y pegar”

### Instalación (ejemplo)
```bash
git clone https://github.com/TU_USUARIO/TU_REPO.git
cd TU_REPO
# instrucciones mínimas
