<p align="center">
   <img width="40%" src="https://user-images.githubusercontent.com/16653840/91781913-f9365080-ebd1-11ea-878c-5fdfb8b9e3f0.png" alt="Segunda next level week">
</p>

<p>
  O repositório compreende as atividades 
  aplicadas durante a segunda <strong>Next LeveWeek</strong>. 
  Evento online de programação realizado pela 
  Rocketseat, do qual apresenta ferramentas e 
  tecnologias que norteiam a stack do Javascript. 
  A categoria o qual participei chama-se 
  launchbase e foi ministrada pelo instrutor 
  Mayk Brito.
</p>

## <img width="4%" src="https://github.com/Heitor-Monteiro/nextlevelweek02/blob/master/nlw02/public/images/favicon.png?raw=true"> Tela inicial do Proffy

<p align="center">
   <img width="100%" 
   src="https://user-images.githubusercontent.com/16653840/90992294-17be9b00-e585-11ea-9750-b3601c18db59.png" alt="Imagem ilustrativa da tela inicial do Ecoleta.">
   <strong><small>Figura 1</small></strong>
</p>

A segunda NLW abordou o desenvolvimento da plataforma Proffy, aplicação web que visa reunir num catalogo, o contato de professores particulares interessados em ministrar aulas na modalidade EAD (ensino à distância). Sua interface inicial (figura 1) dispõem as funcionalidades "Dar aulas" (figura 2) e "Estudar" (figura 3).

## 👩‍🏫 Dar aulas

<p align="center">
   <img width="100%" 
   src="https://user-images.githubusercontent.com/16653840/91639529-98e6b980-e9ed-11ea-8b3a-270374d20c07.gif" alt="Imagem ilustrativa da tela inicial do Ecoleta.">
   <strong><small>Figura 2</small></strong>
</p>

A funcionalidade "Dar aulas" ilustrada na figura 2, compreende a tela o qual o(a) docente registrará seus dados de contato para ministrar aulas em EAD. O mesmo deve informar os seguintes campos cadastrais:

- ✏️ Campos para informar o nome e biografia do(a) docente;

- 🖼️ Campo para receber o link da foto de perfil;

- ☎️ Campo para receber o número atual do Whatsapp;

- 📕 Campo para selecionar qual matéria deseja ministrar EAD;

- 💵 Campo para informar o custo da hora/aula;

- 📆 Campo para informar os dias da semana, e horários disponíveis para EAD.

## 📚 Estudar

<p align="center">
   <img width="100%" 
   src="https://user-images.githubusercontent.com/16653840/91644549-66e84e00-ea13-11ea-86ec-371fb475ef88.gif" alt="Imagem ilustrativa da tela inicial do Ecoleta.">
   <strong><small>Figura 3</small></strong>
</p>

A figura 3 exemplifica o uso de funcionalidades da interface "Estudar", por meio dela o discente consulta na plataforma, o contado de docentes registrados na aplicação, para isso, aplicam-se os seguintes dados e passos para realizar a busca:

- 📌 Todos os campos devem ser informados para realizar a busca;

- 📝 Os campos a serem informados são a Matéria, dia da semana e horário;

- 📇 Ao aplica a filtragem, cada docente retornado na listagem será informado: nome; matéria o qual ensina; biografia; preço da hora aula e botão para contato.

- <img width="15" 
   src="https://user-images.githubusercontent.com/16653840/91775217-ebc49a80-ebc0-11ea-896d-a43c11dc3a83.png" alt=""> Ao clicar no botão "Entrar em contato", será redirecionado para iniciar uma conversa com o docente no whatsApp web.

### Tecnologias e ferramentas envolvidas

- **VScode:** editor de texto utilizado para escrever o código.

  - **Live Server:** extensão do vscode utilizado para monitorar modificações em arquivos HTML e CSS, para então atualizar o browser com tais modificações. O pluguim é utilizado quando o back-end não está implementado/configurado.

- **NodeJS 12.18.3:** ambiente de desenvolvimento e execução do back-end javascript.

  - **Express 4.17.1:** framework para criação de rotas da aplicação.

  - **Nunjucks 3.2.2:** templating engine utilizado para modularizar trechos de código da aplicação, e aplicar estruturas de repetição ou condicionais caso necessário.

  - **sqlite-async 1.1.0:** banco de dados relacional da aplicação. Observa-se que o armazenamento dos dados ocorre em um arquivo dentro da aplicação.

  - **Nodemon 2.0.4:** apos instalar o nodejs, o uso desta biblioteca serve para monitorar mudanças em arquivos do projeto, e aplicar o auto restart durante a execução. Observa-se que sua utilização ocorre durante a faze de construção do projeto, então, a mesma deve ser instalada como dependência de desenvolvimento com o comando: <code>npm install nodemon -D</code>.

## 🖥 Execução do projeto

- ⬇️ Faça o download do projeto, e guarde o diretório **"nlw02"** em local fácil de achar no seu computador.

- 👩‍💻 Abra o diretório **"nlw02"** com o terminal e execute o comando <code>npm install</code> para baixar as dependências do projeto.

- ▶️ Para executar a aplicação, use o camando <code>npm run dev</code> na pasta **"nlw02"**.

- 🔗 Abra o seu navegador, e digite a URL <code>localhost:5500</code> na barra de endereços.

## ✨ Agradecimentos

<table width="100%" border="0">
  <tr align=center>
    <td>
      <a>
        <img width="100" src="https://user-images.githubusercontent.com/16653840/91781749-77debe00-ebd1-11ea-842d-7fa2e20bc213.png">
      </a>
    </td>
    <td>
      <a href="https://rocketseat.com.br/">
        <img width="100" src="https://yt3.ggpht.com/a/AATXAJwSX58F1bJzQBZYiioJa36NuvznvNpsEVDfmc7qfg=s900-c-k-c0xffffffff-no-rj-mo">
      </a>
    </td>
    <td>
      <a href="https://github.com/diego3g">
        <img width="100" src="https://user-images.githubusercontent.com/38081852/83981712-b7f61380-a8f6-11ea-9099-bd3677e97e39.jpg">
      </a>
    </td>
    <td>
      <a href="https://github.com/maykbrito">
        <img width="100" src="https://user-images.githubusercontent.com/38081852/83981753-1de29b00-a8f7-11ea-93cf-23d2ff65fa5c.png">
      </a>
    </td>
  </tr>
  <tr align="center">
    <th><strong>NLW</strong></th>
    <th><strong>Rocketseat</strong></th>
    <th><strong>diego3g</strong></th>
    <th><strong>maykbrito</strong></th>
  </tr>
</table>

## 📜 Licença

Repositório licenciado pela **MIT LICENSE**.

#

<p align="center">Feito com 💜 por Heitor Monteiro & Rocketseat</p>
