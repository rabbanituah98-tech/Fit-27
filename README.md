# RABBANI FIT 2027

Aplikasi web pemantauan diet peribadi dalam Bahasa Melayu. Dibina menggunakan HTML, CSS dan JavaScript vanilla supaya boleh diterbitkan terus melalui GitHub Pages.

## Ciri utama
- Dashboard kalori, protein, karbohidrat, lemak, air dan berat
- Log makanan/minuman dengan katalog makanan tempatan dan nilai nutrisi anggaran
- Water tracker
- Rekod aktiviti fizikal dengan anggaran kalori terbakar
- Rekod berat dan graf trend
- Tetapan profil dan sasaran
- Autosave menggunakan `localStorage`
- Eksport backup JSON dan rekod makanan CSV
- Reka bentuk responsif untuk telefon dan komputer

## Terbitkan menggunakan GitHub Pages
1. Cipta repository baharu di GitHub, contohnya `rabbani-fit-2027`.
2. Muat naik `index.html` dan `README.md` ke root repository.
3. Buka **Settings → Pages**.
4. Pada **Build and deployment**, pilih **Deploy from a branch**.
5. Pilih branch `main`, folder `/ (root)`, kemudian tekan **Save**.
6. Tunggu proses deployment selesai. GitHub akan memaparkan pautan laman web.

## Penting tentang simpanan data
Data disimpan dalam `localStorage` browser/peranti yang digunakan. Ia tidak disegerakkan secara automatik antara telefon dan komputer dan boleh hilang jika data laman/browser dipadam. Gunakan butang **Eksport backup JSON** secara berkala untuk menyimpan salinan rekod.

## Nota kesihatan
Nilai kalori dan makronutrien makanan ialah anggaran dan bergantung pada resipi, jenama serta saiz hidangan. BMR menggunakan formula Mifflin–St Jeor dan TDEE ialah anggaran. Sasaran kalori 1,900 kcal ialah titik permulaan, bukan preskripsi perubatan. Semak trend berat selama beberapa minggu dan laraskan secara beransur-ansur. Aktiviti kalori terbakar tidak ditolak secara automatik daripada bajet makanan.
