Streamify
Streamify é uma plataforma de música com várias funcionalidades que permite aos usuários explorar e curtir playlists, vídeos e muito mais. Este repositório contém os arquivos HTML, CSS e JavaScript que implementam a interface do usuário, funcionalidade de login, e as interações com a plataforma.

Estrutura do Projeto
HTML: Contém a estrutura da página, incluindo o cabeçalho, menus e popups.

CSS: Estilos para o layout do site, incluindo centralização e responsividade.

JavaScript: Scripts para interações, como exibição de popups de vídeo e controle de navegação entre as playlists.

Funcionalidades
Exibição de Playlists: Cada playlist é exibida em uma box com o nome da playlist e um botão de "Detalhes".

Popup para Vídeos e Imagens: Ao clicar no botão de "Detalhes", um popup é exibido com conteúdo relacionado, como imagens ou vídeos.

Login e Registro: Permite que os usuários se registrem e façam login para acessar suas playlists personalizadas.

Estrutura de Navegação: O site tem links para a página inicial, sobre, e login.

Como Rodar
Pré-requisitos
Um servidor web (como XAMPP ou outro servidor local) para rodar os arquivos PHP, caso necessário.

O JavaScript e o CSS já estão configurados, sendo necessário apenas abrir o arquivo index.html ou o arquivo que deseja visualizar no navegador.

Passos
Clone o Repositório:

bash
Copiar
Editar
git clone https://github.com/usuario/streamify.git
Abra os Arquivos no Navegador:

Para visualizar o site, abra os arquivos index.html, sobre.html ou outros diretamente no navegador.

Configuração Local (se necessário):

Caso use PHP, você pode precisar de um servidor local como o XAMPP. Coloque os arquivos na pasta htdocs e acesse pelo navegador através de localhost/nome_da_pasta.

Estrutura de Diretórios
pgsql
Copiar
Editar
streamify/
│
├── albuns/
│   └── logo.png
│
├── imagens/
│   └── (imagens de playlist)
│
├── musicas/
│   └── billie1.mp4
│
├── index.html
├── sobre.html
├── login.html
├── script.js
└── style.css
