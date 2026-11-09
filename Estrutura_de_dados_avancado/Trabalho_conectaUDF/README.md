# 🌐 Projeto Conecta UDF

Um projeto desenvolvido em **Python** para representar e analisar uma rede social utilizando a estrutura de dados **Grafo**. O objetivo é demonstrar como usuários e amizades podem ser representados, além de calcular métricas importantes, como grau dos vértices e densidade da rede.

## 📌 Sobre o projeto

O Conecta UDF é um projeto acadêmico desenvolvido na disciplina de **Estrutura de Dados II**, com o propósito de estudar a aplicação de grafos na representação de redes sociais.

O projeto parte de uma rede original com 6 usuários e realiza uma expansão, adicionando 4 novos usuários e 5 novas amizades. A partir dessas alterações, são realizadas comparações entre a rede original e a atualizada.

## 🎯 Objetivos

- Representar uma rede social utilizando grafos.
- Implementar a estrutura de um grafo por meio de dicionários em Python.
- Adicionar novos usuários e conexões à rede.
- Calcular o grau de cada usuário.
- Calcular a quantidade de amizades existentes.
- Comparar a densidade da rede antes e depois das alterações.
- Compreender a importância das conexões e da privacidade em redes sociais.

## 🛠️ Tecnologias utilizadas

- **Python 3**
- Estrutura de dados: Grafos
- Dicionários e listas
- Funções e operações matemáticas

## ⚙️ Funcionamento

A rede social é representada por um grafo não direcionado, no qual:

- Cada vértice representa um usuário.
- Cada aresta representa uma amizade entre dois usuários.
- Cada usuário possui uma lista com seus respectivos amigos.

A implementação utiliza um dicionário Python para armazenar os usuários e suas conexões.

### 👥 Usuários adicionados

Foram adicionados quatro novos usuários à rede:

- Gabriel
- Helena
- Igor
- Julia

### 🤝 Novas amizades

As seguintes conexões foram adicionadas:

- Gabriel ↔ Ana
- Gabriel ↔ Helena
- Helena ↔ Felipe
- Igor ↔ Diego
- Igor ↔ Julia

## 📊 Resultados obtidos

Após a atualização da rede, foram realizadas comparações entre os dados originais e os novos dados.

| Métrica | Antes | Depois |
|---|---:|---:|
| Usuários | 6 | 10 |
| Amizades | 8 | 13 |
| Soma dos graus | 16 | 26 |
| Densidade | 53,33% | 28,89% |

### Grau dos usuários após a atualização

| Usuário | Grau |
|---|---:|
| Ana | 3 |
| Bruno | 3 |
| Carla | 3 |
| Diego | 4 |
| Elisa | 3 |
| Felipe | 3 |
| Gabriel | 2 |
| Helena | 2 |
| Igor | 2 |
| Julia | 1 |

### 📈 Análise dos resultados

Com a expansão da rede, Diego passou a ser o usuário com maior número de conexões, possuindo 4 amizades.

A densidade da rede diminuiu de 53,33% para 28,89%. Isso demonstra que o aumento no número de usuários não significa necessariamente que a rede ficará mais conectada, pois a quantidade de novas amizades também influencia esse resultado.

## 🧮 Cálculo da densidade

A densidade de um grafo não direcionado é calculada pela seguinte fórmula:

**D = 2 × E / [V × (V - 1)]**

Onde:

- **D:** densidade da rede.
- **E:** quantidade de arestas (amizades).
- **V:** quantidade de vértices (usuários).

O cálculo permite identificar o nível de conexão entre os usuários em relação ao número máximo de amizades possíveis.

## ▶️ Como executar o projeto

1. Clone este repositório:

   ```bash
   git clone URL_DO_REPOSITORIO
   ```

2. Entre na pasta do projeto:

   ```bash
   cd conecta-udf
   ```

3. Execute o arquivo Python:

   ```bash
   python main.py
   ```

**Requisitos:** Python 3 instalado. O projeto utiliza apenas recursos nativos da linguagem, sem necessidade de bibliotecas externas.

## 🔒 Privacidade e considerações

Durante o desenvolvimento, também foram discutidos aspectos relacionados à privacidade em redes sociais, como:

- Não compartilhar listas de amizades sem autorização.
- Permitir que os usuários controlem a visibilidade de seus dados.
- Proteger informações pessoais.
- Respeitar as diretrizes da Lei Geral de Proteção de Dados (LGPD).

## 📚 Aprendizados

O desenvolvimento deste projeto proporcionou conhecimentos práticos sobre:

- Implementação de grafos em Python.
- Representação de redes por meio de listas de adjacência.
- Manipulação de dicionários.
- Cálculo de grau e densidade de grafos.
- Análise e comparação de estruturas de dados.
- Aplicações de grafos em redes sociais.

## 👨‍💻 Autores

Projeto desenvolvido por:

- Arthur Arraes
- Natan Adriel
- Ivo Gustavo
- Matheus Enrico

**Instituição:** UDF – Centro Universitário  
**Disciplina:** Estrutura de Dados II  
**Professora:** Kadidja Valéria Reginaldo de Oliveira

---

⭐ Projeto acadêmico desenvolvido com o objetivo de aplicar conceitos de Estrutura de Dados utilizando Python.
