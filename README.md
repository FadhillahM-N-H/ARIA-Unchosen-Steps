<!-- ===================== HEADER ===================== -->
<div align="center">

<img src="https://capsule-render.vercel.app/api?type=slice&color=0:0B0D10,55:1B2029,100:3A4458&height=240&section=header&text=ARIA&fontSize=84&fontColor=E9EBEE&fontAlignY=42&desc=UNCHOSEN%20STEPS&descSize=22&descAlignY=66&animation=fadeIn" width="100%" alt="ARIA: Unchosen Steps"/>

<!--
  OPSIONAL: ganti banner dengan screenshot / GIF gameplay sendiri.
  1. Simpan gambar di assets/banner.png (rasio lebar, mis. 1600x400)
  2. Hapus <img> capsule-render di atas, lalu pakai:
  <img src="assets/banner.png" width="100%" alt="ARIA: Unchosen Steps"/>
-->

<a href="https://git.io/typing-svg">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=22&pause=1100&color=7FA8FF&center=true&vCenter=true&width=640&lines=Satu+baris+kode.+Satu+langkah+ARIA.;Belajar+Python+lewat+puzzle+3D+%F0%9F%A7%A9;Fasilitas+NEXUS-7+sedang+lockdown...+%F0%9F%94%B4;Tulis+kodenya.+Jalankan.+Lihat+akibatnya." alt="Typing SVG"/>
</a>

<br/><br/>

<a href="https://github.com/FadhillahM-N-H/ARIA-Unchosen-Steps/releases/latest">
  <img src="https://img.shields.io/badge/%E2%AC%87%EF%B8%8F%20DOWNLOAD-ARIA%20v1.0-E9EBEE?style=for-the-badge&labelColor=0B0D10" alt="Download ARIA"/>
</a>

<br/><br/>

