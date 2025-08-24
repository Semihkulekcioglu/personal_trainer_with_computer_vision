# Kişisel Antrenör

[Türkçe](README_TR.md) | [English](README.md)

Gerçek zamanlı olarak egzersiz hareketlerini takip eden ve sayım yapan bir bilgisayarlı görü uygulaması. Proje, MediaPipe ve OpenCV kullanarak vücut pozisyonlarını tespit eder ve egzersiz sayımı yapar.

## Özellikler

- Gerçek zamanlı vücut pozisyonu tespiti
- Şınav hareketi sayımı
- Açı hesaplama ve görselleştirme
- Webcam ve video dosyası desteği

## Gereksinimler

- Python 3.x
- OpenCV
- MediaPipe
- NumPy

## Kurulum

1. Projeyi klonlayın:
```bash
git clone https://github.com/Semihkulekcioglu/personal_trainer_with_computer_vision.git
cd personal_trainer_with_computer_vision
```

2. Gerekli paketleri yükleyin:
```bash
pip install -r requirements.txt
```

## Kullanım

1. Programı çalıştırın:
```bash
python "Kisisel_antrenor(Personal Trainer).py"
```

2. Webcam ile kullanmak için kodu olduğu gibi çalıştırın.
3. Video dosyası ile kullanmak için kodda şu satırı düzenleyin:
```python
cap = cv2.VideoCapture("video_dosyaniz.mp4")
```

## Örnek Çıktılar

Örnek çıktılar Results klasöründe bulunmaktadır.

## Detaylı Özellikler

- **Gerçek Zamanlı Vücut Takibi**: MediaPipe'ın poz tespiti kullanılarak 33 vücut noktası takip edilir
- **Egzersiz Sayımı**: Kol açısına göre otomatik şınav sayımı yapar
- **Görsel Geri Bildirim**: Vücut noktalarını ve bağlantılarını gerçek zamanlı çizer
- **Açı Ölçümü**: Egzersiz sırasında eklem açılarını hesaplar ve gösterir

## Katkıda Bulunma

1. Projeyi forklayın
2. Özellik dalınızı oluşturun (`git checkout -b özellik/HarikaBirÖzellik`)
3. Değişikliklerinizi commit edin (`git commit -m 'Harika bir özellik eklendi'`)
4. Dalınıza push yapın (`git push origin özellik/HarikaBirÖzellik`)
5. Bir Pull Request açın

## Lisans

Bu proje MIT Lisansı ile lisanslanmıştır - detaylar için `LICENSE` dosyasına bakın.
