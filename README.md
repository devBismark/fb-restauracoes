# FB Restaurações

Landing page estática publicada com GitHub e Cloudflare Pages.

## Endereço atual

- https://fb-restauracoes.pages.dev/

## Configuração no Cloudflare Pages

- Framework preset: `None`
- Build command: vazio
- Build output directory: `.`
- Production branch: `main`

## Atualizações

Qualquer `git push` para a branch `main` inicia uma nova publicação automática.

```bash
git add .
git commit -m "fix: refina conteúdo e configurações de produção"
git push
```

## Domínio próprio

Quando um domínio próprio for conectado, atualizar a URL em:

- `index.html` (`canonical` e `og:url`)
- `robots.txt`
- `sitemap.xml`
