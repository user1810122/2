# Titanic Veri Analizi Projesi

Bu proje, Titanic gemisinin batması sırasında yolcuların hayatta kalma durumlarını içeren bir veri kümesini analiz etmek için yapılmıştır. Proje kapsamında Pandas, Matplotlib ve Seaborn gibi Python kütüphaneleri kullanılarak veri temizleme, keşifsel veri analizi (EDA) ve görselleştirmeler gerçekleştirilmiştir.

## Proje Yapısı

- **data/**: Proje ile ilgili veri kümesini içerir (`train.csv`).
- **notebooks/**: Analiz kodlarını içeren Jupyter Notebook dosyaları (`titanic_analysis.ipynb`).
- **README.md**: Proje hakkında genel bilgileri içerir.
- **requirements.txt**: Gerekli Python kütüphanelerini içerir.

## Veri Kümesi

Bu proje, Kaggle'dan alınan Titanic veri kümesini kullanmaktadır. Veri kümesi, Titanic gemisinde yolculuk eden kişilerin bilgilerini ve bu kişilerin hayatta kalıp kalmadığını içermektedir. 

**Kaggle Titanic Veri Kümesi Bağlantısı:** [Kaggle Titanic Data](https://www.kaggle.com/c/titanic/data)

### Veri Kümesi Özellikleri

- `PassengerId`: Yolcu ID'si
- `Survived`: Hayatta kalma durumu (0 = Hayır, 1 = Evet)
- `Pclass`: Bilet sınıfı (1 = 1. sınıf, 2 = 2. sınıf, 3 = 3. sınıf)
- `Name`: Yolcunun adı
- `Sex`: Cinsiyet
- `Age`: Yaş
- `SibSp`: Gemiye birlikte binilen kardeş/eş sayısı
- `Parch`: Gemiye birlikte binilen ebeveyn/çocuk sayısı
- `Ticket`: Bilet numarası
- `Fare`: Bilet ücreti
- `Cabin`: Kabin numarası (Eksik veriler içermektedir)
- `Embarked`: Gemiye binilen liman (C = Cherbourg, Q = Queenstown, S = Southampton)

## Kurulum

Bu projeyi yerel ortamınızda çalıştırmak için aşağıdaki adımları izleyin:

1. **Depoyu klonlayın:**
    ```bash
    git clone https://github.com/kullanici-adi/titanic-veri-analizi.git
    cd titanic-veri-analizi
    ```

2. **Gerekli Python paketlerini yükleyin:**
    ```bash
    pip install -r requirements.txt
    ```

3. **Jupyter Notebook'u çalıştırın:**
    ```bash
    jupyter notebook
    ```

4. **`titanic_analysis.ipynb`** dosyasını açarak adım adım kodları çalıştırabilirsiniz.

## Analiz Adımları

### 1. Veri Temizleme
Veri kümesi üzerinde eksik verilerin doldurulması, gereksiz sütunların kaldırılması ve veri türlerinin dönüştürülmesi işlemleri yapılmıştır.

### 2. Keşifsel Veri Analizi (EDA)
Veri kümesindeki temel istatistikler incelenmiş, cinsiyet, yaş ve yolcu sınıfı gibi faktörlerin hayatta kalma oranları üzerindeki etkileri analiz edilmiştir.

### 3. Görselleştirme
Matplotlib ve Seaborn kullanılarak çeşitli görselleştirmeler yapılmıştır. Örneğin, cinsiyet ve yolcu sınıfına göre hayatta kalma oranları, yaş dağılımı ve hayatta kalma durumu arasındaki ilişki gibi grafikler oluşturulmuştur.

## Sonuçlar ve İçgörüler

- **Cinsiyet:** Kadınların hayatta kalma oranı, erkeklere göre daha yüksektir.
- **Yolcu Sınıfı:** Birinci sınıf yolcuların hayatta kalma oranı daha yüksektir.
- **Yaş:** Çocukların hayatta kalma oranı yetişkinlere göre daha yüksektir.


