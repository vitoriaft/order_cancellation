## Predição de Cancelamento de Pedidos

Este projeto tem como objetivo prever o **cancelamento de pedidos** utilizando dados reais de operação logística brasileira. 


##  Sobre o Conjunto de Dados

O projeto utiliza um conjunto de dados realista inspirado na operação do Delivery Center, uma plataforma brasileira que integra lojistas, marketplaces e entregadores.  
O dataset representa pedidos feitos, incluindo informações de:

- Pedidos (`orders.csv`)
- Entregas (`deliveries.csv`)
- Lojas (`stores.csv`)
- Hubs operacionais (`hubs.csv`)
- Canais (`channels.csv`)
- Pagamentos (`payments.csv`)
- Entregadores (`drivers.csv`)

## Fluxograma do Projeto

```text
Importação dos Dados  →  Exploração  →  Tratamento  →  Junção das Tabelas  →  Criação do Target  →  
Seleção de Features  →  Split Treino/Teste  →  Treinamento  →  Avaliação  →  Exportação (.pkl)  →  Previsão

