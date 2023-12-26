# Ajax
Facilitando o uso de requisições ajax para o servidor
Dentro do meu projeto, observei a repetição de várias requisições AJAX, levando-me a adotar a programação orientada a objetos.
Na instância da requisição, é necessário informar a rota POST (/ROTA/NO/SERVIDOR) e o objeto 'binds', caso deseje enviar informações no corpo da requisição.
O método 'RequisicaoAjax' requer apenas um parâmetro booleano que define se o resultado da requisição deve ser retornado como feedback ao usuário

