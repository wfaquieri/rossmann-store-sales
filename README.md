# Previsão de Vendas para Rede Farmacêutica: A Ciência de Dados Impulsionando Resultados Financeiros

Em um mercado altamente competitivo, a previsão de vendas pode fazer a diferença entre o sucesso e o fracasso de uma empresa. Neste projeto, meu objetivo foi desenvolver um algoritmo de previsão de vendas para uma rede farmacêutica com mais de mil lojas. Além disso, o acesso a essa previsão deveria ser rápido e fácil, disponível 24 horas por dia, 7 dias por semana, por meio de um smartphone.

Para atender a esse desafio, criei um robô no aplicativo de mensagens Telegram. Esse robô recebe o código da loja, consulta o algoritmo via API e retorna em tempo real a previsão de vendas (faturamento) para as próximas 6 semanas. Isso possibilitou uma tomada de decisão mais assertiva por parte da equipe de gestão.

## Contextualização
A Rossmann, com mais de 4.000 lojas e 56 mil colaboradores em 2020, é uma das maiores redes de farmácias da Europa. Este projeto utiliza dados reais disponibilizados pela Rossmann, através do site Kaggle, em uma competição de ciência de dados. Foram utilizados 1.017.209 registros de vendas contendo 18 variáveis que detalham cada venda.

O contexto de negócios descrito é fictício, porém baseado em um problema real enfrentado por grandes varejistas: prever com precisão as vendas.

## Problema de negócio:
Durante uma reunião mensal de resultados da Rossmann, o CFO solicitou aos gerentes das lojas a previsão de vendas (faturamento) para as próximas seis semanas. Essa informação é fundamental para planejar a reforma da rede, que está padronizando suas lojas. No entanto, a previsão precisa ser precisa e rápida, o que pode ser um desafio em um mercado altamente competitivo.

## Premissas de negócio:
Para atender a essa demanda, é necessário que a previsão de vendas esteja disponível 24 horas por dia, sete dias por semana, e seja acessível por meio de dispositivos móveis. Dessa forma, a equipe de gestão pode tomar decisões mais assertivas e agir rapidamente para atender às demandas do mercado. Além disso, a precisão das previsões é fundamental para garantir que os recursos financeiros sejam utilizados de forma eficiente na padronização das lojas.

## Planejamento da solução

1. Produto final
O que será entregue efetivamente?

- Um bot (robô) no aplicativo de mensagens Telegram, que recebe o código da loja, e retorna em tempo real qual a sua previsão de vendas (faturamento) para as próximas 6 semanas.
- Protótipo validado pelo time de negócio: [Google Sheets](https://docs.google.com/spreadsheets/d/1_LKT5vWN0KoR2cQtfOHN9g63l1wHrCk49pb_rP3i5XA/edit#gid=0)

2. Tecnologias utilizadas
O projeto foi desenvolvido utilizando diversas ferramentas e tecnologias, incluindo:

- Python com os pacotes de Machine Learning: sklearn e scipy.
- Jupyter Notebook.
- Git e Github.
- Técnicas de seleção de atributos e redução de dimensionalidade.
- Heroku Cloud, Flask e Python API's.
- Algoritmos de Classificação e Regressão: Linear Regressor, Linear Regressor Regularized, Random Forest e XGBoost.

3. Estratégia de solução
Para solucionar este desafio, vou utilizar a metodologia CRISP-DS, seguindo os passos abaixo:

- Compreender claramente o modelo e o problema de negócios, por meio de estatística descritiva.
- Tratar os dados (formato, dados faltantes, outliers) e realizar limpeza.
- Levantar junto com a equipe de negócios quais são as características que impactam nas vendas. Formular e validar hipóteses para gerar insights de negócios.
- Preparar os dados para a criação do modelo de previsão de vendas, realizando transformações, separação dos dados entre treino e teste e seleção de características de forma automatizada.
- Treinar algoritmos de aprendizado de máquina (lineares e não lineares), comparar sua performance e selecionar o de melhor desempenho.
- Encontrar o conjunto de parâmetros que maximize o aprendizado do modelo selecionado, reduzindo o seu erro nas previsões.
- Interpretar o erro do modelo e traduzi-lo em resultados financeiros para a empresa.
- Avaliar se a previsão de vendas construída já entrega valor para a equipe de negócios e publicá-la em produção em caso positivo. Em caso negativo, realizar um novo ciclo de melhorias pontuais.
- Criar um bot no Telegram para acessar a previsão em tempo real de qualquer lugar.
- Apresentar e disponibilizar o bot do Telegram aos gerentes e CFO, detalhando o funcionamento do modelo e esclarecendo quaisquer dúvidas.


## Resultados
Após a implementação do projeto, a taxa média de erros nas previsões de vendas da rede foi reduzida de 36% para 4,65% em média, o que representa uma redução de 31%. Além disso, houve um aumento de 1,9% no lucro líquido semestral da Rossmann após o primeiro semestre da implantação do projeto.

Considerando o faturamento de 2020 de €10 bilhões, o projeto trouxe um resultado líquido semestral aproximado de €114 milhões.

## Como utilizar
Para utilizar a previsão de vendas, basta enviar o código da loja para o robô no aplicativo de mensagens Telegram e aguardar a resposta em tempo real.

## Autor
Este projeto foi desenvolvido por Winicius Faquieri, em janeiro de 2022. Ele demonstra o poder da ciência de dados em impulsionar resultados financeiros e traz uma solução inovadora e acessível para uma necessidade importante de uma grande rede farmacêutica.