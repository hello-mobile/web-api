# web-api
Api responsável por prover as informações dinâmicas do aplicativo e website hello-mobile

## Features:
GET: /api/v1/palestrantes
response: ID, nome, sobrenome e tópico.

GET: /api/v1/palestrante/{ID}
response: Nome, sobrenome, tópico, url de foto, site, descrição.

POST: /api/v1/contato
params: nome, email, mensagem.
