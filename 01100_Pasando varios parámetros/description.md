¿Y si queremos que `DibujarLinea3` sirva también para dibujar líneas en cualquier dirección? :thought_balloon: Sin dudas tenemos que decirle al procedimiento, además del `color`, en qué `direccion` debe dibujar la línea; y para eso vamos a necesitar un nuevo **parámetro** :open_mouth:. Por suerte, ¡los procedimientos también pueden tener más de un **parámetro**! :raised_hands:

¿Y cómo se hace esto? Muy fácil, al igual que como hacemos al escribir, vamos a **separar cada parámetro usando comas** de esta manera:

```gobstones
procedure DibujarLinea3(color, direccion) {
  Poner(color)
  Mover(direccion)
  Poner(color)
  Mover(direccion)
  Poner(color)
}
```

> Escribí un `program` que use la nueva versión de `DibujarLinea3` (no tenés que crearla, sólo usarla) y dibuje un cuadrado multicolor como este:
>
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
>
> No te preocupes por la posición final del cabezal.