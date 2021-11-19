# SomeTryOns
..
## Soru 1 Cevaplar
- İlk soru için iki farklı cevap kodlanmıştır. 
- Kodların çıktılarını(çalıştırmak zorunda kalmadan) görebilmeniz için bilerek Jupyter Notebook kullandım. 
- Ayrıca kodların içinde metin halinde detaylı açıklamalar da yaptım.
- İlk cevap **"image-comparsion-soru1cvp1.ipynb"** scriptinde görülmektedir. Görsellerin histogramları çıkartılıp karşılaştırılmıştır. Daha sonra bu yöntem çok hoşuma gitmediği için ikinci cevabı hazırladım.
- İkinci cevap **traffic-sign-classification-with-image-processing-soru1cvp2.ipynb** scriptinde görülmektedir. Görsellerin çeşitli özelliklerini karşılaştırıp tabela algısı sağlanmıştır.
- Tabelaların yuvarlaklığı, boyutları, renkleri, benzerlikleri karşılaştırılarak tüm tabelalar tespit edilmiştir.
- Alternatif çözümler hala sunulabilir. Henüz denemedim fakat görüntü kontür ve momentleri üzerinden de güzel sonuçlar elde edilebilirdi.
## Soru 2 Cevap
- Fruit Images veriseti kullanılmıştır.
- Model olarak Faster RCNN kullanılmıştır.
- Model kütüphaneden çağırılmıştır.
- Kendim de model yazabiliyorum fakat vaktim olmadığından model yazma işlemini yetiştiremedim.
- Notebook'da bir sorun oldu çıktı görseller notebook üzerinde görülemiyor. Çıktıları dosya içine ve buraya ekleyeceğim.

###### **Eğitim Çıktısı**
![Egitim Çıktısı](https://github.com/dasmehdix/SomeTryOns/blob/main/Q2/training.png)
###### **Portakal Etiketi**
![prtkl](https://github.com/dasmehdix/SomeTryOns/blob/main/Q2/etiket.png)
###### **Portakal Çıktısı(NonMaxSupression Olmadan)**
![prtkl_](https://github.com/dasmehdix/SomeTryOns/blob/main/Q2/wo_NMS.png)
###### **Portakal Çıktısı(NonMaxSupression İle)**
![prtkl_1](https://github.com/dasmehdix/SomeTryOns/blob/main/Q2/w_NMS.png)
###### **Elma Etiketi**
![elm](https://github.com/dasmehdix/SomeTryOns/blob/main/Q2/etiket_2.png)
###### **Elma Çıktısı(NonMaxSupression İle)**
![elm1](https://github.com/dasmehdix/SomeTryOns/blob/main/Q2/cikti_NMS.png)
