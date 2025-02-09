# Taller 7 Inteligencia artificial generativa

### Presentado por:
- **Ángel Rivera Amortegui**
- **Daniel Echeverry Jimenez**

---
## **Punto 1: Escoger dos de los siguientes ejercicios para su realización. Los ejercicios desarrollados deben ir muy bien documentados.**
Generación de Texto con GPT-3: Realizar ejercicios de generación de texto utilizando una API basada en GPT-3. Pueden generar historias, poemas o respuestas a preguntas específicas.
Archivo: [7_1_Chatbot_Basado_en_Transformer_.ipynb](./7_1_Chatbot_Basado_en_Transformer_.ipynb)
Descripción:  Este código implementa un chatbot basado en la arquitectura Transformer, utilizando GPT-2 de Hugging Face. Primero, carga el modelo y el tokenizador, configurando el padding para evitar errores. Luego, define un conjunto de diálogos de ejemplo y los tokeniza para entrenar al modelo en la generación de respuestas. Se usa Trainer de Hugging Face con argumentos personalizados para entrenar el modelo, desactivando la integración con Weights & Biases para evitar interrupciones.Tras el entrenamiento, el modelo y el tokenizador se guardan para su uso posterior. Finalmente, el código incluye una función interactiva que permite al usuario conversar con el chatbot hasta que escriba "salir". Durante la conversación, el usuario ingresa texto, el modelo genera una respuesta y la muestra en pantalla.

Traducción Automática: Utilizar una implementación de Transformer para
construir un modelo de traducción automática. Pueden entrenar el modelo con un dataset multilingüe y evaluar su rendimiento.**
Archivo: [7_1_Traducción_Automática_con_Transformers.ipynb](./7_1_Traducción_Automática_con_Transformers.ipynb)
Descripción:  El ejercicio consiste en implementar un modelo de Traducción Automática utilizando una arquitectura Transformer, específicamente el modelo MarianMT. Este modelo es una implementación de Transformer optimizada para tareas de traducción automática y es ampliamente utilizado en aplicaciones de traducción de texto. Se utiliza el modelo preentrenado MarianMT para traducir texto de un idioma a otro. Es importante mencionar que aunque en este ejemplo se utiliza un modelo preentrenado, se puede extender el ejercicio para entrenar el modelo con un dataset multilingüe y evaluar su rendimiento.


## **Punto 2: Desarrollar un sistema RAG sencillo para crear un chat que permita acceder a la información actualizada de la Universidad Nacional.**
Archivo: [punto_7_2_RAG.ipynb](./punto_7_2_RAG.ipynb)
Descripción: Este ejercicio implementa un sistema de Recuperación y Generación de Respuestas (RAG, por sus siglas en inglés) utilizando embeddings de oraciones y un modelo generativo (GPT-2). El objetivo es responder preguntas basadas en información recuperada de un texto preprocesado. El sistema combina dos componentes principales: La recuperación de información ya que se utiliza embeddings de oraciones y un índice FAISS para encontrar la información más relevante relacionada con la pregunta, y la generación de respuestas, porque se emplea un modelo generativo (GPT-2) para producir respuestas claras y concisas basadas en la información recuperada.

### Notas adicionales:
Este repositorio contiene la resolución detallada de los puntos del taller 7 sobre inteligencia artificial generativa. Cada programa ha sido documentado con descripciones claras para facilitar su comprensión y replicación.
