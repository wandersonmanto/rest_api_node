#### instalações
- express
- nodemon

#### testando API
 - insomnia
 https://insomnia.rest/download

 ### Primeiro servidor
 index_teste.js

 Feito para entender o uso do insomnia, conceito de endpoints e parametros.

 Usa dois endpoints GET com e sem parametros para exemplificar melhor as duas situações.

 ### Segundo servidor
 index.js

 - Usa o nodemon para restartar os serviços após alteração no código.

 npm run dev - para acionar o script

 - Retorna informações Json

 server.use(express.json());

 - Simula oo CRUD completo usando endpoints GET, POST, PUT e DELETE no padrão REST

