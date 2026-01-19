Este projeto tem como objetivo analisar e compreender os principais fatores que levam ao cancelamento de serviços em uma empresa, utilizando técnicas de Análise Exploratória de Dados.

Os insights gerados visam apoiar decisões estratégicas, auxiliando a empresa na redução da taxa de cancelamento e melhoria da retenção de clientes.

* Observação: Os dados utilizados neste projeto são fictícios e foram criados para fins de estudo e prática.


### METODOLOGIA: 

Passo 1: Exploração de dados - vizualizando a base de dados e suas informações

Passo 2: Tratamento e limpeza - retirando informações inúteis para essa análise

Passo 3: Análise numérica - agrupando os clientes por tempo de assinatura e média

Passo 4: Análise gráfica - usando histograma que relaciona uma coluna da tabela com a coluna "cancelou"

Passo 5: Filtro - selecionando por condições, para redução dos números de cancelamento 


### RESULTADOS:

Durante a análise, foram identificados grupos com maior propensão ao cancelamento, como pode ser observado a baixo:

 - Contratos mensais:
Apresentam o maior índice de cancelamento, configurando um alerta crítico.

 - Clientes com atraso superior a 20 dias: vale a pena ficar atento para atrasos a partir de 15 dias. 

 - Clientes com mais de 50 anos: Indica a necessidade de estratégias para atração e retenção desse público.

 - Clientes que realizaram muitas ligações ao call center:Mais de 3 ligações já representa um alerta. Acima de 5 ligações, o risco de cancelamento é extremamente elevado, indicando possíveis falhas no atendimento ou problemas com o serviço.

 
### EVOLUÇÃO DA TAXA DE CANCELAMENTO

A análise e o tratamento dos dados permitiram uma redução progressiva da taxa de cancelamento:

* Situação inicial: 56,79% de cancelamento

* Após o primeiro tratamento dos dados : 46,14%

* Após análise gráfica: 12,33%

### FERRAMENTAS UTILIZADAS:

* Python
* Pandas
* Plotly
* Matplotlib
* Jupyter Notebook
* VS Code

### CONCLUSÃO

Este projeto demonstra como a Análise Exploratória de Dados pode ser aplicada para detectar padrões de comportamento, identificar riscos e apoiar decisões baseadas em dados.
