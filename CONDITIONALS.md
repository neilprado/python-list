# Lista de exercícios usando estruturas de decisão if/elif/else

1. Escreva um programa em Python que leia um caractere digitado pelo usuário e verifique se a letra digitada é vogal ou consoante. (Lembrando que o Python é case sensitive, use o método `.lower()` ou `.ùpper()` na hora de realizar a comparação)

2. Escreva um programa em Python que leia três números inteiros e mostre qual deles é o maior.

3. Escreva um programa que pergunte ao usuário o turno que ele estuda. O usuário deve digitar **M** para Matutino, **V** para Vespertino e **N** para Noturno. Imprima a mensagem "Bom dia!", "Boa tarde!", "Boa noite!" de acordo com o valor digitado pelo usuário.
   Caso qualquer outro valor seja digitado, deve se exibir a mensagem: "Valor inválido!"

4. Escreva um programa que leia um número e exiba seu dia correspondente da semana de acordo com a tabela abaixo.
   | Entrada | Saída |
   | ------- | :----------: |
   | 1 | Domingo |
   | 2 | Segunda |
   | 3 | Terça-Feira |
   | 4 | Quarta-Feira |
   | 5 | Quinta-Feira |
   | 6 | Sexta-Feira |
   | 7 | Sábado |

5. Escreva um programa que leia os 3 números (inteiros ou ponto flutuante) de um triângulo e determine:

- Verificar se é de fato um triângulo. **É considerado um triângulo se a soma de dois lados é maior que a soma do terceiro**
- Verificar se é um triângulo equilátero **É considerado um triângulo equilátero se os TRÊS LADOS forem IGUAIS**
- Verificar se é um triângulo isósceles **É considerado um triângulo isósceles se DOIS LADOS quaisquer forem IGUAIS**
- Verificar se é um triângulo escaleno **É considerado um triângulo escaleno se os **TRÊS LADOS FOREM DIFERENTES\*\*

6. Faça um programa que leia três notas de um aluno e tire a média destas notas. Caso a média seja 7 ou superior, exiba na tela a mensagem: **Aprovado**, caso a média seja menor que 7 e maior ou igual a 5, exiba a mensagem: **Recuperação**, caso a média seja menor que 5, exiba a mensagem **Reprovado** e se for qualquer outro valor, deve ser exibido: **Média inválida**.

7. Escreva um programa em python que leia dois números e pergunte ao usuário qual operação (adição(+), subtração(-), multiplicação(\*) ou divisão(/)). De acordo com a operação que o usuário escolher, realize o cálculo matemático e exiba qual operação foi escolhida o seu resultado.

8. Escreva um programa que peça para o usuário inserir uma idade e mostre se ele é maior de idade ou não

9. Você foi contratado pelo SBT para mostrar ao Silvio Santos para mostrar um exemplo de uma pergunta de múltipla escolha para ser contratado como estagiária pra desenvolver o novo Show do Milhão. Como o Homem do Baú é um senhor muito ocupado, você foi designada pra realizar essa tarefa usando apenas estruturas de decisão e em 15 minutos. A pergunta foi predefinida pela equipe e deve ser:

- Qual a capital da Paraíba? A - Patos; B - João Pessoa; C - Santa Rita; D - Campina Grande
  Caso a opção correta seja escolhida, exiba a mensagem: "Você acertou!". Caso contrário, exiba a mensagem: "Que pena, você errou..."

10. Faça um programa que exiba um menu com as seguintes opçoes:
    | Opção | Funcionalidade |
    | ------- | :---------------------: |
    | 1 | Celsius para Fahrenheit |
    | 2 | Fahrenheit para Celsius |
    De acordo com a escolha, informe um valor e calcule a conversão de acordo com a seguinte fórmula.

Para converter de fahrenheit para celsius:

```
celsius = 5 * (fahrenheit - 32) / 9
```

Para converter de celsius para fahrenheit:

```
fahrenheit = (celsius / 5) * 9 + 32
```

Deve ser exibido ao usuário a opção escolhida e a temperatura final.
