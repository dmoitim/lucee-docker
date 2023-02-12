# lucee-docker
Cria uma imagem docker com o Lucee e as extensões de Administração e Driver Oracle

Para gerar a imagem, execute o comando:  
`docker build -t lucee-docker .`

Para "subir" o container, execute o comando:  
`docker run --rm --name lucee-light -p 8888:8888 lucee-docker`

Feito isso, basta acessar o endereço http://localhost:8888 pelo navegador.

O administrador está acessível pelo endereço, http://localhost:8888/lucee/admin/server.cfm.


Referência: https://markdrew.io/