# Descrição do projeto

No mundo das vendas, seja de produtos ou serviços, as vendas não são constantes; elas variam e muitas vezes causam prejuízo no negócio. Por exemplo, montar um estoque enorme de produtos e as vendas caírem, ou, pelo contrário, achar que a demanda para aquele determinado período será baixa e não ter como atender a um alto volume de serviço ou venda. Em econometria, estatística e matemática aplicada, existe o estudo das Séries Temporais, que é justamente uma coleção de observações feitas sequencialmente ao longo do tempo.

Nesse projeto, utilizei uma base de dados de um aplicativo de táxi próximo a um aeroporto, com pedidos de táxis a cada hora, para ajudar o aplicativo a atender a demanda nesse local. É necessário saber quais os horários com mais pedidos, assim ele pode enviar mais motoristas para o local nos horários em que a demanda é alta.

Realizei uma análise exploratória e observei que existe um crescimento de pedidos ao longo dos meses. Também percebi que existe sazonalidade nos pedidos, onde há um pico de pedidos muito alto à meia-noite e uma demanda alta depois do meio-dia até aproximadamente às cinco horas da tarde.

Depois de entender o comportamento dos dados, foi hora de treinar um modelo de *machine learning* para prever a demanda por hora. Para fazer as previsões, utilizei a média móvel de 7 dias e lags de 6 dias para criar novas características que foram utilizadas no treinamento dos modelos. Utilizei 4 modelos diferentes, sendo que o que obteve o melhor desempenho foi o CatBoost, que obteve `44,32` de erro quadrático médio (métrica escolhida para avaliar o desempenho).

Gostei muito de trabalhar nesse projeto e me interessei bastante por Séries Temporais. Pretendo continuar estudando e me aprofundar ainda mais nessa área.
