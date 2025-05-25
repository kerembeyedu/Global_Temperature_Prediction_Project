# 🌍 GlobalTemperaturePredictionProject

Bu proje, Global AI Hub kapsamında gerçekleştirilenAkbank Makine Öğrenmesine Giriş Bootcamp programı sürecinde geliştirilmiştir. Amacımız, dünya genelindeki ortalama sıcaklık verilerini analiz ederek gelecekteki sıcaklıkları tahmin eden bir makine öğrenimi modeli geliştirmektir.

## 📌 Giriş

Projede kullanılan veri seti, çeşitli ülkeler için zaman içerisinde ölçülmüş ortalama sıcaklık değerlerini içermektedir. Bu veriler temizlenmiş, ön işleme tabi tutulmuş ve çeşitli makine öğrenimi algoritmaları ile modelleme gerçekleştirilmiştir.

Çalışmanın ana adımları:

- Veri keşfi ve ön işleme
- Aykırı değerlerin tespiti ve temizlenmesi
- Ülkelerin sıcaklık eğilimlerinin incelenmesi
- Encoding ve özellik mühendisliği
- Regresyon modellemeleri (Random Forest, Gradient Boosting, vs.)
- Model değerlendirme ve yorumlama

Detaylı teknik açıklamalara `.ipynb` dosyasında Markdown hücreleri ile yer verilmiştir.

## 📊 Kullanılan Metrikler ve Yorumlar

Modelin başarımını değerlendirmek için aşağıdaki metrikler kullanılmıştır:

- **MAE (Mean Absolute Error):** 7.13  
- **MSE (Mean Squared Error):** 97.22  
- **R² Skoru:** 0.73  

> R² skorunun 0.73 olması, modelin sıcaklık verilerindeki varyansın %73’ünü açıklayabildiğini göstermektedir. MAE’nin 7.13 olması ise, modelin ortalama 7°F'lik bir hata ile tahmin yaptığını ortaya koymaktadır. Bu sonuçlar modelin genel sıcaklık trendlerini başarıyla öğrenebildiğini göstermektedir.

Daha iyi sonuçlar elde etmek için hiperparametre ayarları, veri zenginleştirme ve feature engineering gibi alanlarda geliştirmeler yapılabilir.

## 🚀 Ekler

Projeyi genişletmek için aşağıdaki adımlar planlanmaktadır:

- Streamlit veya Gradio gibi araçlarla basit bir kullanıcı arayüzü oluşturmak
- Gerçek zamanlı sıcaklık verilerini API üzerinden almak ve modeli güncel veriyle test etmek
- Veri setini bölgesel detaylara göre genişletmek (şehir, kıta bazlı)

## 🔮 Sonuç ve Gelecek Çalışmalar

Bu çalışma, küresel sıcaklıkların zaman içindeki değişimini anlamaya ve gelecekteki değerleri tahmin etmeye yönelik başarılı bir ilk adım olmuştur. Gelecekte aşağıdaki alanlarda geliştirme hedeflenmektedir:

- Modelin hassasiyetini artırmak için mevsimsel ve coğrafi faktörlerin daha detaylı incelenmesi
- Farklı model türlerinin denenmesi (LSTM, Prophet gibi zaman serisi modelleri)
- Modelin web tabanlı bir arayüz ile son kullanıcıya sunulması

Projeyi zaman içinde geliştirerek hem teknik yetkinliğimi artırmak hem de sürdürülebilir çevre projelerine katkı sağlamak istiyorum.

---

## Kaggle Linki

https://www.kaggle.com/code/memreu/globaltemperaturepredictionproject
https://www.kaggle.com/code/kerembey/globaltemperaturepredictionproject
