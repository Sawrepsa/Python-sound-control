# El Tespiti ile Ses Seviyesi Kontrolü


Bu proje, el tespiti kullanarak cihazın ses seviyesini kontrol etmeyi sağlar. Proje, Python dilini ve aşağıdaki kütüphaneleri kullanarak ses kontrolünü gerçekleştirir.

## Kullanılan Kütüphaneler
Proje dosyalarını çalıştırmak için aşağıdaki kütüphaneleri yüklemeniz gerekmektedir

- **cv2 (OpenCV)**: Görüntü işleme ve kamera erişimi için kullanılır.
- **Mediapipe**: El tespiti için kullanılan güçlü bir kütüphanedir.
- **math**: Matematiksel işlemler için kullanılır.
- **ctypes**: Düşük seviye C dilleriyle etkileşim sağlar.
- **comtypes**: Windows API aracılığıyla ses kontrolü için kullanılır.
- **pycaw.pycaw**: Ses kontrolü için Windows'daki ses aygıtlarıyla etkileşim sağlar.
- **numpy**: Diziler ve matematiksel işlemler için kullanılır.


## Kullanım
- Proje dosyalarını bilgisayarınıza indirin veya klonlayın.

- Ana dizindeki **python-sound-control.py** dosyasını çalıştırın.

- Program çalıştığında, kamera ekranı açılacak ve elinizi kamera önünde gösterin.

- El tespit edildiğinde, elinizin yüksekliğine bağlı olarak ses seviyesi ayarlanacaktır. El yüksekliği arttıkça ses seviyesi 
 de artar, el yüksekliği azaldıkça ses seviyesi de azalır.

## Nasıl Çalışır?
Proje, Mediapipe kütüphanesi kullanılarak el tespiti yapar.
Elin koordinatlarına göre, el yüksekliğini belirler ve ses seviyesini buna göre ayarlar.
Ses kontrolü için ctypes ve pycaw.pycaw kütüphaneleri kullanılır.
Katkıda Bulunma
Bu proje açık kaynaklıdır ve katkıda bulunmaktan mutluluk duyarız! Düzeltemeyeceğimiz hatalar veya yeni özellikler eklemek için pull request gönderin.



## Teşekkürler
Bu proje, el tespiti için güçlü Mediapipe kütüphanesini kullanmaktadır. Mediapipe ekibine teşekkür ederiz.
Ses kontrolü için ctypes ve pycaw.pycaw kütüphanelerini kullanıyoruz. Bu kütüphaneleri sağlayan geliştiricilere teşekkür ederiz.
İletişim
Eğer herhangi bir sorunuz veya öneriniz varsa, lütfen bize e-posta yoluyla ulaşın: ibwoooo90s@gmail.com

