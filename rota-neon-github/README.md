# Rota Neon Brasil — GitHub Pages

## Publicar no GitHub
1. Crie um repositório no GitHub (por exemplo, `rota-neon-brasil`).
2. Envie **todos os arquivos desta pasta** para a raiz do repositório: `index.html`, `manifest.webmanifest` e `service-worker.js`.
3. No repositório, abra **Settings → Pages**.
4. Em **Build and deployment**, selecione **Deploy from a branch**, escolha `main` e `/ (root)`, e salve.
5. Aguarde a publicação e abra o endereço HTTPS informado pelo GitHub Pages.

## Instalar no celular
- **Android:** abra o endereço no Chrome → menu ⋮ → **Adicionar à tela inicial** ou **Instalar app**.
- **iPhone:** abra no Safari → botão Compartilhar → **Adicionar à Tela de Início**.
- Autorize a localização quando o navegador pedir. O GPS requer HTTPS e permissão de localização.

## Observações importantes
- A navegação, pesquisa de endereços, mapas e dados de radares dependem de serviços externos e de internet; o cache não torna esses serviços disponíveis offline.
- O projeto usa uma chave MapTiler no código do navegador. Antes de publicar um repositório público, configure restrições de domínio/origem para a chave no painel do MapTiler, permitindo apenas o domínio do seu GitHub Pages. Não reutilize uma chave secreta em código público.
- Os dados de ocorrências são guardados localmente neste aparelho, não compartilhados com outros usuários.
- O projeto usa serviços públicos de terceiros (MapTiler, OpenStreetMap/Nominatim, OSRM e Overpass); disponibilidade e limites desses serviços podem variar.
