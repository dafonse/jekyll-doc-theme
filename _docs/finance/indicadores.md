---
title: Indicadores
module:
permalink: /docs/finance/indicadores/
redirect_from: /finance/
categories: uncategorized
tags:
---

### TR (Taxa Referencial)

É uma taxa de juros da economia brasileira, sendo divulgada nos principais portais econômicos em valores diários, mensais e histórico anual. O valor da TR é de responsabilidade do Banco Central do Brasil (BACEN). Este órgão realiza uma pesquisa com os 30 maiores bancos do país, analisando as taxas de juros dos CDBs.O valor desta pesquisa diária foi nomeada TBF (Taxa Básica Financeira). Para encontrar a taxa TR será preciso calcular o valor R. Para isso, a fórmula utilizada é:

$$R=a+b*TBF$$

Onde:

    R: é o redutor
    a: valor fixo igual a 1,005 (valor definido na criação da TR)
    b: depende do valor da TBF e é divulgado pelo Banco Central
    TBF: tarifa básica financeira divulgada pelo Banco Central

Com o valor de $$R$$, substitua os valores na fórmula abaixo e encontre o valor da TR:

$$TR=100x[((1+TBF)/R)-1]$$

O valor da TR nunca é negativo. Ou seja, o seu valor mínimo será igual a zero.

https://www.tororadar.com.br/investimento/taxa-referencial-o-que-e-tr-mensal-calculo
