# Guia-ForEach-Java


## 💻Roteiro de Estudos
| Exercício | Tema  | Descrição |
| :---------------- | :--------- | :--------- |
| `01` | `Soma dos Elementos de uma Lista` | `Crie uma lista de números inteiros e calcule a soma de todos os elementos utilizando o for-each` |]
| `02` | `Contagem de Caracteres em uma String` | `Crie uma lista de strings e conte quantos caracteres cada string possui.` |
| `03` | `Exibição de Elementos em Maiúsculo` | `Crie uma lista de palavras e exiba cada palavras em maiúsculo.` |
| `04` | `Verificação de Paridade` | `Crie uma lista de números e verifique quais são pares e quais são ímpares, exibindo esssa informação.` |
| `05` | `Imprimir Elementos de uma lista de Strings` | `Crie uma lista de nomes e imprima cada nome.` |


## 💻Explicação dos códigos


### Exercício 01
**1. Importação das classes**

- import java.util.List; e import java.util.ArrayList; são usadas para trabalhar com listas dinâmicas em Java.

**2. Criação da lista**

![Capturar_2025_03_17_08_13_41_745](https://github.com/user-attachments/assets/02adc90a-3db7-4783-8ccc-1a7019a52baf)

- Aqui, criamos uma lista do tipo Integer chamada numeros. Como estamos usando ArrayList, a lista pode crescer dinamicamnete confrome adicionamos elementos.

**3. Adição de elementos**

![Capturar_2025_03_17_08_16_28_421](https://github.com/user-attachments/assets/06da9737-22e9-4978-8e77-65fc9e91cf12)

- Esses números são adicionados á lista.

**4. Inicialização da variável soma**

![Capturar_2025_03_17_08_18_09_758](https://github.com/user-attachments/assets/ecaf8130-e794-41cd-ab7c-f7235c2f5124)

- Criamos a variável soma, que será usada para armazenar a soma dos elementos da lista.

**5. Uso do for-each**

![Capturar_2025_03_17_08_21_34_193](https://github.com/user-attachments/assets/fa030e9c-14fa-408c-b72d-b76822aca271)

- Aqui acontece a mágica! O for-each percorre a lista numeros, atribuindo cada elemento à variável numero.
- A cada iteração, o valor de numero é somado à variável soma.

-------------------------------------------------------------------------------------------------------------------

### Exercício 02

![Capturar_2025_03_17_08_24_46_120](https://github.com/user-attachments/assets/07f697a5-320e-47a4-bfff-be0c6eb0e92e)

1. Uso do for-each para percorrer a lista e .length
- O for-each percorre a lista e a cada iteração, a variável string recebe uma das palavras.
-  A função string.length() calcula o número de caracteres da palavra e o exibe no console.

-----------------------------------------------------------------------------------------------------------------------

### Exercício 03

![Capturar_2025_03_17_08_29_07_976](https://github.com/user-attachments/assets/f1350019-bba6-4ffc-9994-55560183e421)

1. Uso do for-each para percorrer a lista é o método .toUpperCase().
- O for-each percorre a lista de palavras, atribuindo cada palavra á variável string.
- Em cada iteração, a palavra é convertida para maiúscula utilizando o método .toUpperCase(). O resultado é armazenado na variável maiuscula.

**🔧 Possível Melhoria**

pode usar um Set (como o HashSet) para garantir que as palavras não se repitam.

![Capturar_2025_03_17_08_43_25_23](https://github.com/user-attachments/assets/a16d175e-7c63-4e79-bfe4-0b04a47aef17)

O que muda?
- Usamos um HashSet para garantir que as palavras repetidas não sejam impressas, já que um Set não permite elementos duplicados.
-----------------------------------------------------------------------------------------------------------------------


### Exercício 04

**1. Uso do for-each para percorrer a lista e if else**

![Capturar_2025_03_17_08_50_15_740](https://github.com/user-attachments/assets/83daac09-14e7-4155-b9d1-ba3b20c8099b)

- O for-each percorre a lista numeros, e a cada iteração, o número (integer) é verificado para determinar se é par ou ímpar.
- A verificação é feita pelo operador de módulo (% 2). Se o resto da divisão for zero (integer % 2 == 0), o número é par. Caso contrário, é ímpar.
- O for-each é útil para percorrer uma lista ou coleção de elementos, enquanto o if-else pode ser usado dentro do loop para tomar decisões sobre cada item da lista.
- Vamos usar uma lista de números e, dentro do for-each, aplicar um if-else para verificar se cada número é par ou ímpar.
- if (numero % 2 == 0)
Dentro do loop, verificamos se o número é par (divisão por 2 com resto zero). Se for, executamos o código dentro do bloco if.
- else
Se o número não for par, o código vai para o bloco else e imprime que o número é ímpar.

**🔧 Sugestões de Melhoria**

2. Evitar repetir números na saída

Se você quiser evitar imprimir múltiplas vezes para números repetidos, pode usar um Set, que vai garantir que cada número seja verificado apenas uma vez. Aqui está como:

O que mudou?

Usamos um HashSet para armazenar os números de maneira única. Ou seja, números duplicados não serão processados novamente.
Também incluímos o número na mensagem para que o programa diga qual número é par ou ímpar.


-----------------------------------------------------------------------------------------------------------------------

### Exercício 05

**1. Loop for-each**

![Capturar_2025_03_17_09_03_29_219](https://github.com/user-attachments/assets/2ff347d9-1065-49b7-a507-d4f89234d866)

   
- O for-each percorre cada elemento da lista, atribuindo o valor de cada elemento à variável string e, em seguida, imprime esse valor.

-----------------------------------------------------------------------------------------------------------------------

### Exercício 06

**1. Criação do Loop e multiplicação**

![Capturar_2025_03_17_09_11_35_20](https://github.com/user-attachments/assets/97ebbd82-f0be-4eb7-ad07-055aa03a3495)

- calculo *= integer;: A cada iteração, o valor de calculo é multiplicado pelo valor atual de integer (o número da lista).
- System.out.println(calculo);: Após cada multiplicação, o resultado é impresso no console.

-----------------------------------------------------------------------------------------------------------------------

### Exercício 07

**1. Loop for-each e método length().**

- O for-each percorre cada palavra da lista e calcula a quantidade de caracteres de cada uma com o método length().

![Capturar_2025_03_17_09_14_19_367](https://github.com/user-attachments/assets/0aec3d1e-1e78-421c-a5ca-d3f3c3317b73)


### Exercício 08

1. Conversão de String para Integer com for-each e Integer.parseInt().
- Integer.parseInt(string): Esse método converte a string para um número inteiro. Por exemplo, "44" será convertido para 44.

![Capturar_2025_03_17_09_17_53_894](https://github.com/user-attachments/assets/80626c1d-ec03-42c2-aff7-a5ada43b79f5)

-----------------------------------------------------------------------------------------------------------------------


### Exercício 09

1. Cálculo da Soma das Notas
- A variável soma é inicializada com zero e, em seguida, o loop for-each percorre todas as notas na lista. A cada iteração, a nota atual é adicionada à variável soma.

![Capturar_2025_03_17_09_22_05_811](https://github.com/user-attachments/assets/b01de9f7-2eaa-4a29-87be-c374f777cf5b)


2. Cálculo da Média
- A média das notas é calculada dividindo a soma total das notas pelo número de elementos na lista (notas.size()). O método size() retorna o número de elementos da lista.

![Capturar_2025_03_17_09_29_10_638](https://github.com/user-attachments/assets/a5da5cf4-d960-41f4-8f54-500fb616c399)

-----------------------------------------------------------------------------------------------------------------------


