<!-- Streak -->
![Streak](https://streak-stats.demolab.com?user=triptalabs&theme=tokyonight&hide_border=true)

<!-- Stats generales -->
![Stats](https://github-readme-stats.vercel.app/api?username=triptalabs&show_icons=true&rank_icon=github&theme=tokyonight&hide_border=true)

<!-- Top Langs -->
![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=triptalabs&layout=compact&theme=tokyonight&hide_border=true)


<!-- Tokyo Night -->
![Activity Graph](https://github-readme-activity-graph.vercel.app/graph?username=triptalabs&theme=tokyo-night&hide_border=true)

<!-- GitHub Dark -->
![Activity Graph](https://github-readme-activity-graph.vercel.app/graph?username=triptalabs&theme=github-dark&hide_border=true)

<!-- High Contrast -->
![Activity Graph](https://github-readme-activity-graph.vercel.app/graph?username=triptalabs&theme=high-contrast&hide_border=true)

<!-- Nord -->
![Activity Graph](https://github-readme-activity-graph.vercel.app/graph?username=triptalabs&theme=nord&hide_border=true)

<!-- Xcode -->
![Activity Graph](https://github-readme-activity-graph.vercel.app/graph?username=triptalabs&theme=xcode&hide_border=true)

<!-- GitHub Compact (similar a tu screenshot pero más limpio) -->
![Activity Graph](https://github-readme-activity-graph.vercel.app/graph?username=triptalabs&theme=github-compact&hide_border=true)

<!--
CATÁLOGO DE GRÁFICAS para @triptalabs
- User: triptalabs
- Repo ejemplo: tripta-heat-pid
- Quita lo que no uses. Cada bloque viene comentado.
-->

# Catálogo de Gráficas (README)

## 0) Contexto breve
Este documento es un menú visual de **gráficas** para README. Hay dos familias:
- **Dinámicas (externas)**: tarjetas/plots servidos por terceros.
- **Mermaid (nativas)**: diagramas que renderiza GitHub directamente.

---

## 1) Gráficas dinámicas (externas)

### 1.1 Stats generales (GitHub Readme Stats) — *Tarjeta*
<picture>
  <img alt="Stats"
    src="https://github-readme-stats.vercel.app/api?username=triptalabs&show_icons=true&include_all_commits=true&rank_icon=github&theme=transparent&hide_border=true" />
</picture>

### 1.2 Lenguajes principales — *Barras compactas*
<picture>
  <img alt="Top Langs"
    src="https://github-readme-stats.vercel.app/api/top-langs/?username=triptalabs&layout=compact&langs_count=10&theme=transparent&hide_border=true" />
</picture>

### 1.3 Racha de contribuciones — *Heat/Bars*
<img alt="Streak"
  src="https://streak-stats.demolab.com?user=triptalabs&theme=transparent&hide_border=true" />

### 1.4 Grafo de actividad — *Commit graph*
<img alt="Activity Graph"
  src="https://github-readme-activity-graph.vercel.app/graph?username=triptalabs&theme=github-compact&hide_border=true" />

### 1.5 Trofeos — *Mosaico de logros*
<img alt="Trophies"
  src="https://github-profile-trophy.vercel.app/?username=triptalabs&theme=flat&no-frame=true&no-bg=true&column=6" />

### 1.6 Tarjeta del repo (pin) — *Mini panel del repo*
<a href="https://github.com/triptalabs/tripta-heat-pid">
  <img alt="tripta-heat-pid"
    src="https://github-readme-stats.vercel.app/api/pin/?username=triptalabs&repo=tripta-heat-pid&theme=transparent&hide_border=true" />
</a>

### 1.7 WakaTime — *Tiempo por lenguaje/semana*  *(opcional)*
<!-- Requiere tener cuenta WakaTime y username. Cambia "triptalabs" si tu usuario allá es distinto. -->
<img alt="WakaTime"
  src="https://github-readme-stats.vercel.app/api/wakatime?username=triptalabs&theme=transparent&hide_border=true" />

### 1.8 Métricas avanzadas (lowlighter) — *Múltiples módulos en SVG*  *(requiere workflow)*
<!-- Una vez configures el Action, expone varios SVGs; aquí ejemplos que puedes dejar enlazados: -->
<!-- Clásico -->
<!-- <img src="https://raw.githubusercontent.com/triptalabs/triptalabs/main/metrics.classic.svg" alt="Metrics classic"> -->
<!-- Isocalendar (heatmap de año) -->
<!-- <img src="https://raw.githubusercontent.com/triptalabs/triptalabs/main/metrics.isocalendar.fullyear.svg" alt="Isocalendar"> -->
<!-- Lenguajes detallados -->
<!-- <img src="https://raw.githubusercontent.com/triptalabs/triptalabs/main/metrics.languages.details.svg" alt="Languages details"> -->
<!-- Logros -->
<!-- <img src="https://raw.githubusercontent.com/triptalabs/triptalabs/main/metrics.achievements.compact.svg" alt="Achievements"> -->

### 1.9 “Snake” de contribuciones — *Animación del grid*  *(requiere workflow)*
<!-- Una vez configurado el Action, queda algo como: -->
<!-- <img src="https://raw.githubusercontent.com/triptalabs/triptalabs/output/github-contribution-grid-snake.svg" alt="Snake"> -->

> **Nota**: 1.8 y 1.9 requieren GitHub Actions; abajo te dejo YAMLs opcionales.

---

## 2) Diagramas Mermaid (nativos en GitHub)

> Edita los contenidos a tu caso. Todos estos **renderizan sin servicios externos**.

### 2.1 Flowchart — *Flujo de control PID (sensor → PID → SSR)*
```mermaid
flowchart LR
  PT100[(PT100 via RS485)] -->|Modbus RTU| SENSOR[Lectura filtrada]
  SENSOR --> PID[Control PID]
  PID -->|PWM/SSR| HEATER[Resistencia 110V]
  PID --> LOG[(NVS)]
  UI[LVGL UI] <---> PID
  UI --> OTA[Actualización OTA]
