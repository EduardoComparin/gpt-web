# Projeto Web

## Descrição
Este é um projeto web criado com React. O projeto possui as seguintes dependências:

- **@testing-library/jest-dom:** ^5.17.0
- **@testing-library/react:** ^13.4.0
- **@testing-library/user-event:** ^13.5.0
- **axios:** ^1.6.2
- **react:** ^18.2.0
- **react-dom:** ^18.2.0
- **react-scripts:** 5.0.1
- **web-vitals:** ^2.1.4

## Scripts

- **start:** `react-scripts start`
  Inicia o aplicativo no modo de desenvolvimento.

- **build:** `react-scripts build`
  Constrói o aplicativo para produção na pasta `build`.

- **test:** `react-scripts test`
  Inicia o executor de testes no modo de observação interativo.

- **eject:** `react-scripts eject`
  Remove a dependência única de construção do seu projeto.

## Configuração ESLint

O projeto utiliza as configurações ESLint com as extensões:

- "react-app"
- "react-app/jest"

## Browsers Compatíveis

O projeto é compatível com os seguintes navegadores:

### Produção

- `>0.2%`
- `not dead`
- `not op_mini all`

### Desenvolvimento

- Última versão do Chrome
- Última versão do Firefox
- Última versão do Safari

## Ignorando Arquivos

O projeto está configurado para ignorar arquivos e pastas comuns que não devem ser versionados. Certifique-se de não adicionar esses arquivos ao controle de versão:

- `node_modules/`
- `build/`
- `.env`
- `package-lock.json`
- `yarn.lock`
- `logs/`
- `.vscode/`
- `.idea/`
- `.DS_Store`
- `Thumbs.db`
- `*.bak`, `*.backup`, `*.swp`, `*.tmp`
- `.env.local`, `.env.development.local`, `.env.test.local`, `.env.production.local`
- `npm-debug.log`, `yarn-error.log`
