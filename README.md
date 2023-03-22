## Chat GPT via API da OpenAI


Este é um projeto desenvolvido em .NET Core 6 que utiliza a API da OpenAI para realizar conversas com o modelo GPT diretamente pelo terminal. Além disso, quando a palavra "imagem" é incluída no início da pergunta, o programa também é capaz de gerar uma imagem relacionada à pergunta.

#Como usar
Para utilizar o programa, basta clonar o repositório e executar o código de acordo com a sua IDE
Ao executar o programa, você será apresentado com um prompt onde pode fazer perguntas. O modelo GPT irá gerar respostas com base no contexto da sua pergunta ou frase.

Caso você queira gerar uma imagem relacionada à pergunta, basta incluir a palavra "imagem" no início da pergunta. O programa irá então utilizar a API da OpenAI para gerar uma imagem e disponibilizar a URL para acesso via browser.

#Configuração
Antes de executar o programa, é necessário configurar a sua API.
Para isso, abra o arquivo e vá até a linha 4, onde esta *string apiKey = "Chave_API_aqui";*

Substitua Chave_API_aqui pela sua chave de API da OpenAI.

Referências
Este projeto foi desenvolvido com base na documentação oficial da OpenAI API: https://beta.openai.com/docs/api-reference/introduction