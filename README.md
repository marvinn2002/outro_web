Autor: Marcus Vinícius Caruso Leite

Link do site em funcionamento: https://vitto-filmes.herokuapp.com/

Esse é o meu projeto final para o curso de extensão HackoonSpace na UFSCar de Sorocaba: Vitto!

<h1>Introdução</h1>

Um sistema de assistente pessoal que faz recomendação de filmes de acordo com a sugestões de pistas de vontade para assistir, executando uma pesquisa dentro de um banco de dados de mais de 400 mil filmes para encontrar a produção melhor enquadrada as pistas entregues.


<h2>O Sistema</h2>

Página da aplicação mostrando o filme com a nota, sinopse e título

O sistema foi feito como uma aplicação web que engloba tanto o back-end quanto o front-end, usando PHP com uma API de banco de dados de filmes chamada "The Movie Database" (TMDb). Além disso, implementei animações e recursos estáticos com HTML, CSS, Javascript, JQuery e fiz requisições assíncronas do algoritmo back-end por meio de Ajax.

O algoritmo executa um tratamento de textos com espaçamentos, vírgulas e caracteres de separação para formar, em cada palavra, uma pesquisa dentro da database da API e retornar o ID de tipo de filme.

Todo o programa feito em PHP utiliza o cURL como ferramenta e organiza a engine de pesquisa por meio de ID associada a cada espaço preenchido:

    Gênero
    Tipo
    Elenco
    Duração
    Época