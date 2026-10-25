# Como publicar o app (GitHub Pages, grátis)

1. No GitHub, crie um repositório público chamado `vistoria` (sem README).
2. Envie todos os arquivos desta pasta `pwa/` para a raiz do repositório (index.html, manifest.webmanifest, sw.js e a pasta icons).
3. No repositório, vá em Settings > Pages, escolha "Deploy from a branch", branch `main`, pasta `/ (root)` e salve.
4. Em um ou dois minutos o app fica em `https://SEU-USUARIO.github.io/vistoria/`.

Para pôr na tela inicial:
- Android (Chrome): abra o link e toque em "Instalar" no aviso, ou no menu de três pontos > "Instalar app".
- iPhone (Safari): abra o link, toque em Compartilhar > "Adicionar à Tela de Início".

Os dados de cada pessoa ficam só no celular dela. Para trocar de aparelho, use o backup dentro do app.
Ao atualizar o app, troque a versão na primeira linha de `sw.js` (ex.: vistoria-v2) para os celulares pegarem a nova versão.
