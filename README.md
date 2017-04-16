# INDEX #
[Judul Program](https://github.com/armyids/WSPMaster#wsp-version-001-beta)

[Fitur Program](https://github.com/armyids/WSPMaster#fitur)

[Software Pendukung](https://github.com/armyids/WSPMaster#software-pendukung-yang-harus-diinstall)

[Instalasi Utama Windows](https://github.com/armyids/WSPMaster#instalasi-utama-windows)

[Instalasi Utama Linux](https://github.com/armyids/WSPMaster#instalasi-utama-linux-debian)

[Video Panduan](https://github.com/armyids/WSPMaster#video-panduan)

[Instalasi Tambahan](https://github.com/armyids/WSPMaster#instalasi-tambahan)

[Cara Menjalankan WSP](https://github.com/armyids/WSPMaster#cara-menjalankan)

[Update Program](https://github.com/armyids/WSPMaster#update)

[Credits](https://github.com/armyids/WSPMaster#credits)

[Contributor Script](https://github.com/armyids/WSPMaster#contributors-script)

[Kontak Dan Saran](https://github.com/armyids/WSPMaster#kontak-dan-saran)

[Disclaimer](https://github.com/armyids/WSPMaster#disclaimer)

# WSP Version 0.0.1 Beta #
WSP (Water Sedimentation Prediction) merupakan auto bash / shell script yang dibuat dengan tujuan untuk menghitung besarnya erosi akibat percikan air (splash erosion), erosi pada permukaan tanah (rill and sheet erosion), laju pengendapan (deposition rate), serta transport sediment pada suatu area, Daerah Aliran Sungai (Watershed), dan slope.

# Fitur #
- [x] Menghitung Erosi Tanah Akibat Percikan Air (Water Splash Erosion)
- [x] Menghitung Erosi Akibat Runoff Pada Permukaan Tanah (Rill and Sheet Erosion)
- [x] Menghitung Laju Pengendapan (Deposition Rate) 
- [x] Menghitung Transport Sediment

# Software Pendukung yang Harus Diinstall #
- Git (Khusus Windows)
	https://git-for-windows.github.io/
- Python 2.7.x (Windows dan Linux)
	https://www.python.org/downloads/windows/

# Instalasi Utama Windows #
Dengan cara klik kanan di folder yang diinginkan dan klik Git Bash Here, kemudian jalankan command berikut: 
- git clone -b master https://github.com/armyids/WSPMaster

Atau bisa juga dapat download file zip langsung : https://github.com/armyids/WSPMaster.git

# Instalasi Utama Linux Debian #

Masuk ke root kemudian jalankan command berikut:
- wget -q --no-check-certificate https://raw.githubusercontent.com/armyids/WSPMaster/linux_debian.sh -O - | bash -

Kemudian clone WSPMaster di folder yang diinginkan
- git clone -b master https://github.com/armyids/WPSMaster && cd WSPMaster && chmod 755 *.sh

# Video Panduan #
- Install Git Bash, Python 2.7.x, Clone WPSMaster

[![Install Git Bash](http://img.youtube.com/vi/U1dOJsD0gWY/0.jpg)](http://www.youtube.com/watch?v=U1dOJsD0gWY)

- Install Git Bash, Python 2.7.x, Clone WPSMaster

[![Install Python 2.7.x](http://img.youtube.com/vi/Myp9nNOcHIc/0.jpg)](http://www.youtube.com/watch?v=Myp9nNOcHIc)

- Install Git Bash, Python 2.7.x, Clone WPSMaster

[![Git Clone WPSMaster](http://img.youtube.com/vi/iPdawz6GqAY/0.jpg)](http://www.youtube.com/watch?v=iPdawz6GqAY)

# Instalasi Tambahan #
- Windows : Jalankan file `install_windows.sh`
- Linux   : Jalankan shell bash `install_debian.sh`

# Cara Menjalankan #
Klik 2 kali file 'WSP.sh', atau juga bisa masukkan command `./WSP.sh` pada git bash atau terminal jika menggunakan linux.

# Update #
Untuk update, buka git bash here di folder WSPMaster, kemudian masukkan command berikut pada git bash :
- `git stash`
- `git pull`
- `git submodule update --init --recursive`

# Credits #

# Contributors Script #

# Kontak Dan Saran #
Kontak, saran, pendapat dan lain-lain bisa menghubungi kami di http://sipil.ft.unsoed.ac.id/
 
# Disclaimer #
Saya selaku penanggungjawab script menyatakan 'Tidak ada backdoor, file, command, virus atau program jahat yang membahayakan di dalam script'
