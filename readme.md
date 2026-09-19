# Nike Air Jordan - Página de Detalhes

> Projeto prático de desenvolvimento web front-end focado na construção de uma página de exibição e detalhes do tênis **Nike Air Jordan**, com foco em semântica HTML, estilização moderna, responsividade e experiência do usuário (UX/UI).

---

## Sumário

- [Visão Geral](#-visão-geral)
- [Demonstração](#-demonstração)
- [Funcionalidades](#-funcionalidades)
- [Tecnologias Utilizadas](#-tecnologias-utilizadas)
- [Estrutura do Projeto](#-estrutura-do-projeto)
- [Como Executar](#-como-executar)
- [Aprendizados e Boas Práticas](#-aprendizados-e-boas-práticas)
- [Autor](#-autor)
- [Licença](#-licença)

---

## Visão Geral

Este projeto foi desenvolvido como parte dos módulos práticos de **Front-End / Web Design**. O objetivo central é criar uma página de produto (*Product Detail Page - PDP*) atrativa e moderna para o **Nike Air Jordan**, permitindo ao usuário:

- Visualizar imagens em alta resolução do calçado.
- Conferir especificações técnicas, história e detalhes de fabricação.
- Interagir com seletores de cores/modelos e grade de tamanhos.
- Ter uma experiência fluida tanto em computadores quanto em dispositivos móveis.

---

## 💻 Demonstração

- **Repositório oficial:** [fhricardo/nike-air-jordan-detalhes](https://github.com/fhricardo/nike-air-jordan-detalhes)
- **Deploy / Live Preview:** _(Adicione aqui a URL do GitHub Pages ou Vercel caso disponível, ex.: `https://fhricardo.github.io/nike-air-jordan-detalhes/`)_

---

## Funcionalidades

- [x] **Header Institucional:** Logotipo, menu de navegação e atalhos rápidos.
- [x] **Galeria / Destaque do Produto:** Imagem principal em alta definição com suporte a miniaturas/ângulos alternativos.
- [x] **Informações Comerciais:** Título do produto, categoria, valor/preço promocional e condições de pagamento.
- [x] **Seletores Interativos:**
  - Grade de tamanhos disponíveis.
  - Variação de cores/estilos.
- [x] **Ação Principal (CTA):** Botão destacado de compra / adicionar ao carrinho.
- [x] **Seção de Detalhes:** Descrição do calçado, tecnologias de amortecimento (*Nike Air*), materiais e durabilidade.
- [x] **Design Responsivo:** Layout adaptável para smartphones, tablets e monitores desktop.

---

## Tecnologias Utilizadas

As principais ferramentas e linguagens aplicadas no desenvolvimento:

- **HTML5:** Marcação semântica (`<header>`, `<main>`, `<section>`, `<article>`, `<footer>`).
- **CSS3:** 
  - Layout flexível com **Flexbox** e **CSS Grid**.
  - Variáveis CSS (Custom Properties) para paleta de cores e tipografia.
  - Media Queries para design mobile-first/responsivo.
  - Efeitos de transição e pseudo-classes (`:hover`, `:focus`, `:active`).
- **JavaScript (Vanilla JS):** *(Opcional / Se aplicável)* Manipulação do DOM para troca de miniaturas, seleção de tamanho e interatividade do carrinho.

---

## Estrutura do Projeto

```plaintext
nike-air-jordan-detalhes/
├── assets/
│   ├── css/
│   │   └── style.css          # Folha de estilo principal
│   ├── js/
│   │   └── script.js         # Lógica de interatividade (se houver)
│   └── images/               # Imagens do calçado, logotipos e ícones
├── index.html                # Estrutura principal da página
└── README.md                 # Documentação do projeto
```

---

## Como Executar Localmente

1. **Clone o repositório:**
   ```bash
   git clone https://github.com/fhricardo/nike-air-jordan-detalhes.git
   ```

2. **Acesse a pasta do projeto:**
   ```bash
   cd nike-air-jordan-detalhes
   ```

3. **Abra o projeto:**
   - Basta abrir o arquivo `index.html` em qualquer navegador web, **ou**
   - Execute com a extensão **Live Server** no Visual Studio Code para atualização em tempo real.

---

## Aprendizados e Boas Práticas

- **Semântica Web:** Melhoria na acessibilidade e indexação (SEO) com tags adequadas.
- **Hierarquia Visual:** Organização tipográfica e contraste de cores para conduzir o olhar do cliente.
- **Responsividade:** Uso de unidades relativas (`rem`, `%`, `vw`, `vh`) para garantir fluidez em qualquer resolução de tela.

---

## Autor

Desenvolvido por **[Flavio Ricardo](https://github.com/fhricardo)**.