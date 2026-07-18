# FB Restaurações

Landing page estática preparada para GitHub e Cloudflare Pages.

## Publicação no Cloudflare Pages

1. Envie o conteúdo desta pasta para a raiz de um repositório GitHub.
2. No Cloudflare, abra **Workers & Pages** e conecte o repositório.
3. Use `None` como framework preset.
4. Deixe o comando de build vazio.
5. Use `/` como diretório de saída.

## Antes do domínio definitivo

Substitua `https://SEU-DOMINIO.com.br/` em:

- `index.html`
- `robots.txt`
- `sitemap.xml`

## Commit inicial

```bash
git init
git add .
git commit -m "feat: publica landing page da FB Restaurações"
```
