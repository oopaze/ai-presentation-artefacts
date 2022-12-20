## Big data and Machine Learning
- Machine Learning: Algoritmos capazes de fazer com que a máquina evolua por conta própria.
- Big Data: Refere-se ao montante de dados que geramos atualmente.
- O dado só útil quando este pode ser analisado, correlacionado e transformado em ações efetivas.
- Com grandes escalas de dados podemos criar modelos preditivos muito mais precisos e relevantes.

## Aprendizado de Máquina supervisado
- Data bem definida e bem representada
- Pode ser definida em dois tipos: `Regressão` e `Classificação`

## Predição por Regressão
- O modelo tenta achar um padrão entre os dados e o resultado
    - Ex.: [Qual preço do imóvel?](./regression.example.md)

## Predição por Classificação
- O modelo separa os dados em categoria e tenta achar a categoria de cada dado.
    - Ex.: [Este email é um spam?](./classification.example.md)

## Apredizado de Máquina não supervisionado
- Data com pouca definição e geralmente composta por aleatoriedades
- Os dados geralmente são diferentes em estrutura:
    - Ex.: Uma compra que pode ter 10 produtos ou somente 1
- Se divide em 2 tipos: `Clusterização` e `Associação` 

## Predição por Associação
- Com algoritmos de associação se analisa a base de dados afim de achar relações entre os dados.
    - Ex.: Sistema de recomendação de produtos com base em suas compras
- Apriori Algorítmo

## Algoritmo Apriori
- Algortimo de Mineração 
- Utilizado em bases de dados com pouca definição e geralmente composta por aleatoriedades
- Usado para criar regras de associação
- Baseado em 3 conceitos: `Support`, `Confidence` e `Lift`

## O que é support", "confidence" e "lift"?
- Support: Frequencia de Items aparecendo a cada transação
- Confidence: Frequencia da Relação aparecendo por cada transação
- Lift: Define a força da relação
    - lift > 1 : Produtos são relacionados (Quanto maior o Lift, mais forte a relação);
    - lift < 1 : Produtos estão negativamente relacionados, ou seja, pessoas não gostam de comprá-los juntos.
    - lift = 1 : Produtos não tem relação

## Demonstração do Algoritmo Apriori
