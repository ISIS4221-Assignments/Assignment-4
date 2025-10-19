# ASSIGNMENT-4

Este proyecto implementa la construcción y entrenamiento de embeddings o incrustaciones personalizadas a partir de la arquitectura Word2Vec, su visualización
en dos dimensiones y su uso en el entrenamiento y comparación de modelos de clasificación a partir de redes neuronales feed forward. Los resultados de las redes
se comparan entren embeddings personalizados y embeddings GLOVE pre-entrenados.

## 📁 Estructura del Proyecto

```
├── data                                           # Datos para el entrenamiento de embeddings y modelos de clasificación
│   ├── austen_emma.txt
│   ├── austen_pride.txt
│   ├── austen_sense.txt
│   ├── dickens_expectations.txt
│   ├── dickens_twist.txt
│   ├── dickens_two_cities.txt
│   ├── twain_huck.txt
│   ├── twain_prince.txt
│   └── twain_tom.txt
├── docs                                           # Documento con la documentación técnica y respuesta a preguntas
│   ├── INFORME.docx
│   └── INFORME.pdf
├── figures                                        # Imagenes visualizando los embeddings en dos dimensiones
│   ├── becky_50d.png
│   ├── carton_50d.png
│   ├── darcy_50d.png
│   ├── darnay_50d.png
│   ├── elinor_50d.png
│   ├── elizabeth_50d.png
│   ├── emma_50d.png
│   ├── fagin_50d.png
│   ├── havisham_50d.png
│   ├── huck_50d.png
│   ├── jim_50d.png
│   ├── knightley_50d.png
│   ├── marianne_50d.png
│   ├── oliver_50d.png
│   ├── pauper_50d.png
│   ├── pip_50d.png
│   ├── prince_50d.png
│   └── tom_50d.png
├── LICENSE
├── models                                         # Modelos de embeddings utilizados (propios y pre-entrenados)
│   ├── Books_100_G01.model
│   ├── Books_100_G01.vec
│   ├── Books_200_G01.model
│   ├── Books_200_G01.vec
│   ├── Books_50_G01.model
│   ├── Books_50_G01.vec
│   └── glove.6b
├── README.md
├── requirements.txt
└── src                                            # Código fuente
    └── embeddings.ipynb
```

## 🐍 Requisitos del Sistema

- **Python**: 3.11.9 (recomendado)
- **Sistema Operativo**: Windows, macOS o Linux

## 🚀 Instalación y Configuración

### 1. Clonar el repositorio
```bash
git clone git@github.com:ISIS4221-Assignments/Assignment-4.git
cd ASSIGNMENT-4
```

### 2. Crear entorno virtual
```bash
# Crear entorno virtual
python -m venv venv

# Activar entorno virtual
# En Windows:
venv\Scripts\activate

# En macOS/Linux:
source venv/bin/activate
```

### 3. Instalar dependencias
```bash
pip install -r requirements.txt
```

## 📋 Documentación Detallada

- **Código**: Todo el código incluye docstrings detallados
- **Documento**: En la carpeta docs se incluye un informe detallado del proyecto, junto con la respuesta a las preguntas planteadas en el enunciado del mismo