# ClickGold Rush - Protótipo Web (HTML5 / Phaser)

Este repositório contém um protótipo funcional do jogo **ClickGold Rush** — um clicker/idle simples pensado para **web mobile** com monetização por anúncios e microtransações.

## O que há aqui
- `index.html` — entrada do jogo.
- `js/game.js` — código Phaser principal.
- `css/style.css` — estilos leves para página.
- `assets/` — SVGs simples (minerador, moeda, background).
- `netlify.toml` — configuração mínima para deploy (opcional).

## Instruções rápidas (deploy)
1. Faça login no GitHub e crie um repositório (ou use local).
2. Suba todos os arquivos e conecte ao Netlify (ou Vercel).
3. No Netlify: **Create new site -> Import from Git -> choose repo**.
4. Depois do deploy, seu jogo estará disponível em `https://<your-site>.netlify.app`.

## Integração de anúncios (AdMob / AdSense)
- Para inserir anúncios, crie conta no AdSense/AdMob.
- Quando aprovado, adicione os scripts fornecidos pelo Google em `index.html` e crie placeholders onde deseja exibir anúncios (ex.: `div#ad-top`).
- Para anúncios reward (vídeo recompensado), use o SDK/endpoint do provedor e chame a função de recompensa para creditar o jogador.

## Integração com Firebase (opcional)
- Para rankings, autenticação social e armazenamento de progresso, crie um projeto no Firebase.
- Adicione o SDK (cdn) ao `index.html` e inicialize com sua configuração no arquivo `js/game.js` (veja comentários no arquivo).
- Use Firestore/Realtime Database para salvar pontuações e Firebase Auth para login.

## Observações
- Este protótipo usa recursos SVG simples para manter tudo leve.
- Substitua os assets por ilustradores/profissionais para deixar o jogo com cara de produzido.
- Leia o guia de políticas do AdSense/AdMob antes de ativar monetização.

Boa sorte! 🚀
