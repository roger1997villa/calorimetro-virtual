# calo# ⚗️ Calorímetro Virtual

[![Demo en vivo](https://img.shields.io/badge/demo-online-success)](https://TU-USUARIO.github.io/calorimetro-virtual/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)](https://developer.mozilla.org/es/docs/Web/HTML)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)](https://developer.mozilla.org/es/docs/Web/JavaScript)

Laboratorio virtual interactivo para **identificar materiales desconocidos** 
a partir de su calor específico, usando el principio de conservación de la energía.

## 🎓 Fundamento físico

Cuando un objeto caliente se sumerge en agua fría, ambos alcanzan una 
temperatura de equilibrio $T_{eq}$. Por conservación de energía:

$$m_{obj} \cdot c_{obj} \cdot (T_{eq} - T_{obj}) = m_{agua} \cdot c_{agua} \cdot (T_{agua} - T_{eq})$$

Despejando el calor específico del objeto desconocido:

$$c_{obj} = \frac{m_{agua} \cdot c_{agua} \cdot (T_{eq} - T_{agua})}{m_{obj} \cdot (T_{obj} - T_{eq})}$$

## ✨ Características

- 🎨 Interfaz glassmorphism con animaciones CSS
- 🌡️ Termómetro y calorímetro animados en tiempo real
- 🔬 Base de datos con 15 materiales reales
- 📊 Identificación automática por proximidad estadística
- 📱 Diseño responsive (móvil, tablet, escritorio)

## 🚀 Demo

[Ver demo en vivo](https://TU-USUARIO.github.io/calorimetro-virtual/)

## 🛠️ Uso local

```bash
git clone https://github.com/TU-USUARIO/calorimetro-virtual.git
cd calorimetro-virtual
# Abre index.html en tu navegador o usa:
python -m http.server 8000rimetro-virtual
