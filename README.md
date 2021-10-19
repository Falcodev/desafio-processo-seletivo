# Desafio Processo Seletivo

Olá, aqui você encontra um template de um projeto VueJS quase vazio, e, a partir dele, você irá montar um projeto em um período de até 2 SEMANAS. Tal projeto foca no desenvolvimento frontend, e precisa estar totalmente responsivo.

## Descrição

Você deve montar um sistema simples de carrinho, Onde nele você terá 3 páginas:

- Página inicial -> Lista com produtos, onde, nessa página, deverá ter as seguintes funcionalidades:
  - Listagem de produtos com preços
  - Possibilidade de adicionar produtos ao carrinho
  - Botão para ir até o carrinho
- Carrinho -> Página onde você vê os produtos que estão adicionados, podendo remover produtos. Também possui um botão para finalizar a compra.
- Página de compra com sucesso ou erro -> Você não precisará implementar nenhum formulário de compra, então, depois que a compra for finalizada, se o valor da compra for maior que 70, a compra será um sucesso, senão, ela irá falhar, essa página deverá dar essa resposta ao cliente.

Além disso, o sistema deverá ter componentes comuns entre todas as páginas, sendo eles:

- Footer
- Header

Todo o sistema deve seguir um padrão de cores coerentes entre si, uma sugestão é criar uma [paleta de cores](https://coolors.co/).
Tanto no Footer quanto no Header, é necessário que haja alguma logo da aplicação, onde a escolha é livre.

## Produtos

Para a obtenção dos produtos, você irá fazer chamadas API para a PokeAPI, nela existe uma rota GET `https://pokeapi.co/api/v2/berry/{id}`, onde você irá passar ids de 1 até 20, para a obtenção de 20 tipos de frutas. Na resposta, apenas dois campos são importantes:

- O nome da fruta
- E o preço, que, nesse caso, será representado pelo campo `smoothness`.

Essas chamadas deverão ser feitas utilizando a biblioteca `axios`, que já está instalada no projeto.

## Requisitos

No projeto, você vê dois arquivos bem importantes, o `router.js`, é nele que você irá controlar as rotas. E o `state.js`, é nele que você controla os estados globais da aplicação. Esses dois conceitos são importantíssimos e por isso são necessários para que esse projeto se concretize.

## Documentações

[Vue](https://vuejs.org/v2/guide/#Getting-Started) <br/>
[Vue-Router](https://router.vuejs.org/guide/#html) <br/>
[Vuex](https://vuex.vuejs.org/guide/#the-simplest-store) (Controle de Estados) <br/>
[Axios](https://github.com/axios/axios)

## Para rodar esse projeto

1. Baixe esse repositório
2. Na pasta do template, rode um `npm install` para instalar as dependências
3. Para rodar o projeto, rode um `npm run serve`

## Considerações finais

Sinta-se livre para instalar bibliotecas que possam auxiliar. <br/>
Também sinta-se livre para mudar o CSS pré definido. <br/>
Esse projeto tem o objetivo de ensinar conceitos importantes do VueJs, mas também de como funciona a arquitetura dos projetos da empresa, então lembre que organização de código é fundamental para trabalhar em equipe. <br/>
Por último, caso precise de ajuda, estamos aqui para ajudar e tentar ao máximo sanar as dúvidas que podem ocorrer.
