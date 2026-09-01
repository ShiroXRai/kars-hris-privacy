# KARS HRIS — Kebijakan Privasi (GitHub Pages)

Situs statis sederhana untuk menghosting **Kebijakan Privasi** KARS HRIS
melalui GitHub Pages.

## Cara pakai

### Opsi A — Repo baru (disarankan, paling bersih)

1. Buat repo publik baru di GitHub, misalnya `kars-hris-privacy`.
2. Isi repo dengan file `index.html` ini (di root).
3. Aktifkan GitHub Pages:
   - Repo → **Settings** → **Pages**
   - Source: `Deploy from a branch` → branch `main` → folder `/ (root)` → **Save**
4. URL hasil: `https://<username>.github.io/kars-hris-privacy/`

### Opsi B — Folder `docs/` di repo yang sudah ada

1. Taruh `index.html` (atau `privacy-policy.html`) di folder `docs/` repo.
2. Aktifkan GitHub Pages di repo tersebut:
   - **Settings** → **Pages** → Source: branch `main` → folder `/docs` → **Save**
3. URL hasil: `https://<username>.github.io/<nama-repo>/privacy-policy.html`

## Verifikasi

Setelah di-publish, buka URL-nya di browser dan pastikan:

- Halaman tampil dengan benar (tidak ada 404)
- Bagian **11. Hubungi Kami** menampilkan: KARS Teknologi Asia,
  Ruko Terrace 9, Suvarna Sutera, Jl. Jati Utama No. 59 Blok D, Wanakerta,
  Sindang Jaya, Tangerang Regency, Banten 15560, email
  karstechnologiesasia@gmail.com

URL final itulah yang diisi di **Play Console → App content → Privacy policy**.
