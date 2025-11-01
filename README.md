# 📖 Livro da Vida - Player de Vídeos

Este é um sistema simples para exibir uma lista de vídeos do YouTube em uma página web e gerenciá-los através de uma interface administrativa.

## Como Funciona

O projeto é composto por 3 arquivos principais:

1.  **`index.html`**: A página principal que exibe o player de vídeo e a lista de vídeos disponíveis. Os dados dos vídeos são carregados a partir do arquivo `videos.json`.
2.  **`admin.html`**: Uma página de administração para adicionar, editar e excluir vídeos. As alterações são salvas no `localStorage` do navegador e podem ser exportadas para o arquivo `videos.json`.
3.  **`videos.json`**: Um arquivo JSON que armazena a lista de vídeos (título e ID do YouTube). Este arquivo é a "fonte da verdade" para o `index.html`.

## Como Gerenciar os Vídeos

1.  **Abra o arquivo `admin.html`** no seu navegador.
2.  A lista de vídeos será carregada.
3.  **Para adicionar um vídeo:** Preencha os campos "Título" e "ID do YouTube" e clique em "Salvar Vídeo".
4.  **Para editar um vídeo:** Clique no botão "Editar" de um vídeo, altere as informações e clique em "Salvar Vídeo".
5.  **Para excluir um vídeo:** Clique no botão "Excluir" do vídeo que deseja remover.
6.  **Para salvar as alterações:** Após fazer todas as modificações, clique no botão **"Exportar videos.json"**.
7.  Um arquivo chamado `videos.json` será baixado para o seu computador.
8.  **Substitua o arquivo `videos.json` antigo** na pasta do seu projeto por este novo arquivo que você baixou.

Dessa forma, a página `index.html` passará a exibir a lista de vídeos atualizada.