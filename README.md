# 📌 Implementasi Infrastruktur Blog Berbasis Container pada Home Server Menggunakan CasaOS dan Cloudflare Tunnel

Proyek ini bertujuan untuk membangun **blog self-hosted** pada **Home Server berbasis STB ZTE HG680P (aarch64)** menggunakan **CasaOS** sebagai antarmuka manajemen container dan **Cloudflare Tunnel** sebagai solusi akses publik yang aman.

Dengan memanfaatkan **CasaOS**, proses instalasi dan pengelolaan aplikasi berbasis **Docker Container** menjadi lebih sederhana dan user-friendly. Blog di-deploy menggunakan **Nginx container** untuk melayani konten statis berbasis template Bootstrap.

---

## ✨ Fitur & Manfaat
- **CasaOS Dashboard** → Manajemen aplikasi container dengan antarmuka berbasis web.  
- **Self-Hosted Blog** → Website pribadi dijalankan langsung dari home server.  
- **Cloudflare Tunnel** → Akses aman dari internet tanpa perlu IP publik statis, sekaligus SSL otomatis.  
- **Home Lab** → Sarana belajar containerization, DevOps dasar, dan pengelolaan server pribadi.  
- **File Management & Extensibility** → Mendukung ekspansi dengan aplikasi lain (Nextcloud, Jellyfin, dsb).  

---

## ⚙️ Teknologi yang Digunakan
- **Hardware**: STB ZTE HG680P (Armbian, aarch64)  
- **OS & Platform**: Armbian + CasaOS  
- **Container Engine**: Docker  
- **Web Server**: Nginx (containerized)  
- **Domain & Networking**: Cloudflare + Cloudflare Tunnel  

---

## 🌐 Hasil Akhir
Blog dapat diakses secara publik melalui domain yang terhubung dengan **Cloudflare Tunnel**, sekaligus mendapatkan **SSL gratis** dari Cloudflare.  
Proyek ini menunjukkan bagaimana perangkat sederhana seperti **STB** dapat dimanfaatkan sebagai **home server hemat biaya**, sekaligus menjadi media belajar infrastruktur modern berbasis container.
