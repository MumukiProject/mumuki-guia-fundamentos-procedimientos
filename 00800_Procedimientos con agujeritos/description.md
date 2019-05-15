¡Empecemos con algo fácil! :raised_hands: Supongamos que queremos **generalizar** a un procedimiento `Poner3Verdes` (que pone 3 bolitas verdes en un casillero), para que funcione con cualquier color que queramos (pero uno solo por vez). Lo que necesitamos es agregarle al procedimiento una especie de _agujero_...:open_mouth:

```gobstones
procedure Poner3(color) {
  Poner(color)
  Poner(color)
  Poner(color)
}
```

...que luego pueda ser completado cada vez que se use: 

```gobstones
program {
  Poner3(Negro)
  Poner3(Rojo)
}
```

> Escribí los códigos anteriores en el editor y fijate qué pasa. :eyes:

