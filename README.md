# BIOFAUNA

Site React + Vite com catálogo inicial, fichas, mapa interativo, gráficos, comparação de espécies, conscientização, apresentação institucional e referências.

## Executar
1. Instale Node.js LTS: https://nodejs.org/
2. Extraia o ZIP e abra a pasta no VS Code.
3. Execute `npm install` e depois `npm run dev`.
4. Para gerar a versão de publicação: `npm run build` (pasta `dist`).

## Publicar na Vercel
Envie a pasta para um repositório GitHub, importe-o na Vercel, use `npm run build` como comando e `dist` como diretório de saída. `vercel.json` já contém o redirecionamento SPA.

## Limitações transparentes desta primeira versão
Os gráficos refletem somente os seis registros iniciais, não toda a fauna brasileira. As marcações do mapa são referências regionais ilustrativas, não pontos precisos de ocorrência. Categorias de conservação precisam ser conferidas nas listas oficiais vigentes antes da publicação. Fotografias externas exigem conferência de licença e atribuição. O catálogo está em `src/data.js`.
