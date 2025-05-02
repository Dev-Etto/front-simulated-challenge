# Trybe News - Processo Seletivo Simulado

## Descrição do Projeto

Este projeto foi desenvolvido como parte de um desafio técnico durante o curso de Desenvolvimento Web da Trybe. O objetivo do projeto é criar uma aplicação frontend que consome uma API de notícias e exibe as informações de forma organizada e interativa. A aplicação é responsiva e utiliza componentes reutilizáveis para facilitar a manutenção e escalabilidade do código.

## Funcionalidades

- Exibição de notícias em destaque ("Break News").
- Listagem de notícias com paginação.
- Filtro de notícias por categorias.
- Botão para carregar mais notícias ou voltar ao topo.
- Indicador de carregamento enquanto os dados são buscados da API.

## Tecnologias Utilizadas

- **React**: Biblioteca para construção de interfaces de usuário. [Documentação](https://reactjs.org/)
- **TypeScript**: Superset do JavaScript que adiciona tipagem estática. [Documentação](https://www.typescriptlang.org/)
- **Vite**: Ferramenta de build rápida para projetos frontend. [Documentação](https://vitejs.dev/)
- **CSS**: Estilização da aplicação.

## Estrutura do Projeto

A estrutura do projeto está organizada da seguinte forma:

```
index.html
package.json
README.md
tsconfig.json
tsconfig.node.json
vite.config.ts
src/
  App.css
  App.tsx
  index.css
  main.tsx
  type.ts
  vite-env.d.ts
  components/
    BreakNews/
    Button/
    Footer/
    Header/
    Loading/
    MoreNews/
  context/
    NewsProvider.tsx
  images/
  service/
    fetchNews.ts
```

- **`components/`**: Contém os componentes reutilizáveis da aplicação.
- **`context/`**: Implementa o contexto para gerenciar o estado global da aplicação.
- **`service/`**: Contém funções para consumir a API de notícias.
- **`images/`**: Contém imagens utilizadas na aplicação.

## Como Executar o Projeto

1. Clone o repositório:
   ```bash
   git clone <URL_DO_REPOSITORIO>
   ```

2. Acesse o diretório do projeto:
   ```bash
   cd front-simulated-challenge
   ```

3. Instale as dependências:
   ```bash
   npm install
   ```

4. Inicie o servidor de desenvolvimento:
   ```bash
   npm run dev
   ```

5. Acesse a aplicação no navegador em `http://localhost:5173`.

## Scripts Disponíveis

- `npm run dev`: Inicia o servidor de desenvolvimento.
- `npm run build`: Gera a build de produção.
- `npm run preview`: Visualiza a build de produção localmente.
- `npm run lint`: Executa o linter para verificar problemas no código.

## API Utilizada

A aplicação consome dados da API pública do IBGE:
- [API de Notícias do IBGE](https://servicodados.ibge.gov.br/api/docs/noticias)

## Autor

Este projeto foi desenvolvido como parte do curso de Desenvolvimento Web da Trybe.

---

## Links Úteis

- [Documentação do React](https://reactjs.org/)
- [Documentação do TypeScript](https://www.typescriptlang.org/)
- [Documentação do Vite](https://vitejs.dev/)
- [Documentação da API do IBGE](https://servicodados.ibge.gov.br/api/docs/noticias)
