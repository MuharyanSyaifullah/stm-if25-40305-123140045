# Tugas 2 - Analisis Sinyal Suara & Noise Statis

Direktori ini berisi penyelesaian Tugas 2 (Individu) Week 03. Fokus tugas ini adalah mengeksplorasi representasi audio 4 dimensi dan menguji dampak *resampling* serta efek *aliasing* pada audio dengan derau statis.

## Dokumentasi Perekaman
* **Perangkat Perekam:** [ISI DENGAN MEREK HP/LAPTOPMU, misal: Smartphone Samsung / iPhone]
* **Sumber Noise Statis:** [ISI DENGAN SUMBER NOISEMU, misal: Kipas Angin / Kompresor AC / Mesin Pompa]
* **Deskripsi:** Rekaman suara membaca artikel berita dengan latar belakang derau statis konstan.

## Struktur Direktori
* `tugas_audio_noise_statis.ipynb` : Jupyter Notebook berisi kode eksekusi dan analisis mandiri.
* `tugas_audio_noise_statis.pdf` : Ekspor cetak PDF dari Notebook (cadangan visual).
* `audio_original.wav` : Berkas audio rekaman asli berita + noise statis.
* `audio_downsampled_naive.wav` : Hasil *downsampling* tanpa filter (*naive decimation*).
* `audio_downsampled_clean.wav` : Hasil *resampling* terfilter (*anti-aliasing*).
