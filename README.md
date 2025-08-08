# 🛒 E-COMMERCE - Projeto de Catálogo de Produtos

Este projeto é um catálogo de produtos para e-commerce, desenvolvido em **HTML**, **CSS** e **JavaScript** puro.  
O arquivo `scripts.js` é responsável por toda a lógica de exibição, busca e filtragem dos produtos.

---

## 📸 Demonstração

Página Inicial<img src="./assets/e-commerce preview tela 1.png" alt= ecommerce inicio>

Produtos <img src="./assets/e-commerce preview products.png" alt= produtos>

🔗 [Veja o projeto funcionando](https://alisson-miguelferreira.github.io/e-commerce/)

---

## ✨ Funcionalidades

- 🖼️ **Exibição dinâmica dos produtos**: Todos os produtos são carregados a partir de um array JS e exibidos em cards responsivos.
- 🔎 **Busca inteligente**: O campo de busca permite encontrar produtos por nome, descrição ou palavras-chave.
- 🗂️ **Filtro por categoria**: Os botões de categoria filtram os produtos exibidos. O botão ativo é destacado em azul.
- 🎬 **Transição suave**: Ao trocar de categoria ou pesquisar, os cards aparecem/desaparecem suavemente com efeito fade.
- 💰 **Preço ajustado**: Todos os preços exibem um acréscimo de R$ 0,90 automaticamente.
- 🖼️ **Ajuste visual para imagens específicas**: A imagem do Sony WH-1000XM5 é centralizada automaticamente para melhor apresentação.

## 🛠️ Estrutura do Código

- **Array de produtos**: Todos os produtos estão definidos no início do arquivo, com propriedades como nome, categoria, preço, imagem e descrição.
- **Função `mostrarProdutos()`**: Responsável por filtrar, montar o HTML dos cards e aplicar o efeito de transição.
- **Função `pesquisar()`**: Atualiza o termo de busca e chama a função de exibição.
- **Filtro por categoria**: Implementado via event listeners nos botões de categoria, alterando a variável `categoriaAtual`.
- **Normalização de texto**: Busca ignora acentos e diferenças de caixa usando a função `normalizarTexto`.
- **Transição visual**: Classe CSS `.fade` aplicada para suavizar a troca de produtos.

## 🚀 Como usar

1. **Digite no campo de busca** 🔍 para filtrar produtos por nome, descrição ou palavras-chave.
2. **Clique nos botões de categoria** 🗂️ para filtrar por tipo de produto.
3. **Os cards serão atualizados automaticamente** conforme a busca ou categoria selecionada.

## 🎨 Personalização

- Para adicionar novos produtos, basta incluir novos objetos no array `produtos`.
- Para adicionar novas categorias, adicione novos botões no HTML com o atributo `data-category` correspondente.

## 💻 Tecnologias

- HTML5
- CSS3
- JavaScript (ES6)

---

🤝 Conecte-se comigo
🔗<a href="https://www.linkedin.com/in/alisson-miguelferreira/">LinkedIn</a>
🐙 <a href="https://github.com/alisson-miguelferreira">GitHub</a>

---

Desenvolvido para fins didáticos e de portfólio. 🚀

