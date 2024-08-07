# Proyecto de Fine-Tuning de GPT-2 para Generación de Texto

Este proyecto tiene como objetivo aplicar técnicas de fine-tuning a un modelo de lenguaje de tipo decoder, específicamente GPT-2, utilizando un conjunto de datos del ámbito médico, PubMedQA. El propósito es mejorar la capacidad del modelo para generar respuestas relevantes en un contexto médico.

## Modelo Utilizado

El modelo base seleccionado es **GPT-2 Large**, un modelo preentrenado disponible a través de la librería Hugging Face Transformers. Este modelo se seleccionó debido a su balance entre capacidad de generación de texto y manejabilidad en términos de recursos computacionales. GPT-2 ha sido probado extensivamente en tareas de generación de texto y ha demostrado ser efectivo en una variedad de dominios.

El propósito de este proyecto es adaptar GPT-2 a un dominio especializado como el médico, lo que requiere ajustes finos a través del entrenamiento en datos específicos.


## Justificación de la Selección del Modelo

Se optó por utilizar GPT-2 Large por varias razones:

1. **Tamaño y Capacidad**: GPT-2 Large es lo suficientemente grande para capturar contextos complejos y generar texto coherente, pero no tan grande como GPT-3, lo que lo hace más manejable para el fine-tuning en entornos con recursos computacionales limitados.
2. **Flexibilidad**: GPT-2 ha demostrado ser altamente adaptable a diferentes tareas de generación de texto, y su arquitectura basada en transformadores es adecuada para el aprendizaje en dominios especializados.
3. **Accesibilidad**: Dado que GPT-2 es un modelo ampliamente utilizado y disponible en la plataforma de Hugging Face, es accesible y tiene una gran cantidad de recursos y documentación que facilita su implementación.


## Instrucciones para Reproducir el Entorno y Ejecutar el Proyecto

### 1. Requisitos Previos

Antes de comenzar, asegúrate de tener instalado **Python 3.8** o superior en tu sistema.

### 2. Clonar el Repositorio

Clona este repositorio en tu máquina local:

```bash
git clone https://github.com/scudr/LLM_Decoder.git
cd LLM_Decoder.git
```

# Crear un entorno virtual
python3 -m venv myenv

# Activar el entorno virtual
# En Linux/MacOS
source myenv/bin/activate

# En Windows
myenv\Scripts\activate

# Instalar dependencias
```bash
pip install transformers datasets torch
```

# Iniciar Jupyter Notebook
jupyter notebook
