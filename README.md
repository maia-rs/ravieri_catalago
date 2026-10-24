# ALAN MAISON — Luxury E-Commerce (Edição 2026)

Implementação inspirada no projeto de referência **Luxury Watch E-commerce Site** com vídeo em tela cheia na capa (*hero*).

## 🎬 Destaques da Nova Versão

- **Capa com Vídeo em Loop Contínuo**:
  - Utiliza o vídeo [`imgens/Luxury_wristwatch_hands_spinning_20261022224415.mp4`](file:///home/rodrigo_maia/site_alan/imgens/Luxury_wristwatch_hands_spinning_20261022224415.mp4) em tela cheia (`h-screen`) com reprodução automática, silenciada e sobreposição cinematográfica suave.
  - Tipografia imponente com botão de rolagem suave para as coleções e para a história da marca.
- **Estrutura Baseada na Referência**:
  - **Navegação Fixa com Logo em Coroa**: Insígnia clássica, links para *Coleções*, *Nossa História*, *Manufatura* e botão de sacola com contador em tempo real.
  - **História & Artesanato (`#story` e `#craftsmanship`)**: Seção sobre tradição relojoeira, métricas de tradição (130+ anos, 40+ artesãos) e os 4 pilares: *Precisão*, *Luxo*, *Herança* e *Garantia*.
  - **Catálogo de Peças (`#collections`)**:
    - Destaque para as peças autênticas do diretório ([`relogio.jpeg`](file:///home/rodrigo_maia/site_alan/imgens/relogio.jpeg), [`bolda.jpeg`](file:///home/rodrigo_maia/site_alan/imgens/bolda.jpeg), [`oculos.jpeg`](file:///home/rodrigo_maia/site_alan/imgens/oculos.jpeg)).
    - Filtros por coleção (*Heritage*, *Maroquinerie*, *Optique*, *Sport*).
    - Botões *Ver Detalhes* e *Adicionar à Sacola*.
  - **Modal de Detalhes do Produto**:
    - Ficha técnica completa (calibre, caixa, mostrador, estanqueidade e pulseira) com selos de garantia e botão de adição direta.
  - **Sacola de Compras Deslizante (`Cart`)**:
    - Painel lateral com controle de quantidades (`+` / `-`), remoção de itens, cálculo automático de subtotal e botão para **finalizar o pedido diretamente pelo WhatsApp** com a lista de peças preenchida.
  - **Notificações Toast**: Alertas discretos ao adicionar peças ou alterar quantidades.

---

## 📂 Arquivos do Projeto

- [`index.html`](file:///home/rodrigo_maia/site_alan/index.html) — HTML completo com vídeo de capa e seções estruturadas.
- [`css/luxury.css`](file:///home/rodrigo_maia/site_alan/css/luxury.css) — Estilização do vídeo de fundo, modais e gaveta lateral.
- [`js/catalog.js`](file:///home/rodrigo_maia/site_alan/js/catalog.js) — Gerenciamento do carrinho, catálogo e cálculo de valores.
- [`imgens/`](file:///home/rodrigo_maia/site_alan/imgens) — Vídeo e fotos das peças originais.
