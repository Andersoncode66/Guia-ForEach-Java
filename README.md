# Guia-ForEach-Java


## 💻Roteiro de Estudos
| Exercício | Tema  | Descrição |
| :---------------- | :--------- | :--------- |
| `01` | `Soma dos Elementos de uma Lista` | `Crie uma lista de números inteiros e calcule a soma de todos os elementos utilizando o for-each` |]
| `02` | `` | `` |
| `03` | `` | `` |
| `04` | `` | `` |
| `06` | `` | `` |


## 💻Explicação dos códigos]


### Exercício 01 
![Capturar_2025_03_15_18_13_45_252](https://github.com/user-attachments/assets/c159e0d9-c9bd-4de9-b1f3-aba3b78fa2b8)

🔍 Explicação do Código
1. Importação das classes

- import java.util.List; e import java.util.ArrayList; são usadas para trabalhar com listas dinâmicas em Java.

2. Criação da lista

List<Integer> numeros = new ArrayList<>();

- Aqui, criamos uma lista do tipo Integer chamada numeros. Como estamos usando ArrayList, a lista pode crescer dinamicamente conforme adicionamos elementos.

3. Adição de elementos

numeros.add(666);
numeros.add(555);
numeros.add(42);
numeros.add(43);
- Esses números são adicionados á lista.

4. Inicialização da variável soma

int soma = 0;

- Criamos a variável soma, que será usada para armazenar a soma dos elementos da lista.

5. Uso do for-each
   
for (Integer numero : numeros) {
    soma += numero;
}

- Aqui acontece a mágica! O for-each percorre a lista numeros, atribuindo cada elemento à variável numero.
- A cada iteração, o valor de numero é somado à variável soma.

---------------------------------------------------------------------------------------------------------------------------


