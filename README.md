# SistemaRecomendacao_CoVisitation

## Descrição Projeto

**Conjunto de dados:**
Dataset do Pinterest para criar ofertas como "Quem viu X também viu Y".

Pinterest é uma plataforma online onde usuários podem explorar imagens e vídeos sobre temas de sua preferência, podendo salvar imagens em seus perfis. Assim, o dataset é composto pelos seguintes dados:

- `user_id`: identificador do usuário
- `item_id`: identificador do item (imagem ou vídeo)
- `rating`: sinal indicando que o usuário salvou o item ou não

**Arquivo:** .parquet

**Objetivo:**
Explorar a recomendação de itens a partir de co-visitação de itens. Este tipo de recomendação é utilizada em ofertas como "Clientes que compraram X também compraram Y". 

**IDE:** Colab

**Linguagem:** Python 

**Principais bibliotecas utilizadas:**
•	Cycler, para personalizar cores em gráficos;
•	Numpy, para realizar cálculos numéricos;
•	Pandas, para manipulação e tratamento dos dados;
•	Matplotlib, para criação e visualização de gráficos;
•	Google.colab, para importar arquivos da núvem;
•	NetworkX, biblioteca que possibilita a criação, manipulação e estudos de estruturas em grafos.


**Sequencia processos:**
1° Instalar bibliotecas;
2° Instalar datasets;
3° Criar o grafo de usuários e itens;
4° Construir a recomendação a partir do grafo;
5° Gerando recomendações;
6° Analisando algumas recomendações (itens vizinhos recomendados).

**Resultado:**
Através da sequência de processos realizadas para analisar e explorar o algoritmo de recomendação coVisitation, foi possível gerar recomendações de imagens e/ou vídeos através de itens salvos na plataforma Pinterest
