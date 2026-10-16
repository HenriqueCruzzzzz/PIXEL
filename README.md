# Pixel Store — Loja Virtual 

## Executar

```bash
npm install
npm run dev
```

Acesse a URL indicada pelo Vite (normalmente http://localhost:5173).

## Gerar versão de produção

```bash
npm run build
```

## Componentes

- **Header**: logo, menu com Início, Produtos, Sobre e Contato e contador do carrinho.
- **Banner**: chamada principal, arte do controle e botão que leva ao catálogo.
- **CardProduto**: componente reutilizável que mostra imagem, nome, descrição, preço e botão Comprar.
- **ListaProdutos**: renderiza seis produtos usando `map()` e `CardProduto`.
- **Sobre**: apresentação da loja e diferenciais.
- **Footer**: autoria (Henrique Cruz), ano 2026 e contatos demonstrativos.
- **App**: integra os componentes e controla o carrinho com `useState`.

O carrinho é uma demonstração local, sem checkout ou processamento de pagamentos.
