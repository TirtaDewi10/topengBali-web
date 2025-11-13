WebGIS: Persebaran Topeng di Bali
--------------------------------
Isi paket ini:
- index.html         : Halaman web peta (buka di browser)
- data/topeng_bali.geojson : Data titik persebaran (GeoJSON)
- js/leaflet.js      : loader kecil yang memuat Leaflet dari CDN
- css/leaflet.css    : wrapper CSS yang mengimpor Leaflet dari CDN

Cara menjalankan (offline/browser lokal):
1. Extract folder.
2. Buka file index.html di browser (double-click). Jika browser menolak memuat file lokal karena kebijakan CORS, jalankan server lokal singkat:
   - Python 3: `python -m http.server 8000` di folder topeng_bali_webmap, lalu buka http://localhost:8000
3. Jika ingin online, upload seluruh folder ke hosting (Netlify/GitHub Pages/000webhost).

Keterangan:
- Basemap: OpenStreetMap (OSM)
- Popup menampilkan 'tahun_ditemukan' dan 'lokasi' serta nama topeng.
