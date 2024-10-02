# IMAGE CAPTIONING (Görüntü Altyazılama) PROJESİ
Bu projede, Flickr8K veri setini kullanarak görüntü altyazılama işlemi gerçekleştirdim. Literatür taramalarım sırasında, Türkçe diline yönelik çok fazla veri seti bulamadığım için, mevcut veri setini Türkçeye çevirmeye karar verdim. 
Ancak, çevirilen cümleler oldukça kısa ve genel kaldı, bu nedenle cümleleri daha açıklayıcı ve detaylı hale getirerek uzattım. Model seçiminde ise, cihaz performansı vedaha verimli çalışması nedeniyle EfficientNet B0 modelini
tercih ettim. Aşağıda yer alan görsellerde, her adımda oluşan kayıp ve başarım oranlarını, test görüntüleri ile birlikte görebilirsiniz. Ayrıca, çevirdiğim Türkçe veri setinin doğruluk oranını BERT ve BLEU skorlarıyla değerlendirdim.
(Karşılaştırmayı Google Translate ile yaptım.) Uzatılmış cümlelerin BERT ve BLEU skorlarını da karşılaştırmalı olarak inceleyebilirsiniz.

* Doğrulama ve Test Oranları
  
![1](https://github.com/user-attachments/assets/da3a8a8f-1d78-4e32-af28-02e0ec2460a6)

* Örnek Görseller
  
![2](https://github.com/user-attachments/assets/ea0757f6-f98a-460a-9071-dfc5aaaafdce)


![3](https://github.com/user-attachments/assets/bb9b49cb-0f1f-49c8-b584-7dbf586ecfac)


![4](https://github.com/user-attachments/assets/009ea4be-94b3-4b34-9b79-adf0cbeb270e)


![8](https://github.com/user-attachments/assets/e13c9c45-462d-4177-9029-2cd5f94b8e24)

* Çeviri Veri Setinin Korpus BLEU Skoru = 0.3586
* Çeviri Veri Setinin Ortalama BLEU Skoru = 0.3332
* Çeviri Veri Setinin chrF Skoru = 68.3832

* Uzatılmış Veri Setinin BERT Skoru = 0.8999
* Uzatılmış Veri Setinin Korpus BLEU Skoru = 0.0630
* UZatılmış Veri Setinin Ortalama BLEU Skoru = 0.0650 

  
