# API do Trabalho Prático de Node do IGTI

Cria API utilizando node.js

## Endpoints
 - /marcas/maisModelos <br> retorna a(s) marca(s) que possui(em) mais modelos]
 - /marcas/menosModelos <br> retorna a(s) marca(s) que possui(em) menos modelos
 - /marcas/listaMaisModelos/qtd <br> retorna uma lista das marcas com mais modelos, essa lista terá o tamanho correspondente ao passado em qtd
 - /marcas/listaMenosModelos/qtd <br> retorna uma lista das marcas com menos modelos, essa lista terá o tamanho correspondente ao passado em qtd
 - /marcas/listaModelos <br> retorna os modelos na marca passada no body. <br> Exemplo: <br> {"nomeMarca": "Hummer"}
 

### Dependências:

Dentro da pasta do projeto, instalar:
 - Dependências do node.js
 
 npm install
 
 - Módulo express
 
 npm install express



