# TwinStickShooter
TwinStickShooter game in Unreal Engine


Controles:
WSDA: Moverse Arriba, abajo, derecha, izquierda
Rotación: Movimiento del mouse
Boton derecho ratón apretado durante 2 segundos y soltar: Dash direccional


Armas:
Base: Trazadora
Se recogen: Vulcan y Misiles
Para cambiar de arma:
1 - Trazadora: Tecla 1 del teclado alfanumerico
2 - Bala: Tecla 2 del teclado alfanumerico
3 - Misil explosivo: Tecla 3 del teclado alfanumerico
Estas teclas seran el cambio de armas y se disparara con el izquierdo del ratón


Enemigos:
Patrulla, que nos dispara y sigue. Si lo perdemos de vista vuelve a patrullar
Huizido, estatico, nos dispara y huye a una posición aleatoria.
Boss, hace un combo de los anteriores.


IA Director: 
Dropea un corazon si tenemos menos de X vida, y hay menos de un corazón en el suelo
Dropea una caja de munición si tenemos menos de X munición, y hay menos de una caja en el suelo
Dropea un máximo de enemigos, después dropea al boss.

Items:
Corazon, recuperamos vida
Caja de munición. Añade munición al arma equipada.