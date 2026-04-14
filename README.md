# 🧠 HCI Cognitive Lab · Batería de tareas atencionales

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.XXXXXXX.svg)](https://doi.org/10.5281/zenodo.XXXXXXX)

> **English** | [Español](#español)

---

## English

### Attention and Memory Task Battery

A complete web‑based battery of 7 cognitive tasks (Stroop, Flanker, Simon, Go/No‑go, ANT, N‑back, Posner) designed for research in attention, inhibitory control, working memory and spatial orienting. Data are stored in **Supabase** (cloud database) and can be exported to CSV/JSON. A unified admin dashboard displays real‑time statistics and participant summaries.

**Author:** Jose Ranero García (ORCID: 0009-0009-3168-6379)

#### 🧪 Tasks included

| Task | Measures | Key output |
|------|----------|-------------|
| **Stroop** | Semantic interference, selective attention | Stroop effect (ms) |
| **Flanker** | Attentional suppression, distractor interference | Flanker effect (ms) |
| **Simon** | Spatial compatibility, stimulus‑response conflict | Simon effect (ms) |
| **Go/No‑go** | Inhibitory control, response suppression | d', false alarms, omissions |
| **ANT** | Attention networks (alerting, orienting, conflict) | Network scores (ms) |
| **N‑back** | Working memory updating | d', hits, false alarms |
| **Posner** | Spatial orienting, attentional shifting | Orienting effect (ms) |

#### 🛠️ Tech stack

- HTML5 / CSS3 / JavaScript (ES6)
- [Supabase](https://supabase.com/) – database & API
- [Chart.js](https://www.chartjs.org/) – real‑time charts
- Hosted on **GitHub Pages**

#### 🚀 Live demo

- Main menu: [https://argira.eus/stroop-attention/](https://argira.eus/stroop-attention/)
- Admin dashboard: [https://argira.eus/stroop-attention/dashboard.html](https://argira.eus/stroop-attention/dashboard.html)

#### 📊 Database schema (Supabase)

Each task has its own table, e.g. `stroop_trials`, `flanker_trials`, etc. Common columns:

- `participant_id` (TEXT) – unique identifier
- `cohort` (TEXT) – experimental / control
- `trial` (INT) – trial number
- `rt_ms` (INT) – reaction time in milliseconds
- `correct` (BOOLEAN) – response accuracy
- `created_at` (TIMESTAMPTZ) – automatic timestamp

#### 📄 How to cite

If you use this battery in your research, please cite it as:

> Ranero García, J. (2026). HCI Cognitive Lab: Attention and memory task battery. Zenodo. https://doi.org/10.5281/zenodo.XXXXXXX

#### 📝 License

MIT License – free to use, modify and distribute with attribution.

---

## Español

### Batería de tareas de atención y memoria

Batería completa de 7 tareas cognitivas web (Stroop, Flanker, Simon, Go/No‑go, ANT, N‑back, Posner) diseñada para investigación en atención, control inhibitorio, memoria de trabajo y orientación espacial. Los datos se almacenan en **Supabase** (base de datos en la nube) y se pueden exportar a CSV/JSON. Un dashboard de administración unificado muestra estadísticas en tiempo real y resúmenes por participante.

**Autor:** Jose Ranero García (ORCID: 0009-0009-3168-6379)

#### 🧪 Tareas incluidas

| Tarea | Mide | Indicador principal |
|-------|------|---------------------|
| **Stroop** | Interferencia semántica, atención selectiva | Efecto Stroop (ms) |
| **Flanker** | Supresión atencional, interferencia de distractores | Efecto Flanker (ms) |
| **Simon** | Compatibilidad espacial, conflicto estímulo‑respuesta | Efecto Simon (ms) |
| **Go/No‑go** | Control inhibitorio, supresión de respuesta | d', falsas alarmas, omisiones |
| **ANT** | Redes atencionales (alerta, orientación, conflicto) | Puntuaciones de red (ms) |
| **N‑back** | Memoria de trabajo, actualización | d', aciertos, falsas alarmas |
| **Posner** | Orientación espacial, cambio de foco atencional | Efecto orientación (ms) |

#### 🛠️ Tecnologías

- HTML5 / CSS3 / JavaScript (ES6)
- [Supabase](https://supabase.com/) – base de datos y API
- [Chart.js](https://www.chartjs.org/) – gráficos en tiempo real
- Alojado en **GitHub Pages**

#### 🚀 Demo en vivo

- Menú principal: [https://argira.eus/stroop-attention/](https://argira.eus/stroop-attention/)
- Dashboard de administración: [https://argira.eus/stroop-attention/dashboard.html](https://argira.eus/stroop-attention/dashboard.html)

#### 📊 Esquema de base de datos (Supabase)

Cada tarea tiene su propia tabla, ej. `stroop_trials`, `flanker_trials`, etc. Columnas comunes:

- `participant_id` (TEXT) – identificador único
- `cohort` (TEXT) – experimental / control
- `trial` (INT) – número de ensayo
- `rt_ms` (INT) – tiempo de reacción en milisegundos
- `correct` (BOOLEAN) – precisión de la respuesta
- `created_at` (TIMESTAMPTZ) – marca de tiempo automática

#### 📄 Cómo citar

Si usas esta batería en tu investigación, por favor cítala como:

> Ranero García, J. (2026). HCI Cognitive Lab: Batería de tareas de atención y memoria. Zenodo. https://doi.org/10.5281/zenodo.XXXXXXX

#### 📝 Licencia

Licencia MIT – libre de usar, modificar y distribuir con atribución.