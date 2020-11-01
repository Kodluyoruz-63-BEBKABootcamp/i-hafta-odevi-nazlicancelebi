# 24 Ekim Ödevleri
 
- GitHub adresime [buradan](https://github.com/nazlicancelebi) ulaşabilirsiniz.
- HackerRank adresime [buradan](https://www.hackerrank.com/nazlicancelebi) ulaşabilirsiniz.
- StackOverFlow adresime [buradan](https://stackoverflow.com/users/14511161/nazlicancelebi) ulaşabilirsiniz.
- Visual Studio benefitlerinden yararlanmak için Microsoft hesabı açıldı.

##  Docker'a ve Docker'a ait kavramlara nelerdir?
Docker, uygulamalarınızı hızla derlemenizi, test etmenizi ve dağıtmanızı sağlayan bir yazılım platformudur. Docker, yazılımları kitaplıklar, sistem araçları, kod ve çalışma zamanı dahil olmak üzere yazılımların çalışması için gerekli her şeyi içeren **container** adlı standartlaştırılmış birimler halinde paketler. Docker'ı kullanarak her ortama hızla uygulama dağıtıp uygulamaları ölçeklendirebilir ve kodunuzu çalıştırabilirsiniz.
### Docker Hakkında Temel Kavramlar
**Image :** içerisinde uygulamaları barındıran container oluşturmak için kullanılan onceden hazırlanmış paketlerdir.
**Container :** İmagelardan türetilen host os üzerinde çalışan veya çalışmaya hazır ortamlardır.
**Dockerfile :** İmage üretmek için önceden belirlenmiş kuralları ve komutları içeren dockera özel dosya yapısı.
**DockerHub :** Docker imageların paylaşıldığı community deposu diyebiliriz. Bir çok official image barındırılmaktadır.
### Avantajları Nelerdir?
-	Docker, Hypervisor kullanmaz ve tam yüklü bir işletim sistemi barındırmaz bu sayede saniyeler içinde çalışır ve kullanıma hazır hale gelir.
-	Docker, yazılımlarınızın tüm altyapı gereksinimlerini kod olarak saklar. (versiyonlama) Bu Docker'ın en önemli özelliklerinden biridir. Bu özellik sayesinde yazılımınızı farklı servis sağlayıcıları üzerinde kolaylıkla gezindirebilir, çoğaltabilir veya paylaşabilirsiniz.
-	Docker, çok az kaynakla büyük işler yapabilmektedir. Bunun ana sebebi kullandığı konteyner teknolojisidir.
-	Uygulamalarınıza beklenmedik bir şekilde yüksek trafik geldiğinde saniyeler içerisinde 1000'lerce konteyner hazır hale gelerek yükünüzü omuzlar.
-	Docker, uygulamalarınızı standart bir zemine oturtarak her platformda aynı şekilde çalışmasını sağlar.

##  .Net Core versiyonları ve bu versiyonlar arasındaki farklar
Asp .Net Core 1.x: Açık kaynak geliştirmeye yönelik çabaların getirdiği en önemli başarı Asp.Net Core 1.0'ın herkese açık olarak piyasaya sürülmesiydi. 2002 ve çekirdek mimarisinde önemli değişiklikler olmadan 4.6.2 sürümüne kadar gelişti; yepyeni çerçeve, MVC, Web API ve web sayfaları gibi önceki tüm web uygulama teknolojilerini, daha önce MVC6 olarak bilinen tek bir programlama modülünde birleştirdi.

Asp .Net Core 2.x: Yeni sürüm, son ikisini eskisi ile daha geriye dönük uyumlu hale getirmek için çoğunlukla .NET Framework, .NET Core ve .NET Standard arasında paylaşılan API'leri standartlaştırmayı amaçlayan çok sayıda önemli arabirim geliştirmesine sahipti: bunlar sayesinde mevcut .NET Framework projelerini .NET Core ve/veya .NET Standard'a taşıma çabaları, eskisinden çok daha kolay hale geldi ve birçok "geleneksel" geliştiriciye mevcut teknik bilgilerini kaybetmeden yeni paradigmayı deneme ve adapte etme şansı verdi.

Asp .Net Core 3.x: Eylül 2019'da piyasaya sürüldü ve başka bir dizi performans ve güvenlik iyileştirmesi ve yeni özelliklerle birlikte geldi. Örneğin: Blazor, gRPC gibi yeni özellikler, Windows Forms ve Windows Presentation Foundation için gelişmiş içe aktarma yetenekleriyle Windows masaüstü uygulamaları desteği, C# 8 desteği vb.

ASP .NET Core geliştirme ekibi, .NET Core 3.0 üzerinde .NET Core Docker deneyimini iyileştirmek için çok çaba sarf etti. Daha spesifik olarak, CoreCLR'yi daha verimli hale getirmek, Docker kaynak sınırlarını (bellek ve CPU gibi) varsayılan olarak daha iyi karşılamak ve daha fazla yapılandırma ayarı sunmak için önemli çalışma zamanı değişiklikleri içeren ilk sürümdür.


##  .Net 5 geçilme ihtiyaçları nelerdir, geçiş sürecinin tamamlanmasıyla neler hedeflenmektedir.
- Temel hedef, .netcore,.net framework xamerin ve mono'nun avantajlarını tek çatı altında toplamaktır. Böylece frameworkler arasındaki uyumsuzluk giderilecek olup daha kullanışlı bir sistem haline gelecektir.
- Game development ile Unity oyun platformu desteklenecek
- Xamarin .Net5 bünyesi içine girerek mobil platformlarada destek sağlanabilecektir.
- HTTP3 desteğinin gelmesi.(Daha hızlı daha günvenli.)
- Asp.net Web form desteğinin sona ermesi ve Microsoft şu anda resmi olarak tanıtılan Blazor’ı öneriyor.
- .NET 5 ile tek bir base class library olacak.
- Windows ARM64 ve ARM64 temelleri
- Kapsamlı performans iyileştirmeleri
- Konteyner boyutu optimizasyonları
- Uygulama kırpma
- C # derleyici geliştirmeleri
- Döküm hata ayıklaması için araç desteği
- Platform, boş değer atanabilir referans türleri için% 80 ek açıklamalıdır

##  Markdown yazımı ve kullanımı 
### M A R K D O W N
En basit tanımı ile, web yazarları için text-to-HTML (metinden HTML’e) dönüştürme aracıdır. Markdown tasarımının temel hedefi geliştiricileri tarafından okunulabilirlik (readability) olarak belirtilmektedir. Bu amaçla e-posta yazımı temelinde ağırlık göstermektedir. Daha detaylı bir tanım olarak, düz metin biçimlendirme (markup language) sözdizimine (syntax) sahip hafif bir düz metin biçimlendirme dili (plain text formatting syntax) olarak ifade edilebilir. Aynı isimli araç sadece HTML dilini desteklese de günümüzde pek çok formatta çıktı üretebilmek için de kullanılmaktadır.
Bu bağlamda **“Markdown”** iki şeydir:
*	Düz bir metin biçimlendirme sözdizimi (plain text formatting syntax),
*	Perl ile yazılmış, düz metin biçimlendirmesini HTML’ye dönüştüren bir yazılım aracı (Markdown.pl).
Markdown dosyaları genellikle **"*.md"** uzantılıdır. Markdown read me yazmak icin yayginca kullanılan bir markup language. GitHub Repolarınızda fırtınalar estirip harika projeler yapsanız bile güzel bir “README.md” dosyanız olmadan kimseye gösteremezsiniz.

##  Yazılım alanında takip ettiğiniz kişiler kimlerdir?
- Engin Demiroğ [GitHub](https://github.com/engindemirog)
- Sadi Evren Şeker [GitHub](https://github.com/BilgisayarKavramlari)
- Mert Çobanoğlu [GitHub](https://github.com/cobanov) 

## Microsoft Azure tarafında ne gibi hizmetler vardır?
Microsoft Azure hem açık çevre ortamlarından hem de İnternet'ten tüketilebilen çok çeşitli İnternet hizmetini sağlamakta" olan bir bulut platformu hizmetidir.
- Uygulama Geliştirme
  - Azure yönetilen veritabanları
  - Geliştirme ve test
  - DevOps
  - DevSecOps
  - E-ticaret
  - Oyun geliştirme
  - Nesnelerin İnterneti
  - Hızlı uygulama geliştirme
  - Mikro hizmet uygulamaları
  - Cep Telefonu
  - Modern uygulama geliştirme
  - Sunucusuz bilgi işlem
  - Azure’daki mesajlaşma hizmetleri
- Yapay Zeka
  - Yapay Zeka
  - Bilgi araştırma
- Buluta Geçiş
  - .NET uygulamaları geçişi
  - Azure’a geçiş merkezi
  - Geliştirme ve test
  - Linux geçişi
  - Ana bilgisayar geçişi
  - Azure üzerinde SAP
  - SQL Server geçişi
  - Windows Server geçişi
- Veri ve Analiz
  - Blok zinciri
  - İş zekası
  - Bulut ölçeğinde analiz
  - Nesnelerin İnterneti
  - Daha güvenli çalışma alanı için Azure IoT
  - Akıllı alanlar için Azure IoT
- Hibrit Bulut ve Altyapı
  - Yedekleme ve olağanüstü durum kurtarma
  - Yüksek performanslı bilgi işlem (HPC)
  - Hibrit bulut çözümleri
  - Ultra düşük gecikmeli uç bilişim
  - İş açısından kritik uygulamalar
- Güvenlik ve idare
  - Azure idaresi
  - Yedekleme ve olağanüstü durum kurtarma
  - Gizli bilgi işlem
  - Azure ağ güvenliği
- Sektör Çözümleri
  - Enerji
  - Finansal hizmetler
  - Oyun geliştirme
  - Kamu
  - Sağlık ve yaşam bilimleri
  - Üretim
  - Medya ve eğlence
  - Perakende

##  Kodun kalitesinin metrik olarak ölçülmesi?
Kodun kalitesi yazılım kalitesi demektir ve Yazılım Kalitesi ölçme işlemi zor bir süreç olduğu için sıklıkla ihmal edilir ve bu iş için zaman ve bütçe ayrılmaz. 
* Büyüklük (Size)
* Karmaşıklık (Complexity) 
* Yapısallık (Structure) 
* Modülerlik (Modularity)
* Nesneye Yönelik (Object Oriented)
* Bakım Yapılabilirlik (Maintainability)
* Gereksiz Kod (Redundant Code)
* İşlev Noktaları (Function Points) 
* Gramer (Grammar) 
* Kod Tekrarları (Duplicate Code) 
gibi özelliklerine bakılarak yazılımın mevcut kalitesini ölçmek , sorunlu birimleri bulmak, teknik borcu kontrol altında tutabilmek, tazılımın/ürünün gelecekteki durumu hakkında öngörüde bulunabilmek demektir.
