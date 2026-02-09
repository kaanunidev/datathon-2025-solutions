# Datathon 2025 Solutions

Bu proje, Datathon 2025 yarışması için geliştirilmiş makine öğrenmesi çözümlerini içermektedir.

## 📋 Proje Hakkında

Bu çözüm, e-ticaret kullanıcı oturumlarının değerini (session value) tahmin etmek için geliştirilmiş bir makine öğrenmesi modelidir. Kullanıcı davranışları (VIEW, ADD_CART, REMOVE_CART, BUY) analiz edilerek oturum değerleri tahmin edilmektedir.

## 🛠️ Kullanılan Teknolojiler

- **Python 3.11**
- **Pandas** - Veri manipülasyonu
- **NumPy** - Sayısal hesaplamalar
- **XGBoost** - Makine öğrenmesi modeli
- **Scikit-learn** - Model değerlendirme ve ön işleme
- **Matplotlib & Seaborn** - Veri görselleştirme

## 📊 Veri Seti

Proje şu event tiplerini içermektedir:
- VIEW: 58,829 olay
- ADD_CART: 42,304 olay
- REMOVE_CART: 25,615 olay
- BUY: 14,471 olay

**Toplam:** 204,170 kayıt

## 🚀 Kurulum

### Gereksinimler

```bash
pip install pandas numpy xgboost scikit-learn matplotlib seaborn
```

### Kullanım

1. Kaggle'dan veri setini indirin
2. Veri setini uygun klasöre yerleştirin
3. Jupyter Notebook'u çalıştırın:

```bash
jupyter notebook datathon-2025-solutions.ipynb
```

## 📈 Model

Model, **XGBoost** regresyon algoritması kullanılarak geliştirilmiştir. Feature engineering ve veri ön işleme adımları dahil edilmiştir:

- RobustScaler ile ölçeklendirme
- K-Fold cross validation
- Label encoding
- Zaman bazlı özellik çıkarımı

## 📝 Notlar

- Veri seti `/kaggle/input/datathon-2025` yolunda bulunmalıdır
- Session value tahminleri train ve test setleri için ayrı ayrı işlenmektedir

## 👤 Yazar

Datathon 2025 katılımcısı tarafından geliştirilmiştir.

## 📄 Lisans

Bu proje Datathon 2025 yarışması kapsamında geliştirilmiştir.

---

⭐ Beğendiyseniz yıldız vermeyi unutmayın!
