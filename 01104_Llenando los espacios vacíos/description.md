Entendamos qué acabamos de hacer. :sweat_smile:

Lo primero que hicimos fue declarar un procedimiento, pero con una pequeña diferencia: toma un _parámetro_, llamado `color`.

```gobstones
procedure Poner3(color) {
  Poner(color)
  Poner(color)
  Poner(color)
}
```

¿Y qué es un parámetro? Son esos nombres que van entre paréntesis para ser reemplazados por valores concretos cuando invocamos al procedimiento. Por ejemplo, si lo invocamos así..

```gobstones
program {
  Poner3(Negro)
}
```

...lo que se ejecuta es:

```gobstones
Poner(Negro)
Poner(Negro)
Poner(Negro)
```

Y si lo invocamos así...

```gobstones
program {
  Poner3(Rojo)
}
```

lo que se ejecuta es:

```gobstones
Poner(Rojo)
Poner(Rojo)
Poner(Rojo)
```

Fijate como cada vez que aparece `color` se reemplaza por el valor que le _pasamos_ a `Poner` :raised_hands:. Veamos si se entiende:

> Escribí un programa que ponga tres bolitas verdes usando el procedimiento `Poner3`.

