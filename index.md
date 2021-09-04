## NODE JS

1 - O que e o NodeJS ?
 - Node e uma Plataforma para a exucucao do JavaScript no lado do servidor.

Para que o JavaScript funcione corretamente, ele precisa de um motor de interpletacao, esse motor de interpletacao do js, ele vai imbutido dentro do browser. como Chrome FireFox Edger.

 - Chrome - Motor -> V8
 - FireFox - Motor -> SpiderMonkey
 - Edger - MOtor -> ChacraCore

Eles que sao responsaveis por interpletar o JS e executa-lo, os Motores geralmente sao escrito em C++

O criador do NOdeJs, se chama *Ryam Dahl*, ele pegou o V8, qeu ja estava dentro do Chrome, e trouxe ele fora, e conseguiu fazer processar o JavaScript em outro contexto.
Isso porque Ryan Dahl, estava procurando uma linguagem que trabalha-se no lado do servidor, quem nao tivesse, uma conexao broqueante.

Obs: o JavaScript e Single-thread, uma unica via de conexao, e nao broqueante, ou seja, ele consegue trabalhar com varias conexoes simultaneamente.


O javaScript e basiado em contexto :
 
- Client/Server
   
   - do lado do Cliente, temos a API no browser a DOM, que podemos manipular, por exemplo : o mouse, teclado, eventos etc..

   - ja no Nodejs, do lado do Servidor Server, temos a malipulacao de arquivos e pastas com a API de fileSistem por exemplo.


   - Como e Estruturado o NodeJs

  **Core Concepts**
  - Conexao nao broqueante, events loops, times etc..

  **API Nativos**
  - exemplo : fileSistem, Http, Criptografia, Path, como ja diz, Modulos nativos do Node
    
  **API Exterrnos**
  - Tudo que instalamos como depedencias em nossos projetos, chamamos de APIs de Terceiros existe um repositorio publico, onde podemos encontrar todos esses modulos, chamado NPM. ele e um gerenciador padrao de pacotes do Nodejs. na verdade ele nao e do node, mas e uma startup, mas ele vem imbutido no node.   

### NPM  
Node Package Manage

 O NPM. **NAO** foi criado pelo Node, NPM e um projeto a parte, mas que ja vem imbutido, quando vc instala o Node.
 NPM, e um gerenciador de pacotes, um repositorio publico, hj uma startup.

- O Node instala Modulos de terceiros em seu projeto
```
npm install -g bootstrap
```

### Yarn
Tambem e um repositorio de pacotes

```
yarn add global bootstrap
```