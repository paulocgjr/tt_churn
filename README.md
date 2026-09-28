## Descrição do projeto
Os clientes do Beta Bank estão saindo: pouco a pouco, escapulindo todo mês. Os banqueiros descobriram que é mais barato manter os clientes existentes do que atrair novos.

Precisamos prever se um cliente vai deixar o banco em breve. Você tem os dados sobre o comportamento passado dos clientes e rescisões de contratos com o banco.

Construa um modelo com o valor máximo possível de F1. Para passar na revisão, você precisa de um F1-score de pelo menos 0,59 para o conjunto de dados de teste. 

Além disso, meça a métrica AUC-ROC e compare-a com o F1-score.

## Instruções do projeto
- Baixe e prepare os dados. 
- Certifique-se de explicar a lógica que você segue durante a preparação.
- Examine o equilíbrio das classes. 
- Treine o modelo sem levar em conta o desequilíbrio.
- Descreva brevemente suas descobertas.
- Melhore a qualidade do modelo. 
- Certifique-se de usar pelo menos duas abordagens para corrigir o desequilíbrio de classe. 
- Use conjuntos de treinamento e validação para encontrar o melhor modelo e o melhor conjunto de parâmetros. 
- Descreva brevemente suas descobertas.
- Realize o teste final.

## Descrição de dados
Os dados podem ser encontrados no arquivo ```Churn.csv```. Faça o download do conjunto de dados.

**Características**

- ```RowNumber``` — índice das strings de dados
- ```CustomerId``` — identificador exclusivo do cliente
- ```Surname``` — sobrenome
- ```CreditScore``` — pontuação de crédito
- ```Geography``` — país de residência
- ```Gender``` — gênero
- ```Age``` — idade
- ```Tenure``` — período de maturação para o depósito fixo de um cliente (anos)
- ```Balance``` — saldo da conta
- ```NumOfProducts``` — número de produtos bancários usados pelo cliente
- ```HasCrCard``` — cliente possui cartão de crédito (1 - sim; 0 - não)
- ```IsActiveMember``` — cliente ativo (1 - sim; 0 - não)
- ```EstimatedSalary``` — salário estimado

**Objetivo**
- ```Exited``` — o cliente saiu (1 - sim; 0 - não)
Avaliação do projeto
Reunimos os critérios de avaliação do projeto. Leia com atenção antes de passar para a tarefa.
