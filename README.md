# Parabellum Jaraguá — landing page

Página estática (um único `index.html`, sem build). Abra direto no navegador ou publique no GitHub Pages.

## Imagens (opcionais, entram sozinhas)

Salve em `assets/img/` com estes nomes exatos:

| Arquivo    | Uso                                   | Formato sugerido            |
|------------|---------------------------------------|-----------------------------|
| `logo.png` | Logo no menu e no rodapé (redondo)    | quadrado, 256×256, fundo escuro |
| `hero.jpg` | Fundo da primeira dobra               | horizontal, ~1920×1080, < 400 KB |
| `og.jpg`   | Prévia ao compartilhar o link         | 1200×630                    |

Sem os arquivos, a página usa o retículo vermelho e o fundo escuro.

## Publicar no GitHub Pages

1. Suba esta pasta para um repositório.
2. Settings → Pages → Source: `Deploy from a branch` → branch `main`, pasta `/ (root)`.
3. Depois de publicado, troque `og:image` no `index.html` pela URL absoluta (ex.: `https://usuario.github.io/repo/assets/img/og.jpg`).

## Onde editar

- Contatos/WhatsApp: busque por `wa.me/5547991170909`.
- Horários do clube: bloco `HORÁRIOS` no HTML **e** o objeto `H` no `<script>` (é ele que calcula o selo "Aberto agora").
