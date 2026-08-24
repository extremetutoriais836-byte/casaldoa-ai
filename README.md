# Açaiteria Lucrativa — página de vendas

Página estática de uma única rota. Sem build, sem dependências.

## Estrutura
```
index.html      página completa (HTML + CSS + JS inline)
img/            logos, foto da live e capas dos 5 volumes (WebP)
vercel.json     cache das imagens e cabeçalhos de segurança
```

## Deploy
1. Suba estes arquivos na **raiz** do repositório (não dentro de uma pasta).
2. No Vercel: Add New → Project → importe o repositório.
3. Framework Preset: **Other**. Build Command e Output Directory: deixe em branco.
4. Deploy.

Cada push na branch principal republica a página automaticamente.

## Manutenção
- **Link do checkout:** `https://pay.kiwify.com.br/2CgbKoX` — aparece em 4 lugares no `index.html`.
- **Preço:** R$ 49,90 com âncora em R$ 79,90. Se mudar, procure por `49,90` e `79,90`.
- **Imagens:** têm cache de 1 ano. Ao trocar uma capa, use um nome de arquivo novo
  (ex: `capa-vol1-v2.webp`), senão quem já visitou continua vendo a antiga.
