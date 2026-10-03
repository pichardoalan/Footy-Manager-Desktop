# Footy Manager Desktop ⚽🌍

Versión de escritorio independiente del simulador web [Footy Manager: World Stage](https://footy-manager.com/).

Este proyecto empaqueta el juego original en una aplicación nativa para Windows (.exe) mediante Electron, garantizando guardado local persistente a través de particiones de almacenamiento aisladas.

---

## ⚠️ Créditos
* **Juego Original (Lógica, UI y mecánicas):** Aidan O'Hara
* **Empaquetado y Persistencia de Escritorio:** Alan Pichardo Villavicencio

---

## 🎮 Cómo Jugar (Usuarios)

1. En la barra lateral derecha de este repositorio, ve a la sección **Releases**.
2. Descarga el archivo ejecutable **Footy Manager.exe**.
3. Ejecútalo directamente con doble clic. No requiere instalación y las partidas se guardan de forma automática en tu equipo.

---

## 💻 Para Desarrolladores (Compilación manual)

Si deseas clonar el proyecto y compilar el binario por tu cuenta:

### 1. Clonar el repositorio
git clone https://github.com/pichardoalan/Footy-Manager-Desktop.git
cd Footy-Manager-Desktop

### 2. Instalar dependencias
npm install

### 3. Probar en modo desarrollo
npm start

### 4. Generar el ejecutable (.exe)
npm run build

El archivo ejecutable portable se creará en la carpeta dist/.
