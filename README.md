# Proyecto_digitales
&read me_: // rev1.0
&autor: Cazzulino Renzo

********************** Descripcion del proyecto ************************

________________________________Idea 1______________________________________
Máquina de premios: 3 turnos

En cada partida, el jugador obtiene 4 turnos para dejar caer, pulsador y un 
pequeño motor mediante, algún tipo de ficha/canica en el tablero. Dependiendo
la ranura por la que caiga, tendrá más o menos puntos: En concreto

ranura A: 1 punto
ranura B: 2 puntos
ranura C: 3 puntos
ranura D: 4 puntos

Y de acuerdo a la siguiente tabla de puntajes, se otorga un premio:

4-6 puntos: planta 1
7-10 puntos: planta 2
11-15 puntos: planta 3
16 puntos: planta 4

En cada planta, salvo en la última (4ta), tras acabar los turnos, el jugador
se podrá desplazar mediante 2 pulsadores, a izquierda o derecha con un cursor 
para seleccionar su premio


________________________________Idea 2______________________________________
Ruleta triple:

La estructura se basa en 3/4 ruletas, físicamente concéntricas. El jugador 
empieza por la exterior, y a medida que avanza en cada etapa, sigue en la 
inmediatamente interior. 
Para ganar cada etapa, debe presionar el único pulsador central cuando el 
LED superior se esté iluminando.

A medida que se avanza, un multiplexor permite aumentar el clock  y con 
ello la frecuencia de las ruletas, y a su vez, modifica la ruleta. 
Un display 7 segmentos lleva la cuenta de la etapa. Y al ganar la 4ta, 
debe prenderse un led verde.



************************************************************************


