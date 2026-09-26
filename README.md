## Hi there 👋
<!-- HEADER BANNER -->
<div align="center">
  <h1>Merhaba, ben Ceren</h1>
  <h3>Endüstri Mühendisliği · Yapay Zeka · Sensör Füzyonu & Optimizasyon</h3>
  <p>Karmaşık sensör verilerini operasyonel kararlara dönüştüren; veri füzyonu, tehdit önceliklendirme, simülasyon ve matematiksel optimizasyon modelleri geliştiriyorum.</p>
  
  <a href="#proje-vitrini">
    <img src="https://img.shields.io/badge/PROJELERİMİ_İNCELE-black?style=for-the-badge&logo=github" alt="Projelerim" />
  </a>
</div>

<br/>

---

###  Odak Alanlarım

| Sensör Füzyonu & YZ | Endüstri Mühendisliği | Karar Destek & Optimizasyon |
| :--- | :--- | :--- |
| • Görüntü & Radar Füzyonu | • Üretim & Kapasite Planlama | • Karar Destek Sistemleri (DSS) |
| • Nesne Tespiti (YOLO/ResNet) | • İşlem/Süreç Simülasyonu | • Çok Kriterli Karar Verme (AHP/TOPSIS) |
| • Anomali & Tehdit Analizi | • Stok & Kalite Analitiği | • Dinamik Çizelgeleme & Atama |

---

### 🛠️ Teknoloji Yığını

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![Scikit-Learn](https://img.shields.io/badge/Scikit_Learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white)
![PuLP](https://img.shields.io/badge/PuLP_MILP-008000?style=for-the-badge)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)

---

<h3 id="proje-vitrini">📌 Proje Vitrini</h3>

#### 1. Çoklu Sensör Veri Füzyonu ile Hava Hedeflerinin Tespiti ve Tehdit Önceliklendirmesi
Elektro-optik görüntü ve radar verilerinin birleştirilmesiyle hava hedeflerinin (İHA, helikopter, uçak) yüksek doğrulukla tespiti, sınıflandırılması ve tehdit derecelerine göre sıralanması amaçlanmaktadır. 

**Kapsam:**
* Görüntü tabanlı nesne tespiti modelleri (YOLO/ResNet) ile radar verilerinin (RCS, mesafe, hız) Kalman Filtresi ve Bayes Ağları ile füzyonlanması.
* Sensör çelişkilerinin giderilmesi ve tespit edilen hedeflerin Çok Kriterli Karar Verme (AHP/TOPSIS) yöntemleriyle önceliklendirilmesi.
* **Çıktılar:** Modüler Python kütüphanesi, karşılaştırmalı performans analizleri ve karar destek arayüzü.

> *(Projenin mimari şemasını veya grafiğini buraya gorsel olarak ekleyebilirsin: `![Proje Görseli](assets/project_image.png)`)*

---

#### 2. Hungarian Algorithması ile Radar-Görüntü Veri İlişkilendirmesi (Data Association)
Karmaşık hava sahasında çoklu hedeflerin takibi sırasında radar koordinatları ile kamera bounding box çıktılarının anlık ve doğru eşleştirilmesi amaçlanmaktadır.

**Kapsam:**
* Sensörlerden gelen konum/uzaklık matrislerinin oluşturulması.
* Hungarian (Munkres) Algoritması kullanılarak optimal atama probleminin çözülmesi ve yanlış eşleşme (False Acceptance) oranlarının minimize edilmesi.
* **Çıktılar:** Veri ilişkilendirme algoritması kütüphanesi, simülasyon senaryoları ve benchmark sonuçları.
