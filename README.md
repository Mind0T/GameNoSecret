# 🔢 Juego del Número Secreto – Challenge de Lógica de Programación

Este proyecto forma parte de un curso de lógica de programación con JavaScript. El reto consistió en desarrollar la lógica del juego del **Número Secreto**, usando únicamente JavaScript puro y conectándolo con una interfaz HTML y CSS previamente proporcionada.

## 📌 Descripción

El juego desafía al usuario a adivinar un número secreto generado aleatoriamente dentro de un rango variable. El jugador dispone de un número limitado de intentos. Si acierta, gana; si se queda sin intentos, pierde.

## ⚙️ Funcionalidades

✅ **Generación dinámica del rango**:  
El número secreto se genera dentro de un rango aleatorio múltiplo de 10 (entre 10 y 100).

✅ **Intentos limitados**:  
El jugador tiene 3 o 6 intentos según el tamaño del rango.

✅ **Mensajes dinámicos**:  
El juego indica si el número ingresado es mayor o menor al número secreto, y cuántos intentos quedan.

✅ **Prevención de repeticiones**:  
Se evita que el número secreto se repita mientras haya opciones disponibles.

✅ **Reinicio del juego**:  
Al finalizar, el botón “Nuevo juego” permite reiniciar todo desde cero.

## 🧠 Lógica implementada (JavaScript)

- `generarNumeroSecreto()` genera un número aleatorio único dentro del rango.
- `verificarIntento()` compara el número ingresado con el secreto y muestra pistas.
- `condicionesIniciales()` define el estado inicial del juego, incluyendo rango e intentos.
- `reiniciarJuego()` restablece todo sin recargar la página.
- `asignarTextoElemento()` simplifica la actualización del DOM.

## 📂 Estructura del proyecto

```
/numero-secreto/
├── index.html          // Interfaz HTML proporcionada
├── style.css           // Estilos visuales
├── app.js              // Lógica del juego (desarrollada)
├── assets/             // Recursos visuales
└── README.md           // Este archivo
```
## 🎮 Como jugarlo

1. Abre el link de la pagina con el juego
```bash
    https://mind0t.github.io/GameNoSecret/
```
2. Ingresa un numero, y trata de adivinar en el menor toma en cuenta el rango en el que se encuentra el número y la cantidad de intentos.
   
3. Una vez que hayas logrado adivinar o que se hayan terminado tus intentos, puedes iniciar un nuevo juego.

4. Puedes compartir el link y probarlo desde cualquier dispositivo, Diviertete!!!


## 🚀 Cómo ver codigo y probarlo

1. Clona este repositorio:
``` bash
    https://github.com/Mind0T/GameNoSecret.git
```
2. Abre el archivo index.html
 
3. Ingresa un numero, toma en cuenta el rango en el que se encuentra el número y la cantidad de intentos.

4. Puedes compartir el link y probarlo desde cualquier dispositivo, Diviertete!!!


## 💡 Posibles mejoras futuras

- Agregar niveles de dificultad (fácil, medio, difícil).
- Incluir un contador de victorias/derrotas.
- Mostrar los números previamente ingresados.
- Añadir sonidos o animaciones simples al acertar o fallar.

## 🧑‍💻 Autor

**Irvin Soriano**  
Estudiante de Ingeniería en Inteligencia Artificial  
Apasionado por la lógica, los retos de programación y la creación de experiencias interactivas con código.
