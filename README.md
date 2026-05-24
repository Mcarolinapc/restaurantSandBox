# Java Restaurant Sandbox - Repositorio de Referencia MVC

Este repositorio es un **fork académico** utilizado como entorno de pruebas (*sandbox*) y material de consulta para el estudio de la Programación Orientada a Objetos (POO) y el patrón arquitectónico **MVC (Modelo-Vista-Controlador)** en Java Standard Edition.

---

##  Propósito del Repositorio

El objetivo de mantener este proyecto en mi perfil es contar con una **guía de referencia rápida** sobre la estructura limpia de proyectos en Java, la separación de responsabilidades y la modularización de software antes de dar el salto a frameworks empresariales.

Sirve como base de estudio personal para analizar:
* La captura y control de flujos continuos en consola mediante loops reactivos (`while(true)`).
* La abstracción de datos simulando una capa de persistencia en memoria (`repository`).
* La sincronización entre controladores (`controller`) y gestores de lógica de negocio (`manager`).

---

##  Arquitectura de Referencia Analizada

El proyecto destaca por una distribución modular de responsabilidades muy clara, ideal para repasar fundamentos de ingeniería de software:

* ** `controller`**: Capa encargada de capturar los inputs del usuario (vía `Scanner`) y coordinar el enrutamiento de las pantallas.
* ** `manager`**: Módulos de lógica de negocio puros que orquestan las acciones del sistema (gestión de comandas, mesas y menús).
* ** `model`**: Entidades puras y objetos de dominio que representan el modelo de datos.
* ** `repository`**: Componentes encargados de abstraer la simulación y el almacenamiento de datos en memoria.
* ** `view`**: Componentes responsables de la renderización de textos e interfaces por consola.

---

##  Tecnologías y Herramientas

* ![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white) **Java SE**
* **Maven:** Gestión de dependencias y automatización del ciclo de vida a través del archivo `pom.xml`.
* **Design Patterns:** Arquitectura desacoplada basada en capas de servicio.

---

##  Créditos y Autoría original

* **Desarrollo y Estructura del Proyecto:** Profesor Albert (`@AlbertProfe`)
* **Uso del Repositorio:** Consultoría técnica, análisis de patrones y entorno de pruebas académico.
* **Institución:** CIFO 'La Violeta'
