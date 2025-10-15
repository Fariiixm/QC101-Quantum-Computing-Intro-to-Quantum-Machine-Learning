<div align="center">
  <h1> QC101 Quantum Computing & Intro to Quantum Machine Learning </h1>
  <p><strong>Código del Curso Best-Seller de Udemy</strong></p>
  <img src="https://img.shields.io/badge/Tecnologías-Qiskit%20|%20Q%23%20|%20Java-5C2D91?style=for-the-badge&logo=qiskit&logoColor=white" alt="Tecnologías">
  <img src="https://img.shields.io/badge/Conceptos-Superposición%20|%20Entrelazamiento%20|%20QML-A51890?style=for-the-badge" alt="Conceptos Clave">
</div>

---

[cite_start]Este repositorio es la colección de código, simulaciones y proyectos prácticos desarrollados para el curso **"QC101 Quantum Computing & Intro to Quantum Machine Learning"** de Udemy[cite: 1, 2].

[cite_start]Documenta mi viaje de aprendizaje, desde los fundamentos teóricos hasta la implementación práctica con las herramientas líderes de la industria, preparándome para la **"próxima ola de la industria del software"** y la revolución de la tecnología cuántica[cite: 1, 2].

---

##  Estructura del Repositorio y Proyectos Clave

[cite_start]El repositorio está organizado por los principales temas del curso, abarcando ejemplos de física cuántica, protocolos de cifrado cuántico y algoritmos de Machine Learning Cuántico (QML)[cite: 1, 2].

### 1. Simuladores de Fundamentos Cuánticos (Java)

[cite_start]Estos archivos contienen simuladores de baja fidelidad en Java para comprender intuitivamente la física detrás del comportamiento de los qubits, la medición y el entrelazamiento[cite: 1, 2].

| Archivo | Descripción | Concepto Central |
| :--- | :--- | :--- |
| `simulator/ClassicalPhoton.java` | [cite_start]Un ejemplo simple para establecer el ángulo de polarización de un fotón clásico (90 grados por defecto)[cite: 1, 2, 4]. | [cite_start]Representación clásica de un fotón (antes del qubit)[cite: 1, 2]. |
| `simulator/PhotonPolarizationMeasurement.java` | [cite_start]Simula la **medición** de un qubit de fotón y cómo la medición **cambia su estado** (colapso de la función de onda)[cite: 1, 2, 5]. | [cite_start]**Medición de Qubit** y **Colapso Cuántico**[cite: 1, 2]. |
| `simulator/EntangledPhotonMeasurement.java` | [cite_start]Simula el comportamiento de fotones en estado **entrelazado** ($\beta_{00}$), calculando probabilidades de medición y cómo la medición en un fotón afecta inmediatamente al otro[cite: 1, 2, 3]. | [cite_start]**Entrelazamiento Cuántico** y sus efectos en la probabilidad[cite: 1, 2]. |

### 2. Implementación de Circuitos Cuánticos (Q\# y Qiskit)

[cite_start]Aquí se encuentran los ejemplos prácticos de cómo construir circuitos cuánticos usando las principales plataformas[cite: 1, 2].

| Archivo | Herramienta | Concepto Central |
| :--- | :--- | :--- |
| `QB4/QB4.qs` | **Microsoft Q\#** | [cite_start]Contiene una operación `QB4Run` que demuestra los bloques de construcción de la computación cuántica, incluyendo: `X` (NOT), `H` (Hadamard), `CNOT`, `SWAP` y la compuerta `CCNOT` (Toffoli) en configuraciones de NOT, AND y FANOUT[cite: 1, 2, 7, 8, 9, 10, 11, 12, 13, 14, 15]. |
| `QB4/qc101project.csproj` | **.NET/Q\#** | [cite_start]Archivo de proyecto que configura el entorno para ejecutar las operaciones Q\# con el `Microsoft.Quantum.Sdk/0.12.20072031`[cite: 1, 2, 7]. |

### 3. Machine Learning Cuántico (QML) con Qiskit

[cite_start]El "killer-app" de la computación cuántica: la aceleración de algoritmos de Machine Learning[cite: 1, 2].

| Archivo | Herramienta | Concepto Central |
| :--- | :--- | :--- |
| `knn1.py` | **Qiskit** | [cite_start]Comparación de la clasificación **k-Nearest Neighbors (kNN)** clásica con una implementación cuántica, demostrando la preparación del estado cuántico y la medición para obtener probabilidades de clase[cite: 1, 2, 6]. |
| `qsvm.py` | **Qiskit Machine Learning** | Implementación de un **Quantum Support Vector Machine (QSVM)**. Utiliza el `ZZFeatureMap` y el `FidelityQuantumKernel` para clasificar el conjunto de datos Iris. [cite_start]Este es el proyecto final que muestra el potencial de QML[cite: 1, 2, 6]. |

---

##  Tecnologías Utilizadas

* [cite_start]**Qiskit (Python):** La biblioteca de IBM para el trabajo con circuitos cuánticos y QML[cite: 1, 2].
* [cite_start]**Microsoft Q\#:** El lenguaje de programación cuántica de Microsoft[cite: 1, 2].
* [cite_start]**Java:** Usado para simuladores conceptuales de baja fidelidad[cite: 1, 2].
