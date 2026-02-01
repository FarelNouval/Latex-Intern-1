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

```
---

### 3. Install package menggunakan tlmgr
```
tlmgr install <package_name>
```

### 4. Install Git SCM dan hubungkan ke repository GitHub
Download Git dari:
https://git-scm.com/

### 5. Install Antigravity dan extension vscode-pdf
Install Antigravity
Install extension vscode-pdf di VS Code

### Package yang diperlukan
Install semua package sekaligus:
```
tlmgr install inputenc fontenc mathptmx courier helvet amsmath babel geometry setspace titlesec graphicx
```

### Atau install satu per satu
```
tlmgr install inputenc
tlmgr install fontenc
tlmgr install mathptmx
tlmgr install courier
tlmgr install helvet
tlmgr install amsmath
tlmgr install babel
tlmgr install geometry
tlmgr install setspace
tlmgr install titlesec
tlmgr install graphicx
```

## Cara Menjalankan Project
1. Buka folder project menggunakan Antigravity / VS Code

2. Buka file main.tex

3. Compile dengan LaTeX (PDF akan otomatis terbentuk)

4. Preview hasil PDF menggunakan extension vscode-pdf




