### README

# O Impacto dos Atores Recorrentes nas Produções Cinematográficas

## Integrantes do Projeto
- **Márcio Gastaldi** - RM98811
- **Arthur Bessa Pian** - RM99215
- **Davi Desenzi** - RM550849

## Descrição do Projeto
Este projeto investiga a influência da presença de atores recorrentes nos catálogos de filmes e séries das plataformas Netflix, IMDb e Rotten Tomatoes. A partir de análises estatísticas e de testes de hipóteses, buscamos entender como a participação desses atores afeta diferentes aspectos das produções, como duração, classificação etária, avaliações e a relação entre as notas da crítica e do público.

### Objetivo
Explorar e responder as seguintes questões-chave:
1. Há uma correlação entre a presença de atores em comum e as avaliações dos filmes?
2. Existe uma tendência em relação ao público-alvo dos filmes com esses atores?
3. Filmes com atores recorrentes apresentam uma maior duração média?
4. Os filmes com atores em comum apresentam uma variação significativa nas avaliações entre crítica e público?

### Ferramentas e Conjuntos de Dados Utilizados
- **Linguagem**: Python
- **Bibliotecas**: `pandas`, `numpy`, `matplotlib`, `seaborn`, `scipy.stats`
- **Conjuntos de Dados**:
  - [Netflix Shows](https://www.kaggle.com/datasets/shivamb/netflix-shows)
  - [IMDb Movies](https://www.kaggle.com/datasets/ashpalsingh1525/imdb-movies-dataset)
  - [Rotten Tomatoes](https://www.kaggle.com/datasets/stefanoleone992/rotten-tomatoes-movies-and-critic-reviews-dataset/data)

## Resultados e Conclusões
- **Avaliações**: Não há uma correlação significativa entre a presença de atores em comum e as notas dos filmes.
- **Classificação Etária**: A maioria das produções com atores em comum é destinada a um público adulto, com predominância de classificações "R", "PG-13" e "TV-MA".
- **Duração**: Filmes e séries com atores em comum tendem a ser mais longos do que aqueles sem esses atores, sugerindo uma associação com produções mais elaboradas.
- **Variação nas Avaliações**: Existe uma diferença significativa na variação das avaliações entre filmes com e sem atores em comum. Filmes com atores recorrentes mostram menor variação entre crítica e público, indicando uma consistência nas expectativas.

## Estrutura do Projeto
O projeto está estruturado em um notebook que contém:
1. Introdução e definição do problema.
2. Coleta e pré-processamento dos dados.
3. Análises exploratórias e estatísticas.
4. Testes de hipótese para responder às perguntas do projeto.
5. Visualizações para apresentar as conclusões de forma clara.

## Como Executar o Projeto
1. Clone este repositório para o seu ambiente local.
2. Certifique-se de ter o Python e as bibliotecas necessárias instaladas (`pandas`, `numpy`, `matplotlib`, `seaborn`, `scipy`).
3. Execute o notebook Jupyter para visualizar as análises e gráficos.
4. Os datasets utilizados devem estar disponíveis no mesmo diretório do notebook para garantir a correta execução do código.

## Conclusão
Este projeto forneceu insights valiosos sobre o impacto dos atores recorrentes em múltiplas plataformas cinematográficas. Os resultados mostraram que, embora a presença desses atores não esteja diretamente associada a avaliações mais altas, ela influencia outros aspectos, como duração e variação nas avaliações, refletindo a complexidade da percepção das produções cinematográficas no mercado atual.
