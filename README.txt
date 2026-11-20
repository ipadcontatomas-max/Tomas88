STUG Guarda — PWA

Ficheiros:
- index.html: planeador original
- manifest.webmanifest: configuração de instalação
- sw.js: cache da aplicação e suporte offline básico
- icon-192.png / icon-512.png: ícones PWA
- apple-touch-icon.png: ícone para iPhone/iPad

Publicação e instalação:
1. Coloca todos os ficheiros da pasta no mesmo diretório do teu alojamento.
2. Publica o diretório num servidor HTTPS.
3. Abre a página no Chrome/Android e escolhe "Instalar aplicação".
4. No iPhone/iPad, abre no Safari, toca em Partilhar e escolhe
   "Adicionar ao ecrã principal".

Importante:
- O HTML já inclui o registo do service worker e a gestão de atualizações.
- O núcleo local e os dados incluídos no HTML ficam disponíveis em cache.
- Mapas, tiles OpenStreetMap, geocodificação e Google Maps dependem da Internet.
- A instalação PWA exige HTTPS (ou localhost durante testes).
