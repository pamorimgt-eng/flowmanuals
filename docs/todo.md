# TODO

## Estado atual (30 ago 2026)
- Shopify ligado à loja certa (flowmanuals.com / uauf3z-hp.myshopify.com).
- `sections/lp-stratton-manual.liquid` e `templates/page.flow-manual-lp.json`
  publicados no tema de RASCUNHO "Ride - Stratton draft" (não é o tema live "Ride").
- Página "Flow Manual" criada (handle `flow-manual`, `isPublished: true` para
  permitir pré-visualização). No tema live isto mostra uma página em branco
  (sem o template certo); no tema de rascunho mostra a LP completa.
- Preview: https://uauf3z-hp.myshopify.com/pages/flow-manual?preview_theme_id=203975754066
- Conteúdo confirmado a renderizar: hero, 6 bullets, pattern interrupt, bloco
  "why this manual still works", 3 symptom cards, mechanism, 4 módulos, 3 tiers
  de pricing (€17,52 / €24,52 / €34,52), trust block, garantia, 7 FAQs, CTA final
  com disclaimer legal.

## Por rever com o utilizador
- [ ] Ver a LP no preview acima e dar feedback de copy/layout.
- [ ] Decidir: esta LP substitui a homepage atual, ou fica como página separada
      para tráfego pago (ex: anúncios a apontar direto para /pages/flow-manual)?
- [ ] Os 3 tiers de pricing (Manual / Manual+Swipe File / Manual+Swipe File+Audio)
      são novos — o produto atual só tem 1 variant a €17,52. Confirmar se
      queres mesmo 3 tiers (implica criar bónus reais: swipe file PDF e áudio)
      ou manter só 1 produto por agora.

## Pendente (depois do review)
- [ ] Imagens reais via Higgsfield: mockup do eBook (hero), imagem de página do
      manual ("about"), imagem para o bloco "mechanism" — atualmente a mostrar
      placeholders partidos.
- [ ] Se avançar com os 3 tiers: criar variants no produto Shopify e ligar cada
      um ao ficheiro certo na app de digital downloads (bónus ainda não existem).
- [ ] Publicar o tema de rascunho como live (ou fazer merge das secções no tema
      "Ride" atual) só depois de aprovado.
- [ ] Configurar/rever páginas legais (Termos, Privacidade, Reembolso).
- [ ] Testar checkout completo em mobile.

## Depois de publicado a sério
- [ ] Recolher testemunhos reais dos primeiros compradores (não inventar).
- [ ] Rever `docs/legal-notas.md` antes de correr tráfego pago a sério.
