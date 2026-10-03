# Footy Manager Desktop ⚽🌍

Una versión de escritorio independiente del simulador web [Footy Manager: World Stage](https://footy-manager.com/). 

Este proyecto utiliza **Electron** para encapsular el juego web original en una aplicación nativa para Windows (`.exe`). El objetivo principal de esta implementación es solucionar los problemas de pérdida de datos ocasionados por las políticas de limpieza de caché y `localStorage` de los navegadores web modernos, garantizando un **guardado local persistente y seguro** a través de particiones de Electron.

## ⚠️ Créditos y Aviso Legal
* **Creador del juego original (Lógica, UI y código base):** Aidan O'Hara
* **Arquitectura de Escritorio y Empaquetado:** Alan Pichardo Villavicencio

Este repositorio no busca apropiarse del juego original. Únicamente proporciona un contenedor de escritorio configurado para mejorar la experiencia de usuario mediante la persistencia de datos offline.

## ✨ Características
* **Partidas Seguras:** Utiliza `persist:footy-manager` en Electron para asegurar que tu avance nunca se borre al cerrar la aplicación.
* **App Independiente:** Ventana de juego limpia, sin barras de navegación ni distracciones.
* **Portable:** Se compila como un ejecutable `.exe` único que puedes llevar en una USB sin necesidad de instalación.

## 🛠️️ Requisitos Previos
Para compilar este proyecto por tu cuenta, necesitas tener instalado:
* [Node.js](https://nodejs.org/) (incluye npm)
* Git

## 🚀 Instalación y Uso

1. **Clonar el repositorio:**
   ```bash
   git clone [https://github.com/pichardoalan/Footy-Manager-Desktop.git](https://github.com/pichardoalan/Footy-Manager-Desktop.git)
   cd Footy-Manager-Desktop
   1. **Clonar el repositorio:**
   git clone [https://github.com/pichardoalan/Footy-Manager-Desktop.git](https://github.com/pichardoalan/Footy-Manager-Desktop.git)
   cd Footy-Manager-Desktop
