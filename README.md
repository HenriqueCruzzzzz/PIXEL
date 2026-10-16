# Pixel Store — Loja Virtual React

Projeto acadêmico desenvolvido com React e Vite.

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

## Publicar no GitHub

Crie um repositório vazio chamado `pixel-store` em https://github.com/new e execute:

```bash
git init
git add .
git commit -m "Projeto Pixel Store em React"
git branch -M main
git remote add origin https://github.com/SEU-USUARIO/pixel-store.git
git push -u origin main
```

Substitua `SEU-USUARIO` pelo seu usuário do GitHub.

## Hospedar na Vercel

1. Entre em https://vercel.com/new.
2. Importe o repositório `pixel-store` do GitHub.
3. Selecione **Vite** como framework (normalmente detectado automaticamente).
4. Build command: `npm run build`; output directory: `dist`.
5. Clique em **Deploy** e copie a URL fornecida.

## Entrega

- GitHub: adicionar link do repositório publicado.
- Print: `print-tela-inicial.png` (incluído no ZIP).
- Componentes: descritos neste README.
- Vercel: adicionar link após deploy.
