# mr-manual: página inicial do mr.manualdorecemnascido.com.br

- Repo `brunotropolis/mr-manual` (GitHub Pages, sem CNAME, serve em `brunotropolis.github.io/mr-manual/`).
- No ar via Worker Cloudflare `mr-home` (código e deploy em `D:\CLAUDE\mr-manual-worker\`): só `/` e `/mrn-assets/*` vêm daqui; o resto do subdomínio é o WordPress.
- Publicar mudança: editar `index.html`, commit + push em `main`, esperar o Pages (~1 min). O Worker guarda a home por 2 min no cache.
- Imagens ficam em `mrn-assets/` (prefixo próprio pra não colidir com caminhos do WordPress).
- Tracking: GTM `GTM-MNFVDBCP`, Clarity `whcopa4tqv`, repasse de UTM/fbclid/fbp/fbc pro checkout Greenn. VSL vturb `684d8948a513dfb8ce77ee91` (domínio precisa estar liberado na vturb > Segurança > Domínios).
- Diário: `D:\CLAUDE\DIARIO-sites.md` (bloco "Manual do Recém-Nascido").
