## OBM — OmfoBalkanMicroElectronics

**OBM (OmfoBalkanMicroElectronics)**'e hoş geldiniz. Mikrodenetleyici tabanlı teknolojileri keşfetmeye, geliştirmeye ve belgelendirmeye odaklanan bir gömülü sistemler ve donanım araştırma organizasyonuyuz.

## Hikayemiz

OBM, Türkiye'den gömülü sistemlerle ilgilenen iki elektronik meraklısının **STM32** mikrodenetleyicileri üzerinde çalışmaya başlamasıyla ortaya çıkan basit bir fikirden doğdu.

İlk proje fikirlerimiz ve tasarımlarımız **OCM32** adı altında geliştirildi. Bu süreçte STM32 tabanlı projeler, özel geliştirme kartları ve Nucleo tarzı shield tasarımları üzerinde çalıştık. Zamanla bu çalışmaları, bilgi paylaşabileceğimiz, kendimizi geliştirebileceğimiz ve yaptığımız keşifleri belgeleyebileceğimiz gerçek bir organizasyona dönüştürmeye karar verdik.

**OmfoBalkanMicroElectronics** ismi ise aslında bir şaka olarak ortaya çıktı. İsim, en sevdiğimiz Balkan müzik gruplarından biri olan **OMFO**'dan ilham alınarak oluşturuldu. Eğlence amaçlı başlayan bu isim, zamanla büyüyen gömülü sistemler yolculuğumuzun kimliği haline geldi.

## Neler Yapıyoruz

Çalışmalarımız şu alanlara odaklanmaktadır:

- Gömülü sistem geliştirme
- Mikrodenetleyici programlama
- Firmware geliştirme ve modifikasyonu
- Donanım araştırmaları ve tersine mühendislik
- Dokümantasyonu bulunmayan platformların belgelenmesi
- Geliştirme araçları ve deneysel donanımlar

Başlıca üzerinde çalıştığımız platformlar:

- **STM32** (STM32F7 ve RTOS tabanlı projeler dahil)
- **Microchip PIC** mikrodenetleyicileri
- **JieLi (AC69xx serisi)** ses platformları
- **NationalChip / GuoXin GX serisi**
- Araştırmalarımız sırasında karşılaştığımız diğer gömülü platformlar

## Güncel Ana Projeler

OBM bünyesinde birçok farklı deneysel çalışma, araştırma ve geliştirme deposu (repository) bulunacaktır. Bunların tamamını burada listelemek pratik olmadığı için, bu bölümde yalnızca en önemli ve aktif projelerimiz yer almaktadır.

## MagicPIC

### Sorumlu Geliştirici(ler)

**Barbaror4**  
**MeteÖnelge**

**MagicPIC**, klasik PIC mikrodenetleyicilerinin sadeliğini ve yeteneklerini keşfetmeye odaklanan PIC tabanlı geliştirme projemizdir.

Proje, **PIC16F886** temel alınarak geliştirilmekte olup; özel geliştirme kartları, deneysel çalışmalar ve öğrenme kaynakları oluşturmayı amaçlamaktadır. Basit bir mikrodenetleyici platformu olarak başlayan MagicPIC'in zamanla daha büyük bir ekosisteme dönüşmesini hedefliyoruz.

**Proje Durumu:** MagicPIC şu anda en önemli geliştirme odaklarımızdan biridir. Gömülü sistemler bizim için en büyük ilgi ve merak alanıdır. Donanım geliştirme, yazılım deneyleri ve kapsamlı dokümantasyon ile projeyi büyütmeyi hedefliyoruz. Katkılar, fikirler ve geri bildirimler her zaman memnuniyetle karşılanmaktadır.

**Projenin Şu Anki Durumu:** MagicPIC projesi aktif geliştirme sürecindedir. **MeteÖnelge**'nin proje ve **HackPROM** projesi için temin ettiği bileşenler kendisine ulaşmıştır. **Barbaror4** ise gerekli bileşenlerin siparişini tamamlamış olup kargo sürecini beklemektedir. Donanımların tamamlanmasının ardından ilk prototiplerin geliştirilmesine başlanacak ve proje deposu (repository) kamuya açılarak geliştirme süreci düzenli olarak belgelenecektir.

*(S.E.: Barbaror4)*

## STM32F746G-DISCO Zephyr RTOS MP3 Player

### Sorumlu Geliştirici

**Barbaror4**

**STM32F746G-DISCO** geliştirme kartı üzerine inşa edilen gelişmiş bir gömülü ses oynatıcı projesidir.

Projenin amacı aşağıdaki özelliklere sahip gelişmiş bir MP3 oynatıcı geliştirmektir:

- STM32F746 mikrodenetleyicisi
- Zephyr RTOS
- Özel ses işleme altyapısı
- Modern grafiksel kullanıcı arayüzü

Temel mimari ve yazılım altyapısı geliştirilmeye devam ettiği için depo (repository) şu anda gizlidir.

**Proje Durumu:** Şu anda ana geliştirme odağımı **MagicPIC** platformuna ve diğer gömülü sistem araştırmalarına kaydırmış bulunuyorum. Bu nedenle proje aktif olarak geliştirilmemektedir. Ancak ileride şartlar ve ilgi doğrultusunda geliştirme sürecine yeniden başlanması planlanabilir.

## JieLi AC6925 Araştırmaları ve Firmware Geliştirme

### Sorumlu Geliştirici

**Barbaror4**

En önemli araştırma alanlarımızdan biri **JieLi AC6925** platformudur.

Çalışmalarımız şunları kapsamaktadır:

