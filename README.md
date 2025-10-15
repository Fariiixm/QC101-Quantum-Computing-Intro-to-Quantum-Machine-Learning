QC101 Quantum Computing & Intro to Quantum Machine Learning - Código del Curso
Este repositorio contiene el código, simulaciones y proyectos prácticos desarrollados para el curso QC101 Quantum Computing & Intro to Quantum Machine Learning de Udemy, el curso best-seller de computación cuántica.

Este proyecto documenta mi viaje de aprendizaje, desde los fundamentos teóricos hasta la implementación práctica con las herramientas líderes de la industria, preparándome para la "próxima ola de la industria del software" y la revolución de la tecnología cuántica.

🛠️ Estructura del Repositorio y Proyectos Clave
El repositorio está organizado por los principales temas del curso, incluyendo ejemplos de física cuántica, protocolos de cifrado y algoritmos de Machine Learning Cuántico (QML).

1. Simuladores de Fundamentos Cuánticos (Java)
Archivo	Descripción	Concepto Central
simulator/ClassicalPhoton.java	Un ejemplo simple para establecer el ángulo de polarización de un fotón clásico (90 grados por defecto).	Representación clásica de un fotón (antes del qubit).
simulator/PhotonPolarizationMeasurement.java	Simula la medición de un qubit de fotón y cómo la medición cambia su estado (colapso de la función de onda).	Medición de Qubit y Colapso Cuántico.
simulator/EntangledPhotonMeasurement.java	Simula el comportamiento de fotones en estado entrelazado (β 
00
​
 ), calculando probabilidades de medición y cómo la medición en un fotón afecta inmediatamente al otro.	Entrelazamiento Cuántico y sus efectos en la probabilidad.
2. Implementación de Circuitos Cuánticos (Q# y Qiskit)
Archivo	Herramienta	Concepto Central
QB4/QB4.qs	Microsoft Q#	
Contiene una operación QB4Run que demuestra los bloques de construcción de la computación cuántica, incluyendo: X (NOT), H (Hadamard), CNOT, SWAP y la compuerta CCNOT (Toffoli) en configuraciones de NOT, AND y FANOUT. 

QB4/qc101project.csproj	.NET/Q#	
Archivo de proyecto que configura el entorno para ejecutar las operaciones Q# con el Microsoft.Quantum.Sdk. 

3. Machine Learning Cuántico (QML) con Qiskit
Archivo	Herramienta	Concepto Central
knn1.py	Qiskit	Comparación de la clasificación k-Nearest Neighbors (kNN) clásica con una implementación cuántica, demostrando la preparación del estado cuántico y la medición para obtener probabilidades de clase.
qsvm.py	Qiskit Machine Learning	Implementación de un Quantum Support Vector Machine (QSVM). Utiliza el ZZFeatureMap y el FidelityQuantumKernel para clasificar el conjunto de datos Iris. Este es el proyecto final que muestra el potencial de QML.
