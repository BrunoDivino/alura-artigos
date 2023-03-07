# Chegou a hora de se desafiar!!!

---

Vamos a mais um desafio de lógica de programação! Vença esse obstáculo se for capaz!

Tenho a seguinte situação:

## Problema

---

Recentemente, um amigo seu acaba de adotar um gato de um abrigo de animais. O abrigo tem o registro de quantos dias de vida o gato tem, porém, seu amigo está curioso para saber qual a idade do animal separada em **anos**, **meses** e **dias**. Como você deve um favor a ele, você resolveu criar um programa em JavaScript que ajude ele com essa questão.

Crie um programa que receba a **idade em dias** e devolva a mesma idade separada em **anos**, **meses** e **dias**. Considere que todos os anos possuem 360 dias e todos os meses possuem 30 dias.


### Exemplos de Input

Exemplo 1:
```
327
```

Exemplo 2:
```
487
```

### Exemplos de Output

Exemplo 1:
```
0 ano(s)
10 mes(es)
27 dia(s)
```

Exemplo 2:
```
1 ano(s)
4 mes(es)
2 dia(s)
```

### Dicas preciosas

O desafio pode ser resolvido em diversos ambientes, inclusive o próprio console no DevTools do navegador.

Uma forma de conseguir informar um input para o console do navegador seria utilizando a função `prompt()`.

```
var input = prompt();
```

Para utilizar apenas a parte inteira de um número decimal, basta utilizar a função `parseInt()`. Observe o exemplo:

```
x = 151.988698515;
parseInt(x);
'151'
```

> Perceba que isso não é o mesmo que um arredondamento!


Hora de botar a mão na massa! 

Caso tenho alguma dúvida, fique a vontade para usar o nosso fórum e, caso queira compartilhar a sua solução, acesse o [**Discord da Alura**](https://discord.gg/QeBdgAjXnn) e troque algumas ideias com outros alunos!

# Resolução

---

Dentro da lógica de programação, algumas vezes existem muitas formas de solucionar um mesmo desafio. Uma das possíveis formas de solucionar o problema passado é a seguinte:

```
const input = prompt("Insira a idade do animal em dias:");

var dias = parseInt(input);

const anos = parseInt(dias / 360);
dias = dias % 365;

const meses = parseInt(dias / 30);
dias = dias % 30;

console.log(anos + " ano(s)");
console.log(meses + " mes(es)");
console.log(dias + " dia(s)");
```

A sua solução ficou parecida? Compartilhe conosco o seu código através da [**Comunidade da Alura no Discord**](https://discord.gg/QeBdgAjXnn) e discuta com outros colegas sobre quais são as melhores alternativas para solucionar essa questão.
