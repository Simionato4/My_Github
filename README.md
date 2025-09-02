# Guia Prático: Git & GitHub

## Branches
- `main` (produção / GitHub Pages)
- `develop` (integração)

## Features (cada uma com PR → develop)
- `feat/conceitos` – Conceitos básicos (Git, repo, commit, push/pull)
- `feat/fluxos` – Fluxos de trabalho (branches, PRs, reviews)
- `feat/conflitos` – Resolução de conflitos (merge/rebase)

## Integração final
- PR `develop` → `main`
- Deploy com GitHub Pages (branch `main`, pasta root)

## Como rodar
Abra `index.html` no navegador.

## Como simular e resolver conflitos
1. Crie duas branches e edite a mesma linha em ambas.
2. Gere o merge/rebase para provocar o conflito.
3. Resolva no editor (remova os marcadores), `git add`, e finalize com `git commit` (merge) ou `git rebase --continue` (rebase).
