Trabalho 2 - Banco de Dados I 2017/2

2º Trabalho apresentado a disciplina de Banco de Dados 1 onde o objetivo do trabalho prático foi projetar e implementar um banco de dados sobre produtos vendidos em uma loja de comércio eletrônico, incluindo avaliações e comentários de usuários sobre estes produtos. O trabalho consistia na criação de um Banco de Dados Relacional contendo dados sobre compras de produtos e elaboração de um Dashboard, um painel para monitoramento dos dados de compra, gerando uma série de relatórios e gráficos. Os dados usados para o banco de dados foi o arquivo “Amazon product co-purchasing network metadata” que faz parte do Stanford Network Analysis Project (SNAP). Os dados foram coletados em 2006 do site Amazon e informações de produto e comentários de clientes sobre 548.552 produtos diferentes (livros, CDs de música, DVDs e fitas de vídeo VHS).

Como executar:

1) Carregamento dos dados:
 - Entre na pasta Parser
 - $sudo make
 - $./main [caminho_do_arquivo] [nome_database] [usuario] [senha] [endereço_host]

 Obs: Os dados são commitados depois de 20000 inserções
 Obs2: Os similares são inseridos depois de todas as inserções

2) Usando o Dashboard:
 - Entre na pasta Dashboard
 - $sudo make
 - $./main [nome_database] [usuario] [senha] [endereco_host]
