# 📌 50Tazo - Juego de Cartas

El juego 50Tazo se presenta como el tercer miniproyecto para la materia FPOE de la Universidad del Valle.
Consiste en la creacion de un juego de cartas basado en un mazo de poker, donde las cartas, según su valor, suman, restan, 
o no añaden nada a la suma total de la mesa en juego. El objetivo del juego es ir apilando cartas sin pasarse de la suma 
de 50 en la mesa. El juego transcurre entre máximo 4 jugadores, un jugador humano (usuario final), y 3 jugadores CPU (mínimo 1).

Para el desarrollo del juego se logra implementar correctamente el manejo de eventos, el estilo de interfaces con heuristicas
de usabilidad (UI). el manejo de excepciones durante la ejecución del programa, la implementacion de hilos para la concurrencia y
el manejo aislado y simultaneo de procesos, además de la implementación de pruebas unitarias para la verificacion de correcta
ejecucion del juego.

---

## 🚀 Tecnologías utilizadas
- Java 17 (JDK amazon coretto 17.0.17)
- Libreria JavaFX 17 (UI)

---

##  ⚙ Características
- ✔️ Manejo de lógica de ejecución, suma y resta de cartas, consecucion de turnos.
- ✔️ Implementación de funciones lógicas para la ejecucion y toma de decisiones CPU.
- ✔️ Interfaz clara, llamativa y tematizada según el contexto del juego.

---

## 📦 Instalación

1. Clona el repositorio:
   ```bash
   git clone https://github.com/TheRoscar/50Tazo.git

2. Abrir con el IDE IntellijIdea

3. Compilar y ejecutar (Necesaria la configuración y uso de librerias de Java 17).

## 🛠 Estructura del programa (Arquitectura MVC)
```bash
src/
└── main/
    └── java/
        └── org.example.mini/
            ├── controller/
            │   ├── GameController
            │   ├── IGameController
            │   ├── IStartController
            │   └── StartController
            │
            ├── model/
            │   ├── card/
            │   │   └── Card
            │   │
            │   ├── deck/
            │   │   ├── Deck
            │   │   └── IDeck
            │   │
            │   ├── exceptions/
            │   │   ├── EliminatedPlayerException
            │   │   └── EmptyDeckException
            │   │
            │   ├── game/
            │   │   ├── Game
            │   │   └── IGame
            │   │
            │   └── player/
            │       ├── HumanPlayer
            │       ├── IPlayer
            │       ├── MachinePlayer
            │       ├── Player
            │       └── Table
            │
            ├── util/
            │   ├── TableMonitorThread
            │   └── TurnMonitorThread
            │
            ├── view/
            │   ├── GameView
            │   └── StartView.java
            │
            └── Main
```

## 👀 Vista del juego 
<img width="798" height="716" alt="image" src="https://github.com/user-attachments/assets/9be6c739-7097-47b4-bc6a-2c90d10ed50a" />


## 👤 Autores

1. Nombre: Oscar Andrés Rengifo Bustos   
   GitHub: TheRoscar   
   Correo: oscar.andres.rengifo@correounivalle.edu.co

2. Nombre: Juan David López Jiménez 
   Github: juanjk25
   Correo: jua.lopez.jimenez@correounivalle.edu.co

3. Nombre:   
   GitHub:   
   Correo:   


 
