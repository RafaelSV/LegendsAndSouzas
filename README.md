# LegendAndSouzas
Este projeto busca desenvolver um sistema online que registra e exibe informações dos jogadores cadastrados. Com algumas informações pessoais sobre o jogador e diversas informações sobre suas estatísticas e desempenho no jogo League of Legends.

O site possui 4 telas principais: Tela de Login, Tela de Registro, Tela de Seleção de Players e Tela de Informação dos Players.

## Telas

### Tela de Login
Campo de entrada de texto para o usuário
Campo de entrada de texto para a senha
Botão para realizar o login
Botão "Forget password" para recuperação de senha (implementação futura)
Botão para registro
Logotipo do projeto em destaque

### Tela de Registro
Campo de entrada de texto para o e-mail
Campo de entrada de texto para o usuário
Campo de entrada de texto para a senha
Botão para realizar o cadastro
Botão para voltar para a tela de login
Logotipo do projeto em destaque

### Tela de Seleção de Players
Imagem e nome de todos os players cadastrados
Barra de pesquisa para filtrar por nome de players
Clicar na imagem/nome de um player redireciona para a Tela de Informação dos Players específica desse player

### Tela de Informação dos Players
Essa tela é composta por várias seções verticais, ocupando o equivalente a 4 telas.
4.1 - Informações gerais do player (nome, foto e descrição)
4.2 - Informações gerais da "Champion pool" do player
4.3 - Elo do Player e informações sobre partidas ranqueadas
4.4 - Vídeos e melhores jogadas do player com campeões específicos

## Recursos
Menu superior presente em todas as telas com os seguintes botões: Login, Register, Players e Clash (botão desabilitado para uma expansão futura)
Se o usuário estiver deslogado e clicar no botão "Players" no menu, uma mensagem solicita que ele faça o login antes.
Se o usuário estiver logado, os botões "Login" e "Register" são substituídos pelo botão "Logout".
Footer com informações sobre os desenvolvedores e informações genéricas.

## Banco de Dados
Banco de dados MySQL online (recomendação: db4free.net)
Tabelas sugeridas:
Tabela "Users" para armazenar informações de usuários (nome, usuário, senha, e-mail)
Tabela "Players" para armazenar informações dos jogadores (nome, foto, descrição, estatísticas)

## Hospedagem de Vídeos e Imagens
Vídeos: Hospedagem de vídeos no YouTube em um canal não listado
Imagens: Armazenamento de imagens em um servidor ou uso de serviços de armazenamento de imagens em nuvem (recomendação: Cloudinary, Amazon S3)

## Segurança
Implementar práticas recomendadas de segurança, como armazenamento seguro de senhas e proteção contra ataques de força bruta.
No momento, a segurança não é uma preocupação crítica, pois o projeto é apenas para uso interno entre amigos.
Esta documentação fornece uma visão geral do projeto e destaca os principais recursos e requisitos. Certifique-se de atualizá-la com detalhes adicionais à medida que o desenvolvimento progredir e novos recursos forem adicionados.