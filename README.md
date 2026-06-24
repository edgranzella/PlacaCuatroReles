# Placa Cuatro Relés - Hardware y PCB 🚀

Este repositorio contiene el diseño completo de la placa de circuito impreso (PCB) desarrollado en **KiCad** para un sistema de conmutación y control de potencia de **4 canales de relés**.

---

## 📌 Características del Diseño
* **Canales de Potencia:** 4 relés independientes con aislamiento optoacoplado para proteger la etapa de control.
* **Bornes de Conexión:** Bloques de terminales de tornillo (Terminal Blocks) robustos para salidas de alta corriente (NA / NC / COM).
* **Etapa de Disparo:** Transistores/Optoacopladores dedicados por canal con diodos de libre circulación (flyback) integrados.
* **Indicadores Visuales:** LEDs de estado montados en placa para retroalimentación visual de la activación de cada canal.

---

## 🛠️ Especificaciones Técnicas de Fabricación
Configuración sugerida en base a las reglas de diseño (DRC) aplicadas en KiCad:

| Parámetro | Configuración Sugerida |
| :--- | :--- |
| **Capas (Layers)** | 2 Capas |
| **Grosor de la Placa** | 1.6 mm |
| **Ancho de Pistas** | Señales estándar / Pistas de potencia reforzadas |
| **Acabado Superficial** | HASL (with lead) o ENIG |

---

## 👥 Desarrollado por
* **Damian Granzella** - *Ingeniería de Hardware* - [edgranzella](https://github.com)
