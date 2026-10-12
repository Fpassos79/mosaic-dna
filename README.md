# MOSAIC DNA Online — versão publicável

Este pacote adapta a versão 3 do MOSAIC DNA para hospedagem web HTTPS e adiciona um botão de consulta do último concurso na API pública de loterias da CAIXA. Não há garantia de que a API aceite requisições diretas do navegador (CORS); quando bloqueadas, o app mostra um erro, sem inventar dados.

## Publicar no GitHub Pages
1. Crie um repositório GitHub (ex.: mosaic-dna).
2. Envie index.html e manifest.webmanifest para a raiz do repositório.
3. Settings > Pages > Deploy from a branch > main / (root) > Save.
4. Abra o endereço HTTPS informado pelo GitHub. No Android, use menu do Chrome > Adicionar à tela inicial.

## Limitações atuais
- Não há backend nem banco de dados compartilhado. Os registros são locais a cada navegador.
- A consulta online cobre apenas o último concurso e pode ser bloqueada por CORS.
- O histórico completo dos sorteios não está embutido; importe CSV confiável na aba Resultados.
- As pesquisas do MOSAIC estão documentadas em resumo, não implementadas integralmente como pipelines reproduzíveis.
- Para sincronização multi-dispositivo, contas de usuário, atualização automática de todo o histórico e análises remotas é preciso desenvolver e implantar backend seguro, banco de dados e tarefas agendadas.
