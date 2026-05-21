# TechStore | Checkout de E-commerce

Página final de compra de uma loja virtual, construída com Bootstrap 5. O foco está em formulários avançados, validação visual e customização de variáveis CSS do framework.

## Funcionalidades

- **Navbar** com logotipo e ícone de carrinho com badge de itens
- **Formulário de cobrança** utilizando Floating Labels, estados de validação (`is-valid`, `is-invalid`) e feedback textual
- **Input Group** com ícone no campo de número do cartão
- **Seção de cupom** com botão “Aplicar” e feedback visual de sucesso
- **List Group** com resumo do pedido (itens, desconto, total) e badge de contagem
- **Customização do tema primário** do Bootstrap através de variáveis CSS no `:root`
- Layout responsivo com coluna lateral fixa (sticky) no resumo

## Tecnologias Utilizadas

- HTML5
- CSS3
- [Bootstrap 5.3.3](https://getbootstrap.com/)
- [Bootstrap Icons 1.11.3](https://icons.getbootstrap.com/)

O pacote JavaScript do Bootstrap está incluído, mas não há script personalizado — toda a interação é baseada em classes e estilos.

## Estrutura de Arquivos

│ index.html
│ style.css


## Como Executar

1. Faça o download ou clone este repositório.
2. Abra o arquivo `index.html` em um navegador.

Nenhuma instalação adicional é necessária; os recursos do Bootstrap são obtidos via CDN.

## Destaques Técnicos

- **Floating Labels**: campos com label animada (`.form-floating`)
- **Validação visual**: classes `is-valid` e `is-invalid` acompanhadas de `valid-feedback` e `invalid-feedback`
- **Input Groups**: combinação de ícone e campo no número do cartão (`.input-group`)
- **Customização da cor primária**: no `style.css`, as variáveis `--bs-primary` e `--bs-primary-rgb` são sobrescritas para alterar toda a paleta de botões, links e foco de elementos
- **Sticky sidebar**: a coluna do resumo utiliza `.sticky-top` para acompanhar a rolagem

---

Desenvolvido no curso de Front-End
