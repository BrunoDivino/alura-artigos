# Chegou a hora de se desafiar!!!

---

Chegou a hora de colocar seus conhecimentos de JavaScript e lógica de programação mais uma vez a prova! Solucione o desafio abaixo e mostre do que é capaz!

Tenho a seguinte situação:

## Problema

---

Assim como muitos brasileiros, você quer viajar para o litoral brasileiro no feriado de 7 de setembro. Interesado em lhe ajudar, seu tio, um ávido colecionador de carros, lhe emprestar um de seus carros para fazer a viagem, uma autêntica Volkswagen Brasília amarela, o primeiro carro a ser produzido no Brasil. Como é a primeira vez dirigindo o carro, você não faz ideia de quanto combustível o carro irá consumir na viagem, apenas que seu consumo é de 9,3 km/l. 

Com a finalidade de descobrir a quantidade de litros gastos na viagem, crie um programa em JavaScript ao qual será fornecido como entrada o **tempo gasto na viagem (em horas)** e a **velocidade média** da mesma (km/h). Através dessas informações será possível descobrir a distância percorrida e, em seguida, calcular a quantidade de litros necessária. A resposta dever ter, no máximo, duas casas decimais.


### Exemplos de Input

Exemplo 1:
```
12
80
```

Exemplo 2:
```
8
100
```

### Exemplos de Output

Exemplo 1:
```
A quantidade de combustível a ser consumida será de 103.23 litros
```

Exemplo 2:
```
A quantidade de combustível a ser consumida será de 86.02 litros
```

### Dicas preciosas

O desafio pode ser resolvido em diversos ambientes, inclusive o próprio console no DevTools do navegador.

Uma forma de conseguir informar um input para o console do navegador seria utilizando a função `prompt()`.

```
var input = prompt();
```

Para determinar um número fixo de casas decimais em algum valor, basta utilizar a função `toFixed()`. Veja um exemplo de uso:

```
x = 151.988698515;
x.toFixed(2);
'151.99'
```

Hora de botar a mão na massa! 

Caso tenho alguma dúvida, fique a vontade para usar o nosso fórum e, caso queira compartilhar a sua solução, acesse o [**Discord da Alura**](https://discord.gg/QeBdgAjXnn) e troque algumas ideias com outros alunos!

# Resolução

---

Dentro da lógica de programação, algumas vezes existem muitas formas de solucionar um mesmo desafio. Uma das possíveis formas de solucionar o problema passado é a seguinte:

```
const tempo = prompt("Tempo de viagem em horas:");
const velocidade = prompt("Velocidade média da viagem em km/h:");

const calculo = (tempo * velocidade) / 9.3;

console.log("A quantidade de combustível a ser consumida será de " + calculo.toFixed(2) + " litros");
```

A sua solução ficou parecida? Compartilhe conosco o seu código através da [**Comunidade da Alura no Discord**](https://discord.gg/QeBdgAjXnn) e discuta com outros colegas sobre quais são as melhores alternativas para solucionar essa questão.
