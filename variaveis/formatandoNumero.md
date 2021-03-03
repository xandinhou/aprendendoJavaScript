## Formatação de números

* Número com duas casas decimais:
```
  var n1 = 15.1
  var n1 = n1.toFixed(2) //=> 15.10
```

* Trocar ponto por virugla
```
   var n1 = 15.1
   var n1 = n1.toFixed(2).replace('.',',') //=> 15.10
```
* Monetario
```
  var n1 = 1510.5
  n1.toLocaleString('pt-br', {style: 'currency' , currency : 'BRL'}) //=> R$ 1.510,50
```
