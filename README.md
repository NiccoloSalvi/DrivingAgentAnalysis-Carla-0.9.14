# InterFuser vs TransFuser – Agent Behavior Analysis in CARLA 0.9.14

This repository contains a comparative analysis of the behavior of two autonomous driving agents—**InterFuser** and **TransFuser**—evaluated within the CARLA simulator (version 0.9.14) and Python 3.8.  
Our study identifies and visualizes key failure cases using simulation footage and qualitative reasoning.

## 🔍 Overview

- **Environment**: CARLA 0.9.14
- **Agents analyzed**:  
  - [InterFuser](https://github.com/opendilab/InterFuser)  
  - [TransFuser](https://github.com/autonomousvision/transfuser)
- **Focus**: Agent behavior in realistic driving scenarios

## 📑 Contents

- 📄 `report.pdf`: Full report including observations, failure analyses, and discussion
- 📁 `gifs/`: Animated examples (GIFs) of major failure cases
- 📁 `images/`: Additional visual assets from simulations

## ⚠️ Observed Issues

| ID  | Failure Case                           | Affected Agent(s) |
|-----|----------------------------------------|-------------------|
| P1  | Premature stop at intersections        | InterFuser, TransFuser |
| P2  | Blocked by static vehicles             | InterFuser        |
| P3  | Struggles under very dark conditions   | InterFuser        |

Each of these issues is documented with both **video evidence** and **analysis of sensor input/output**.

## 🎬 Sample GIFs

| Failure | Preview |
|--------|---------|
| Premature Stop | ![](gifs/p1_premature_stop.gif) |
| Darkness Navigation Failure | ![](gifs/p3_dark_condition.gif) |

## 📘 Report

You can find the full analysis in [`report/report.pdf`](report/report.pdf), including:
- Metric-based evaluation
- Root cause discussions
- Sensor fusion limitations
- Suggestions for improvements

## 📎 Related Repositories

- 🔗 [InterFuser-Carla-0.9.14](https://github.com/NiccoloSalvi/InterFuser-Carla0914)
- 🔗 [TransFuser-Carla-0.9.14](https://github.com/NiccoloSalvi/TransFuser-Carla0914)

## 📅 Project Info

- **Author**: [NIccolò Salvi](https://github.com/NiccoloSalvi) & [Beatrice Zani](https://github.com/beazani) 
- **Course/Project**: Research Project - Software Engineering 2 @ Politecnico di Milano
- **Date**: July 2025
