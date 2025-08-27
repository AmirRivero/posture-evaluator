# Posture Evaluator 🧍‍♂️💻

![Python](https://img.shields.io/badge/Python-3.11%2B-blue.svg)
![OpenCV](https://img.shields.io/badge/OpenCV-4.x-green.svg)
![MediaPipe](https://img.shields.io/badge/MediaPipe-Pose-orange.svg)
![License](https://img.shields.io/badge/License-MIT-lightgrey.svg)

Monitorea y evalúa la postura al estar sentado en oficina usando **Python**, **OpenCV** y **MediaPipe Pose**.  
Mide inclinación de espalda, posición de cabeza, simetría de hombros/caderas y entrega un **puntaje en tiempo real (0–100)** con **consejos para mejorar tu ergonomía**.

---

## **✨ Características**
- **Detección en tiempo real** de puntos clave del cuerpo (keypoints).
- **Puntaje de postura (0–100)** con recomendaciones automáticas.
- **Compatible con webcam o cámara del celular** (IP Webcam / DroidCam).
- **Instalación automática** en Windows (`setup_postura.ps1` / `run_postura.bat`).
- Código modular y listo para futuras mejoras (ej. ML).

---

## **📦 Instalación rápida (Windows)**

```powershell
git clone https://github.com/TU_USUARIO/posture-evaluator.git
cd posture-evaluator
.\scripts\run_postura.bat
