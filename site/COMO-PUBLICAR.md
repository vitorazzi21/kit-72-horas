# Como publicar a página no GitHub Pages

Arquivo a subir: `index.html` (esta pasta). Só ele.

## 1. Criar o repositório
1. Entre em https://github.com/new
2. Repository name: `kit-72-horas` (ou outro nome; ele aparece no link).
3. Marque **Public** (no plano grátis, o Pages só funciona com repositório público).
4. Clique em **Create repository**.

## 2. Subir o arquivo
1. Na página do repositório, clique em **uploading an existing file**.
2. Arraste o `index.html` desta pasta.
3. Clique em **Commit changes**.

## 3. Ativar o Pages
1. No repositório: **Settings** → **Pages** (menu da esquerda).
2. Em **Source**, escolha **Deploy from a branch**.
3. Branch: **main**, pasta **/ (root)**. Clique em **Save**.
4. Espere 1 a 2 minutos e recarregue. O link aparece no topo:
   `https://SEU-USUARIO.github.io/kit-72-horas/`

## Para atualizar depois
1. Edite `index.html` (ou peça ao Claude).
2. No repositório, clique no `index.html` → ícone de lápis → cole o conteúdo novo, ou apague e suba o arquivo de novo.
3. Commit changes. O site atualiza em 1 a 2 minutos.

## Pendente
- Link do checkout: trocar `CHECKOUT_URL` no topo do `index.html`.
