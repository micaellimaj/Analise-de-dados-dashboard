# Projeto análise de dados de filiais de mercado e Relatório no Power BI

O dataset utlizado nesse projeto nos traz dados a respeito de três filias de supermercados e suas respectivas cidades, e histórico de crescimento de vendas durante três meses. Com esses dados podemos fazer várias análises com com python e no power BI em relação ao desempenho das filiais, de modo a trazer melhorias para o negócio e entender os pontos fortes e fracos desse mercado, dentre vários insights.

O conjunto de dados utilizado pode ser encontrado no seguinte link:  https://www.kaggle.com/datasets/aungpyaeap/supermarket-sales

## Painel:

Para o desenvovimento desse relatório tivemos que passar por diversas fases de processamneto dos dados para deixá-lo no formato ideal para o power BI, além de termos trabalhado bastante no visual do relatório e de como iriamos apresentar as informações para a geração de insights. Segue abaixo o link para o relatório: https://bit.ly/Micael-Lima-Analista-de-dados-Relatorio-supermercados

## Tecnologias utilizadas:

* <img src="https://img.shields.io/badge/Python-000000?style=for-the-badge&logo=python&logoColor=yellow1" alt="icon python" > 
* <img src="https://img.shields.io/badge/Power_BI-000000?style=for-the-badge&logo=powerbi&logoColor=yellow" alt="icon power bi">
* <img src="https://img.shields.io/badge/Colab-F9AB00?style=for-the-badge&logo=googlecolab&color=525252" alt="icon colab">

## Atributos:

O conjunto de dados possui as seguintes colunas:

*   **Invoice id**: Número de identificação da fatura do comprovante de vendas gerado por computador;
*   **Branch**: Filial do supercentro (3 filiais estão disponíveis identificadas por A, B e C);
*   **City**: Localização dos supercentros;
*   **Customer type**: Tipo de cliente, cadastrado por Integrante para clientes com cartão de associado e Normal para sem cartão de associado;
*   **Gender**: Gênero tipo de cliente;
*   **Product line**: Grupos de categorização geral de itens - Acessórios eletrônicos, Acessórios de moda, Alimentos e bebidas, Saúde e beleza, Casa e estilo de vida, Esportes e viagens;
*   **Unit price**: Preço
de cada produto em $;
*   **Quantity**: Número de produtos adquiridos por cliente;
*   **Tax**: taxa de imposto de 5% para compra do cliente;
*   **Total**: Preço total incluindo impostos;
*   **Date**: Data da compra (registro disponível de janeiro de 2019 a março de 2019);
*   **Time**: Horário da compra (10h às 21h);
*   **Payment**: Pagamento utilizado pelo cliente para compra (3 métodos disponíveis - Dinheiro, Cartão de crédito e Ewallet);
*   **COGS**: Custo das mercadorias vendido;
*   **Gross margin percentage**: Porcentagem da margem bruta;
*   **Gross income**: Receita bruta;
*   **Rating**: Classificação de estratificação do cliente em sua experiência geral de compra (em uma escala de 1 a 10).

## Desenvolvimento:

Foram aplicadas diversas técnicas para o desenvolvimento desse projeto, tais como:

* Importação, exploração da base de dados trabalhada.
* Manipulação e transformação de dados para o formato desejado.
* Salvamento de dados após a transformação dos dados para seu uso no power BI
* Analises da distribuição dos dados e visualizações gráficas.
* Analises financeiras a respeito dos dados e entendimento do negócio.
* Desenvolvimento de um relatório financeiro no power BI.
* Realização de trabalho com design de layout do BI no Power point.
  
## Importações Python:


```
import math
from typing import Iterator
from datetime import datetime, timedelta
import matplotlib.pyplot as plt
import seaborn as sns
import numpy as np
import pandas as pd
from IPython.display import Image, display
import plotly.express as px
import seaborn.objects as so
```

## Organização do Projeto:
------------


    
    │
    ├── LICENSE
    │
    ├── README.md                 <- O Readme de nível superior para desenvolvedores que usam esse projeto.
    │
    ├── Personalização            <- Contém imagens utilizadas para deixar o caderno apresentável para o usuário.
    │
    ├── Relatórios                <- Coleção de capturas de tela sobre todo o processo de análise de dados no google colab.
    │
    ├── dashboard                 <- Contém imagens referente ao layot do relatório do power BI.
    │
    ├── Documentos                <- datasets utilizados no projeto.
    │  
    └── Notebook                  <- caderno jupyter notebook utilizado para contrução e apresentação do projeto
    



## Referências

* https://plotly.com/graphing-libraries/
* https://seaborn.pydata.org/index.html
* https://www.flaticon.com/
* https://www.youtube.com/@ItaloDiegoTeotonio
* https://br.freepik.com/
* https://ebaconline.com.br/

