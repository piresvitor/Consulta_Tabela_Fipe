# Desafio


implementar uma aplicação para consultar o valor médio de veículos (carros, motos ou caminhões) de acordo com a tabela FIPE, que pode ser acessada através [desse site](https://veiculos.fipe.org.br/).


## Objetivos do projeto

- O objetivo do projeto é ter um fluxo similar ao que é feito no site, porém com algumas melhorias.
- Criaremos um projeto Spring com linha de comando, utilizando a classe Scanner para fazer interações com o usuário via terminal.
- Solicitaremos que o usuário digite o tipo de veículo desejado (carro, caminhão ou moto).
- Feito isso, listaremos todas as marcas daquele tipo de veículo, solicitando que o usuário escolha uma marca pelo código.
- Após essa escolha, listaremos todos os modelos de veículos daquela marca.
- Solicitaremos que o usuário digite um trecho do modelo que ele quer visualizar, por exemplo **PALIO**.
- Listaremos apenas os modelos que tiverem a palavra **PALIO** no nome.
- Usuário escolherá um modelo específico pelo código e, diferente do site, já listaremos as avaliações para **TODOS** os anos disponíveis daquele modelo, retornando uma lista de forma similar à imagem abaixo:


## Observações:

- Exibir em nossa aplicação as avaliações de todos os anos para esse modelo, será necessário trabalhar com as coleções e estruturas de repetição para poder exibir já todos as avaliações de todos os anos para o nosso usuário.
- Utilizar a biblioteca Jackson para a desserialização dos dados.
- Modelar as classes de acordo com o necessário para representar as marcas, modelos e dados dos veículos.
- Relembrar os conceitos vistos no curso para filtrar os modelos por um trecho do nome. 

