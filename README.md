# Academic Machine Learning Models

Este repositorio contiene implementaciones **a nivel académico** de tres modelos de aprendizaje automático, desarrollados con fines educativos para comprender los conceptos y el flujo básico de trabajo en distintas áreas de clasificación y detección.  
⚠ **Nota:** Los modelos y datos utilizados **no son de uso productivo**. Su objetivo es únicamente ilustrar ideas y metodologías de forma simplificada.

---

## 📂 Contenido del repositorio

1. **Clasificador de Spam con Naive Bayes**  
   - **Objetivo:** Distinguir entre mensajes spam y no spam.  
   - **Enfoque:** Uso de un modelo Naive Bayes para clasificación de texto.  
   - **Datos:** Dataset académico
   - **Puntos clave:**  
     - Limpieza y tokenización de texto.  
     - Conversión a representación numérica (Bag of Words)
     - Entrenamiento y evaluación básica.

2. **Detección de Anomalías de Red con Isolation Tree**  
   - **Objetivo:** Identificar patrones anómalos en datos de tráfico de red.  
   - **Enfoque:** Modelo Isolation Forest para detección no supervisada de anomalías.  
   - **Datos:** Conjuntos de datos limpiados.
   - **Puntos clave:**  
     - Evaluación en datos simulados.

3. **Detector de Malware con CNN**  
   - **Objetivo:** Clasificar binarios simulados o transformados a formato de imagen como benignos o maliciosos.  
   - **Enfoque:** Red neuronal convolucional (CNN).  
   - **Datos:** Representación en imagenes de archivos malware.
   - **Base:** Arquitectura CNN preexistente adaptada para este experimento.  
---

## 🛠 Tecnologías utilizadas

- **Python 3.x**
- **Bibliotecas principales:**
  - `scikit-learn`
  - `numpy`, `pandas`
  - `matplotlib`, `seaborn`
  - `PyTorch` (para la CNN)

---

## ⚠ Aviso importante

- **No** se recomienda el uso de estos modelos en entornos reales.
- El modelo de CNN se basa en una arquitectura ya existente, adaptada para este proyecto.


