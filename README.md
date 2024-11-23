# Spotify_Track_Analysis

![SPOTIFY](https://raw.githubusercontent.com/fatihakar5/Spotify_Track_Analysis/refs/heads/main/spotify.jpg)
![SPOTIFY]()
Spotify Şarkıları Verisetini analiz ediyoruz. Verisetinde, Spotify'da bulunan şarkılara ait çeşitli bilgiler yer almaktadır.

Spotify, dünya çapında en popüler müzik akış platformlarından biridir ve bu verisetini incelemek, müzikle ilgili eğilimleri ve desenleri keşfetmek için mükemmel bir fırsat sunmaktadır. Bu analiz ile, şarkıların popülerliği ile ses özellikleri arasındaki ilişkileri anlamayı amaçlıyoruz.

Amaçlar:
 - 🎵 Şarkı popülerliğinin dağılımını incelemek ve ses özellikleri ile ilişkisini araştırmak.
 - 🔊 Farklı ses özellikleri (örneğin, tempo, yüksek ses seviyesi, dans edilebilirlik) arasındaki korelasyonları keşfetmek.
 - 🌎 Türlerin dağılımını analiz etmek ve türlerin şarkı özelliklerine etkisini incelemek.
 - 📊 Veriyi görselleştirerek önemli desenleri ve trendleri ortaya çıkarmak.
 - 🎵 Bu keşifsel analiz, müzik dünyasında ilginç desenler ortaya koymayı ve bir şarkının popülerliğine etki eden ses özelliklerini anlamayı hedeflemektedir.
 - 🔊 Bu proje, Spotify şarkı veri setini kullanarak müzik dünyasındaki trendleri, ses özelliklerinin popülerlik üzerindeki etkilerini ve türler arasındaki farkları keşfetmeyi amaçlamaktadır.
 - 🎵 Spotify, dünya çapında milyonlarca kullanıcı tarafından tercih edilen bir platformdur ve bu analiz, şarkıların teknik özellikleriyle 
kullanıcıların tercihleri arasındaki bağlantıları anlamak için mükemmel bir fırsat sunmaktadır.

# SONUÇ VE ÖNERİLER¶
- En popüler şarklı türü "POP-FILM" iken en az popüler şarkı türü "IRANIAN" olarak bulunmuştur.
- En popüler şarkıcılar : "SAM SMITH;KIM PETRAS , BAD BUNNY;CHECHO CORLEONE , MANUEL TURIZO VE BIZARRAP;QUEVEDO"
- Dans edilebilirliği en yüksek olan şarkı türü "KIDS"
- Enerjisi en yüksek şarkı türü "DEATH-METAL"
- Canlı söylenme olasılığı en yüksek şarkı türü "COMEDY"
- Konuşma içeriği oranı en yüksek olan şarkı türü "COMEDY"
- Enstrümantal oranı en yüksek şarkı türü "STUDY"
- Duygusallığı en yüksek şarkı türü "SALSA"
- Temposu en yüksek şarkı türü "DRUM-AND-BASS"
- Şarkı açık içerikli sözler içerdiğinde popülerliği ,dans edilebilirliği ve canlı söylenme oranı artıyor
- Canlı söyleme oranı düşük olduğunda şarkının popülerliği daha yüksektir
- Şarkı süresi 0-1 dakika arasında iken popülerlik daha yüksektir
- Şarkı sayısının fazla olması popülerliği etkilemiyor
- Şarkının açık içerik içermesi ile içermemesi arasında istatistiksel olarak farklılıklar vardır
- Şarkıların parça tonları(key) arasında istatistiksel olarak anlamlı farklılıklar vardır
- Yapılan analizler sonucunda ortaya çıkan sonuçları değerlendirdiğimizde popularity değişkenini sınıflandırarak yeni veri seti oluşturmamız makine öğrenmesi modellerinde daha iyi ve güvenilir sonuçlar verecektir.

#### UYGUN ML MODELLERİ

- LogisticRegression
- XGBoost
- Catboost
- LightGBM
- DecisionTree
- SVC
## Bu modeller uygulanarak iyi sonuçlar elde edilebilir. GridSearch veya RandomSearch uygulanarak en iyi modeli seçebiliriz.

# PROJE KAGGLE LINK : [https://www.kaggle.com/code/fatihakar5/spotify-track-analysis]
