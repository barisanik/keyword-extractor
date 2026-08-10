# İş İlanı Anahtar Kelime Çıkarıcı

İş ilanı metinlerindeki anahtar kelimeleri kategorilere ayırarak takip eden ve bu kelimeleri verilen yetkinlik setiyle karşılaştırıp eksikleri (gap) işaretleyen basit bir araçtır.
Tek bir HTML dosyasından ibarettir. Tarayıcıda açıp doğrudan kullanılabilir.

<img width="1121" height="1035" alt="image" src="https://github.com/user-attachments/assets/b1c6d508-b4f0-402f-8786-d6d4c0552c12" />
<img width="842" height="336" alt="image" src="https://github.com/user-attachments/assets/9e70aabb-3985-4d42-b8cf-74e7bdbae84b" />
<img width="837" height="703" alt="image" src="https://github.com/user-attachments/assets/59981ad5-c70b-40bf-b401-3a2d94598908" />

## Özellikler

- **Anahtar kelime çıkarımı:** `Tekli Analiz` ve `İlan Karşılaştırma` sayfalarında verilen ilanlarda yer alan anahtar kelimeleri tespit eder, vurgular ve kategorize eder.
- **Kategorizasyon:** Data, Frontend, Backend, DevOps, Cloud, Analytics, SoftSkills gibi kategoriler altında anahtar kelimeleri gruplar.
- **Yetkinlik Eşleşmesi:** `Yetkinliklerim` listesinde tanımlanan yetkinlikler (anahtar kelimeler) ile ilan içeriğindeki anahtar kelimeleri karşılaştırır. Kelimenin kullanım sıklığını da hesaba katarak ilanın eşleşme yüzdesini belirtir. 
- **Zorunlu/Opsiyonel Yetkinlik Ayrımı:** "Requirements" / "Preferred Qualifications" gibi bölümleri otomatik ayırt eder, eksik zorunlu gereksinimleri için uyarı metni gösterir.
- **Deneyim Yılı Karşılaştırması:** İlanlarda bulunan "5 yıl deneyim"/"5 years of experience" gibi ifadelerdeki yıl bilgisini algılar, `Yetkinliklerim` kısmında belirtilen deneyim yılı bilgisiyle karşılaştırabilir.
- **İlan Karşılaştırma:** Birden fazla ilanı bilgisayarınızdaki herhangi bir klasörde `.txt` veya `.md` formatıyla ekleyip eşleşme oranına göre sıralı şekilde ilanları görebilirsiniz.
- **Düzenlenebilir Anahtar Kelime Bankası:** Anahtar kelime bankası kişiselleştirilebilir, JSON olarak içe/dışa aktarılabilir.
- **Bağlı Anahtar Kelime Tanımlama:** Mevcut anahtar kelimelere bağlanacak eş anlamlı kelimeler tanımlanabilir. Örneğin "Google Cloud Platform" anahtar kelimesine "GCP" anahtar kelimesi bağlanabilir.
- **Anahtar Kelime Yönetim Paneli:** Bu sayfadan mevcutta tanımlı anahtar kelimeleri ve bağlı anahtar kelimeleri görüntüleyebilirsiniz. 

## Önemli Uyarı

Sonradan eklenen tüm anahtar kelimeler ve yetkinlikler oturum boyunca tarayıcı hafızasında tutulur. Anahtar kelimelerin kalıcı olarak saklanabilmesi için `⬇ JSON indir` ve `⬆ JSON yükle` butonları kullanılır.

**Not:** `İlan Karşılaştırma` sekmesinde yer alan klasör seçme işlemi esnasında bir kerelik açılan uyarı mesajı üzerinden ilgili klasöre erişim izni verilmesi gerekmektedir. Bu standart bir tarayıcı erişim iznidir. Sonraki girişlerde bu klasöre erişim için izin gerekmez.
<center>
<img width="444" height="178" alt="image" src="https://github.com/user-attachments/assets/91babf89-f4c6-43b3-a746-24cc9ad897b7" />
