¿No recordás como se escribe un procedimiento? No te preocupes, es normal, recién estamos empezando. :wink: 

Mirá como ejemplo este procedimiento que mueve el cabezal tres veces hacia el norte y el programa que lo usa:

```gobstones
procedure Mover5VecesHaciaElNorte() {
  Mover(Norte)
  Mover(Norte)
  Mover(Norte)
  Mover(Norte)
  Mover(Norte)
}

program {
  Mover5VecesHaciaElNorte()   
}
```