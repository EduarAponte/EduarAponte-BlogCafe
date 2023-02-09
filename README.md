# EduarAponte-BlogCafe

Project acadêmico criado no curso de Desenvolvimento Web Completo na Udemy.

<br>

<div align="center">
  <img src="https://user-images.githubusercontent.com/92584428/213260486-fab48eea-7515-4f49-9af2-6798119cf323.png" style="margin: 0 8px;" width="30%" height="30%" />
  <img src="https://user-images.githubusercontent.com/92584428/213260505-692adc6d-40eb-4ffb-9d3e-a4564909fb3b.png" style="margin: 0 8px;" width="30%" height="30%" /> 
  <img src="https://user-images.githubusercontent.com/92584428/213260518-4604433e-c88c-460a-ac7c-d270d6bfa54b.png" style="margin: 0 8px;" width="30%" height="30%" />  
</div>

<br>

# Descrição

- Um blog de café construído com HTML e CSS, implementado alguns performance como Lazy Loading, Preload, Prefetch, imagens Webp, e etiqueta meta para melhoras de busca na internet

- Lazy Loading é uma estratégia para identificar recursos como não bloqueadores (não críticos) e carregá-los somente quando necessário. 
- Preload valor do atributo <link>do elemento rel permite que você declare solicitações de busca no HTML <head>, especificando recursos que sua página precisará muito em breve, que você deseja começar a carregar no início do ciclo de vida da página, antes que o mecanismo principal de renderização dos navegadores entre em ação
- Prefetch é um mecanismo do navegador que utiliza o tempo ocioso do navegador para baixar ou pré -buscar documentos que o usuário pode visitar em um futuro próximo.
- Webp é um formato de imagem de compressão sem perdas e com perdas desenvolvido pelo Google.

- Quer conhecer mais visite os site de referência 

Lazy Loading [Clique aqui](https://developer.mozilla.org/en-US/docs/Web/Performance/Lazy_loading)
  
Preload [Clique aqui](https://developer.mozilla.org/en-US/docs/Web/HTML/Attributes/rel/preload)
  
Prefetch [Clique aqui](https://developer.mozilla.org/en-US/docs/Web/HTTP/Link_prefetching_FAQ)
  
Webp [Clique aqui](https://developer.mozilla.org/en-US/docs/Glossary/WebP)
  
<br>

# Objetivo

O principal objetivo do projeto é colocar em prática os conhecimentos em performance do site e uso de imagens Webp

```

<meta name="description" content="Página web de blog de café">

<link rel="prefetch" href="cursos.html"as="document">

<link rel="preload" href="css/style.css" as="style">

```
Como usar imagens Webp no HTML

```
<picture>
   <source loading="lazy" srcset="img/blog1.webp" type="image/webp">
   <img loading="lazy" src="img/blog1.jpg" alt="Imagem do blog">
</picture> 

```
Como usar imagens Webp no css
```
.webp .header {
    background-image: url(../img/banner.webp);
}
.no-webo .header {
    background-image: url(../img/banner.jpg);
}
```

<br>

# Ferramentas Utilizadas

- HTML
- CSS
- Normalize.css
- Modernizr.js

<br>

# Como Testar

Você pode acessar o projeto [![Netlify Status](https://api.netlify.com/api/v1/badges/e417a718-c0c7-45e3-97a9-a7b79149be7f/deploy-status)](https://eduaraponte-blogcafe.netlify.app) ou [![GitHub](https://img.shields.io/badge/GitHub-4B0082?style=for-the-badge&logo=github&logoColor=white&style="border-radius:65px;)](https://eduaraponte.github.io/EduarAponte-BlogCafe/)

Ou rodar na sua maquina.

```

git clone https://github.com/EduarAponte/EduarAponte-BlogCafe.git

```

<br>

# Observações

- Projeto para fim demonstrativo e acadêmico.

- o projeto esta construido utilizando as tecnologias HTML e CSS porém os itens agregados não estão num banco de dados nem usa um linguagem de programação

  <br>
  
> Status do projeto: Finalizado
<br>
O caminho das pedras para entrar no universo da programação e começar com a criação de sites utilizando as linguagens populares CSS, HTML e JavaScript.
