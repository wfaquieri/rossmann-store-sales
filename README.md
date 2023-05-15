# Previsão de Vendas para Rede Farmacêutica: A Ciência de Dados Impulsionando Resultados Financeiros

Em um mercado altamente competitivo, a previsão de vendas pode fazer a diferença entre o sucesso e o fracasso de uma empresa. Neste projeto, meu objetivo foi desenvolver um algoritmo de previsão de vendas para uma rede farmacêutica com mais de mil lojas. Além disso, o acesso a essa previsão deveria ser rápido e fácil, disponível 24 horas por dia, 7 dias por semana, por meio de um smartphone.

Para atender a esse desafio, criei um robô no aplicativo de mensagens Telegram. Esse robô recebe o código da loja, consulta o algoritmo via API e retorna em tempo real a previsão de vendas (faturamento) para as próximas 6 semanas. Isso possibilitou uma tomada de decisão mais assertiva por parte da equipe de gestão.

## Contextualização:
A Rossmann, com mais de 4.000 lojas e 56 mil colaboradores em 2020, é uma das maiores redes de farmácias da Europa. Este projeto utiliza dados reais disponibilizados pela Rossmann, através do site Kaggle, em uma competição de ciência de dados. Foram utilizados 1.017.209 registros de vendas contendo 18 variáveis que detalham cada venda.

O contexto de negócios descrito é fictício, porém baseado em um problema real enfrentado por grandes varejistas: prever com precisão as vendas.

## Tecnologias utilizadas
O projeto foi desenvolvido utilizando diversas ferramentas e tecnologias, incluindo:

- Python com os pacotes de Machine Learning: sklearn e scipy
- Jupyter Notebook
- Git e Github
- Técnicas de seleção de atributos e redução de dimensionalidade
- Heroku Cloud, Flask e Python API's
- Algoritmos de Classificação e Regressão: Linear Regressor, Linear Regressor Regularized, Random Forest e XGBoost.

## Resultados
Após a implementação do projeto, a taxa média de erros nas previsões de vendas da rede foi reduzida de 36% para 4,65% em média, o que representa uma redução de 31%. Além disso, houve um aumento de 1,9% no lucro líquido semestral da Rossmann após o primeiro semestre da implantação do projeto.

Considerando o faturamento de 2020 de €10 bilhões, o projeto trouxe um resultado líquido semestral aproximado de €114 milhões.

## Como utilizar
Para utilizar a previsão de vendas, basta enviar o código da loja para o robô no aplicativo de mensagens Telegram e aguardar a resposta em tempo real.

## Autor
Este projeto foi desenvolvido por [seu nome aqui], em janeiro de 2022. Ele demonstra o poder da ciência de dados em impulsionar resultados financeiros e traz uma solução inovadora e acessível para uma necessidade importante de uma grande rede farmacêutica.