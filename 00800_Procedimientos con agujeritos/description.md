¡Empecemos con algo fácil! :raised_hands: Supongamos que tenemos un procedimiento llamado `Poner3Verdes`, que pone 3 bolitas verdes en un casillero, y lo queremos **generalizar** para que funcione con cualquier color que queramos (pero uno solo por vez). Lo que necesitamos es agregarle al procedimiento una especie de _agujero_... 

```gobstones
procedure Poner3(color) {
  repeat(3) {
    Poner(color)
  }
}
```

...que luego pueda ser completado con el color que queramos: 

```gobstones
program {
  Poner3(Negro)
  Poner3(Rojo)
}
```

> Escribí los códigos anteriores en el editor y fijate qué pasa. :eyes:

