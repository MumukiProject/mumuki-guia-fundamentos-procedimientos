Para terminar esta lección vamos a definir un procedimiento  llamado `Triada` ¡que recibe tres parámetros! :open_mouth:

`Triada` recibe tres colores por parámetro y pone tres bolitas, una al lado de la otra hacia el Este, en el mismo orden en que se reciben. El cabezal empieza en el origen y debe terminar sobre la última bolita de la tríada.

Por ejemplo: `Triada(Rojo, Azul, Verde)` nos da como tablero resultante:

<gs-board>
  GBB/1.0
    size 3 1
    cell 0 0 Rojo 1
    cell 1 0 Azul 1
    cell 2 0 Verde 1
    head 2 0
</gs-board>

mientras que `Triada(Azul, Verde, Rojo)`:

<gs-board>
  GBB/1.0
    size 3 1
    cell 0 0 Azul 1
    cell 1 0 Verde 1
    cell 2 0 Rojo 1
    head 2 0
</gs-board>

> Definí el procedimiento `Triada`. 