# Cupons & Descontos — Fernanda Damasceno

Página única (`index.html`), sem dependências, pronta pra GitHub Pages.
Tema claro (mesmo DNA da página pessoal: navy/cobalto/prata).

Hub de **cupons, descontos e links de indicação** de coisas que a Fernanda usa e
recomenda de verdade. Inclui aviso de transparência ("links de indicação · sem
custo extra pra você") para proteger a confiança da audiência.

## Conteúdo atual
- **Saúde & bem-estar:** Queima Diária (link de indicação: `quei.ma/c/143ghfa9dj457`)

## Como adicionar um cupom/desconto novo
Copie um bloco `<li>...</li>` e troque:
- `href` → o link
- `.t` → nome
- `.s` → descrição curta
- (opcional) adicione `<span class="coupon">CÓDIGO</span>` dentro de `.txt` para
  mostrar o código do cupom num "chip" verde.

Crie novas seções duplicando um `<p class="section-label">...</p>` + `<ul class="links">`.

## 🚀 Publicar / atualizar
Repo público `linksdescontos`. Cada `git push` na `main` redeploya o GitHub Pages.
URL: `https://ferdamas96.github.io/linksdescontos/`
