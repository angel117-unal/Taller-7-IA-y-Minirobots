# Taller 7 Inteligencia artificial generativa

### Presentado por:
- **Ángel Rivera Amortegui**
- **Daniel Echeverry Jimenez**

---
## **Punto 1: Escoger dos de los siguientes ejercicios para su realización. Los ejercicios desarrollados deben ir muy bien documentados.**
Generación de Texto con GPT-3: Realizar ejercicios de generación de texto utilizando una API basada en GPT-3. Pueden generar historias, poemas o respuestas a preguntas específicas.
Archivo: [reconocLetras.ipynb](./reconocLetras.ipynb)
Descripción:  El ejercicio consiste en implementar un modelo de Traducción Automática utilizando una arquitectura Transformer, específicamente el modelo MarianMT. Este modelo es una implementación de Transformer optimizada para tareas de traducción automática y es ampliamente utilizado en aplicaciones de traducción de texto.

Traducción Automática: Utilizar una implementación de Transformer para
construir un modelo de traducción automática. Pueden entrenar el modelo con un dataset multilingüe y evaluar su rendimiento.**
Archivo: [7_1_Traducción_Automática_con_Transformers.ipynb](./7_1_Traducción_Automática_con_Transformers.ipynb)
Descripción:  El ejercicio consiste en implementar un modelo de Traducción Automática utilizando una arquitectura Transformer, específicamente el modelo MarianMT. Este modelo es una implementación de Transformer optimizada para tareas de traducción automática y es ampliamente utilizado en aplicaciones de traducción de texto. Se utiliza el modelo preentrenado MarianMT para traducir texto de un idioma a otro. Es importante mencionar que aunque en este ejemplo se utiliza un modelo preentrenado, se puede extender el ejercicio para entrenar el modelo con un dataset multilingüe y evaluar su rendimiento.


## **Punto 2: Desarrollar un sistema RAG sencillo para crear un chat que permita acceder a la información actualizada de la Universidad Nacional.**
Archivo: [punto_7_2_RAG.ipynb](./punto_7_2_RAG.ipynb)
Descripción: Este ejercicio implementa un sistema de Recuperación y Generación de Respuestas (RAG, por sus siglas en inglés) utilizando embeddings de oraciones y un modelo generativo (GPT-2). El objetivo es responder preguntas basadas en información recuperada de un texto preprocesado. El sistema combina dos componentes principales: La recuperación de información ya que se utiliza embeddings de oraciones y un índice FAISS para encontrar la información más relevante relacionada con la pregunta, y la generación de respuestas, porque se emplea un modelo generativo (GPT-2) para producir respuestas claras y concisas basadas en la información recuperada
