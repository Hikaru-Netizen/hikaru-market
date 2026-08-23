HIKARU MARKET — FINAL

Versi ini sudah disiapkan untuk upload sebagai website statis.

STRUKTUR:
- index.html harus berada di root/public_html.
- Folder assets harus berada sejajar dengan index.html.
- QRIS pembayaran: assets/qris.png

ALUR CHECKOUT:
1. Pembeli memilih Mobile Legends atau Free Fire.
2. Pembeli mengisi ID game dan data kontak.
3. Website menampilkan ringkasan pesanan dan QRIS.
4. Setelah membayar, pembeli menekan tombol “Saya Sudah Bayar — Lanjut ke WhatsApp”.
5. WhatsApp admin terbuka dengan nomor pesanan dan detail pesanan.
6. Pembeli melampirkan bukti pembayaran di WhatsApp.

CATATAN KEAMANAN:
- Ini adalah checkout manual QRIS + WhatsApp, bukan payment gateway otomatis.
- Nominal pembayaran harus diverifikasi admin dari bukti/transaksi QRIS.
- Validasi di browser membantu mencegah input salah, tetapi bukan pengganti validasi server.
- Jangan menaruh API key, password, atau secret di index.html.

SEBELUM GO-LIVE:
- Pastikan QRIS yang tampil memang QRIS milik toko.
- Pastikan nomor WhatsApp admin benar.
- Upload index.html dan folder assets ke root hosting.
- Uji checkout ML dan FF dari perangkat HP sebelum menerima order.
