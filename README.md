# BINANCE-FUTURES-AI — BASE

Dashboard monitoring data publik Binance USDⓈ-M Futures secara real-time.

## Fitur
- Binance REST API untuk daftar kontrak aktif dan ticker 24 jam.
- Binance Futures WebSocket ticker real-time.
- Watchlist awal 29 simbol; hanya kontrak USDT perpetual aktif yang ditampilkan.
- Search, last price, perubahan 24 jam, volume, top gainer/loser.
- UI responsif untuk Android dan desktop.

## Deploy GitHub Pages
1. Upload seluruh isi folder ke root repository.
2. Buka Settings → Pages.
3. Pilih Deploy from a branch, branch `main`, folder `/(root)`, lalu Save.

## Batasan
Ini market-data dashboard read-only, bukan bot eksekusi order. Tidak meminta API key dan tidak mengirim order. Backtest, walk-forward, OOS, Monte Carlo, dan AI consensus belum diimplementasikan pada base ini; oleh sebab itu tidak mengklaim edge terbukti dan tidak mengeluarkan sinyal BUY/SELL tervalidasi. Kontrak non-crypto seperti XAU/NVDA/QQQ hanya muncul bila Binance menyediakan kontrak USDⓈ-M perpetual yang sesuai.

## Struktur
- `index.html`
- `assets/style.css`
- `assets/app.js`
- `README.md`
