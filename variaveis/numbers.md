# Numbers
 
## Tipos
<p>Estamos acostumados em outras linguaguens existir pelo menos esses dois tipos de números:</p>
<ul>
    <li>int</li>
    <li>float</li>
</ul>
<p> No <b>JavaScript</b> é diferente, só temos um tipo para todos números:
 <ul>
   <li>Number</li>
</ul>

Exemplos:
```
    #Exemplos de números
    var x = 10; // X recebe 10
    var y = 20.55; // Y recebe 20.55
    
    // Agora perguntamos o tipo para o JS:
    
    console.log(typeof(x));
    console.log(typeof(y));    
```
Saída:
```
    number
    number
```
Agora podemos perguntar se o tipo deles são iguais:
```
    var iguais = typeof(x) == typeof(y); // Iguais recebe o valor booleano da pergunta (  tipo de x é igual a y?)
    
    // Manda o JS exibir o resultado:
    console.log(iguais)
```
Saída
```
    true
```

## Conclusão
<p>
  Com isso aprendemos que em JavaScript é trabalhado com apenas um tipo de dado para números,
  não tendo a diferença entre Inteiros e Reais
</p>
