# Loja de Materiais Digitais — CISC Saúde

Página estática servida por um Cloudflare Worker (static assets).

- `public/index.html` — a página (imagens embutidas em base64)
- `public/favicon.ico`
- `wrangler.jsonc` — configuração do Worker

## Deploy

```bash
npx wrangler deploy
```

Ou conecte este repositório em Cloudflare Dashboard → Workers & Pages → Create → Import a repository (build command vazio, deploy command `npx wrangler deploy`).
