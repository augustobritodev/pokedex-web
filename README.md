<h1 align="center">
    Pokédex Web
</h1>

### 📝 Sobre

Projeto Web que consome dados da [API](https://github.com/augustobritodev/pokedex-doc) de Pokémons 

### 🧰 Dependências

Este projeto foi desenvolvido utilizando das seguintes dependências:

- [react](https://reactjs.org/)
- [material-ui](https://material-ui.com/getting-started/installation/)

### 💻 Inicializando o Projeto

Siga os passos a seguir para inicializar o projeto

- **Clonar**

  Clone o repositório para sua máquina local com o comando:

  ```shell
  git clone https://github.com/augustobritodev/pokedex-api.git
  ```

- **Instalar as Dependências**

  Agora você precisa usar o yarn para instalar as dependências necessárias.

  ```shell
  cd interview-mestres-web
  yarn
  ```

- **Variáveis de Ambiente**
  É necessário que você configure as variáveis no arquivo .env
  ```shell
  DATABASE_URL=
  SERVER_HOSTNAME=
  SERVER_PORT=
  ```

- **Executando**

  Para executar o projeto siga os passos:


  * Iniciar em Modo de Desenvolvimento
  ```shell
  cd interview-mestres-web

  yarn start:dev
  ```
  * Iniciar em Modo de Produção
  ```shell
  cd interview-mestres-web

  yarn start:prod
  ```
  * Efetuar a build
  ```shell
  cd interview-mestres-web

  yarn build
  ```

   * Tests, Lint e Style
  ```shell
  cd interview-mestres-web

  # Test usando Jest
  yarn test
  yarn test:watch
  yarn test:coverage

  # Lint
  yarn lint
  yarn lint:fix

  # Style
  yarn style
  yarn style:fix
  
  ```


  >   Acessar por [http://localhost:3000](http://localhost:3000)
  
  >   Ou [Netlify](https://pokedex-web-netlify.netlify.app)



