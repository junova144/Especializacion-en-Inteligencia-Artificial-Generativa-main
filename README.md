
# ⭐ 🔖 Especialización en IA Generativa

## 🚀 Objetivo del Curso
Este curso te llevará de cero a construir **soluciones de IA generativa completas**, donde no solo aprenderás teoría, sino que **crearás proyectos reales que funcionan**. Aprenderás a combinar **recuperación de información (RAG), agentes inteligentes y multimodalidad**, para generar texto, imágenes, audio y video de manera integrada.  

Al finalizar, serás capaz de diseñar **aplicaciones generativas que resuelven problemas reales**, desde asistentes inteligentes que buscan y resumen información, hasta sistemas multimodales que crean contenido creativo de manera autónoma.

## 🌟 Motivación: ¿Por qué tomar este curso?
Si siempre te has preguntado cómo funcionan ChatGPT, DALL·E o aplicaciones que combinan texto, imagen y audio, este curso te mostrará **el potencial real de la IA generativa**.  

Al finalizar, podrás:  
- Construir tu propio **motor RAG** para responder preguntas con información precisa de documentos o bases de datos.  
- Desarrollar **agentes inteligentes y multiagente** que colaboran entre sí para tareas complejas.  
- Crear **aplicaciones multimodales**, generando contenido con texto, imágenes, audio y video de forma integrada.  
- Transformar tus ideas en **prototipos funcionales o productos listos para presentar a empresas**.  
- Explorar y dominar **herramientas profesionales** como LangChain, LlamaIndex, FAISS, y más, para llevar tus proyectos a producción.  

Este curso no es solo teoría: **cada módulo incluye prácticas y proyectos que te permiten ver resultados tangibles desde el primer día**, demostrando el verdadero poder de la IA generativa.


---

## 📚 Contenido del Curso

### 1️⃣ Fundamentos de IA
- Teoría: [Ver teoría](docs/fundamentos.md)
- Práctico: [Proyectos iniciales](notebooks/fundamentos.ipynb)

### 2️⃣ Aplicaciones Generativas
- Teoría: [Ver teoría](docs/generativos.md)
- Práctico: [Proyectos generativos](notebooks/generativos.ipynb)

### 3️⃣ RAG - Recuperación Aumentada
- Teoría: [Ver teoría](docs/rag.md)
- Práctico: [Proyectos RAG](notebooks/rag.ipynb)

### 4️⃣ Agentes y Multiagentes
- Teoría: [Ver teoría](docs/agentes.md)
- Práctico: [Proyectos de agentes](notebooks/agentes.ipynb)

### 5️⃣ Protocolos de Interoperabilidad
- Teoría: [Ver teoría](docs/protocolos.md)
- Práctico: [Ejercicios y demos](notebooks/protocolos.ipynb)

### 6️⃣ Experiencia Multimodal
- Teoría: [Ver teoría](docs/multimodal.md)
- Práctico: [Proyectos multimodales](notebooks/multimodal.ipynb)

---

## 🗂 Estructura General de los Proyectos

```text
Proyecto-IA/
├── README.md                # Archivo principal del proyecto
├── requirements.txt         # Librerías necesarias para ejecutar los ejemplos
├── environment.yml          # Alternativa Conda para reproducibilidad
├── setup.sh                 # Script de setup para Linux/Mac
├── setup.bat                # Script de setup para Windows
├── .gitignore               # Archivos/carpetas a ignorar en Git
├── config/
│   ├── .env.example         # Ejemplo de variables de entorno y llaves API
│   ├── main_config.yaml     # Configuración general del proyecto
│   └── models.yaml          # Configuración de modelos disponibles
├── docs/
│   ├── arquitectura.md      # Diagramas y explicación de la arquitectura
│   ├── guia_usuario.md      # Guía de usuario general
│   ├── rag.md               # Explicación de RAG / embeddings
│   └── api.md               # Documentación de APIs externas
├── core/
│   ├── agents/              # Lógica de agentes individuales
│   ├── multiagents/         # Coordinación multiagente / multiusuario
│   ├── rag/                 # Embeddings, retrievers, QA
│   ├── api_clients/         # Conexión con APIs externas
│   ├── data/                # Preprocesamiento de datasets
│   ├── models/              # Definición de modelos
│   └── utils/               # Funciones auxiliares y utilidades
├── notebooks/               # Notebooks de ejemplo y experimentos
├── frontend/
│   ├── app.py               # Script principal de la interfaz (Streamlit/Flask)
│   ├── static/              # Recursos estáticos (CSS, JS, imágenes)
│   └── templates/           # Templates HTML / Jinja
├── tests/                   # Pruebas unitarias y de integración
├── scripts/
│   ├── run_local.py         # Ejecutar todo en local
│   ├── run_distributed.py   # Ejecutar en cluster / multiusuario
│   └── train_model.py       # Entrenar modelos
├── logs/                    # Archivos de logs
├── storage/                 # Datasets, PDFs u otros contenidos persistentes
├── vectors/                 # Bases vectoriales FAISS u otros
└── models/                  # Modelos locales o descargados
```
## Nota
La estructura mostrada arriba es **solo de referencia**. Cada módulo puede incluir solo las carpetas necesarias.  
El objetivo es que cualquier usuario pueda entender rápidamente la organización del curso y cómo ejecutar los ejemplos.


## 🔈 Anuncios y Actualizaciones

- Próximamente: Nuevos notebooks y ejercicios integradores.
- Se actualizará con nuevas referencias de papers y tutoriales cada mes.

---

## 🎓 Contribuciones

Si quieres colaborar o sugerir mejoras, abre un **pull request** en la sección correspondiente y coloca tu aporte en el módulo/sección correcta.

---

## 📌 Licencia

Uso educativo permitido. Para fines comerciales o distribución, contactar al autor.

---


