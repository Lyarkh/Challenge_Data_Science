 # Challenge Alura Voz
 ---
 
 ## Resumo sobre o challenge

Você foi contratado(a) como cientista de dados pela operadora de telecomunicações Alura Voz. Na reunião inicial com as pessoas responsáveis pela área de vendas da empresa, foi explicada a importância de se reduzir a Taxa de Evasão de Clientes, conhecido como Churn Rate. Basicamente, o Churn Rate indica o quanto a empresa perdeu de receita ou clientes em um período de tempo.

Com sua experiência, você sugere, como passo inicial, a identificação de clientes que teriam uma maior chance de deixar a empresa. Para isso, você explica que é interessante investigar algumas características de clientes ou dos planos de clientes para tentar CLASSIFICAR estas pessoas como potenciais candidatas a deixar a empresa ou não.

Assim, você solicita o conjunto de dados para começar a explorar, tratar e modelar a partir de agora. Em seguida, o foco será na otimização de cada um dos modelos com a finalidade de obter o melhor resultado para a tomada de decisão da Alura Voz.

## Fonte de dados

Os dados estão em um formato não tão convencional, ja que vem de uma **API**. Já que as informações são de uma API, vem no formato JSON.

Os dados estão neste link : [Dados Alura-Voz](https://raw.githubusercontent.com/sthemonica/alura-voz/main/Dados/Telco-Customer-Churn.json)

Para vizualizar melhor os dados contidos no arquivo json, cole as informações no site de [JSON Viewer](http://jsonviewer.stack.hu)


## Informações sobre cada variável do dataset

> - `customerID` : Código de cada cliente
> - `Churn` : Métrica que indica o quanto de clientes a empresa perdeu

 #### Dados Relacionados ao `customer`
> - `gender` : Gênero do cliente (Masc. ou Femin.)
> - `SeniorCitizen` : Se o cliente é idoso (1/0 - True/False)
> - `Partner` : Coluna referente se o cliente possui um parceiro/parceira
> - `Dependents` : Caso seja dependente de outra pessoa
> - `tenure` : Tempo de permanência 

 #### Dados Relacionados ao `phone`
> - `PhoneService` : Se possui serviço de telefone
> - `MultipleLines` : Se possui múltiplas linhas telefônicas

 #### Dados Relacionados a `internet`
> - `InternetService` : Se possui serviço de internet
> - `OnlineSecurity` : Se assinou o adicional de segurança online
> - `OnlineBackup` : Se assinou o adicional de backup online
> - `DeviceProtection` : Se assinou o adicional de proteção do aparelho
> - `TechSupport` : Se assinou o suporte técnico
> - `StreamingTV` : Se assinou Tv a cabo
> - `StreamingMovies` : Caso tenha assinado Streaming de filnes

 #### Dados Relacionados a `account`
> - `Contract` : Tipo de contrato
> - `PaperlessBilling` : Se o cliente prefere receber online a fatura
> - `PaymentMethod` : Método escolhido para pagamento do contrato
> - `Charges.Monthly` : Gasto mensal de todos os serviços do cliente 
> - `Charges.Total` : Gasto total do cliente


## Semana 1 - Importando e tratando dados 

O objetivo da primeira semana foi importar e tratar as inconsistências da base de dados.
As colunas que tiveram inconsistência:

- `Churn`
- `SeniorCitizen`
- `Charges.Total`

## Semana 2 -
---
(🚧Em construção🚧)

## Semana 3 -
---
(🚧Em construção🚧)


## Semana 4 -
---
(🚧Em construção🚧)
