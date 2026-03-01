📺 Página de Compilação de Vídeos
Este projeto é uma página HTML que reúne vídeos musicais selecionados, incorporados diretamente do YouTube. Ele foi desenvolvido para praticar a estrutura semântica correta em HTML e o uso de iframes para incorporar conteúdo externo.

🎯 Objetivo
- Criar uma página que apresente vídeos musicais em seções organizadas.
- Utilizar elementos semânticos (<section>, <h2>, <p>, <iframe>) para estruturar o conteúdo.
- Incorporar vídeos do YouTube de forma correta, usando o formato https://www.youtube.com/embed/ID_DO_VIDEO.

📂 Estrutura do Código
- <main>: contém todo o conteúdo principal da página.
- <h1>: título principal da página.
- <p>: introdução logo abaixo do título.
- <section>: cada vídeo é apresentado em uma seção com:
- <h2> → título da música.
- <p> → breve descrição do vídeo.
- <iframe> → player do YouTube incorporado.

✅ Requisitos atendidos
- Parágrafo introdutório logo abaixo do <h1>.
- Três <section> abaixo do primeiro <p>.
- Cada <section> começa com <h2>.
- Cada <section> contém <p> como segundo filho.
- Cada <section> contém <iframe> como terceiro filho.
- Todos os <iframe> possuem title e width.

🚀 Como usar
- Clone este repositório:
git clone https://github.com/seu-usuario/compilacao-de-video.git
- Abra o arquivo index.html em qualquer navegador moderno.
- A página exibirá três seções com vídeos musicais:
- SZA - Broken Clocks
- Alcione - Você me vira a cabeça
- Beyoncé - Bigger

🔗 Observações importantes
- Alguns vídeos podem aparecer como “Vídeo indisponível”. Isso acontece quando o dono do canal bloqueia a incorporação em sites externos.
- Nesse caso, o visitante pode clicar em “Assistir no YouTube” e abrir o vídeo diretamente na plataforma.
- O atributo title nos iframes garante acessibilidade e ajuda nos testes automatizados.
- O uso de allowfullscreen permite que o usuário assista em tela cheia.
