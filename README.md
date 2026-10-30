# Altus Mídia — Site

Site estático da agência Altus Mídia (HTML, CSS e JS em arquivos únicos, sem build).

## Estrutura
- `index.html` — página principal
- `privacidade/index.html` — Política de Privacidade (endereço `/privacidade`)
- `_headers` — cabeçalhos de segurança do Cloudflare Pages

## Publicar no Cloudflare Pages (via GitHub)
1. Cloudflare → Workers e Pages → Criar → Pages → Conectar ao Git.
2. Escolha este repositório e a branch `main`.
3. Framework preset: **None**
4. Build command: *(deixe vazio)*
5. Build output directory: `/`
6. Salvar e implantar. A cada `git push` na `main`, o site atualiza sozinho.
