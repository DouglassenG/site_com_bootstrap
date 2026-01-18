# 🌐 Site Institucional - Bootstrap UI

![Status](https://img.shields.io/badge/Status-Finalizado-green)
![Bootstrap](https://img.shields.io/badge/Framework-Bootstrap-purple?logo=bootstrap&logoColor=white)
![HTML5](https://img.shields.io/badge/Code-HTML5-orange?logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/Style-CSS3-blue?logo=css3&logoColor=white)

> Uma aplicação web completa que demonstra a construção rápida de interfaces robustas e responsivas utilizando o ecossistema de componentes do Bootstrap.

## 🎯 Motivação e Propósito

No mercado de trabalho, a velocidade de entrega e a consistência visual são essenciais. O propósito deste projeto foi consolidar o conhecimento sobre **Frameworks CSS**.

Este repositório resolve o problema de criar um site do zero, utilizando uma abordagem baseada em componentes pré-testados. O foco foi dominar o **Grid System** para garantir que o layout se adapte perfeitamente a celulares, tablets e desktops (Responsividade), além de implementar componentes de navegação e exibição de conteúdo de forma semântica.

## 🖼️ Demonstração Visual

*(Se o projeto estiver hospedado no GitHub Pages ou Vercel, insira o link aqui. Ex: [Ver Site Online](URL))*

## 🛠️ Tecnologias Utilizadas

A stack tecnológica prioriza a padronização e agilidade:

* **[Bootstrap](https://getbootstrap.com/):** Framework de UI principal. Utilizado para:
    * **Grid System:** Estruturação de colunas e linhas (`container`, `row`, `col`).
    * **Navbar:** Menu de navegação responsivo com comportamento colapsável (hambúrguer).
    * **Carousel:** Slider de imagens para a seção Hero.
    * **Cards:** Componentes modulares para exibição de itens/produtos.
* **[HTML5](https://developer.mozilla.org/pt-BR/docs/Web/HTML):** Estrutura semântica da página.
* **[CSS3 Customizado](https://developer.mozilla.org/pt-BR/docs/Web/CSS):** Estilos pontuais (`main.css`) para personalização da identidade visual (sobrescrita de variáveis do Bootstrap).

## ✨ Funcionalidades

O site é estruturado como uma Landing Page institucional completa:

1.  **Navegação Responsiva:** Menu superior que se adapta ao tamanho da tela, fixando-se ao topo ou tornando-se um menu lateral em mobile.
2.  **Destaque Visual (Hero):** Uso de Carrossel (Slider) para apresentação de banners principais.
3.  **Catálogo de Conteúdo:** Seção de produtos ou serviços organizada em Cards, utilizando o Grid System para alinhar 1 item por linha (mobile) ou 3/4 itens por linha (desktop).
4.  **Formulários:** Interface de contato estilizada com classes nativas do framework (`form-control`).

## 📂 Estrutura de Arquivos

A organização do projeto segue o padrão de sites estáticos, separando a estrutura (HTML) da estilização (CSS) e dos ativos (Imagens):

```text
site_com_bootstrap/
├── images/          # Diretório contendo banners, logos e fotos de produtos
├── main.css         # CSS customizado (ajustes finos sobre o Bootstrap)
├── index.html       # Arquivo principal (Markup + Classes Bootstrap)
└── README.md        # Documentação do projeto
