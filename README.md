# Proyecto-NLP-Fine-Tuning

# Proyecto de Fine-tuning de Modelos Transformer para NLP

Este repositorio alberga un proyecto integral centrado en el fine-tuning de varios modelos de Hugging Face Transformers para abordar tres tareas fundamentales de Procesamiento de Lenguaje Natural (PLN):

## Tareas Implementadas:

### 1. Clasificación de Secuencias (Detección de Texto IA/Humano)
- **Modelo Base:** DistilBERT
- **Dataset:** `AI-human-text`
- **Descripción:** Clasificación de textos para determinar si fueron generados por un humano o por una Inteligencia Artificial. El modelo predice una de dos clases: `0` (humano) o `1` (IA).

### 2. Etiquetado de Secuencias (Named Entity Recognition - NER en Películas)
- **Modelo Base:** DistilBERT
- **Dataset:** `ner_movie`
- **Descripción:** Reconocimiento de Entidades Nombradas en descripciones de películas. Se identifican y etiquetan elementos como actores, puntos de la trama (plot), opiniones, años y más, en el texto.

### 3. Secuencia a Secuencia (Resumen de Artículos Científicos - ArXiv Summarization)
- **Modelo Base:** T5-small
- **Dataset:** `arxiv-summarization`
- **Descripción:** Generación de resúmenes concisos (tipo abstract) para artículos científicos extraídos del dataset de ArXiv.

Google Colab link: https://colab.research.google.com/drive/1yMd6TFLTj62QL6XH98NTxO9gJLZunYs4?usp=sharing
