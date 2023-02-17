# Chegou a hora de se desafiar!!!

---

Você já acumulou conhecimento suficiente da linguagem JavaScript para entender princípios básicos de lógica de programação.

Agora é hora de colocar seus estudos à prova e me ajudar a solucionar um super desafio!

Tenho a seguinte situação:

## Problema

---

Um amigo meu que trabalha em uma loja de vendas me pediu para criar um *script* que retorne o total que um funcionário irá receber de salário ao final do mês. Cada funcionário tem um salário fixo específico que é somado com uma comissão de 10% em cima do total de vendas realizadas no mês pelo mesmo. 

Esse meu amigo gostaria de um script no qual ele fornecesse o **NOME**, **SALÁRIO FIXO** e **TOTAL DE VENDAS DO MÊS** de dado funcionário e o console respondesse com o valor total do salário. 

Ambos **SALÁRIO FIXO** e **TOTAL DE VENDAS DO MÊS** são valores de precisão dupla, ou seja, **doubles** e o valor do salário total deve ter duas casas decimais.

### Exemplos de Input

Exemplo 1
```
Lucas
500
1325
```

Exemplo 2:
```
Katia 750 2834
```

### Exemplos de Output

Exemplo 1:
```
O(A) funcionário(a) Lucas deve receber R$ 632,50
```

Exemplo 2:
```
O(A) funcionário(a) Katia deve receber R$ 1033,40
```

### Dicas preciosas

O desafio pode ser resolvido em diversos ambientes, inclusive o próprio console no DevTools do navegador.

Uma forma de conseguir informar um input para o console do navegador seria utilizando a função `prompt()`.

```
var input = prompt();
```

Hora de botar a mão na massa! 

Caso tenho alguma dúvida, fique a vontade para usar o nosso fórum e, caso queira compartilhar a sua solução, acesse o [**Discord da Alura**](https://discord.gg/QeBdgAjXnn) e troque algumas ideias com outros alunos!

# Resolução da instrutora

---

Dentro da lógica de programação, algumas vezes existem muitas formas de solucionar um mesmo desafio. Uma das possíveis formas de solucionar o problema passado é a seguinte:

```
var input = prompt()
var lines = input.split(" ");
    
var nomeFuncionario = lines.shift();
var salarioFixo = parseFloat(lines.shift());
var vendasMes = parseFloat(lines.shift());
var totalSalario = ((vendasMes * 10) / 100) + salarioFixo;

console.log("O(A) funcionário(a)  " + nomeFuncionario + " deve receber R$ " + totalSalario.toFixed(2));
```

A sua solução ficou parecida? Compartilhe conosco o seu código através da [**Comunidade da Alura no Discord**](https://discord.gg/QeBdgAjXnn) e discuta com outros colegas sobre quais são as melhores alternativas para solucionar essa questão.
