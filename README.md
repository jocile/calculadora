
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

## React Docs

A documentação oficial do React é um excelente recurso para aprender mais sobre a biblioteca e suas funcionalidades. Você pode acessá-la em [https://reactjs.org/docs/getting-started.html](https://reactjs.org/docs/getting-started.html).

Ela agrupa corretamente o React em modo de produção e otimiza a construção para o melhor desempenho.

A construção é minificada e os nomes dos arquivos incluem os hashes.\
Seu aplicativo está pronto para ser implantado!

Consulte a seção sobre [implantação](https://facebook.github.io/create-react-app/docs/deployment) para obter mais informações.

## Implantação no GitHub Pages

Para implantar uma aplicação React no GitHub Pages, siga estes passos:

1. Instale o `gh-pages`: Adicione `gh-pages` como uma dependência de desenvolvimento no seu projeto (`npm install gh-pages --save-dev`). 
2. Configure o `package.json`: Adicione a propriedade "homepage" com a URL do seu site (ex: `http://seu-usuario.github.io/nome-repo`) e configure os scripts "predeploy" e "deploy" para construir a aplicação e publicá-la. 
3. Execute o deploy: No terminal, rode o comando `npm run deploy`. 
4. Aguarde e verifique: O processo criará uma branch `gh-pages` e publicará seu aplicativo. O site ficará acessível após alguns minutos no endereço configurado. 

## Passo a Passo Detalhado

1. **Crie ou configure seu projeto React**: Se não tiver um projeto, crie um usando `npx create-react-app nome-do-app`. Certifique-se de que o repositório do seu projeto esteja no GitHub.
2. Instale a biblioteca `gh-pages`: Abra o terminal na pasta do seu projeto e execute: 

Código

```bash
    npm install gh-pages --save-dev
```

Isso adiciona a biblioteca como uma dependência para desenvolvimento. 

3. Configure o `package.json`: Abra o arquivo `package.json` no seu projeto e adicione ou modifique as seguintes linhas:
    - `homepage`: Defina a URL para o seu site no GitHub Pages.

Código

```json
        "homepage": "http://seu-usuario.github.io/nome-do-repositorio"
```

Substitua `seu-usuario` pelo seu nome de usuário no GitHub e `nome-do-repositorio` pelo nome do seu projeto. 

- `scripts`: Adicione os scripts `predeploy` e `deploy`.

Código

```json
"scripts": {
	"start": "react-scripts start",
	"build": "react-scripts build",
	"test": "react-scripts test",
	"eject": "react-scripts eject",
	"predeploy": "npm run build",
	"deploy": "gh-pages -d build"
}
```

4. **Execute o comando de deploy**: No terminal, dentro da pasta do seu projeto, execute:

Código

```bash
    npm run deploy
```

Este comando irá compilar sua aplicação e fazer um push para uma nova branch chamada `gh-pages`. 

5. **Verifique sua implantação**: Após a execução do comando, seu aplicativo deve estar ativo. O link para acessá-lo será o definido no campo `homepage` do seu `package.json`. Pode levar alguns minutos para o site aparecer. Você também pode ir nas configurações do seu repositório no GitHub e verificar a seção "GitHub Pages" para encontrar o link.

## Scripts Disponíveis

### `npm run build`

Compila a aplicação para produção na pasta `build`.

### `npm run eject`

**Cuidado:**
Esta ação é irreversível.

Se você não estiver satisfeito com a ferramenta de build e as escolhas de configuração, você pode `eject` a qualquer momento. Este comando removerá a única dependência de build do seu projeto.

Em vez disso, ele copiará todos os arquivos de configuração e as dependências transitivas (webpack, Babel, ESLint, etc) diretamente para o seu projeto, para que você tenha controle total sobre eles. Todos os comandos, exceto `eject`, ainda funcionarão, mas apontarão para os scripts copiados, para que você possa ajustá-los. Neste ponto, você está por conta própria.

Você não precisa usar o `eject`. O conjunto de recursos curados é adequado para implantações pequenas e médias, e você não deve se sentir obrigado a usar esse recurso. No entanto, entendemos que essa ferramenta não seria útil se você não pudesse personalizá-la quando estivesse pronto para isso.

## Saber mais

Você pode aprender mais na [documentação do Create React App](https://facebook.github.io/create-react-app/docs/getting-started).

Para aprender React, confira a [documentação do React](https://reactjs.org/).

### Code Splitting

Esta seção foi movida para cá: [https://facebook.github.io/create-react-app/docs/code-splitting](https://facebook.github.io/create-react-app/docs/code-splitting)

### Analyzing the Bundle Size

Esta seção foi movida para cá: [https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size](https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size)

### Making a Progressive Web App

Esta seção foi movida para cá: [https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app](https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app)

### Advanced Configuration

Esta seção foi movida para cá: [https://facebook.github.io/create-react-app/docs/advanced-configuration](https://facebook.github.io/create-react-app/docs/advanced-configuration)

### Deployment

Esta seção foi movida para cá: [https://facebook.github.io/create-react-app/docs/deployment](https://facebook.github.io/create-react-app/docs/deployment)

### `npm run build` fails to minify

Esta seção foi movida para cá: [https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify](https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify)
