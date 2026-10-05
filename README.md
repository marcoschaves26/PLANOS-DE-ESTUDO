# Planos de Estudo · Curso Loghus Barra

Site estático publicado pelo **GitHub Pages**. Cada aluno tem a própria página em `alunos/`.

## Estrutura

```
PLANOS DE ESTUDO/
├── index.html        → página inicial (não lista os alunos, de propósito)
├── alunos/
│   ├── julia-ogliari-2026.html
│   ├── bernardo-roseti-2026.html
│   ├── eduarda-javaroni-2026.html
│   └── lucas-leal-2026.html
├── robots.txt        → pede aos buscadores que não indexem o site
├── .nojekyll         → faz o GitHub servir os arquivos exatamente como estão
└── README.md         → este arquivo
```

## Planos publicados

| Aluno | Arquivo | Período do plano |
|---|---|---|
| Julia Ogliari Balthazar | `alunos/julia-ogliari-2026.html` | 6 a 31/10/2026 |
| Bernardo Borges Brasil Zopelari Roseti | `alunos/bernardo-roseti-2026.html` | 6 a 31/10/2026 |
| Eduarda Ferrer Javaroni | `alunos/eduarda-javaroni-2026.html` | 6 a 31/10/2026 |
| Lucas Leal de Aguiar | `alunos/lucas-leal-2026.html` | 6 a 31/10/2026 |

Cada página traz: desempenho nas quatro áreas ao longo dos simulados de 2026, grade de
itens questão a questão, habilidades e conteúdos recorrentes nos erros, a rotina semanal
encaixada na grade de aulas e plantões da Turma Medicina, e o cronograma das quatro
semanas de outubro com checkpoint por semana.

**Fontes:** Painel de Simulados do Curso Loghus (Power BI) e as fichas-mapa de conteúdos,
competências e habilidades de cada simulado. Dados de 02/10/2026, já com o 2º dia do
10º simulado.

## Publicar pela primeira vez

1. Em github.com: **+ → New repository** → nome `planos-loghus` → **Public** → **Create repository**.
2. Clique em **uploading an existing file** e arraste **todo o conteúdo desta pasta**
   (index.html, robots.txt, .nojekyll, README.md e a pasta `alunos`). → **Commit changes**.
   - No Mac o `.nojekyll` fica oculto no Finder: aperte **Cmd + Shift + .** para ver.
3. **Settings → Pages** → Source: *Deploy from a branch* → Branch **main** / **(root)** → **Save**.
4. Em 1–2 minutos o site sai em `https://SEU-USUARIO.github.io/planos-loghus/`.

Links dos alunos: `https://SEU-USUARIO.github.io/planos-loghus/alunos/NOME-DO-ARQUIVO`

## Adicionar ou atualizar um aluno

1. Salve o HTML do plano em `alunos/` com nome **minúsculo, sem espaços nem acentos**:
   `nome-sobrenome-2026.html`.
2. No GitHub, entre na pasta `alunos` → **Add file → Upload files** → arraste o arquivo → **Commit changes**.
3. Para **atualizar** um plano, suba de novo um arquivo com o **mesmo nome**: ele substitui o anterior.

## Privacidade

- O repositório é público: qualquer pessoa com o link vê a página.
- A página inicial não lista os alunos, e as páginas pedem para não serem indexadas
  (`robots.txt` + `noindex`). Isso dificulta encontrar os planos, mas **não é senha** —
  as páginas trazem nome completo e desempenho dos alunos. Se isso for um problema,
  o repositório pode ser privado e os planos distribuídos como arquivo.
- Não use `git` direto nesta pasta: ela fica no Google Drive, e o Drive costuma corromper a pasta `.git`.
  Suba os arquivos pelo site do GitHub.
