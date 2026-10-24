# Linktree · Dra. Júlia Vefago

Site estático (HTML + CSS, sem build). Páginas:

- `/` → index.html (Início)
- `/conteudos` → conteudos.html
- `/instituto` → instituto.html

## Deploy

1. Crie um repositório no GitHub e envie todos os arquivos desta pasta (a raiz do repositório deve conter `index.html`).
2. Na Vercel: **Add New → Project → Import** o repositório.
3. Framework Preset: **Other**. Build Command: vazio. Output Directory: vazio (raiz).
4. Deploy. Para usar domínio próprio: Project → Settings → Domains.

`vercel.json` ativa URLs limpas (`/conteudos` em vez de `/conteudos.html`) e cache longo para `/assets`.
