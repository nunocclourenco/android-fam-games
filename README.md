# Sala de Jogos 🎮

Web app (PWA) com dois jogos para dois jogadores no mesmo dispositivo:

- **4 em Linha** — encaixa 4 peças seguidas (horizontal, vertical ou diagonal).
- **Jogo do Galo** — 3 em linha para ganhar.

Sem inteligência artificial: só o tabuleiro e as regras. Funciona no telemóvel e no PC, e pode ser adicionado ao ecrã principal como um ícone.

## Pôr online no GitHub Pages

1. Cria um repositório novo e **vazio** no GitHub (sem README), por exemplo `android-fam-games`.
2. No teu terminal (Mac), dentro desta pasta:

   ```bash
   git remote add origin git@github.com:O-TEU-USER/android-fam-games.git
   git push -u origin main
   ```

3. No GitHub: **Settings → Pages → Build and deployment**. Em *Source* escolhe **Deploy from a branch**, *Branch* = **main** e pasta **/ (root)**. Guarda.
4. Ao fim de ~1 minuto o link fica disponível em:
   `https://O-TEU-USER.github.io/android-fam-games/`

## Instalar no telemóvel (Android)

1. Abre o link acima no **Chrome**.
2. Menu dos três pontos (⋮) → **Adicionar ao ecrã principal**.
3. Fica um ícone "Jogos" no telemóvel, abre em ecrã inteiro como uma app.
