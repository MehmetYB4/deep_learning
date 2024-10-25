# 🌌 Derin Öğrenmeye Giriş

## 📚 Derin Öğrenme Nedir?

**Derin Öğrenme** (Deep Learning), yapay sinir ağları kullanılarak makinelerin öğrenme becerisini geliştiren bir yapay zeka (AI) alanıdır. Özellikle büyük veri setlerinde ve karmaşık görevlerde etkili sonuçlar elde eder. Derin öğrenme, insan beyninin çalışma biçiminden esinlenilerek geliştirilmiştir ve **katmanlı yapısı** sayesinde verilerden otomatik olarak özellik çıkarabilir.

---

## 🧠 Sinir Ağları ve Derin Öğrenme

**Sinir ağları**, birbirine bağlı **nöronlardan** oluşur ve verilerin içindeki desenleri öğrenme prensibine dayanır. **Derin sinir ağları**, birden fazla gizli katman içerir ve bu katmanlar sayesinde karmaşık veri ilişkilerini öğrenebilir.

### 🎯 Derin Öğrenme Neden Önemli?
Derin öğrenme, aşağıdaki alanlarda oldukça başarılıdır:
- **Görüntü Tanıma** 📸 (Örneğin, nesne tanıma)
- **Doğal Dil İşleme** 🗣️ (Çeviri, duygu analizi)
- **Öneri Sistemleri** 🎬 (Film önerme, alışveriş önerileri)
- **Otonom Araçlar** 🚗 (Kendi kendine sürüş teknolojileri)

---

## 🔗 Derin Öğrenme Yapısı: Katmanlar

Derin öğrenme modelleri, **girdi** ve **çıktı** katmanları arasında **gizli katmanlar** bulunduran bir yapıya sahiptir. Bu gizli katmanlar, verinin özelliklerini öğrenip dönüştürür. Her katman, veriden belirli bir özellik çıkarır ve bir sonraki katmana iletir.

### 1. **Girdi Katmanı** 🚪
   - Verilerin ilk olarak modele sunulduğu katmandır.
   - Örneğin, bir 28x28 piksellik gri tonlamalı görüntü için, girdi boyutu 784 olur.

### 2. **Gizli Katmanlar** 🌫️
   - Modelin öğrenme sürecini gerçekleştirdiği katmanlardır.
   - Çok sayıda gizli katman, daha karmaşık ilişkileri öğrenme yeteneği sağlar.

### 3. **Çıktı Katmanı** 🎯
   - Modelin nihai tahminini veya sonucunu ürettiği katmandır.
   - Örneğin, bir nesne tanıma modeli için, çıktı katmanı nesne sınıfını verir.

---

## ⚙️ Aktivasyon Fonksiyonları

Aktivasyon fonksiyonları, sinir ağlarındaki nöronların **aktif olup olmayacağına** karar verir. Verinin modelde ilerlemesini sağlar ve doğrusal olmayan (non-linear) ilişkileri öğrenmesine yardımcı olur.

### 🎇 Popüler Aktivasyon Fonksiyonları

1. **Sigmoid** 📉
   - Çıkışı 0 ile 1 arasında sıkıştırır.
   - Çoğunlukla son katmanlarda, ikili sınıflandırma problemlerinde kullanılır.

2. **ReLU (Rectified Linear Unit)** 🚀
   - Negatif değerleri sıfıra indirir, pozitif değerleri olduğu gibi geçirir.
   - Derin ağlarda yaygın olarak kullanılır, hesaplama açısından verimlidir.

3. **Tanh** 🌊
   - Çıkışı -1 ile 1 arasına sıkıştırır, sıfır merkezi sağlar.
   - Verilerin orta değerlere yakın olmasını sağlayarak daha hızlı öğrenme sağlar.

---

## 🔍 Önemli Kavramlar

### 1. **Aşırı Uyum (Overfitting)** 🎭
   - Modelin eğitim verisine aşırı uyum sağlaması durumudur.
   - Sonuç olarak, model yeni verilere iyi genelleme yapamaz.
   - **Dropout** gibi tekniklerle önlenebilir.

### 2. **Yetersiz Uyum (Underfitting)** 📉
   - Modelin ne eğitim ne de test verisinde yeterince başarılı olamaması durumudur.
   - Modelin daha fazla veri ve daha karmaşık bir yapıyla eğitilmesi gerekebilir.

### 3. **Optimizasyon Algoritmaları** ⚖️
   - Modelin kayıp fonksiyonunu minimize ederek, daha iyi sonuçlar elde etmesine yardımcı olur.
   - **Adam**, **SGD** gibi yaygın algoritmalar kullanılır.

---

## 🔧 Derin Öğrenme ile Model Eğitimi

1. **Veri Hazırlama** 📊
   - Verinin ön işleme süreci; normalizasyon, veri artırma (augmentation) ve ayrıştırma gibi adımlar içerir.
   - Eğitim ve test setlerine bölünerek eğitime başlanır.

2. **Model Tasarımı** 🏗️
   - Modelin katman yapısı belirlenir.
   - Katman sayısı, aktivasyon fonksiyonları, ve diğer parametreler seçilir.

3. **Eğitim (Training)** 🏋️
   - Model, veriden örnekler alarak kendini günceller.
   - **Epoch** ve **batch size** gibi parametrelerle kontrol edilir.
  
4. **Model Değerlendirme** 📈
   - Modelin doğruluğu, hassasiyeti (precision) gibi metriklerle değerlendirilir.
   - Eğer gerekliyse modelin yeniden eğitimi yapılabilir.

---

## 🚀 Derin Öğrenme ile İlgili Uygulamalar

1. **Görüntü Tanıma** 🖼️
   - CNN'ler (Convolutional Neural Networks) ile görüntülerden otomatik özellik çıkarımı yapılır.

2. **Ses Tanıma** 🎤
   - RNN (Recurrent Neural Networks) modelleri, ses dalgalarındaki ardışık verileri işleyebilir.

3. **Doğal Dil İşleme** 🌐
   - Metin verilerini analiz eder ve dil modelleri oluşturur.

4. **Oyunlar ve Simülasyonlar** 🎮
   - Yapay zeka, oyun stratejileri öğrenmek için kullanılabilir (örneğin, AlphaGo).

---

## 🔥 Derin Öğrenme Kütüphaneleri

1. **TensorFlow** 🌐
   - Google tarafından geliştirilen popüler bir kütüphanedir.
  
2. **PyTorch** 🔥
   - Özellikle araştırma ve geliştirme için yaygın olarak tercih edilir.

3. **Keras** 🍫
   - Kolay kullanımı ile bilinen bir kütüphanedir, TensorFlow'un bir üst katmanı olarak kullanılabilir.

---

Derin öğrenme, dünyamızı değiştiren pek çok yeniliğe güç katmaktadır. Daha derin ağlar, daha büyük veri setleri ve daha güçlü donanımlar ile bu alan hızla gelişmeye devam ediyor. 🌐🧠💥
