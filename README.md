# Projeto: Website Institucional - Agência Criativa Web

Este projeto consiste no desenvolvimento de uma página web única (Single Page Application) para uma agência de design digital fictícia chamada **Agência Criativa Web**. O objetivo principal foi aplicar na prática conceitos fundamentais de desenvolvimento front-end, focando em semântica estrutural e técnicas modernas de estilização responsiva.

Projeto desenvolvido para fins acadêmicos como parte dos critérios de avaliação da disciplina de Desenvolvimento Web / Design Responsivo.

---

## 🚀 Tecnologias Utilizadas

* HTML5: Estruturação semântica da página (uso de tags como `<header>`, `<nav>`, `<section>`, `<footer>`).
* CSS3: Estilização global, gerenciamento de layouts e tipografia.
* Flexbox: Utilizado para alinhar os itens do menu de navegação e organizar os blocos de depoimentos.
* CSS Grid: Utilizado especificamente na seção de "Serviços" para criar uma grade adaptável de cards.

---

## 📐 Conceitos de Responsividade Aplicados

Para cumprir as exigências de um design moderno e totalmente adaptável a qualquer tamanho de tela (Desktops, Tablets e Smartphones), foram implementadas as seguintes soluções:

1.  Unidades Relativas: Substituição do uso rígido de pixels (`px`) por unidades flexíveis como `%, vh, rem` e `fr` (no CSS Grid), garantindo a elasticidade dos elementos.
2.  Media Queries (`@media`): Criação de pontos de quebra (breakpoints) em `768px` para reorganizar o layout de colunas lado a lado (Desktop) para um formato empilhado em linha única (Mobile).
3.  Otimização de Imagens (`srcset` e `sizes`): Implementação de imagens responsivas no bloco de Contato. O navegador baixa o arquivo correto (`escritorio-p.jpg`, `escritorio-m.jpg` ou `escritorio-g.jpg`) dependendo da resolução e densidade de pixels do dispositivo do usuário, economizando largura de banda.

---

## 🗂️ Estrutura do Projeto

O site foi dividido estritamente nas seções requisitadas:
* Home: Banner de boas-vindas com chamada para ação (Call to Action).
* Sobre Nós: Breve descrição dos valores e objetivos da agência.
* Serviços: Grid responsivo listando as principais soluções da empresa.
* Depoimentos: Seção flexível contendo feedbacks de clientes.
* Contato: Bloco com informações institucionais, imagem otimizada e um formulário funcional com campos de validação básica (Nome, E-mail e Mensagem).

---

## ⚙️ Como Executar o Projeto Localmente

1. Faça o download ou clone este repositório.
2. Certifique-se de manter a estrutura de pastas abaixo:
   ```text
   ├── img/
   │   ├── escritorio-p.jpg
   │   ├── escritorio-m.jpg
   │   └── escritorio-g.jpg
   ├── index.html
   └── styles.css
