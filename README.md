# Atv2-Crosta
Atividade 2 da crosta: Uma pequena refatoração aplicando boas práticas no primeiro modelo de site para o DCOMP com foco no index.html e index.css.


# Historico de modificações:
- Inicialmente, modifiquei o arquivo html em `<!DOCTYPE LUCAS_MAU>` para `<!DOCTYPE html>`, logo em seguida ajustei a linguagem de "en" para "pt-BR".
- Ao longo de todo processo de refatoração foi utilizado uma melhor prática de indentação (visto que a indentação provocava mal-estar).
- Em todas as `<img>` foram adicionado descrições, utilizando o alt = "(descrição)".
- A fim de manter boas práticas, as tags `<i>` foram substituidas por `<em>`.
- Todo `<br/>` com a função de separar paragrafos, foi apagado e substuituido por modificações na margem.
# `<head>`:
- Apaguei as tags `<meta>` que seguiam sem utilidade e também retirei os links que eram redundantes a funcionalidade.
# `<body>`:
- Adicionei um `<main>` para que a estrutura do `<body>` esteja dividida em `<header>`, `<main>`, `<footer>`.
## `<header>`:
- troquei o `<div class= "header">` para `<div class = "introduction">`, como consequência, também troquei a classe dentro do css para manter o style. Dentro desse bloco está contido um `<header>` e um `<article>`, ambos substituiram `<div>`.
- O `<header>` por sua vez, comportava um bloco `<div>` que alterei para `<nav>`, onde contém os links para outras divisões da página.
- Nos elementos do `<article>` foram adicionados display = "block". também coloquei um `<div>` para melhorar a estilização do botão.
## `<main>`:
- Separei o `<main>` em `<article>`,`<article>`,`<article>`,`<section>` no lugar dos `<div>`.
## `<footer>`:
- troquei a tag `<div>` por `<footer>`.
- excluí a class = "footer" no css e seu style foi especificado em footer.
