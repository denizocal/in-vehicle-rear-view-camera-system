# Raspberry Pi Tabanlı Araç İçi Geri Görüş Kamera Sistemi

Bu proje, araç geri vitese alındığında navigasyon ekranından geri görüş kamerası görüntüsüne otomatik olarak geçiş yapabilen, Raspberry Pi tabanlı bir araç içi görüntüleme sistemi olarak geliştirilmiştir.

Sistem, sürüş sırasında navigasyon işlevini destekleyen; geri manevra anında ise kamera görüntüsünü önceliklendirerek kullanıcıya daha güvenli ve işlevsel bir kullanım sunmayı amaçlayan bir yapı üzerine kurulmuştur.

## Proje Özeti

Bu çalışmada, araç içi kullanım senaryosuna uygun bir geri görüş kamera sistemi tasarlanmıştır. Sistem içerisinde Raspberry Pi ana işlem birimi olarak kullanılmış, Raspberry Pi uyumlu kamera modülü ile canlı görüntü alınmış ve geri vites bilgisine bağlı olarak ekran içeriği dinamik şekilde değiştirilmiştir.

Normal kullanımda navigasyon ekranı aktif durumda çalışırken, araç geri vitese geçirildiğinde sistem otomatik olarak kamera görüntüsünü ekrana yansıtmakta; böylece sürücü geri manevra sırasında arka görüşü doğrudan izleyebilmektedir.

## Projenin Amacı

Bu projenin temel amacı aşağıdaki alanlarda uygulamalı deneyim kazanmaktır:

- Raspberry Pi tabanlı gömülü sistem geliştirme
- Kamera modülü entegrasyonu
- Araç içi ekran senaryolarına uygun görüntüleme sistemi oluşturma
- Farklı çalışma modları arasında otomatik geçiş mantığı geliştirme
- Gerçek kullanım odaklı elektronik ve yazılım entegrasyonu sağlama

## Sistem Çalışma Mantığı

Sistem iki temel çalışma moduna sahiptir:

### Navigasyon Modu
Araç normal sürüş durumundayken ekranda navigasyon arayüzü görüntülenmektedir.

### Geri Görüş Modu
Araç geri vitese geçirildiğinde sistem ilgili sinyali algılamakta ve ekran içeriğini otomatik olarak değiştirerek geri görüş kamerası görüntüsünü göstermektedir.

Bu sayede sürücünün manuel olarak ekran değiştirmesine gerek kalmadan, kullanım senaryosuna uygun görüntü otomatik olarak sunulmaktadır.

## Sistem Bileşenleri

Projede yer alan temel bileşenler aşağıdaki gibidir:

- Raspberry Pi
- Raspberry Pi uyumlu kamera modülü
- Araç içi ekran / görüntüleme altyapısı
- Geri vites tetikleme mantığı
- Görüntü geçiş kontrol yazılımı
- Güç bağlantı ve sistem entegrasyon yapısı

## Gerçekleştirilen Çalışmalar

- Raspberry Pi tabanlı sistem mimarisi oluşturuldu
- Uyumlu kamera modülü sisteme entegre edildi
- Canlı görüntü alma yapısı kuruldu
- Navigasyon ve kamera görüntüsü arasında geçiş senaryosu tasarlandı
- Geri vitese bağlı otomatik ekran geçiş mantığı oluşturuldu
- Araç içi kullanım senaryosuna uygun test yapısı planlandı

## Kullanılan Teknolojiler ve Araçlar

- Raspberry Pi
- Raspberry Pi kamera modülü
- Gömülü Linux tabanlı çalışma yapısı
- Görüntüleme ve arayüz kontrol mantığı
- Araç içi entegrasyona uygun bağlantı yapısı

## Teknik Kazanımlar

Bu proje kapsamında aşağıdaki alanlarda uygulamalı deneyim kazanılmıştır:

- Kamera tabanlı gömülü sistem geliştirme
- Gerçek zamanlı görüntü alma
- Kullanım senaryosuna bağlı arayüz geçiş mantığı oluşturma
- Donanım ve yazılım entegrasyonu
- Araç elektroniğine yönelik sistem düşüncesi geliştirme

## Uygulama Alanları

Bu proje yapısı aşağıdaki uygulamalara uyarlanabilecek altyapıya sahiptir:

- Araç içi geri görüş sistemleri
- Akıllı araç ekran çözümleri
- Görüntü tabanlı sürüş destek sistemleri
- Raspberry Pi tabanlı otomotiv prototipleri

## Proje Görselleri

![Sistem Görünümü](images/sistem-gorunumu.png)

![Kamera Modülü](images/kamera-modulu.png)

![Ekran Arayüzü](images/ekran-arayuzu.png)

![Geri Görüş Modu](images/geri-gorus-modu.png)

## Geliştirme Potansiyeli

Bu proje aşağıdaki yönlerden geliştirilebilir:

- Gece görüş performansının iyileştirilmesi
- Daha hızlı ekran geçiş mekanizması
- Park yardımcı çizgilerinin eklenmesi
- Daha kompakt muhafaza tasarımı
- Kayıt alma özelliği
- Kablosuz kamera entegrasyonu
- Daha gelişmiş araç içi multimedya arayüzü

## Sonuç

Bu proje, araç içi görüntüleme ve sürüş destek senaryoları için işlevsel bir Raspberry Pi uygulamasıdır. Navigasyon ekranı ile geri görüş kamerası arasında otomatik geçiş yapabilmesi, projeyi yalnızca temel bir kamera entegrasyonu olmaktan çıkarıp gerçek kullanım senaryosuna yakın bir sistem haline getirmektedir. Donanım-yazılım entegrasyonu, kullanım mantığı ve otomotiv odaklı düşünce yapısı açısından güçlü bir uygulama çalışmasıdır.
