# Agência Criativa Web

Site institucional de uma agência digital, desenvolvido com HTML5 e CSS3 puro, sem frameworks externos.

## 📁 Estrutura do Projeto

```
Agencia--Criativa--Web/
├── img/
│   └── escritorio.jpg
├── index.html
└── styles.css
```

## 🖥️ Seções da Página

- **Home (Banner):** Apresentação principal com chamada para ação.
- **Sobre Nós:** Descrição da agência e seu diferencial.
- **Serviços:** Grade com três cards — Design Gráfico, Desenvolvimento Web e Branding.
- **Depoimentos:** Avaliações de clientes em cards destacados.
- **Contato:** Informações da agência, imagem responsiva e formulário de contato.
- **Rodapé:** Copyright 2026.

## 🛠️ Tecnologias Utilizadas

- **HTML5** — Estrutura semântica com seções, header, footer e formulário.
- **CSS3** — Estilização completa com:
  - **Flexbox** — Cabeçalho, depoimentos e seção de contato.
  - **CSS Grid** — Grade de serviços (3 colunas no desktop, 1 no mobile).
  - **Media Queries** — Layout responsivo para telas até 768px.
  - **Imagem Responsiva** — Atributo `srcset` e `sizes` para diferentes resoluções (568w, 768w, 1440w).

## 🎨 Identidade Visual

| Elemento | Cor |
|---|---|
| Primária (roxo) | `#8e44ad` |
| Secundária (azul escuro) | `#2c3e50` |
| Background corpo | `#f9f9f9` |
| Background serviços/contato | `#f4f6f7` |
| Botão enviar | `#2c3e50` |

Fonte principal: `'Segoe UI'`, Tahoma, Geneva, Verdana, sans-serif.

## 📱 Responsividade

O layout se adapta automaticamente para dispositivos móveis (`max-width: 768px`):

- Cabeçalho empilha logo e menu verticalmente.
- Grade de serviços passa de 3 colunas para 1 coluna.
- Depoimentos e seção de contato mudam de row para column.
- Título do banner reduz de `3rem` para `2.2rem`.

## 📞 Informações de Contato (Demonstração)

- **Endereço:** Av. Paulista, 1000 — São Paulo, SP
- **Telefone:** (11) 98899-6503
- **E-mail:** jconceicaogabriel@gmail.com

## 🚀 Como Executar

1. Clone ou baixe o repositório.
2. Abra o arquivo `index.html` diretamente no navegador, **ou**
3. Use a extensão **Live Server** do VS Code para visualização com recarregamento automático.

> Nenhuma dependência ou instalação necessária.

## 📄 Licença

© 2026 Agência Criativa Web. Todos os direitos reservados.
