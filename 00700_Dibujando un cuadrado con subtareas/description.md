¡Ya podemos dibujar nuestro cuadrado! El cual debería verse así:

<gs-board>
  GBB/1.0
   size 3 3
   cell 0 0 Negro 1
   cell 0 1 Negro 1
   cell 0 2 Negro 1
   cell 1 0 Negro 1
   cell 1 1 Negro 1
   cell 1 2 Negro 1
   cell 2 0 Negro 1
   cell 2 1 Negro 1
   cell 2 2 Negro 1
   head 0 2
</gs-board>

El cabezal comienza en el origen, es decir, en el casillero de abajo a la izquierda:

<gs-board>
  GBB/1.0
   size 3 3
   head 0 0
</gs-board>

> Definí, e invoca en un `program`, el procedimiento `DibujarCuadradoNegroDeLado3` que, usando `DibujarLineaNegra3`, dibuje un cuadrado negro sobre el tablero.