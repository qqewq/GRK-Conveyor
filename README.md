# GRK-Conveyor | Конвейер GRK

**Mathematical Core for Robotics | Математическое ядро для робототехники**

[![arXiv](https://img.shields.io/badge/arXiv-preprint-b31b1b.svg)](https://arxiv.org)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

---

## 🧠 Overview | Описание

**EN:**  
GRK-Conveyor is a mathematical framework for embodied AI and robotics based on contradiction functional minimization ($J \to 0$) and novelty tracking ($N(O)$). It implements the GRA (Generative Robotic Architecture) core, enabling rapid meta-nullification under perturbations and stable sim-to-real transfer.

**RU:**  
GRK-Conveyor — это математический фреймворк для embodied AI и робототехники, основанный на минимизации функционала противоречий ($J \to 0$) и отслеживании новизны ($N(O)$). Он реализует ядро GRA (Generative Robotic Architecture), обеспечивая быстрое мета-обнуление при возмущениях и стабильный перенос sim-to-real.

---

## 📐 Key Concepts | Ключевые концепции

| Concept | EN | RU |
|--------|----|----|
| **Contradiction Functional** | $J = \sum_i w_i \cdot C_i$, where $C_i$ are contradiction terms. Goal: $J \to 0$. | Функционал противоречий: $J = \sum_i w_i \cdot C_i$, где $C_i$ — члены противоречий. Цель: $J \to 0$. |
| **Novelty Tracking** | $N(O)$ measures deviation from known operational manifold. | Отслеживание новизны: $N(O)$ измеряет отклонение от известного операционального многообразия. |
| **Meta-Nullification** | Rapid reset of internal state when $J$ exceeds threshold. | Мета-обнуление: быстрый сброс внутреннего состояния при превышении порога $J$. |
| **RAD-Revision** | Recursive Architecture Diagnosis for self-correction. | RAD-ревизия: рекурсивная диагностика архитектуры для самокоррекции. |

---

## 🚀 Getting Started | Начало работы

### Prerequisites | Требования

- Python 3.9+
- MuJoCo or Isaac Sim (for simulation)
- LaTeX (for paper compilation)

### Installation | Установка

```bash
git clone https://github.com/qqewq/GRK-Conveyor.git
cd GRK-Conveyor
pip install -r requirements.txt
```

### Running Simulations | Запуск симуляций

```bash
python simulations/run_gra.py --env mujoco --task ant_balance
```

---

## 📄 Paper | Статья

The core mathematical formulation is described in `paper.tex`. Compile with:

```bash
pdflatex paper.tex
```

**EN:** The paper includes problem statement, GRA architecture, formulas for $J$ and $N(O)$, and RAD-revision algorithm.  
**RU:** Статья включает постановку задачи, архитектуру GRA, формулы для $J$ и $N(O)$, и алгоритм RAD-ревизии.

---

## 🤝 Contributing | Участие

**EN:** We are looking for co-authors and ML engineers to implement simulations and publish at CoRL/ICRA.  
**RU:** Мы ищем соавторов и ML-инженеров для реализации симуляций и публикации на CoRL/ICRA.

Contact: [oleg.bits.97@gmail.com]

---

## 📜 License | Лицензия

MIT License | Лицензия MIT