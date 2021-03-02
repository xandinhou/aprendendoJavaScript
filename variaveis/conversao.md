# Conversão de dados

## Números

* String para number
```
  // Repare que nesse caso ele íra pegar só a parte inteira, essa é uma caracteristica do parseInt
  Number.parseInt("1.5") => //=> 1 
  // Nesse caso ele irá pegar tanto a parte inteira como a fracionaria
  Number.parseFloat("1.5) //=> 2
  // Nas versões atuais podemos omitir é utilizar apenas Number, o javascript trata de identificar automaticamente qual tipo
  Number("43.125") //=> 43.125
```  
 * Float para Int
 ```
  var float = 35.12
  var int = Number.parseInt(float) //=> Saída: 35, ele desconsidera a parte fracionaria, não faz **arrendondamentos**
 ```
 
 Considere atualmente esses os casos importantes do uso pois converter um 
 Int para Float em **JavaScript** não tem diferença alguma, caso suja outros exemplos importantes adiciono
