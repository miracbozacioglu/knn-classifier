<div align="center">

  <h1>K-Nearest Neighbors (K-NN) Algoritması ile Veri Madenciliği</h1>
  
  

  <!-- Rozetler (Badges) -->
  <a href="https://www.python.org/">
    <img src="https://img.shields.io/badge/Python-3.9%2B-blue?style=for-the-badge&logo=python&logoColor=white" alt="Python Version" />
  </a>
  <a href="https://scikit-learn.org/">
    <img src="https://img.shields.io/badge/Scikit--Learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white" alt="Scikit-Learn" />
  </a>
  <a href="https://jupyter.org/">
    <img src="https://img.shields.io/badge/Jupyter-Notebook-F37626?style=for-the-badge&logo=jupyter&logoColor=white" alt="Jupyter Notebook" />
  </a>
  

</div>

<hr />

## 📌 Proje Genel Bakışı

Bu proje, **Veri Madenciliği** dersi kapsamında **K-Nearest Neighbors (K-NN)** algoritmasının teorik altyapısını ve pratik uygulamasını somutlaştırmak amacıyla geliştirilmiştir. Ham veri setinden başlayarak nihai model değerlendirmesine kadar olan tüm adımlar tek bir **Jupyter Notebook** üzerinde şeffaf biçimde yürütülmüştür.

### 🎯 Temel Kazanımlar (K-NN Algoritması)
- **Tembel Öğrenme (Lazy Learning):** Modelin önceden eğitilmediği, tüm hesaplama yükünün tahmin (*query*) anında yürütüldüğü çalışma mekanizması.
- **Geometrik Uzaklık Mantığı:** Yeni veri noktalarının sınıfını belirlemek için Öklid ve Manhattan mesafesi üzerinden uzamsal komşuluk hesaplama.
- **Hiperparametre Dengesi ($K$ Değeri):** Küçük $K$ değerlerinde aşırı öğrenme (*overfitting/gürültü hassasiyeti*), büyük $K$ değerlerinde eksik öğrenme (*underfitting*) dinamikleri.
- **Oylama Stratejileri:** Komşuların doğrudan çoğunluk oylaması (*uniform*) veya mesafenin tersiyle ağırlıklandırılmış (*distance-weighted*) karar süreci.
---

## 📂 Proje Yapısı

```bash
├── data/
│   └── Social_Network_Ads.csv             
├── notebooks/
│   └── k_nearest_neighbors.ipynb 
             