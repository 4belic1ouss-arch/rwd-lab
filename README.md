# RWD Lab — Responsive Web Design

## Deskripsi
Project praktikum Web Programming yang menerapkan konsep Responsive Web Design, Semantic HTML, Accessibility, Flexbox, CSS Grid, dan Responsive Layout.

## Struktur Project

- `index.html` — struktur halaman website
- `css/reset.css` — reset CSS
- `css/variables.css` — variabel warna, font, ukuran, dan spacing
- `css/style.css` — styling dan responsive layout
- `assets/images/` — penyimpanan gambar

## Fitur yang Diterapkan

1. Semantic HTML
2. Skip Link untuk aksesibilitas
3. Responsive Layout Mobile-First
4. Flexbox
5. CSS Grid
6. Responsive Breakpoint
7. Keyboard Navigation
8. Hover dan Focus State
9. Card Component
10. Lighthouse Testing

## Breakpoint

- Mobile: di bawah 768px
- Tablet: mulai 768px
- Desktop: mulai 1024px

## Pengujian

| ID | Fitur | Viewport | Pengujian | Expected | Actual | Status |
|---|---|---|---|---|---|---|
| TC-01 | Navigasi Menu | 1440px | Klik menu navigasi | Menu dapat digunakan | Berfungsi | Pass |
| TC-02 | Hero Section | 1440px | Cek tampilan hero | Layout tampil dengan baik | Sesuai | Pass |
| TC-03 | Grid Katalog | 768px | Cek susunan card | Card tersusun responsif | Sesuai | Pass |
| TC-04 | Navigasi Keyboard | 375px | Tekan Tab | Fokus berpindah dengan benar | Berfungsi | Pass |

## Lighthouse

Hasil pengujian Lighthouse:

- Performance: 99
- Accessibility: 95
- Best Practices: 100
- SEO: 100

## Kesimpulan

Project berhasil menerapkan konsep responsive web design dengan menggunakan Semantic HTML, Flexbox, CSS Grid, serta pengujian aksesibilitas dan responsive layout.