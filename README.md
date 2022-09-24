# automacaoindicadores
Projeto de Automação de Indicadores elaborado e desenvolvido ao longo do Curso Python Impressionador, ministrado pela Hashtag Treinamentos. Consiste desde o cálculo de indicadores a partir de uma base em Excel, manipulação de pastas e arquivos dentro do computador, e disparo de e-mail contendo os principais indicadores de cada uma das lojas (fictícias).

- A situação-desafio que foi proposta para a elaboração deste projeto foi:
"Imagine que você trabalha em uma grande rede de lojas de roupa com 25 lojas espalhadas por todo o Brasil.

Todo dia, pela manhã, a equipe de análise de dados calcula os chamados One Pages e envia para o gerente de cada loja o OnePage da sua loja, bem como todas as informações usadas no cálculo dos indicadores.

Um One Page é um resumo muito simples e direto ao ponto, usado pela equipe de gerência de loja para saber os principais indicadores de cada loja e permitir em 1 página (daí o nome OnePage) tanto a comparação entre diferentes lojas, quanto quais indicadores aquela loja conseguiu cumprir naquele dia ou não.

![image](https://user-images.githubusercontent.com/71049963/192113210-b1150ea4-66fd-4d43-b0f2-ffac40c0acf0.png)

O seu papel, como Analista de Dados, é conseguir criar um processo da forma mais automática possível para calcular o OnePage de cada loja e enviar um email para o gerente de cada loja com o seu OnePage no corpo do e-mail e também o arquivo completo com os dados da sua respectiva loja em anexo.

Ex: O e-mail a ser enviado para o Gerente da Loja A deve ser como exemplo

![image](https://user-images.githubusercontent.com/71049963/192113219-b2e4491e-94da-454d-8f4e-fef4ed7999c8.png)

Arquivos e Informações Importantes
Arquivo Emails.xlsx com o nome, a loja e o e-mail de cada gerente.

Arquivo Vendas.xlsx com as vendas de todas as lojas. Obs: Cada gerente só deve receber o OnePage e um arquivo em excel em anexo com as vendas da sua loja. As informações de outra loja não devem ser enviados ao gerente que não é daquela loja.

Arquivo Lojas.csv com o nome de cada Loja

Ao final, sua rotina deve enviar ainda um e-mail para a diretoria (informações também estão no arquivo Emails.xlsx) com 2 rankings das lojas em anexo, 1 ranking do dia e outro ranking anual. Além disso, no corpo do e-mail, deve ressaltar qual foi a melhor e a pior loja do dia e também a melhor e pior loja do ano. O ranking de uma loja é dado pelo faturamento da loja.

As planilhas de cada loja devem ser salvas dentro da pasta da loja com a data da planilha, a fim de criar um histórico de backup

Indicadores do OnePage
Faturamento -> Meta Ano: 1.650.000 / Meta Dia: 1000
Diversidade de Produtos (quantos produtos diferentes foram vendidos naquele período) -> Meta Ano: 120 / Meta Dia: 4
Ticket Médio por Venda -> Meta Ano: 500 / Meta Dia: 500
Obs: Cada indicador deve ser calculado no dia e no ano. O indicador do dia deve ser o do último dia disponível na planilha de Vendas (a data mais recente)
