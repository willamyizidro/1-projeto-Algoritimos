Vamos construir um sistema de recomendações rudimentar. Um sistema de recomendações é a aplicação que fornece indicações de conteúdo para ser consumido em um serviço online, como por exemplo, streaming de filmes, músicas, vídeos em geral.

Para nosso sistema de recomendações, vamos considerar justamente um serviço de streaming de filmes temos a seguinte sequência de passos: 1- Solicitar a inclusão de um total de 10 filmes (no papel de operador do serviço); 2- Exibir os filmes ao usuário 1 e perguntar se ele assistiu cada um (no papel de usuário 1); 3- Exibir os filmes ao usuário 2 e perguntar se ele assistiu cada um (no papel de usuário 2); 4- Mostrar recomendações para o usuário 1: aqueles filmes que ele não assistiu, mas foram assistidos pelo usuário 2. 5- Mostrar recomendações para o usuário 2: aqueles filmes que ele não assistiu, mas foram assistidos pelo usuário 1.

Para estruturar as informações, usaremos: Lista de strings contendo os nomes dos filmes; Lista de booleanos contendo os filmes assistidos pelo usuário 1; Lista de booleanos contendo os filmes assistidos pelo usuário 2;