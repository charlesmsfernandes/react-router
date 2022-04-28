### `json-server --watch db.json --port 5000`

Inicia o json server q vai mockar o retorno de uma api
Caso seja exibido uma mensagem de erro como essa:

```
json-server: comando não encontrado
```
Então é preciso instalar o json server globalmente

`npm install -g json-server`

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.\
You will also see any lint errors in the console.

### Aula 1

* - Configuramos rotas para componentes diversos utilizando condições com if.
* - Vimos o problema de se utilizar as condições if para a navegação de componentes.
* - Melhoramos o código com a biblioteca do React Router e deixamos a responsabilidade de direcionar os componentes com ela.

### Aula 2

* - Criamos um componente 404 para quando a pessoa tentar acessar alguma página que não existe.
* - Vimos a diferença entre uma SPA (Single Page Application) e um MPA (Multi Pages Application).
* - Montamos a navbar utilizando o React Router para simular uma MPA (Multi Pages Application).

### Aula 3

* - Mudamos a tag <a> do html para que o React consiga entender utilizando o Link ;
* - Utilizamos a biblioteca axios para fazer requisições no servidor para buscar artigos;
* - Fizemos uma requisição de um artigo específico passando o id do curso, utilizando o useEffect.