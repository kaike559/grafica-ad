# AD ADESIVOS — Sistema (HTML)

Este repositório contém um sistema simples em **HTML/CSS/JS** (sem backend), com login local via `localStorage`.

## ✅ Como publicar no GitHub Pages (mais fácil)

1. Crie um repositório no GitHub (ex.: `ad-adesivos-sistema`).
2. Faça upload de **todos os arquivos** desta pasta (na raiz do repositório).
3. No GitHub, vá em:
   - **Settings → Pages**
   - Em **Build and deployment**
     - **Source**: *Deploy from a branch*
     - **Branch**: `main` (ou `master`)
     - **Folder**: `/ (root)`
4. Salve. Aguarde o GitHub gerar a URL do site.

> **Entrada do site:** `index.html`

## 🔐 Observações importantes (segurança)
- O login funciona **somente no navegador** e os usuários/senhas ficam no `localStorage`.
- Isso **não é seguro** para uso público na internet (qualquer pessoa pode abrir o DevTools e ver/alterar dados).
- Para segurança real, o ideal é um backend (ex.: Node/Express, Firebase Auth, Supabase, etc.).

## Arquivos
- `login_preto_amarelo.html` — tela de login
- `index.html` — painel inicial
- `fluxo.html` — fluxo de caixa
- `clientes.html` — clientes
- `orcamento_novo.html` — orçamento
- `recibo_novo.html` — recibo
- `backup.html` — backup (admin)

