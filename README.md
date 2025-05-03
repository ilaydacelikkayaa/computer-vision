# Yüz Algılama ve Siyah-Beyaz Mod Projesi

Bu repo, webcam görüntüsünü kullanarak yüz algılama ve siyah-beyaz mod özelliklerini içeren iki farklı projeyi barındırmaktadır. OpenCV kullanılarak geliştirilen bu projeler, görseller üzerinde bazı görsel manipülasyonlar yapmaktadır.

## Projeler

### 1. Yüz Algılama ve Siyah-Beyaz Mod (Yüz Renkli, Diğer Bölge Siyah-Beyaz)

Bu projede, webcam görüntüsü başlangıçta siyah-beyaz olarak gösterilir ve 3 saniye sonra yüz algılaması yapılır. Algılanan yüz kısmı renkli olarak kalır, geri kalan her şey ise siyah-beyaz olur.

#### Özellikler:
- Başlangıçta siyah-beyaz görüntü
- 3 saniye sonra yüz algılama yapılır
- Yüz kısmı renkli kalır, geri kalan her şey siyah-beyaz olur

### 2. 5 Saniye Sonra Siyah-Beyaz Mod Projesi

Bu projede, webcam görüntüsü ilk 5 saniye boyunca renkli olarak gösterilir. 5 saniye sonunda görüntü siyah-beyaz hale gelir ve ekranda mod değişim bilgisi görüntülenir.

#### Özellikler:
- İlk 5 saniye renkli görüntü gösterilir
- 5 saniye sonra görüntü siyah-beyaz olur
- Mod değişimi hakkında bilgi yazısı

## Kurulum ve Kullanım

### Gerekli Kütüphaneler:
Projeyi çalıştırabilmek için aşağıdaki Python kütüphanelerini yüklemeniz gerekmektedir:
- OpenCV (`cv2`)

Bu kütüphaneyi yüklemek için şu komutu kullanabilirsiniz:

```bash
pip install opencv-python
