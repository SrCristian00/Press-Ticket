# Press-Ticket

<p align="center">
  <a href="https://www.codefactor.io/repository/github/rtenorioh/press-ticket"><img src="https://www.codefactor.io/repository/github/rtenorioh/press-ticket/badge" alt="CodeFactor" /></a>

  <img alt="Repository size" src="https://img.shields.io/github/repo-size/rtenorioh/Press-Ticket">

  <a href="https://github.com/rtenorioh/Press-Ticket/commits/master">
    <img alt="GitHub last commit" src="https://img.shields.io/github/last-commit/rtenorioh/Press-Ticket">
  </a>
      
   <a href="https://github.com/rtenorioh/Press-Ticket/stargazers">
    <img alt="Stargazers" src="https://img.shields.io/github/stars/rtenorioh/Press-Ticket">
  </a>
</p>

## Changelog

### 14/03/2022
- Add CodeFactor; e
- Correções.

### 13/03/2022
- Implementado autorização para o User poder trocar de senha;
- Removido o caption que era enviado junto com a imagem;
- Ignorar mensagens de grupos [caso de tela branca ao acessar a página de configurações, rodar o seguinte código no mysql: ```INSERT INTO `Settings` (`key`, `value`, `createdAt`, `updatedAt`) VALUES ('CheckMsgIsGroup', 'enabled', '2022-03-02 17:17:00.000000', '2022-03-02 17:17:00.000000');``` ];
- Customização da página de configurações (trocando select por swicher); e
- Ignorando chamadas de vídeo/áudio [caso de tela branca ao acessar a página de configurações, rodar o seguinte código no mysql: ```INSERT INTO `Settings` (`key`, `value`, `createdAt`, `updatedAt`) VALUES ('call', 'disabled', '2022-03-13 18:00:00.000000', '2022-03-13 18:00:00.000000');``` ].

### 12/03/2022

- Sistema base;
- Habilitado para MD;
- Usando MySql ao invés de Docker;
- Implementado função de aparecer digitando... ao antes de enviar a lista de setores;
- Implentado a inclusão do nome do usuário na msg de boas vindas;
- Criado uma variável no arquivo de tradução para alterar o nome Press Ticket;
- Na página de contatos o botão importar contatos está disponível apenas para Admin; e
- Conexões foi movido para a área administrativa.