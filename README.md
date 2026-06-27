# SmartCarta

Carta digital QR para hostelería (demo). App self-contained generada desde Claude Design (`x-dc` + `support.js`), con React/ReactDOM por CDN.

Funciones: hero, búsqueda, filtro alérgenos/dietas, categorías, platos + stories, carrito con checkout, modal de plato, chat SmartWaiter, divisa, tema claro/oscuro, i18n ES/EN.

## Dev local
Servir estático (no build):
```bash
npx serve        # o: python -m http.server 4178
```
Abrir el puerto indicado.

## Deploy
Estático en Vercel (sin framework). `vercel --prod`.
