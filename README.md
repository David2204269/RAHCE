# RAHCE
RAHCE - Human Activity Recognition using simulated event-camera data and deep learning on HMDB51.

## Reconocimiento de Actividades Humanas a partir de Adquisición Simulada con Cámaras de Eventos y Aprendizaje Profundo

### Descripción del proyecto

RAHCE es un proyecto de investigación desarrollado en el programa de Ingeniería Electrónica de la Universidad Industrial de Santander (UIS), cuyo objetivo es implementar y evaluar un modelo de aprendizaje profundo para el reconocimiento de actividades humanas (Human Activity Recognition, HAR) utilizando datos obtenidos mediante la simulación de cámaras de eventos a partir de videos convencionales.

La propuesta busca explorar las ventajas de la visión basada en eventos, una tecnología bioinspirada que registra únicamente cambios de intensidad luminosa en la escena, reduciendo la redundancia temporal presente en los sistemas de captura RGB tradicionales y permitiendo un procesamiento potencialmente más eficiente.

---

## Objetivo General

Implementar un modelo de aprendizaje profundo para reconocimiento de actividades humanas utilizando datos obtenidos mediante adquisición simulada con cámaras de eventos.

---

## Objetivos Específicos

* Seleccionar una arquitectura de aprendizaje profundo adecuada para tareas de reconocimiento de actividades humanas.
* Generar un conjunto de datos basado en eventos a partir de videos RGB mediante simulación.
* Adaptar la arquitectura seleccionada para procesar representaciones derivadas de eventos.
* Evaluar el desempeño del sistema mediante métricas de clasificación y análisis comparativos.

---

## Metodología General

```text
HMDB51
   │
   ▼
Videos RGB
   │
   ▼
Simulación de eventos (V2E)
   │
   ▼
Representación de eventos
(Event Frame / Voxel Grid)
   │
   ▼
Modelo de aprendizaje profundo
   │
   ▼
Entrenamiento y validación
   │
   ▼
Evaluación y análisis de resultados
```

---

## Dataset

### HMDB51

El proyecto utiliza el dataset HMDB51, uno de los conjuntos de datos más utilizados para investigación en reconocimiento de actividades humanas.

Características principales:

* 51 categorías de actividades humanas.
* Más de 6.700 videos.
* Escenarios reales y no controlados.
* Amplia diversidad de movimientos y condiciones visuales.

---

## Tecnologías y Herramientas

### Simulación de eventos

* V2E (Video to Events)

### Desarrollo

* Python
* Google Colab
* Jupyter Notebook

### Aprendizaje profundo

* PyTorch
* Torchvision
* PyTorchVideo

### Procesamiento de datos

* NumPy
* OpenCV
* Pandas
* Matplotlib

---

## Estructura del repositorio

```text
RAHCE/
│
├── checkpoints/  
├── docs/                 # Documentación e informes
├── notebooks/            # Experimentos en Colab
├── simulacion_eventos/   # Configuración y uso de V2E
├── src/                  # Código fuente principal
├── experiments/          # Experimentos realizados
├── resultados/           # Métricas, gráficas y análisis
├── referencias/          # Bibliografía y artículos
│
├── README.md
├── requirements.txt
└── .gitignore
```

---

## Estado Actual del Proyecto

* [x] Formulación y aprobación del plan de trabajo.
* [x] Definición de objetivos y metodología.
* [x] Selección del dataset HMDB51.
* [ ] Implementación del entorno experimental.
* [ ] Simulación de eventos mediante V2E.
* [ ] Adaptación de la arquitectura seleccionada.
* [ ] Entrenamiento del modelo.
* [ ] Evaluación y análisis de resultados.
* [ ] Redacción final del documento de tesis.

---

## Resultados Esperados

* Dataset derivado de eventos a partir de HMDB51.
* Implementación reproducible del pipeline de procesamiento.
* Modelo adaptado para reconocimiento de actividades humanas basado en eventos.
* Evaluación comparativa entre información RGB y eventos simulados.
* Documento final de trabajo de grado.

---

## Autores

David Josué Díaz Ortiz

Elkin Yesid Lozada Cabrera

---

## Director

Hans Yecid García Arenas

---

## Codirector

Sebastián Ardila Leal

---

## Institución

Universidad Industrial de Santander

Facultad de Ingenierías Fisicomecánicas

Escuela de Ingenierías Eléctrica, Electrónica y de Telecomunicaciones

Bucaramanga, Colombia

2026

