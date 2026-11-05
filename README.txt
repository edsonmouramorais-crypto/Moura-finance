MOURA FINANCE — PWA PARA IPHONE (GRATUITO)

O projeto é uma PWA (web app instalável) e não precisa App Store/Apple Developer.

COMO USAR:
1) Para publicar/servir a PWA, os arquivos precisam estar em HTTPS. Maneira simples: criar conta gratuita no GitHub e usar GitHub Pages (ou Netlify/Vercel free).
2) Suba index.html, manifest.json, sw.js e os ícones para um repositório.
3) Ative GitHub Pages nas configurações do repositório.
4) Abra o endereço HTTPS no Safari do iPhone.
5) Safari > botão Compartilhar > Adicionar à Tela de Início > Adicionar.
6) Abra pelo ícone Moura Finance.

NOTA:
- Dados são salvos no armazenamento local do navegador/iPhone (localStorage). Não sincroniza nem faz backup na nuvem.
- Protótipo inicial: pagamento manual, totais e categorias; recorrência pode gerar próxima ocorrência após pagamento.
- Anexos ainda não armazenam o conteúdo; apenas nome é registrado. Para guardar anexos, implementar IndexedDB.
- Notificações automáticas em PWA iOS têm restrições e exigem instalação, versão compatível do iOS e permissão; alertas persistentes confiáveis precisam evoluir.
- Recomenda-se exportação/backup antes de usar com dados financeiros reais.
