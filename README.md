# Crypto Radar Pro

Aplicación web estática y PWA para visualizar señales técnicas informativas LONG/SHORT de Binance USDⓈ-M Perpetual USDT.

## Características
- Ranking de los 100 contratos perpetuos USDT-M con mayor volumen cotizado 24 h.
- Análisis de los 30 primeros.
- Tendencia M15 (EMA20/EMA50) y confirmación M5 (EMA9/EMA21, RSI, MACD, volumen relativo y ruptura de rango).
- Solo velas cerradas para confirmar las condiciones de entrada.
- Precio en streaming mediante WebSocket público de Binance.
- Niveles orientativos, riesgo objetivo $1, tamaño de posición sujeto a filtros de lote y notional, y apalancamiento sugerido aislado 3x–5x.
- PWA instalable; no necesita cuenta ni claves API.

## Publicación gratuita
Activar GitHub Pages desde Settings → Pages → Build and deployment → Deploy from a branch → `main` → `/ (root)` → Save.

## Aviso
No conecta a cuentas, no ejecuta órdenes y no garantiza resultados. Los cálculos son aproximados y no incluyen comisiones, funding, slippage, riesgo de liquidación ni cambios en filtros del exchange. Notificaciones web solo se muestran cuando el navegador permite y la app está activa. Verifica siempre la información antes de operar.