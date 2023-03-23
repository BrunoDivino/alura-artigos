# Chegou a hora de se desafiar!!!

---

Chegou o momento de se colocar à prova de novo. Será que você vai solucionar esse desafio?


## Problema

---

Pedro, um construtor muito habilidoso, recebeu um pedido um tanto inusitado de um de seus clientes. Construir um ofurô de base triangular. Pedro constatou que para começar a criar tal inovação ele irá precisar de 3 tábuas de madeira iniciais que formarão os lados do triângulo da base do Ofurô. Contudo, Pedro ainda quer decidir qual será o tamanho do Ofurô e o seu formato exato, uma vez que existem vários tipos de triângulo. O problema é que não são todos os valores de comprimentos de tábua que resultam em um triâgulo. 

Para ajudar Pedro em sua tarefa, crie um programa que aceite 3 valores inteiros e retorne uma resposta indicando se tais comprimentos de tábua podem formar um triângulo ou não.

Um triangulo só pode existir se cada lado for menor em tamanho do que a soma dos outros dois lados:

**A < B + C**
**B < A + C**
**C < A + B**

### Exemplos de Input

Exemplo 1:
```
6
4
3
```

Exemplo 2:
```
7
3
2
```

### Exemplos de Output

Exemplo 1:
```
Os três valores formam um triângulo!
```

Exemplo 2:
```
Os três valores não formam um triângulo!
```

### Dicas preciosas

O desafio pode ser resolvido em diversos ambientes, inclusive o próprio console no DevTools do navegador.

Uma forma de conseguir informar um input para o console do navegador seria utilizando a função `prompt()`.

```
var input = prompt();
```

Hora de botar a mão na massa! 

Caso tenho alguma dúvida, fique a vontade para usar o nosso fórum e, caso queira compartilhar a sua solução, acesse o [**Discord da Alura**](https://discord.gg/QeBdgAjXnn) e troque algumas ideias com outros alunos!

# Resolução

---

Dentro da lógica de programação, algumas vezes existem muitas formas de solucionar um mesmo desafio. Uma das possíveis formas de solucionar o problema passado é a seguinte:

```
var A = prompt("Insira o primeiro número:");
var B = prompt("Insira o segundo número:");
var C = prompt("Insira o terceiro número:");

if(A < B + C && B < A + C && C < A + B){
    console.log("Os três valores formam um triângulo!");
}else{
    console.log("Os três valores não formam um triângulo!");
}
```

A sua solução ficou parecida? Compartilhe conosco o seu código através da [**Comunidade da Alura no Discord**](https://discord.gg/QeBdgAjXnn) e discuta com outros colegas sobre quais são as melhores alternativas para solucionar essa questão.
