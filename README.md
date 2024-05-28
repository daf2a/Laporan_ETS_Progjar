# Laporan ETS Progjar 

Repositori ini berisi laporan untuk ETS Progjar dibuat menggunakan LaTeX.

## Penulis
Muhammad Daffa Ashdaqfillah (5025211015)

## Laporan PDF
Laporan dapat diakses melalui link berikut:
[PDF url](https://daf2a.github.io/Laporan_ETS_Progjar/Laporan_ETS_Progjar_5025211015.pdf)

## Struktur Direktori

- `src/`: Berisi kode sumber Python untuk server HTTP dan HTTPS.
- `Laporan_ETS_Progjar_5025211015.tex`: File LaTeX utama untuk laporan.
- `img/`: Direktori yang berisi gambar yang digunakan dalam laporan.
- `index.html`: Halaman utama untuk situs GitHub Pages.
- `.github/workflows/`: Berisi file konfigurasi untuk GitHub Actions.

## Kode Sumber

Kode sumber dalam direktori `src/` berisi implementasi server HTTP dan HTTPS. Server ini diimplementasikan menggunakan threading dan proses.

## GitHub Actions

Repositori ini menggunakan GitHub Actions untuk otomatisasi beberapa tugas:

- `check_latex.yml`: Mengecek kompilasi LaTeX dan mengunggah file PDF sebagai artifact.
- `publish_static.yml`: Mengunggah seluruh repositori sebagai artifact dan menerapkan ke GitHub Pages.

## Lisensi

Proyek ini dilisensikan di bawah lisensi MIT. Lihat file [LICENSE](LICENSE) untuk detail lebih lanjut.
