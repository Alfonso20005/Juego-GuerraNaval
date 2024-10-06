# 🛳️ Guerra Naval - ¡El clásico juego de batalla naval!

¡Bienvenidos a **Guerra Naval**! Este es un proyecto que recrea el popular juego de mesa de batallas navales, donde dos jugadores intentan hundir los barcos de su oponente.

## 🚀 Características del Juego

- Modo de juego clásico: 2 jugadores colocan sus barcos y lanzan ataques para hundir la flota enemiga.
- Tableros generados automáticamente.
- Validación de movimientos y reglas del juego.
- Interfaz gráfica sencilla con la consola.
  
## 📂 Estructura del Proyecto

Juego-GuerraNaval/ │ ├── src/ # Código fuente del juego │ ├── main.py # Archivo principal para ejecutar el juego │ ├── tablero.py # Lógica del tablero, colocación de barcos, etc. │ └── jugador.py # Gestión de los jugadores y su estado en el juego │ ├── assets/ # (Opcional) Podrías colocar archivos de recursos gráficos, si los implementas ├── README.md # Documentación del proyecto └── requirements.txt # Dependencias (si las hay)


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