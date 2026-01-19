# Log Progres THT RSC

## Minggu, 18 Januari 2026
**Fokus:** Membaca ketentuan THT, inisialisasi GitHub Repository, dan instalasi segala hal yang akan diperlukan.

### **Membaca ketentuan THT**  
Sempat mengalami kebingungan megenai format dan tempat penjawaban, serta apa yang harus ditambah pada logbook, namun akhirnya mengerti mengenai tempat jawaban dan menganggap bahwa **format jawaban dibebaskan**.

### **Inisialisasi GitHub Repo**  
Inisialisasi GitHub Repository menggunakan template dilakukan pada website GitHub, lalu di-_clone_ menggunakan GitHub Desktop (kebiasaan dari matkul Alpro IF1210)

### **Instalasi (Container) Ubuntu 22.04.5 LTS, ROS2, dan OpenCV**  
Karena saya menggunakan Arch Linux sebagai _daily driver_ (dual boot dengan Windows) dan tidak ingin mengganti distro, saya memilih untuk menginstal Ubuntu 22.04 sebagai _container_ dengan Distrobox atas rekomendasi Gemini AI 3.0 Pro.  
* Instalasi ROS2 berjalan dengan lancar.
* Pada instalasi OpenCV, bingung cara instalasinya.. Jadi tanya AI dan akhirnya di-download dengan
    ``` shell
    sudo apt install ros-humble-vision-opencv python3-opencv
    ```
    Nanti akan diganti kalau harusnya bukan begitu

### **Penggunaan AI** 
* Whether to use Ubuntu in VM, triple boot, and ask for suggestions where it suggested using a container instead with Distrobox and podman
* Logbook layout and required information (in the end I didn't really go along with it)  

> [!NOTE]  
> From now on, I will be using English instead of Indonesian for everything because I'm more comfortable in using English. The instruction say to use "Bahasa Indonesia secara efisien dan komprehensif", but well.. I'm not a Ca-RSC anyway.

## Monday, 19th of Janauary 
**Focus**: Start making the logbook, integration of Ubuntu container with host, tried the "turtlesim, ros2, rqt" tutorial, question 1

### **Logbook**  
Decide to split the stuff apart into days, where each day has
* Date
* Focus
* Explanation of focus
  * If it's not very related to a question, then it will be in bullet points
  * If it's related to a question, there will be a question subsection and numbered points according to question number
* AI usage in points

### **Integration of Ubuntu container with host**  
I use fish as the shell and starship for configuration, so I configured the container to use fish and make sure every intended bash command uses fish with the help of bass, with help of AI.

### **AI Usage**: 
* Helped with Ubuntu container shell integration

## Tuesday, 20th of January
**Focus**: Question 2 (Source Control Management)

### **2. Source Control Management**
1. Took too long on this question, learnt merge, squash, rebase when it would've been discussed on 3... Oh well.

### **AI Usage**
* Helped with understanding rebase, merge, squash