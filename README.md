# Flow Manuals

Loja Shopify mono-produto (flowmanuals.com) a vender o manual de vendas restaurado
da Stratton Oakmont em formato digital (PDF).

## Estrutura

- `ideias.pdf` — spec original com a estrutura completa da landing page (secções, copy,
  pricing, guardrails éticos/legais, checklist técnico).
- `theme/sections/lp-stratton-manual.liquid` — secção Shopify (Online Store 2.0) com toda
  a LP: hero, bullets, agitação do problema, "o que está incluído", pricing (3 tiers),
  garantia, FAQ e disclaimer legal. Totalmente editável no Theme Editor (blocks para
  bullets, symptom cards, módulos, tiers de preço e FAQ).
- `theme/templates/page.flow-manual-lp.json` — template de página que usa a secção acima,
  para servir como a página funil (sem navegação, mobile-first).
- `docs/` — notas de copy e decisões de posicionamento.

## Aviso legal / posicionamento

O produto é apresentado como um documento histórico restaurado (não como material
"oficial" endossado pelo Jordan Belfort). O footer da LP inclui disclaimer explícito de
não afiliação, para reduzir risco de publicidade enganosa / uso indevido de nome e
imagem. Ver `docs/legal-notas.md`.

## Como publicar no Shopify

1. Na loja Shopify (Online Store > Themes > Edit code), criar:
   - `sections/lp-stratton-manual.liquid` (copiar conteúdo daqui)
   - `templates/page.flow-manual-lp.json` (copiar conteúdo daqui)
2. Criar uma página ("Flow Manual") e atribuir-lhe o template `page.flow-manual-lp`.
3. No Theme Editor, preencher imagens (hero, "about", mechanism) e ajustar os links de
   compra de cada tier de preço para o botão/variant correto do produto.
4. Configurar entrega digital (app de digital downloads) e ligar o PDF final ao produto.

## Próximos passos

Ver lista de pendências em `docs/todo.md`.
