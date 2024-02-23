# Análise Exploratória de Dados e Previsão de Preços de Apartamentos para Aluguel
Este projeto visa realizar uma análise exploratória dos dados disponíveis sobre apartamentos para aluguel em uma plataforma, além de desenvolver um modelo de previsão de preços. Vamos explorar as características dos dados, formular algumas hipóteses de negócio e responder a perguntas-chave sobre investimentos e padrões nos dados.

## Análise Exploratória de Dados (EDA)
Durante a EDA, investigamos as principais características das variáveis disponíveis nos dados. Isso inclui análise estatística descritiva, visualizações gráficas e identificação de correlações e padrões.

## Principais características entre as variáveis:
Preço: Distribuição dos preços de aluguel e sua relação com outras variáveis.
Localização: Análise geográfica dos apartamentos e sua influência nos preços.
Número mínimo de noites: Correlação com o preço e sazonalidade.
Disponibilidade ao longo do ano: Impacto nos preços e variação sazonal.
Texto do nome do local: Padrões linguísticos relacionados aos valores dos apartamentos.
Hipóteses de Negócio:
Localização influencia o preço: Bairros ou regiões mais centrais tendem a ter aluguéis mais caros.
Sazonalidade: Preços podem variar conforme a época do ano, influenciados pela disponibilidade e demanda.
Atributos dos apartamentos: Número mínimo de noites e características do imóvel podem afetar os preços.
Perguntas-chave
1. Onde seria mais indicada a compra de um apartamento para alugar na plataforma?
Para responder a esta pergunta, consideramos a análise de localização, preços médios e tendências de mercado.

2. O número mínimo de noites e a disponibilidade ao longo do ano interferem no preço?
Exploramos a correlação entre esses atributos e os preços de aluguel, buscando padrões sazonais e impactos na demanda.

3. Existe algum padrão no texto do nome do local para lugares de mais alto valor?
Analisamos os padrões linguísticos nos nomes dos locais para identificar possíveis relações com os preços dos apartamentos.

## Previsão de Preços
Desenvolvemos um modelo de previsão de preços com base nos dados disponíveis. Utilizamos técnicas de regressão para estimar os preços com base em diversas variáveis explicativas, como localização, características do imóvel e sazonalidade.

## Tipo de Problema:
Estamos resolvendo um problema de regressão, onde buscamos prever valores contínuos (preços dos aluguéis).

## Modelo Escolhido:
Exploramos diversos modelos de regressão, como regressão linear, regressão polinomial e modelos de árvore de decisão. Avaliamos os prós e contras de cada modelo em relação à capacidade de generalização e interpretabilidade.

## Medida de Performance:
Utilizamos métricas como o erro médio absoluto (MAE) ou o erro quadrático médio (MSE) para avaliar o desempenho do modelo. Escolhemos a métrica mais adequada com base na interpretabilidade e sensibilidade a outliers.

Este README fornece uma visão geral do projeto e dos processos envolvidos na análise exploratória e previsão de preços de apartamentos para aluguel. Para mais detalhes, consulte a documentação completa e os resultados da análise.

Como executar:
- python -m venv <nomedavenv>
- pip install -r requirements.txt
  Após isso pode executar o nootbook normalmente.
