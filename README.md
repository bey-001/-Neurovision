# -Neurovision

Neurovision, medikal görüntüleme verilerini (özellikle NIfTI formatındaki MR görüntüleri) işlemek, analiz etmek ve derin öğrenme modelleri (Segmentation/Classification) ile anlamlandırmak için geliştirilmiş açık kaynaklı bir projedir.

Bu proje, MONAI (Medical Open Network for AI) kütüphanesi kullanılarak, tıbbi görüntüleme iş akışlarını (preprocessing, training, inference) standartlaştırmayı hedefler.

## 🚀 Özellikler

NIfTI Desteği: Tıbbi standart olan .nii ve .nii.gz formatlarıyla tam uyum.

MONAI Pipelines: Veri artırma (augmentation) ve ön işleme için optimize edilmiş transformlar.

Model Mimarisi: Gelişmiş 3D UNet ve varyantları.

Esnek Veri Yapısı: Farklı veri setlerine kolayca adapte edilebilir mimari.


## 📊 Veri Seti Hazırlığı 
Bu proje, gerçekçi beyin MR simülasyonları sağlayan BrainWeb veri seti ile uyumlu çalışacak şekilde tasarlanmıştır.

Veriyi İndirin: BrainWeb (Simulated Brain Database) adresine gidin.

Dosyaları Alın: Projeyi test etmek için farklı modalitelerdeki (T1, T2, PD) ve farklı gürültü seviyelerindeki simüle edilmiş ham verileri (Raw data) indirebilirsiniz.

Dizini Yapılandırın: İndirdiğiniz dosyaları NIfTI formatına dönüştürdükten sonra projenin ana dizininde aşağıdaki klasör yapısını oluşturun:
