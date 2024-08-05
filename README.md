# Çalışma Başlığı: Maaş Tahmini ve Veri Analizi

## Çalışma Genel Bakış

Bu çalışma, maaş tahmini yapmak ve veri analizi sürecini detaylı bir şekilde ele almayı amaçlamaktadır. Çalışma, veri setinin incelenmesi, görselleştirilmesi, model kurulması ve etkileşimli hesaplamalar yapılması adımlarını kapsamaktadır.

### Veriye İlk Temas
1. İlk olarak veri setinin ilk beş satırına göz attım.
2. Veri setinin son beş satırını kontrol ettim.
3. Veri setinde genel bilgi edindim.
4. Veri indekslerine göz attım.
5. Verinin sayısal dağılımını inceledim.
6. Verinin şeklini belirledim.
7. Verinin içinde boş veri olup olmadığını kontrol ettim.

### Veri Görselleştirmesi
1. Genel olarak veriye bakış yaptım.
2. Yıllık iş tecrübesinin maaşlar üzerindeki etkisini inceledim ve görselleştirdim.
3. Cinsiyetin maaş üzerindeki etkisini değerlendirdim ve görselleştirdim.
4. Tüm veriyi tek bir tabloda görselleştirerek genel bir bakış elde ettim.

### Model Kurma
1. Veriyi kullanarak bir model kurdum. Modelin parametrelerini belirledim ve hiperparametre ayarlarını yaptım.
2. Model sonuçlarını görselleştirdim ve performans değerlendirmesi yaptım.
3. Veri setinden rastgele veriler seçerek model üzerinde çeşitli işlemler gerçekleştirdim.

### Etkileşimli Hesaplama Yapma
1. Kullanıcı etkileşimli bir GUI (Grafiksel Kullanıcı Arayüzü) geliştirdim.

## Kullanılan Kütüphaneler
- `pandas` - Veri işleme ve analizi için.
- `seaborn` ve `matplotlib` - Veri görselleştirmesi için.
- `numpy` - Sayısal işlemler için.
- `sklearn` - Modelleme ve değerlendirme için.
- `tensorflow.keras` - Derin öğrenme modelleme için.
- `tkinter` - GUI geliştirme için.

## Veri Seti

Aşağıdaki veri seti kullanılmıştır:

```python
<class 'pandas.core.frame.DataFrame'>
RangeIndex: 400 entries, 0 to 399
Data columns (total 5 columns):
 #   Column              Non-Null Count  Dtype
---  ------              --------------  -----
 0   ID                  400 non-null    int64
 1   Gender              400 non-null    int32
 2   Experience (Years)  400 non-null    int64
 3   Position            400 non-null    int32
 4   Salary              400 non-null    int64
dtypes: int32(2), int64(3)
memory usage: 12.6 KB

## Proje Sonuçları
Yıllık iş tecrübesinin maaş üzerindeki etkisi ve cinsiyetin maaş üzerindeki etkisi detaylı bir şekilde analiz edilmiştir.
Modelleme adımlarında, veriler eğitim ve test setlerine ayrılmış, sonuçlar görselleştirilmiştir.
Kullanıcı etkileşimli GUI uygulaması ile sonuçların daha erişilebilir ve etkileşimli hale getirilmesi sağlanmıştır.

## Kullanım
Projenin nasıl kullanılacağını ve çalıştırılacağını öğrenmek için README dosyasını inceleyebilirsiniz.

## İletişim
Sorularınız veya geri bildirimleriniz için bana e-posta veya LinkedIn üzerinden ulaşabilirsiniz.

