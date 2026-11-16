# Contagem SOC Mobile

Aplicativo HTML/PWA para contagem por setores SOC no POCO F8, com cálculos em linha, totais automáticos, exportação PNG, backup e funcionamento offline.

## Publicação GitHub Pages

1. Acesse [Settings > Pages](https://github.com/franciscoaniltoan/Transfer/settings/pages).
2. Em **Build and deployment**, selecione **Deploy from a branch**.
3. Em **Branch**, selecione `main` e `/(root)`, depois **Save**.
4. Quando o GitHub indicar que o site foi publicado, abra https://franciscoaniltoan.github.io/Transfer/ no Chrome Android.
5. No menu do Chrome (⋮), escolha **Instalar app** ou **Adicionar à tela inicial**.

O arquivo `index.html` é o app; `manifest.webmanifest` e os ícones configuram a instalação; `service-worker.js` mantém o app disponível offline.

**Privacidade:** as contagens ficam armazenadas localmente no dispositivo. Elas não são enviadas ao GitHub. Faça backup das contagens antes de limpar os dados do navegador ou trocar de aparelho.
