# RetinaFace vs MTCNN: Yüz Tespiti Karşılaştırması

Bu proje, iki popüler yüz tespiti modelini — **MTCNN** ve **RetinaFace** — karşılaştırarak performanslarını değerlendirir. Farklı yüz tespiti senaryolarında doğruluk, hız ve esneklik gibi önemli metrikler üzerinden bir analiz sunulmaktadır.

## 📌 Proje Amacı

- **MTCNN** ve **RetinaFace** modellerinin karşılaştırılması
- Yüz tespiti doğruluğu, hız ve esneklik açısından değerlendirme
- Her iki modelin avantajları ve sınırlamaları hakkında bilgi sağlama

## 🧠 Kullanılan Modeller

### 1. MTCNN (Multi-task Cascaded Convolutional Networks)
- **Açıklama:** MTCNN, yüz tespiti, yüz hizalama ve yüz bölgesi çıkarımı için üç aşamalı bir ağ yapısına sahiptir. Hızlı ve etkili bir model olarak bilinir.

### 2. RetinaFace
- **Açıklama:** RetinaFace, tek aşamalı bir yüz tespiti modelidir ve yüzün her pikselini tahmin ederek yüksek doğruluk sağlar. Özellikle zor koşullarda etkili sonuçlar verir.

## ⚙️ Kullanılan Kütüphaneler

- `tensorflow`
- `keras`
- `opencv`
- `matplotlib`
- `numpy`

## 📊 Karşılaştırma Metrikleri

- **Doğruluk (Accuracy):** Yüz tespitinin doğruluğu
- **Hız (Speed):** Her bir modelin işlem süresi
- **Esneklik (Robustness):** Farklı koşullarda modelin performansı

## SONUÇLAR

**Doğruluk:** RetinaFace, MTCNN'ye kıyasla daha yüksek doğruluk oranları sergilemiştir.
**Hız:** MTCNN, RetinaFace'e göre daha hızlı çalışmaktadır.
**Esneklik:** RetinaFace, zorlu koşullarda daha başarılı sonuçlar elde etmiştir.
