# saezmarketing.com

Site da Sáez Marketing. HTML estático, sem build e sem framework.
Publicado pelo Cloudflare Pages: sem comando de build; os arquivos servidos são os de `public/`.

| Arquivo | O que é |
|---|---|
| `public/index.html` | A página principal |
| `public/construtora.html` · `sindicato.html` · `ong.html` | Levantamento Quantitare, um por setor |
| `public/assets/` | Foto, símbolo do Quantitare e a imagem de compartilhamento |
| `wrangler.jsonc` | Diz à Cloudflare que o site é estático e mora em `public/` |

Só o que está em `public/` vai para o ar.

**Este repositório é o destino, não a origem.** As páginas são geradas em
`neftasaez/nefta-virtual`, em `documentos/marca/site/`, e copiadas para cá.
Editar um arquivo aqui direto faz a alteração se perder na próxima cópia.
