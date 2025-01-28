# 🎵 Spotify & YouTube Data Analysis Project

Bu proje, **Spotify** ve **YouTube** platformlarındaki şarkıların çeşitli özelliklerini analiz etmeyi ve bu analizleri görselleştirmeyi amaçlamaktadır. Proje kapsamında, Python kullanılarak veri işleme, analiz ve görselleştirme çalışmaları yapılmıştır.

---

## 📂 Proje İçeriği

### 1. **Veri Seti Bilgileri**
Veri seti, Spotify ve YouTube platformlarına ait şarkıların aşağıdaki özelliklerini içermektedir:
- **Spotify Özellikleri**:
  - `Danceability`, `Energy`, `Tempo`, `Loudness`, `Valence`, vb.
- **YouTube Özellikleri**:
  - `Views`, `Likes`, `Comments`, `Channel`, `Licensed`, `official_video`, vb.
- Toplam 28 sütun ve 20.718 satır içermektedir.

---

### 2. **Analizler ve Görselleştirmeler**
Proje kapsamında aşağıdaki analizler gerçekleştirilmiştir:

#### 🎧 **Spotify vs YouTube Karşılaştırması**
- Spotify'daki toplam dinlenme sayısı (%58.7) YouTube toplam izlenme sayısına kıyasla daha yüksektir.
- **Pasta Grafiği** ile iki platform arasındaki fark görselleştirilmiştir.

#### 📈 **Top 10 Şarkılar**
- **YouTube**: En çok izlenen ilk 10 şarkı.
- **Spotify**: En çok dinlenen ilk 10 şarkı.
- Her iki platformda da en popüler şarkı: *Shape of You*.
- **Çubuk Grafikler** ile karşılaştırmalı analiz yapılmıştır.

#### 🎵 **Albüm Tipleri Analizi**
- En çok tercih edilen albüm türü: **Album**.
- Albüm tiplerinin dağılımı:
  - Album: %72
  - Single: %24
  - Compilation: %4

#### 🧑‍🎤 **Sanatçı Performansları**
- En çok izlenme ve dinlenme sayılarına sahip sanatçılar sıralanmıştır:
  - **Ed Sheeran**, Spotify ve YouTube'da en popüler sanatçıdır.
  - **CoComelon**, YouTube'da oldukça popüler olmasına rağmen Spotify'da düşük performans göstermektedir.
- **Çubuk Grafikler** ile sanatçıların platform bazlı performansları görselleştirilmiştir.

#### 📊 **Korelasyon Analizi**
- `Views`, `Likes` ve `Comments` arasında güçlü pozitif korelasyon bulunmuştur.
- Yüksek enerji ve ses yüksekliği (`Energy` ve `Loudness`) arasında güçlü bir ilişki vardır.

#### ⏱️ **Şarkı Süresi Analizi**
- Şarkıların süre dağılımı incelenmiştir:
  - Ortalama şarkı süresi: 3-5 dakika arası.
  - **Histogram** görselleştirmesi ile yoğunluk analizi yapılmıştır.

#### 🏆 **Ed Sheeran'ın En Popüler Şarkıları**
- Ed Sheeran'ın en popüler şarkıları:
  - Shape of You
  - Thinking Out Loud
  - Perfect
- Şarkıların toplam dinlenme ve izlenme sayıları analiz edilmiştir.

---

## 🛠️ Kullanılan Teknolojiler

- **Python**:
  - Veri işleme: `pandas`, `numpy`
  - İstatistiksel analiz: `scipy`
  - Veri görselleştirme: `matplotlib`, `seaborn`, `plotly`
- **Jupyter Notebook**: Analizlerin gerçekleştirilmesi ve raporlanması.

---

## 📊 Kullanılan Görselleştirme Teknikleri
- Pasta Grafikler (Pie Charts)
- Çubuk Grafikler (Bar Charts)
- Isı Haritası (Heatmap)
- Histogramlar
- Kategorik Grafikler (Categorical Plots)

---

## 📁 Proje Yapısı

- **`spotify_youtube_analysis.ipynb`**: Proje kodları ve analizler.
- **`Spotify_Youtube.csv`**: Projede kullanılan veri seti.


---



## 📬 İletişim

Proje hakkında geri bildirim veya katkıda bulunmak isterseniz benimle iletişime geçebilirsiniz:

**GitHub**: [tayfun79](https://github.com/tayfun79)

---

