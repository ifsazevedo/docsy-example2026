---
title: Goldydocs
description: Avaliação de temperatura de mingau &mdash; na nuvem!
params:
  body_class: td-navbar-links-all-active
---

{{% blocks/cover
  title="Bem-vindo ao Goldydocs: um exemplo e projeto inicial do Docsy!"
  height="full td-below-navbar"
  image_anchor="top"
%}}

<!--
  Want a cover without an image?
  Add the following argument to the blocks/cover shortcode:
    color="primary bg-gradient td-below-navbar"
-->

<!-- prettier-ignore -->
{{% _param description %}}
{.display-6}

<!-- prettier-ignore -->
<div class="td-cta-buttons my-5">
  <a {{% _param btn-lg primary %}} href="docs/">
    Aprenda mais
  </a>
  <a {{% _param btn-lg secondary %}}
    href="{{% param github_repo %}}"
    target="_blank" rel="noopener noreferrer">
    Baixar
    {{% _param FA brands github "" %}}
  </a>
</div>

{{% blocks/link-down color="info" %}}

{{% /blocks/cover %}}

{{% blocks/lead color="white" %}}

O Goldydocs oferece uma interface web única que proporciona visibilidade da temperatura das papas, do tamanho da cadeira e da suavidade da cama! Pode até descobrir quem comeu o **seu** mingau.

(Infelizmente, o Goldydocs não é um projeto real, mas você pode usar este site como exemplo para criar seus próprios sites reais com [Docsy](https://docsy.dev))

{{% /blocks/lead %}}

{{% blocks/section color="primary" type="row" %}}

{{% blocks/feature title="Novas métricas de cadeira!" icon="fa-lightbulb" %}}

A interface do usuário do Goldydocs agora mostra métricas de tamanho de cadeira por padrão.

Por favor, siga este espaço para atualizações!

{{% /blocks/feature %}}

{{% blocks/feature
  title="Contribuições são bem-vindas!" icon="fab fa-github"
  url="https://github.com/google/docsy-example"
%}}

Nós usamos um fluxo de trabalho de contribuições [Pull Request](https://github.com/google/docsy-example/pulls) no **GitHub**. Novos usuários são sempre bem-vindos!

{{% /blocks/feature %}}

{{% blocks/feature
  title="Siga-nos no X!" icon="fab fa-x-twitter"
  url="https://x.com/docsydocs"
%}}

Para anúncios das últimas funcionalidades, etc.

{{% /blocks/feature %}}

{{% /blocks/section %}}

{{% blocks/section color="white" type="row text-center h1" %}}

Esta é a segunda seção

{{% /blocks/section %}}

{{% blocks/section color="secondary" type="row text-center h1" %}}

Esta é outra seção com alinhamento ao centro

{{% /blocks/section %}}
