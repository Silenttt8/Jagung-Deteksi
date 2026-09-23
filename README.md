<div align="center">
  <img src="logo.png" alt="CornVision Logo" width="120" />
  
  # 🌽 CornVision
  ### Deteksi Penyakit Daun Jagung Berbasis AI
  
  ![HTML](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
  ![CSS](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
  ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
  ![YOLOv8](https://img.shields.io/badge/YOLOv8-00FFFF?style=for-the-badge&logo=yolo&logoColor=black)
  ![TensorFlow.js](https://img.shields.io/badge/TensorFlow.js-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)

  > Aplikasi web untuk mendeteksi penyakit daun jagung secara real-time menggunakan model YOLOv8 yang berjalan langsung di browser (tanpa server).
</div>

---

## ✨ Fitur Utama

- 🔍 **Deteksi Real-time** — Upload foto daun jagung dan dapatkan hasil deteksi instan
- 🤖 **AI di Browser** — Model YOLOv8 berjalan langsung di browser via TensorFlow.js, tanpa perlu server
- 📊 **Info Penyakit Lengkap** — Penjelasan detail setiap penyakit beserta cara penanganannya
- 📱 **Responsive** — Tampilan optimal di desktop maupun smartphone
- 🎨 **Modern UI** — Desain dark mode dengan animasi smooth

---

## 🦠 Penyakit yang Dideteksi

| Nama Penyakit | Kelas | Keterangan |
|---|---|---|
| **Blight** | `blight` | Hawar daun jagung |
| **Common Rust** | `common_rust` | Karat biasa pada daun |
| **Gray Leaf Spot** | `gray_leaf_spot` | Bercak daun abu-abu |
| **Healthy** | `healthy` | Daun sehat / normal |

---

## 🗂️ Struktur Proyek

```
Jagung-Deteksi/
├── 📄 index.html              # Halaman beranda
├── 📄 deteksi.html            # Halaman deteksi AI
├── 📄 penyakit.html           # Halaman info penyakit
├── 🎨 style.css               # Stylesheet global
├── ⚙️  script.js               # Logic & model inference
├── 🖼️  logo.png                # Logo aplikasi
├── 📁 Model/                  # Model YOLOv8 (TensorFlow.js)
│   ├── model.json
│   ├── group1-shard1of3.bin
│   ├── group1-shard2of3.bin
│   ├── group1-shard3of3.bin
│   └── metadata.yaml
└── 📓 train_jagung_FINAL.ipynb  # Notebook training model
```

---

## 🚀 Cara Menjalankan

### Pakai XAMPP (Local)
1. Clone repo ini ke folder `htdocs` XAMPP:
   ```bash
   git clone https://github.com/Silenttt8/Jagung-Deteksi.git
   ```
2. Jalankan XAMPP → Start **Apache**
3. Buka browser → `http://localhost/Jagung-Deteksi`

### Langsung buka file
> ⚠️ Model tidak akan load jika dibuka langsung lewat `file://` karena CORS. Gunakan local server (XAMPP/VS Code Live Server).

---

## 🧠 Model AI

- **Arsitektur:** YOLOv8 (Ultralytics)
- **Format:** TensorFlow.js (berjalan di browser)
- **Input Size:** 640×640 px
- **Jumlah Kelas:** 4 (blight, common_rust, gray_leaf_spot, healthy)
- **Trained:** Juli 2026

---

## 🛠️ Teknologi

| Teknologi | Kegunaan |
|---|---|
| HTML5 + CSS3 | Struktur & tampilan antarmuka |
| JavaScript (Vanilla) | Logic deteksi & interaksi |
| TensorFlow.js | Inference model di browser |
| YOLOv8 | Arsitektur model deteksi objek |
| Font Awesome | Ikon UI |
| Google Fonts (Inter) | Typography |

---

## 👨‍💻 Author

**Silenttt8**  
📧 GitHub: [@Silenttt8](https://github.com/Silenttt8)

---

<div align="center">
  <sub>Dibuat dengan ❤️ untuk deteksi penyakit tanaman jagung</sub>
</div>
