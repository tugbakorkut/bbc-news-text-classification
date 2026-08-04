# 📰 BBC News Metin Sınıflandırma Projesi (Text Classification)

Bu proje, BBC haber metinlerini doğal dil işleme (NLP) ve makine öğrenimi teknikleri kullanarak otomatik olarak doğru kategorilere ayırmayı amaçlayan bir veri bilimi çalışmasıdır.

## 🎯 Projenin Amacı ve Kapsamı
Haber metinleri üzerinde ön işleme adımları (temizleme, durdurma kelimelerini çıkarma vb.) uygulanarak metinler vektörleştirilmiş ve farklı sınıflandırma modelleri eğitilmiştir. Süreç şu adımları içermektedir:
1. **Veriseti İncelemesi ve Keşifsel Veri Analizi (EDA):** Kategori dağılımları, kelime sayıları istatistikleri ve metin uzunlukları analizi.
2. **Görselleştirme:** Kategori bazlı dağılımlar, kutu grafikleri (Box Plot), keman grafikleri (Violin Plot) ve kelime bulutları (WordCloud).
3. **Metin Ön İşleme & Özellik Çıkarımı:** TF-IDF ve Count Vectorizer yöntemleri ile metinlerin sayısal modele dönüştürülmesi.
4. **Model Eğitimi ve Optimizasyonu:** Destek Vektör Makineleri (SVM), Lojistik Regresyon, Random Forest ve Naive Bayes gibi algoritmaların test edilmesi ve performans değerlendirmesi.

---

## 📊 Model Başarısı ve Performans
Geliştirilen en iyi model optimizasyonlar sonucunda **%98.32 Doğruluk Oranı (Accuracy)** başarısına ulaşmıştır.

---

## 🛠️ Kullanılan Teknolojiler ve Kütüphaneler
Projede kullanılan temel Python kütüphaneleri:
- **Veri Manipülasyonu:** `pandas`, `numpy`
- **Doğal Dil İşleme (NLP):** `nltk` (Stop-words, metin ön işleme)
- **Makine Öğrenimi:** `scikit-learn` (TfidfVectorizer, SVC, RandomForestClassifier, GridSearchCV vb.)
- **Görselleştirme:** `matplotlib`, `seaborn`, `wordcloud`

---

## 📁 Dosya Yapısı
- `BBC_News_Metin_Sınıflandırma.ipynb`: Tüm veri analizi, görselleştirme ve model eğitim adımlarını içeren Jupyter Notebook dosyası.
- `BBC News Train.csv`: Modelin eğitildiği BBC haber metinleri veriseti.

---

## 🚀 Projeyi Nasıl Çalıştırırsınız?
1. Bu depoyu (repository) bilgisayarınıza klonlayın veya indirin.
2. `BBC News Train.csv` dosyasının kod dosyasıyla aynı klasörde olduğundan emin olun.
3. `BBC_News_Metin_Sınıflandırma.ipynb` dosyasını Jupyter Notebook, JupyterLab veya Google Colab üzerinden açarak adım adım çalıştırabilirsiniz.
