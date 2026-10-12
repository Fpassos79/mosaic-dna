# MOSAIC DNA v4.0 — online

Interface estática para GitHub Pages, com consulta e sincronização manual de resultados via API da CAIXA.

## Publicar
Envie `index.html`, `manifest.webmanifest` e `README.md` para a raiz do repositório `mosaic-dna` na branch `main`. GitHub Pages deve apontar para `main / (root)`.

## Limitações
A API da CAIXA pode bloquear chamadas do navegador por CORS; nesse caso, importe resultados em CSV ou configure um backend autorizado. Não existe atualização automática no servidor nem sincronização entre aparelhos. Os resultados são armazenados no localStorage. Não há base histórica oficial completa embutida.

## Segurança científica
Padrões passados não oferecem vantagem comprovada em sorteios justos. SELECT-30/35 estão encerrados.
