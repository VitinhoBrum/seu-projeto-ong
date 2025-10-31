# Plataforma ONG - Experiência Prática I

![Status](https://img.shields.io/badge/Status-Concluído-brightgreen)

Projeto desenvolvido como parte da atividade "Experiência Prática I" da disciplina de Desenvolvimento Front-End. O objetivo desta primeira entrega é construir a base estrutural de uma plataforma web para uma ONG fictícia, focando exclusivamente na aplicação correta e semântica do **HTML5**.

## 🎯 Sobre o Projeto

Este projeto simula a criação de um website para a "ONG Salve Vidas". O foco desta primeira etapa foi estabelecer a estrutura de pastas e criar as três páginas principais da plataforma, demonstrando domínio dos conceitos de semântica, formulários complexos e multimídia.

---

## 📑 Páginas Desenvolvidas

Foram criadas 3 páginas HTML distintas, conforme solicitado nos requisitos da atividade:

1.  **`index.html` (Página Inicial):**
    * Apresenta a organização, sua missão e visão.
    * Inclui informações de contato básicas.
    * Utiliza imagens e estrutura semântica com `<header>`, `<main>`, `<section>` e `<footer>`.

2.  **`projetos.html` (Projetos Sociais):**
    * Detalha os projetos sociais da ONG (como o "EducaAção" e "Prato Cheio").
    * Contém uma seção "Como Ajudar", que direciona para as áreas de voluntariado e doações.
    * Utiliza `<article>` para separar logicamente cada projeto.

3.  **`cadastro.html` (Cadastro de Voluntário):**
    * Apresenta um formulário complexo para o cadastro de novos voluntários.
    * Esta página é o foco principal dos requisitos técnicos de formulário.

---

## ✅ Requisitos Técnicos Cumpridos (Entrega I)

Esta entrega cumpre os seguintes requisitos obrigatórios:

* **Estrutura Semântica HTML5:** As páginas utilizam tags como `<header>`, `<nav>`, `<main>`, `<section>`, `<article>` e `<footer>` para dar significado ao conteúdo.
* **Hierarquia de Títulos:** Os títulos (`<h1>` a `<h3>`) são usados de forma lógica e consistente.
* **Formulário Complexo:** O arquivo `cadastro.html` implementa:
    * **Tipos de Input HTML5:** `text`, `email`, `tel`, `date`.
    * **Agrupamento Lógico:** Uso de `<fieldset>` e `<legend>` para separar "Dados Pessoais" e "Endereço".
    * **Validação Nativa:** Atributos `required` são usados para garantir que os campos sejam preenchidos.
    * **Máscaras (via `pattern`):** O atributo `pattern` é utilizado para validar o formato de campos como CPF, Telefone e CEP, simulando o requisito de máscara de input.
* **Organização de Pastas:** O projeto segue a estrutura de pastas recomendada, separando arquivos `HTML` e `img`.
* **Validação W3C:** Todos os arquivos HTML foram verificados e validados no [W3C Validator](https://validator.w3.org/) para garantir a conformidade com os padrões web.

---

## 🛠️ Tecnologias Utilizadas

* **HTML5**

---

## 🚀 Como Visualizar

Como este projeto é composto apenas por arquivos estáticos (HTML e imagens), não há necessidade de instalação.

1.  Clone este repositório:
    ```bash
    git clone https://github.com/VitinhoBrum/seu-projeto-ong/tree/5a5ff31b3dc0706b6f0aafc15c93532499567d43/seu-projeto-ong
    ```
2.  Navegue até a pasta do projeto:
    ```bash
    cd seu-projeto-ong
    ```
3.  Abra qualquer um dos arquivos `.html` (começando pelo `index.html`) diretamente no seu navegador.

---

## 👨‍💻 Autor

* **VitinhoBrum**
* **GitHub:** `@VitinhoBrum`
