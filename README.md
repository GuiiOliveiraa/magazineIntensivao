# 🛒 Magazine Hashtag - E-commerce

Um projeto de e-commerce funcional e responsivo desenvolvido durante o Intensivão de Programação. A aplicação simula uma loja de roupas (Zara) com catálogo interativo, sistema de carrinho e histórico de pedidos.

## 🚀 Funcionalidades

* **Catálogo Dinâmico**: Renderização automatizada de produtos a partir de uma base de dados interna.
* **Filtros Inteligentes**: Opções para filtrar produtos por categoria (Masculino, Feminino ou Todos).
* **Carrinho Completo**: Adicionar itens, incrementar/decrementar quantidades e remoção de produtos com atualização de preço em tempo real.
* **Checkout e Pedidos**: Processo de finalização de compra com armazenamento de dados no `localStorage` para persistência do histórico de pedidos.
* **Design Responsivo**: Interface construída com **Tailwind CSS** para garantir uma boa experiência em qualquer dispositivo.

## 🛠️ Tecnologias Utilizadas

* **HTML5 & JavaScript (ES6+)**: Estrutura e lógica do lado do cliente.
* **Tailwind CSS**: Estilização moderna e utilitária.
* **Vite**: Ferramenta de build para um ambiente de desenvolvimento rápido e otimizado.
* **Font Awesome**: Ícones para melhoria da interface visual.

## 📂 Estrutura do Projeto

* `/src`: Contém a lógica principal dividida em módulos (carrinho, catálogo, filtros e utilidades).
* `/assets`: Imagens dos produtos e logotipos da marca.
* `index.html`: Página principal com o catálogo.
* `checkout.html` & `pedidos.html`: Telas de finalização e histórico.

## 🔧 Como Executar

1. Certifique-se de ter o [Node.js](https://nodejs.org/) instalado.
2. Instale as dependências:
```bash
npm install

```


3. Inicie o servidor de desenvolvimento:
```bash
npm run dev

```


4. Para gerar a versão final (build):
```bash
npm run build

```



---

*Este projeto foi desenvolvido para fins educacionais de aprendizado em desenvolvimento Front-End.*
