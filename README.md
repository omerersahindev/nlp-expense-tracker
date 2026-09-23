# 💬 Doğal Dil İşleme Destekli Kişisel Harcama Takipçisi

Bu proje, kullanıcıların günlük dilde yazdığı cümleleri (örneğin *"kahve içtim 200"*, *"taksiye 150 tl verdim"*) analiz ederek tutar ve harcama kategorisini otomatik ayrıştıran ve SQLite veritabanında depolayan akıllı bir uygulamadır.

## 🚀 Öne Çıkan Özellikler

- **Metin Ayrıştırma (Text Parsing):** Düzenli ifadeler (Regex) kullanarak serbest metin içerisinden sayısal tutarları ve harcama yerlerini otomatik olarak çekme.
- **İlişkisel Veritabanı:** Verileri SQLite üzerinde depolama ve yönetme.
- **SQL Analitik Sorguları:** `GROUP BY` ve `SUM` kullanarak harcama kategorilerine göre otomatik özet raporlar oluşturma.
- **Veri Görselleştirme:** `Matplotlib` ile harcama dağılımını gösteren pasta grafikleri üretme.

## 🛠️ Kullanılan Teknolojiler

- **Dil:** Python 3.x
- **Veritabanı:** SQLite3
- **Veri Analizi & Görselleştirme:** Pandas, Matplotlib
- **Metin İşleme:** `re` (Regular Expressions)

## 💻 Nasıl Çalıştırılır?

```bash
# Gerekli kütüphaneleri yükleyin
pip install pandas matplotlib

# Uygulamayı çalıştırın
python main.py
