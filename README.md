# Mavory - versão VS Code

Projeto HTML, CSS e JavaScript baseado no protótipo do Stitch.

## Estrutura
- `index.html` abre a página inicial.
- `pages/` contém as telas do Mavory.
- `assets/css/style.css` contém ajustes visuais simples.
- `assets/js/app.js` contém interações gerais.
- `assets/images/logo.png` é a logo oficial enviada para o projeto.

## Câmera
A câmera da tela `pages/compartilhar.html` usa `navigator.mediaDevices.getUserMedia()`.
Para testar no computador, abra o projeto pelo Live Server do VS Code e permita o acesso à câmera.


## Atualização desta versão
- Perfil de exemplo removido e substituído por ícone de perfil.
- Nome do perfil: Caleb.
- Acervo com 6 receitas acessíveis.
- Cada receita abre uma página de detalhes com ingredientes e modo de preparo.
- A câmera continua na página Compartilhar e usa getUserMedia do navegador.
