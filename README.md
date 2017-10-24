# React Brasil Docs 
A idéia deste repositório é: Conter material traduzido para guiar o estudo de iniciantes no desenvolvimento com React

### Documentação Oficial

## Instalação
React é flexível e pode ser usado em uma variedade de projetos. Você pode criar novos apps com ele, mas você também pode inseri-lo gradualmente em um código base existente sem necessáriamente precisar fazer uma reescrita.

Aqui estão algumas maneiras de começar:

## Experimentando o React:
Se você está apenas interessado em dar uma olhada no React você pode usar o CodePen.

Tente começar por este exemplo estilo hello world, você não precisa instalar nada apenas  vá modificando o código e vendo se funciona.
Se você preferir usar o seu próprio editor de texto, você pode também baixar este arquivo HTML, abri-lo no seu navegador. Ele tem um atraso na execução devido a transformação de código então, não use em produção.

Se voc&e deseja usá-lo para uma aplicaçãp completa existem duas maneiras populares para começar: Usando o `create-react-app` ou adicionando o react a uma aplicação existente

## Criando um novo app
Create React App é a melhor maneira de começar a construir uma nova aplicaço single page React. Ele configura o seu ambiente de desenvolvimento ento voc pode usar as útlimas features do JavaScript. Prov uma boa experiência pro desenvolvedor e optimiza o seu aplicativo para produção. Você irá precisar ter o Npde >- 6 na sua máquina.

```
npm install -g create-react-app
create-react-app my-app

cd my-app
npm start
```

Caso você tenha o npm 5.2.0+ instalado você pode usar o `npx` no lugar do npm.
```
npx create-react-app my-app

cd my-app
npm start
```

Create React App não lida com lógica de backend ou databases; ele apenas cria um pipeline pra build frontend pré-configurado então você pode usar com o backend que quiser :). Ele usa build tools como o babel e o webpack por baixo do capô mas funciona sem nenhuma configuração adicional.

Quando você estiver pronto para subir o seu app pra produção rode o comando `npm run build`. Ele irá criar um build otimizado pro seu app na pasta `build`. Você pode saber mais sobre o Create React App a partir pro seu próprio readme and guia do usuário.

## Adicionando o React
[Tradução em andamento]
