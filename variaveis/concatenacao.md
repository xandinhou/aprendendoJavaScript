# Caracteristicas interessante da concatenacao

* String + String = String
```
  var nome = "Alexandre"
  var cidade = "BSB"
  console.log(nome + " Mora em " + cidade) //=> Alexandre Mora em BSB
```

* Número + String
```
  // Se eu tiver qualquer número ao lado de uma string ele ira concatenar
  console.log( 1 + 2 + "Caramba"); //=> ((1+2)+Caramba) > 3Caramba
  
  var a = 1.5
  var b = "112"
  console.log(a+b) //=> 1.5112, ou seja, ele transforma a para string e concatena com b
  
```
