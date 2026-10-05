# MeuDinheiro

App de finanças pessoais da Isabelle. Pergunta central: **quanto eu ainda posso gastar?**

- Publicado pelo GitHub Pages.
- Dados no Firebase Realtime Database, projeto `isabelle-financas`, gaveta `financas/meudinheiro-5b8e31c2d9f4`.
- Também salva no aparelho e funciona sem internet.

## Arquivos
- `index.html` — o app inteiro
- `manifest.json` — nome, cores e ícones para instalar no celular
- `sw.js` — deixa o app abrir sem internet
- `icons/` — ícones

## Publicar uma versão nova
1. Troque o arquivo no repositório.
2. Em `sw.js`, aumente a versão em `CACHE` (ex.: `meudinheiro-v1.1`).
