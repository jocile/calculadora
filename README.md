
# Calculadora Simples com React

Este projeto demonstra como o React pode ser utilizado para criar uma calculadora simples, com operações básicas de soma, subtração, multiplicação e divisão.

## Por que usar React para uma calculadora?

O React facilita a criação de interfaces dinâmicas e reativas. Com ele, é possível atualizar a tela automaticamente sempre que o usuário interage com os botões da calculadora, sem precisar manipular o DOM manualmente.

## Como funciona a calculadora

- **Componentização:** Cada parte da calculadora (botão, display, layout) é um componente React reutilizável.
- **Estado:** O React gerencia os valores digitados, a operação selecionada e o resultado usando o hook `useState`.
- **Eventos:** As funções de clique dos botões atualizam o estado, que por sua vez atualiza a interface automaticamente.

## Estrutura dos arquivos

- `src/App.js`: Componente principal, onde está a lógica da calculadora.
- `src/components/Button`: Componente de botão reutilizável.
- `src/components/Input`: Componente de display da calculadora.
- `src/styles.js`: Estilos globais e de layout.

## Exemplo de funcionamento

1. O usuário digita um número clicando nos botões.
2. Ao clicar em uma operação (`+`, `-`, `x`, `/`), o número e a operação são armazenados no estado.
3. O usuário digita o próximo número.
4. Ao clicar em `=`, o resultado é calculado e exibido.

## Como executar

1. Instale as dependências:

```bash
npm install
```

1. Inicie o projeto:

```bash
npm start
```

1. Acesse [http://localhost:3000](http://localhost:3000) no navegador.

## Personalização

Você pode adicionar novas operações, melhorar o layout ou criar novas funcionalidades facilmente, aproveitando a modularidade dos componentes React.

---

**React** é uma ótima escolha para projetos interativos como uma calculadora, pois facilita a atualização da interface e a organização do código.
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`

**Note: this is a one-way operation. Once you `eject`, you can't go back!**

If you aren't satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you're on your own.

You don't have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn't feel obligated to use this feature. However we understand that this tool wouldn't be useful if you couldn't customize it when you are ready for it.

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).

### Code Splitting

This section has moved here: [https://facebook.github.io/create-react-app/docs/code-splitting](https://facebook.github.io/create-react-app/docs/code-splitting)

### Analyzing the Bundle Size

This section has moved here: [https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size](https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size)

### Making a Progressive Web App

This section has moved here: [https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app](https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app)

### Advanced Configuration

This section has moved here: [https://facebook.github.io/create-react-app/docs/advanced-configuration](https://facebook.github.io/create-react-app/docs/advanced-configuration)

### Deployment

This section has moved here: [https://facebook.github.io/create-react-app/docs/deployment](https://facebook.github.io/create-react-app/docs/deployment)

### `npm run build` fails to minify

This section has moved here: [https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify](https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify)
