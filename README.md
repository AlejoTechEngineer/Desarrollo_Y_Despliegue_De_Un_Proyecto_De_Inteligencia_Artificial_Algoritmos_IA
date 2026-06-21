<div align="center">

# 📌 Desarrollo y Despliegue de un Proyecto de Inteligencia Artificial - Algoritmos IA  

## 📖 Descripción

</div>

---

Este proyecto desarrolla un sistema basado en Inteligencia Artificial para optimizar procesos mediante modelos de aprendizaje automático.

## 🛠️ Funcionalidades  
- Implementación de algoritmos de Machine Learning.  
- Entrenamiento y validación de modelos.  
- Despliegue del modelo en un entorno de producción.  
- Evaluación del rendimiento mediante métricas clave.  

## Arquitectura

```mermaid
flowchart TD
    A[pip install -r requirements.txt] --> B{Algoritmo}
    B --> C[Algoritmo A* - AlgoritmoAAsterisco/]
    B --> D[Algoritmo Voraz hacia Bogota]
    B --> E[Algoritmo Voraz hacia Cali]
    B --> F[Algoritmo Voraz hacia Medellin]
    C & D & E & F --> G[python train.py - Entrenamiento del modelo]
    G --> H[Validacion y evaluacion de metricas]
    H --> I[python app.py - Servidor Flask/FastAPI]
    I --> J[API en produccion - AWS / Google Cloud]
    J --> K[Cliente: Postman o aplicacion web]
```

## 🚀 Tecnologías utilizadas  
- Python  
- TensorFlow / Scikit-Learn  
- Flask / FastAPI  
- AWS / Google Cloud  

## ▶️ Cómo ejecutar el proyecto  
1. Instalar dependencias con `pip install -r requirements.txt`.  
2. Entrenar el modelo con `python train.py`.  
3. Ejecutar el servidor API con `python app.py`.  
4. Consumir la API desde Postman o una aplicación web.  

## 📌 Autor  
👨‍💻 **Alejandro De Mendoza**

---

## Autor

**Alejandro De Mendoza**  
Ingeniero Informático · Especialista en IA · Especialista en Ingeniería de Software · Máster en Arquitectura de Software

[![GitHub](https://img.shields.io/badge/GitHub-AlejoTechEngineer-181717?style=for-the-badge&logo=github)](https://github.com/AlejoTechEngineer)
