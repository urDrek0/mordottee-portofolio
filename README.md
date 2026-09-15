# Mordottee Portfolio

Portfolio website untuk Mordottee, freelance digital artist. Website ini menampilkan karya dalam beberapa kategori seperti sketches, illustrations, chibi, dan concept arts.

## Fitur

- Gallery karya dengan layout masonry seperti Pinterest
- Gambar tetap menggunakan rasio aslinya dan tidak di-crop
- Filter karya berdasarkan kategori
- Halaman about dan contact
- Responsive untuk desktop dan mobile

## Struktur Project

```text
index.html          Halaman utama dan logika gallery
src/data.json       Data karya dan kategori
src/style.css       Source CSS tambahan
src/output.css      CSS hasil build Tailwind
asset/              Gambar karya, logo, background, dan persona
```

## Menjalankan Project

Install dependency terlebih dahulu:

```bash
npm install
```

Jalankan Tailwind dalam mode watch:

```bash
npm run dev
```

Kemudian buka `index.html` menggunakan extension Live Server di VS Code atau web server lokal lainnya. Web server diperlukan agar `src/data.json` dapat di-fetch oleh browser.

## Catatan Kategori

Nilai kategori di tombol filter harus sama persis dengan nilai `categori` di `src/data.json`:

```text
sketches
illustrations
chibi
concept
```