![Unity](https://img.shields.io/badge/Dibuat%20dengan-Unity-000000?style=for-the-badge&logo=unity&logoColor=white)
![Blender](https://img.shields.io/badge/Blender-3D%20Assets-E87D0D?style=for-the-badge&logo=blender&logoColor=white)
![Python](https://img.shields.io/badge/Mengajarkan-Python-3776AB?style=for-the-badge&logo=python&logoColor=white)

![Version](https://img.shields.io/badge/version-v1.0-E9EBEE?style=flat-square&labelColor=0B0D10)
![Platform](https://img.shields.io/badge/platform-Windows-1F6FEB?style=flat-square&labelColor=0B0D10)
![Genre](https://img.shields.io/badge/genre-programming%20puzzle-8250DF?style=flat-square&labelColor=0B0D10)
![Mode](https://img.shields.io/badge/mode-single%20player-E9EBEE?style=flat-square&labelColor=0B0D10)
![Downloads](https://img.shields.io/github/downloads/FadhillahM-N-H/ARIA-Unchosen-Steps/total?style=flat-square&labelColor=0B0D10)

</div>

---

## 🛰️ Transmisi Masuk

> **`NEXUS-7 // STATUS: LOCKDOWN`**
> Semua pintu terkunci. Unit **ARIA** masih menyala, tetapi tidak bisa mengambil keputusan sendiri.
> Satu-satunya cara menggerakkannya adalah **kode yang kamu tulis**.

**ARIA: Unchosen Steps** adalah *programming puzzle game* 3D tempat kamu berperan sebagai teknisi yang mengendalikan ARIA. Kamu menyusun instruksi, menjalankannya, lalu melihat sendiri apa yang terjadi. Dari situ, konsep dasar **Python** dipelajari lewat konsekuensi nyata di dalam level, bukan lewat hafalan.

> 🎓 Dibuat sebagai tugas UAS mata kuliah **Pemrograman Game** sekaligus bahan proposal Tugas Akhir.

---

## ⬇️ Unduh dan Mainkan

1. Buka halaman **[Releases](https://github.com/FadhillahM-N-H/ARIA-Unchosen-Steps/releases/latest)** dan unduh file `.zip` terbaru.
2. **Ekstrak seluruh isi zip** ke satu folder. Jangan menjalankan game langsung dari dalam zip.
3. Buka folder hasil ekstrak, lalu jalankan file **`.exe`** game.
4. Mainkan. Bila baru pertama kali, mulai dari level pengantar.

> 💡 Jika Windows menampilkan peringatan *"Windows protected your PC"*, klik **More info ▸ Run anyway**. Peringatan ini muncul karena game belum bertanda tangan digital, bukan karena ada masalah.

---

## 🔁 Siklus Bermain

```mermaid
flowchart LR
    A[📖 Baca peta<br/>dan tujuan] --> B[🧩 Susun kode<br/>fase perencanaan]
    B --> C[▶️ Jalankan<br/>program]
    C --> D{Sampai<br/>garis finis?}
    D -- Ya --> E[🏁 Level selesai]
    D -- Tidak --> F[❤️ Nyawa berkurang<br/>baca ulang kodemu]
    F --> B
```

1. **Pilih level** dari menu.
2. **Pelajari peta** dan temukan garis finis.
3. **Susun instruksi** untuk ARIA pada fase perencanaan.
4. **Jalankan** dan amati gerakannya.
5. **Perbaiki** kodemu bila gagal, ingat nyawa terbatas.

---

## ✨ Fitur

| | Fitur | Keterangan |
|---|---|---|
| 🧩 | **Dua mode kode** | Mulai dari blok seret-dan-lepas, lalu naik ke Mode Teks dengan sintaks Python sungguhan |
| 🧠 | **Belajar bertahap** | Setiap level memperkenalkan satu ide baru, tanpa lompatan besar |
| 🗺️ | **8 level, 22 stage** | Level 1–7 masing-masing 3 stage, Level 8 adalah stage penutup, ditambah level pengantar |
| ❤️ | **Sistem nyawa** | Salah langkah ada harganya, jadi pemain terdorong membaca sebelum menjalankan |
| 💡 | **Catatan Dea** | Petunjuk bertahap yang menuntun tanpa langsung memberi jawaban |
| 🎬 | **Tutorial kontekstual** | Level pengantar untuk kontrol dasar, plus tutorial mini setiap ada cara input baru |
| 🎨 | **Gaya HOLLOW ARRAY** | Hitam matte dan gunmetal, bentuk *hard-surface* low-poly, merah hanya untuk peringatan |

---

## 🐍 Konsep Python yang Dipelajari

| Tahap | Konsep | Contoh |
|---|---|---|
| Awal | Urutan perintah | Memerintah ARIA langkah demi langkah dengan blok |
| Stage 2-3 | **Mode Teks** | Mengetik perintah sendiri |
| Stage 3-1 | **Parameter** | `move(3)` |
| Stage 3-2 | **Variabel dan rumus** | `data = read_terminal()` lalu `data + 5` |
| Stage 4-1 | **Kondisi `if`** | Memeriksa ubin dengan `check_anomaly` |
| Stage 4-2 | **`elif`** | Cabang kondisi tambahan |
| Stage 4-3 | **Indentasi** | Menempatkan baris di dalam blok yang benar |
| Level lanjut | **Perulangan** | Mengulang pola langkah |

Gaya kode di dalam game:

```python
data = read_terminal()
password = data + 5
move(3)
```

---

<details>
<summary><b>⚠️ Catatan Versi</b></summary>

<br/>

- 🧪 Game belum melalui playtest dengan pemain lain, jadi masukan sangat dihargai.
- ✍️ Di Mode Teks, tip "garis merah" bisa muncul saat kamu masih mengetik.
- 🧱 Jika dinding tampak pekat (tidak transparan) di perangkatmu, tolong laporkan lewat [Issues](https://github.com/FadhillahM-N-H/ARIA-Unchosen-Steps/issues).

</details>

---

## 🙏 Kredit dan Aset

- **Model 3D lingkungan, musuh, dan unit ARIA:** dibuat sendiri di Blender.
- **Model SentryRobot:** paket *Light Hearted Tech* (aset pihak ketiga).
- **Font** (lisensi SIL OFL): Barlow, Barlow Condensed, IBM Plex Mono, JetBrains Mono, Rajdhani.
- **Dibuat dengan:** Unity 6000.5.10f1 · Universal RP · Cinemachine · Input System · UI Toolkit.

---

## 🧭 Rencana Pengembangan

- [ ] Reset Progres di menu Pengaturan
- [ ] Optimasi performa dan model 3D
- [ ] Bahasa Inggris
- [ ] Level boss (di luar cakupan v1.0)

---

## 🐞 Menemukan Bug?

Buka tab **[Issues](https://github.com/FadhillahM-N-H/ARIA-Unchosen-Steps/issues)** lalu ceritakan apa yang terjadi, di level dan stage berapa, serta spesifikasi perangkatmu. Screenshot sangat membantu.

---

## 👤 Pembuat

<div align="center">

**Fadhillah Muhammad Nur Hafiz**
D4 Manajemen Informatika · Fakultas Vokasi · Universitas Negeri Surabaya
*Solo developer · 1 September 2026 → build v1.0, 1 November 2026*

<a href="https://github.com/FadhillahM-N-H"><img src="https://img.shields.io/badge/GitHub-FadhillahM--N--H-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"/></a>

</div>

---

## 📄 Hak Penggunaan

© 2026 Fadhillah Muhammad Nur Hafiz. Game ini dibagikan untuk dimainkan dan dinilai sebagai karya akademik. Mohon tidak mendistribusikan ulang atau menjualnya tanpa izin.

<!-- ===================== FOOTER ===================== -->
<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=slice&color=0:3A4458,55:1B2029,100:0B0D10&height=110&section=footer" width="100%" alt="Footer"/>
</div>
