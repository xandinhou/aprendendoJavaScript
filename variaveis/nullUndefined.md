# Null e Undefined
 
## Null:
Representa um valor nulo ou "vazio" que aponta para uma area de memoria de um objeto inexistente, as vezes é devolvido num lugar de um objeto esperado ( APIs),
esteja ciente das diferenças entre o operador de igualdade (==) e o de igualdade estrita (===) (em inglês). Uma conversão de tipos é realizada na operação de igualdade.

## Undefined
O undefined é uma propriedade do objeto global, ou seja, é uma variável no escopo global. O valor inicial de undefined é o valor primitivo undefined.
* Uma **variável** que não teve um valor atribuído é do tipo undefined.
* Um **método** ou sentença também retorna undefined se a variável que está sendo avaliada não tem um valor atribuído. 
* Uma **função** retorna undefined se um valor não for retornado.

## Exemplos:
```
  // foo não existe, não foi definido e jamais foi inicializado:
  > foo
  "ReferenceError: foo is not defined"

  // foo é conhecido e existe, mas não aponta para nenhum tipo ou valor:
  > var foo = null; foo
"null"
```
 # Diferenças entre Null e Undefined
 ```
  typeof null        // object (bug no ECMAScript, deveria ser null - http://2ality.com/2013/10/typeof-null.html)
  typeof undefined   // undefined
  null === undefined // falso
  null  == undefined // verdadeiro
 ```
