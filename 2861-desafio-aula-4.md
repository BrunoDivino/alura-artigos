# Chegou a hora de se desafiar!!!

---

Mais um desafio quentinho saindo do forno para você desafiar suas habilidades de programação!


## Problema

---
Você é um programador inciante a acabou de conseguir um estágio em uma empresa que desenvolve jogos para celular. O jogo que você está ajudando a desenvolver consome muita bateria do aparelho e seu chefe pediu para criar um programa que cheque a bateria do celular antes do jogo ser inicializado.

Crie um programa em JavaScript que leia um número inteiro (porcentagem da bateria) e retorne a cor correspondente ao intervalo que esse número se encontra dentro de ([0,25] - VERMELHO, (25,50] - LARANJA, (50,75] - AMARELO, (75,100] - VERDE). Se o número lido estiver fora do intervalo, mostre uma mensagem de erro.

O símbolo "(" significa que o número vindo em seguida marca o inicio do intervalo, mas não está incluso no mesmo. Já o símbulo "]" indica que o número anterior reprensenta o último número do intervalo e está incluso no mesmo.

### Exemplos de Input

Exemplo 1:
```
37
```

Exemplo 2:
```
75
```

### Exemplos de Output

Exemplo 1:
```
A bateria do celular está no nível LARANJA
```

Exemplo 2:
```
A bateria do celular está no nível AMARELO
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
var numero = prompt("Insira a porcentagem da bateria sem o simbolo %");

if (0 <= numero && numero <= 25) {
  console.log("A bateria do celular está no nível VERMELHO");
} else if (25 < numero && numero <= 50) {
  console.log("A bateria do celular está no nível LARANJA");
} else if (50 < numero && numero <= 75) {
  console.log("A bateria do celular está no nível AMARELO");
} else if (75 < numero && numero <= 100) {
  console.log("A bateria do celular está no nível VERDE");
} else {
  console.log("ERRO DE LEITURA");
}
```

A sua solução ficou parecida? Compartilhe conosco o seu código através da [**Comunidade da Alura no Discord**](https://discord.gg/QeBdgAjXnn) e discuta com outros colegas sobre quais são as melhores alternativas para solucionar essa questão.
