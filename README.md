# 🛳️ Guerra Naval - ¡El clásico juego de batalla naval!

¡Bienvenidos a **Guerra Naval**! Este es un proyecto que recrea el popular juego de mesa de batallas navales, donde dos jugadores intentan hundir los barcos de su oponente.

## 🚀 Características del Juego

- Modo de juego clásico: 2 jugadores colocan sus barcos y lanzan ataques para hundir la flota enemiga.
- Tableros generados automáticamente.
- Validación de movimientos y reglas del juego.
- Interfaz gráfica sencilla con la consola.
  
## 📂 Estructura del Proyecto

Tienes un archivo llamado **guerraNaval.py** el cual esta compuesto por clases en python, donde utilizo las clases para definir los dos jugadores, donde se van a colocar los barcos **(Horizontal H o Vertical V)**, además de contar los impactos y los barcos hundidos del contrincante.


## 🕹️ ¿Cómo Jugar?

### 1. Colocación de Barcos:
Cada jugador tiene una flota de barcos que debe colocar en su tablero. Los barcos tienen diferentes tamaños y deben ubicarse horizontal o verticalmente sin solaparse.

### 2. Turnos de Ataque:
Los jugadores se alternan en lanzar ataques al tablero enemigo, intentando hundir los barcos del adversario.

### 3. Finalización del Juego:
El juego termina cuando un jugador ha hundido todos los barcos del oponente.

## 📦 Instalación

1. Clona el repositorio:
   ```bash
   git clone https://github.com/Alfonso20005/Juego-GuerraNaval.git
   cd Juego-GuerraNaval

2. Ejecuta el juego:
   ```bash
    python src/main.py

## 🧠 Lógica de Juego

### 1. Tablero:
El tablero es una matriz de 10x10 celdas donde cada celda representa:

- **`~`**: Parte del océano.
- **`B`**: Parte de un barco.
- **`X`**: Impacto en un barco (barco dañado).
- **`O`**: Agua (ataque fallido).

### 2. Colocación de barcos:
- Los jugadores pueden colocar sus barcos en el tablero de forma horizontal o vertical.
- El tamaño de los barcos varía y deben estar completamente dentro del tablero (10x10).
- No se permite la superposición de barcos.

## 👥 Contribuciones

¡Cualquier contribución es bienvenida! Siéntete libre de hacer un fork del repositorio, trabajar en una nueva funcionalidad o corregir algún error.

1. Haz un fork del proyecto.
2. Crea una nueva rama con tu funcionalidad:
   ```bash
   git checkout -b nueva-funcionalidad
   ```
3. Haz un commit de tus cambios:
   ```bash
   git commit -m 'Añadida nueva funcionalidad'
   ```
4. Haz un push a la rama:
   ```bash
   git push origin nueva-funcionalidad
   ```
5. Abre un Pull Request.

## 📄 Licencia

Este proyecto mo tiene ningun tipo de licencia puede usarlo todo el mundo.

---

¡Disfruta del juego y que ganen los mejores estrategas navales! 🌊⚓




