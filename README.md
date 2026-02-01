# Latex Template Laporan

Untuk memakai template ini dengan mudah, gunakan aplikasi **Antigravity** dengan fitur **Open Folder**  
(jangan lupa install extension `vscode-pdf`), kemudian ikuti langkah berikut.

---

## Install LaTeX

### 1. Install R terlebih dahulu

Download dan install R dari:
https://cran.r-project.org/

---

### 2. Install TinyTeX

Jalankan perintah berikut di R:

```r
install.packages('tinytex')
tinytex::install_tinytex()

# Untuk uninstall TinyTeX
tinytex::uninstall_tinytex()

# Cek instalasi
tinytex::tinytex_root()
tinytex::tlmgr("--version")

###
