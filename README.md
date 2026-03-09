Motor Lógico y Visual para Juego de Damas (C++)

Este proyecto es el desarrollo completo del juego de las Damas. Está programado en C++. El proyecto aplica los principios de la Programación Orientada a Objetos. También gestiona la memoria de manera eficiente y utiliza estructuras de datos dinámicas.

Desarrollado como proyecto para la asignatura de Metodología de la Programación en la Universitat Autònoma de Barcelona.

Características Principales

- Motor Lógico Completo: Implementación de las reglas de las Damas. Esto incluye la validación de movimientos diagonales y capturas múltiples.

- Gestión Dinámica de Memoria: El tablero gestiona el ciclo de vida de las piezas en tiempo real.

- Sistema de Historial y Modo Replay: Implementación de una estructura de datos de Cola para registrar cada movimiento de la partida, además de un menú interactivo para elegir el modo de juego.

- Interfaz Gráfica Interactiva: Bucle de juego que procesa eventos de entrada y resalta visualmente los movimientos válidos.

- Serialización de Estado: Capacidad para cargar estados iniciales de tablero personalizados y exportar el historial de movimientos.

Tecnologías y Conceptos Clave

- Lenguaje: C++

- Arquitectura: POO

- Estructuras de Datos: Colas Dinámicas Enlazadas, Matrices, Vectores

- Memoria: Punteros y gestión manual de memoria dinámica

Retos Técnicos Superados

Uno de los principales desafíos fue el diseño del algoritmo de validación de movimientos. Fue necesario precalcular todos los caminos posibles de una pieza para determinar la legalidad del movimiento. También fue un desafío migrar de un modelo de memoria estático a uno dinámico basado en punteros.

Desarrollado por Víctor Segura García - Estudiante de Ingeniería Informática en la UAB.
