# IA-Checkers
Resumen: Programa ejecutable desarrollado en Python que tiene un agente inteligente que juega damas contra humanos utilizando el algoritmo de minimax.

## Instalaciones necesarias
 1) Python v3.12.6
 2) Pygame

* Instrucciones para instalar
2) Instalar Python: https://www.python.org/downloads/
3) Ejecutar en consola el comando: pip install Pygame

### Información complementaria
Este programa utiliza el algoritmo de busqueda informada minimax para realizar acciones que garanticen el mayor beneficio para un agente inteligente que juega Damas contra un jugador humano a través de una interfaz gráfica diseñada con la libreria Pygames. Utiliza <b>2 funciones heurísticas: h1 = Posiciones seguras del tablero y h2 = Captura y ventaja de estado de partida</b>. <b>Para ejecutar este código, ingresar al IDE de Python y abrir el archivo 'damas_game.py'</b>.

#### Manual de usuarios
Todas las fichas estan promovidas a 'Damas' desde el inicio de la partida, el jugador puede moverse adelante y hacia atras haciendo <b>CLICK DERECHO</b> en la ficha que desea mover y posteriormente haciendo click en las casillas diagonales disponibles (si estan vacias), para capturar fichas rivales el usuario debe hacer <b>CLICK DERECHO</b> en la ficha a jugar y si tiene una ficha en diagonal cuya casilla posterior en diagonal esta libre entonces hacer click en dicha casilla para capturar. Si ambos jugadores llegan al turno 64 entonces se declara en tablas la partida (empate). En el caso de que uno de los jugadores logre vencer al rival se sumara +1 al contador de victorias y podrá jugar una nueva partida presionando la <b>'BARRA ESPACIADORA'</b>.

