# Planos de Estudo · Curso Loghus Barra

Site estático publicado pelo **GitHub Pages**. Cada aluno tem a própria página em `alunos/`.

## Estrutura

```
PLANOS DE ESTUDO/
├── index.html        → página inicial (não lista os alunos, de propósito)
├── alunos/
│   └── julia-ogliari-2026.html
├── robots.txt        → pede aos buscadores que não indexem o site
├── .nojekyll         → faz o GitHub servir os arquivos exatamente como estão
└── README.md         → este arquivo
```

## Publicar pela primeira vez

1. Em github.com: **+ → New repository** → nome `planos-loghus` → **Public** → **Create repository**.
2. Clique em **uploading an existing file** e arraste **todo o conteúdo desta pasta**
   (index.html, robots.txt, .nojekyll, README.md e a pasta `alunos`). → **Commit changes**.
   - No Mac o `.nojekyll` fica oculto no Finder: aperte **Cmd + Shift + .** para ver.
3. **Settings → Pages** → Source: *Deploy from a branch* → Branch **main** / **(root)** → **Save**.
4. Em 1–2 minutos o site sai em `https://SEU-USUARIO.github.io/planos-loghus/`.

Link da aluna: `https://SEU-USUARIO.github.io/planos-loghus/alunos/julia-ogliari-2026.html`

## Adicionar um novo aluno

1. Salve o HTML do plano em `alunos/` com nome **minúsculo, sem espaços nem acentos**:
   `nome-sobrenome-2026.html`.
2. No GitHub, entre na pasta `alunos` → **Add file → Upload files** → arraste o arquivo → **Commit changes**.
3. O link fica `.../planos-loghus/alunos/nome-sobrenome-2026.html`.

Para atualizar um plano, suba de novo um arquivo com o **mesmo nome**: ele substitui o anterior.

## Privacidade

- O repositório é público: qualquer pessoa com o link vê a página.
- A página inicial não lista os alunos, e as páginas pedem para não serem indexadas
  (`robots.txt` + `noindex`). Isso dificulta encontrar os planos, mas não é senha.
- Não use `git` direto nesta pasta: ela fica no Google Drive, e o Drive costuma corromper a pasta `.git`.
  Suba os arquivos pelo site do GitHub.