- Özel çevre birimi (peripheral) kodlarının geliştirilmesi
- Yazılımsal I2C (Software I2C) uygulamaları
- SSD1306/SSD1315 tabanlı OLED ekranların sürülmesi
- 4x20 OLED/LCD arayüzleriyle çalışma
- Firmware modifikasyonu ve analizi
- Boot modlarının ve firmware yükleme yöntemlerinin araştırılması
- Geliştirme ve test amaçlı özel donanım araçlarının oluşturulması

Bu projenin amacı, yaygın olarak kullanılan ancak yeterince dokümante edilmemiş bu ses SoC'lerini daha iyi anlamak ve belgelendirmektir.

**Proje Durumu:** Şu anda JieLi platformuna yönelik araştırmaları ve dokümantasyonu geliştirmeye odaklanıyorum. Projede ayrıntılı dokümantasyon, örnek projeler ve hızlı prototipleme ile test yapmayı kolaylaştıracak kaynaklar yer alacaktır. 

Araştırmaların devamı için **BT201 JieLi AC6925** tabanlı bir modül temin edilmiştir. Bu modül üzerinde OLED entegrasyonu, özel çevre birimi geliştirmeleri ve çeşitli donanım/yazılım deneyleri gerçekleştirilecektir. Gerekli test ve geliştirme süreçleri tamamlandıktan sonra elde edilen çalışmalar, örnekler ve dokümantasyon kamuya açık şekilde paylaşılacaktır.

Özellikle bu alandaki katkılar her zaman memnuniyetle karşılanmaktadır; çünkü topluluk desteği, az bilinen bu gömülü platformların anlaşılmasına, belgelenmesine ve korunmasına büyük katkı sağlamaktadır.

*(S.E.: Barbaror4)*
## NationalChip / GuoXin Araştırmaları

### Sorumlu Geliştirici(ler)

**Barbaror4**  
**MeteÖnelge**

Ayrıca **NationalChip (GuoXin GX serisi)** platformları üzerinde de çalışmalar yürütmekteyiz.

Araştırma konularımız:

- UART haberleşme analizi
- GXDownloader etkileşimi
- Boot haberleşmesi araştırmaları
- Firmware araştırmaları ve korunması

Araştırmalarımız sonucunda GX platformlarıyla UART üzerinden başarılı haberleşme kurulmuş olup, firmware analizleri ve platform araştırmaları devam etmektedir.

**Proje Durumu:** NationalChip tabanlı platformlar üzerinde aktif olarak araştırmalar yürütüyoruz. MeteÖnelge şu anda GX tabanlı olduğunu düşündüğümüz bir STB alıcısı üzerinde çalışmaktadır. Barbaror4 ise çeşitli STB kartlarını araştırmaktadır. Bunlardan biri olan **AT1511S**, yapılan tersine mühendislik çalışmaları sonucunda yeniden markalanmış bir **NationalChip GX6101D** platformu olarak tanımlanmıştır. Dokümantasyon, donanım bilgileri ve katkılar her zaman memnuniyetle karşılanmaktadır. Topluluk araştırmaları, yeterince belgelenmemiş bu gömülü sistemlerin anlaşılmasına ve korunmasına büyük katkı sağlamaktadır.

## HackPROM

### Sorumlu Geliştirici

**MeteÖnelge**

**HackPROM**, **Flash** ve **EEPROM** gibi programlanabilir bellek yongaları üzerinde çalışan bir donanım araştırma projesidir.

Proje kapsamında:

- Flash ve EEPROM yongalarından firmware ve veri okunması
- Çıkarılan firmware'lerin analiz edilmesi ve değiştirilmesi
- Gömülü sistemlerin tersine mühendisliği
- Özel payload'ların ve değiştirilmiş firmware dosyalarının oluşturulması
- Tüketici elektroniğinde ve gömülü sistemlerde kullanılan bellek yongalarının araştırılması

Projede, çeşitli bellek yongalarını okumak, yazmak ve araştırmak amacıyla **CH341A programlayıcısı** kullanılmaktadır.

**Proje Durumu:** HackPROM, firmware depolama yapısını ve gömülü donanımları daha iyi anlamaya odaklanmaktadır. Amaç; bellek yongalarındaki verilerin okunmasını, analiz edilmesini ve değiştirilmesini kolaylaştırmaktır. Dokümantasyon, deneysel çalışmalar ve araştırma sonuçları geliştirme süreci boyunca paylaşılacaktır.

Katkılar, donanım örnekleri ve araştırma sonuçları her zaman memnuniyetle karşılanmaktadır.

## Tersine Mühendislik ve Donanım Araştırmaları

OBM'nin önemli çalışma alanlarından biri, yeterli dokümantasyona sahip olmayan donanımları anlamaktır.

Bunlara örnek olarak:

- Bilinmeyen yongaların ve kartların tersine mühendisliği
- Pin analizleri ile dokümantasyonu bulunmayan entegre devrelerin tanımlanması
- Tüketici elektroniği donanımlarının araştırılması

Bunun örneklerinden biri **AT1511S** yongasıdır. Yapılan tersine mühendislik çalışmaları sonucunda bu yonganın aslında **NationalChip GX6101D** platformuna dayandığı ortaya çıkarılmıştır.

## Hedefimiz

OBM'nin amacı öğrenmek, deney yapmak ve bilgiyi paylaşmaktır.

Yeterince belgelenmemiş donanımların, unutulmuş platformların ve gizemini koruyan yongaların; merak, araştırma ve iş birliği sayesinde anlaşılabileceğine inanıyoruz.

Basit PIC deneylerinden gelişmiş gömülü sistem tersine mühendisliğine kadar uzanan yolculuğumuzda hedefimiz, elektronik dünyasını keşfetmeye devam etmektir.

**OBM'ye hoş geldiniz.**
