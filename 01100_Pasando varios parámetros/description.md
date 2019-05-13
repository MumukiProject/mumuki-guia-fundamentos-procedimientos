Como te adelantamos en el ejercicio anterior, los procedimientos pueden tener más de un **parámetro** (o _agujerito_). 

Por ejemplo: ¿qué pasaría si ahora queremos que `DibujarLinea3` sirva para dibujar líneas en cualquier dirección? Sin dudas vamos a necesitar que quien use el procedimiento nos diga, además del `color`, en qué `direccion` quiere que dibujemos la linea; y para eso necesitamos un nuevo **parámetro**.

¿Y cómo se hace esto? Muy fácil, al igual que como hacemos al escribir, vamos a **separar cada parámetro usando comas**. Mirá cómo queda:

```gobstones
procedure DibujarLinea3(color, direccion) {
  Poner(color)
  Mover(direccion)
  Poner(color)
  Mover(direccion)
  Poner(color)
}
```

(Para simplificar la explicación, por ahora vamos a olvidarnos de la posición final del cabezal. Ya volveremos con eso en las siguientes guías.)

> Tu tarea es ahora escribir un `program` que use la nueva versión de `DibujarLinea3` (no tenés que crearla, sólo usarla) y dibuje un cuadrado multicolor como este:

<gs-board>
  GBB/1.0
    size 4 4
    cell 0 1 Azul 1
    cell 0 2 Azul 1
    cell 0 3 Azul 1
    cell 1 3 Negro 1
    cell 2 3 Negro 1
    cell 3 3 Negro 1
    cell 3 2 Rojo 1
    cell 3 1 Rojo 1
    cell 3 0 Rojo 1
    cell 2 0 Verde 1
    cell 1 0 Verde 1
    cell 0 0 Verde 1
    head 0 0
</gs-board>