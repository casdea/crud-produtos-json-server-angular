Crie o diretorio
   backend
   execute no prompt os seguintes comandos: 
       npm init -y
       npm i json-server@0.16.1 - meu node é 10
   crie o arquivo de banco de dados e coloque nele suas tabelas db.json
   no arquivo package.json na entrada scripts abra a seguinte entrada
     "start": "json-server --watch db.json --port 3001"

   para rodar o servidor node npm start
   agora pode fazer testes de api no endereço http://localhost:3001/products
   
                 