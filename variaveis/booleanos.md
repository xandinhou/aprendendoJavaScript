<p>Booleano, são os valores True (verdadeiro) ou False (falso). Esses valores são úteis para representar, o resultado de uma comparação.</p>

<b>OBS1:</b> Antes dos exemplos precisamos conferir as tabelas verdade. 
 
|and  | A   | B   |
|-----|-----|-----|
|True |True |True |
|False|False|False|
|False|True |False|
|False|False|True |
<br>
<b>OBS2:</b> Observe que quando usamos <b>AND</b> uma preposição só é verdadeira quando as duas condições forem verdadeiras.<br>


|or   | A   | B   |
|-----|-----|-----|
|True |True |True |
|False|False|False|
|True |True |False|
|True |False|True |

<br>
<b>OBS2:</b> Observe que quando usamos <b>OR</b> uma preposição só é falsa quando as duas condições forem falsas.

Operações logicas em Javascript:
* var res = true && false equivale a true(**booleano**) and false(**booleano**), res será do tipo **booleano**
* var res = 0 && 1 equivale a false and true só que aqui o retorno é em number( 0 ou 1 ), nesse caso 0
* var res = true & false, nesse caso, somente com um & o retorno logico será em number ( 0 ou 1 )
*  var res = true || false equivale a true(**booleano**) or false(**booleano**), res será do tipo **booleano**
* var res = 0 || 1 equivale a false or true só que aqui o retorno é em number( 0 ou 1 ), nesse caso 0
* var res = true | false, nesse caso, somente com um | o retorno logico será em number ( 0 ou 1 )


## Exemplos

```
    var a = true
    var b = false
    
    console.log(typeof(a))
    console.log(typeof(b))
    
    var c = a && b
    console.log(c)
    
    c = a || b
    console.log(c)
    
    c = a && a
    console.log(c)
    
    c = a || a
    console.log(c)
    
    c = b || b 
    console.log(c)
```
Saída
```
    boolean
    boolean
    false
    true
    true
    true
    false
```

## Finalizando
Você agora possui conhecimento sobre oque são os booleanos e como eles funcionam, em <b>JavaScript</b>. Prossiga nos seus estudos e pule para o próximo <b>readme.</b>
