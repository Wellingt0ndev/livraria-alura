<h1 align="center"> Projeto feito no curso da Alura : API Rest com Express e MongoDB </h1>

Nesse projeto criamos uma API de uma livraria para adicionar, remover, consultar livros, onde todos os dados dos livros ficam salvos no MOngoDB 


# 🛠️ Abrir e rodar o projeto

Após baixar o projeto, você pode abrir com o Visual Studio Code e instalar os seguintes itens:

Instale a biblioteca chamada Nodemon para fazer um live reload
```npm install nodemon@2.0.15 -D```

O '-D' significa que é uma dependência de desenvolvimento

Foi adicionado no script do package.json
 ```"dev": "nodemon server.js"``` 
Para iniciar use no terminal 
```npm run dev```

instale o mongoose
```npm install mongoose@6.2.6```

instale o dotenv para deixar o arquivo de conexão mais seguro, 
```npm install dotenv@16.0.3```
Olhe o arquivo exemplo.env para fazer a conexão com o banco de dados e configure o .env com seus dados

iniciei o ESLint no projeto
```npm init @eslint/config```

Para aplicar a formatação
```npx eslint ./src --fix```

instale o plugin de autopopulate do mongoose
```npm install mongoose-autopopulate```

