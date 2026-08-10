# 📚 Implementação de uma Pilha em C

Este projeto apresenta uma implementação simples de uma **estrutura de dados do tipo Pilha (Stack)** utilizando a linguagem **C**.

A pilha segue o conceito **LIFO (Last In, First Out)**, onde o último elemento inserido é o primeiro a ser removido.

## 🧠 Conceitos utilizados

Neste código são trabalhados conceitos importantes de estruturas de dados, como:

* 📦 Estrutura `struct`
* 🔢 Vetores
* 🔝 Controle do topo da pilha
* ➕ Inserção de elementos (**Push**)
* ➖ Remoção de elementos (**Pop**)
* 👀 Visualização dos elementos (**Display**)
* 🔄 Estruturas de repetição
* 🔀 Estruturas condicionais
* 🧩 Funções em C

## ⚙️ Funcionamento

A pilha possui uma capacidade máxima de **15 elementos**, definida pela constante:

```c
#define MAXSIZE 15
```

O atributo `top` é utilizado para controlar a posição do elemento que está no topo da pilha.

Inicialmente, a pilha começa vazia:

```c
s.top = -1;
```

### ➕ PUSH

A operação `push()` adiciona um novo elemento ao topo da pilha.

Antes da inserção, o programa verifica se a pilha está cheia. Caso esteja, uma mensagem de erro é exibida.

```text
Pilha cheia!
```

### ➖ POP

A operação `pop()` remove o elemento que está no topo da pilha.

Caso a pilha esteja vazia, o programa informa:

```text
Pilha vazia!
```

Como a pilha utiliza o conceito **LIFO**, o último elemento inserido será o primeiro a ser removido.

### 👀 DISPLAY

A função `display()` mostra todos os elementos presentes na pilha, começando pelo elemento que está no topo.

Exemplo:

```text
Elementos na pilha:
30
20
10
```

Nesse caso, o elemento `30` será o primeiro a ser removido.

## 🖥️ Menu do programa

Ao executar o programa, é apresentado um menu com as seguintes opções:

```text
----------------
 1 --> PUSH
 2 --> POP
 3 --> DISPLAY
 4 --> SAIR
----------------
```

O usuário pode escolher qual operação deseja realizar.

## 🎯 Objetivo

O objetivo deste código é praticar a implementação e o funcionamento de uma **pilha utilizando um vetor**, compreendendo na prática as operações básicas de inserção, remoção e visualização de elementos.

> 📌 **Conceito principal:** uma pilha funciona no modelo **LIFO — Last In, First Out**, ou seja, o último elemento que entra é o primeiro que sai.
> 
Esse descrição foi feita na IA, mas esse código eu fiz para testar métodos de ordenação em pilhas e filas utilizando o Dev-C++.
