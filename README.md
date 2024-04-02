# Emlak Portalı Projesi
Bu proje, bir emlak portalı için API sunan bir uygulamayı içerir. Aşağıda proje dosya yapısı ve dosyaların işlevleri açıklanmaktadır.

## Dosya Yapısı

- **App_Data**: Bu klasör, uygulamanın veritabanı dosyalarını içerir. `emlakDB01.mdf` ve `emlakDB01_log.ldf` dosyaları burada bulunur. Bu dosyalar, uygulamanın temel veritabanı oluşturulması için kullanılır.

- **App_Start**: Bu klasör, uygulamanın başlangıç ayarlarını içerir. `SwaggerConfig.cs`, API belgelerini otomatik olarak oluşturan ve yayınlayan Swagger konfigürasyon dosyasıdır. `WebApiConfig.cs`, Web API rotalarını yapılandıran ayar dosyasıdır.

- **Controllers**: Bu klasör, uygulamanın API denetleyicilerini içerir. Örneğin, `ServisController.cs`, emlak servislerini yöneten bir API denetleyici sınıfıdır.

- **Models**: Bu klasör, uygulamanın veri modellerini içerir. `Ilan.cs`, `Kategori.cs`, `Uye.cs`, `Yorum.cs` gibi sınıflar, ilanlar, kategoriler, üyeler ve yorumlar gibi emlak veri nesnelerini temsil eder. Ayrıca, Entity Framework tarafından kullanılan veritabanı bağlamı ve model dosyaları da burada bulunur.

- **Properties**: Bu klasör, proje özellik dosyalarını içerir.

- **ViewModel**: Bu klasör, uygulamanın görünüm modellerini içerir.

- **bin**: Bu klasör, derlenmiş uygulama dosyalarını içerir.

- **obj/Debug**: Bu klasör, derleme sırasında oluşan geçici dosyaları içerir.

- **scripts**: Bu klasör, uygulamanın JavaScript dosyalarını içerir.

- **ApplicationInsights.config**: Bu dosya, uygulamanın Application Insights yapılandırma dosyasıdır.

- **Global.asax**: Bu dosya, ASP.NET uygulamasının ana dosyasıdır.

- **Global.asax.cs**: Bu dosya, Global.asax dosyasının kod dosyasıdır.

- **README.md**: Bu dosya, proje için bir README dosyasıdır.

- **Web.Debug.config**: Bu dosya, Debug modunda kullanılan web yapılandırma dosyasıdır.

- **Web.Release.config**: Bu dosya, Release modunda kullanılan web yapılandırma dosyasıdır.

- **Web.config**: Bu dosya, ASP.NET uygulamasının ana yapılandırma dosyasıdır.

- **emlak.csproj**: Bu dosya, proje dosyasıdır.

- **emlak.csproj.user**: Bu dosya, proje kullanıcı dosyasıdır.

- **packages.config**: Bu dosya, proje için kullanılan paketlerin listesini içerir.

## Proje Açıklaması
Bu proje, bir emlak portalının arkasında yer alan API sunucusunu temsil eder. API, kullanıcıların emlak ilanlarını arama, eklemek, güncellemek ve silmek gibi işlemleri gerçekleştirmelerine olanak tanır. Ayrıca, kullanıcıların kategorileri ve yorumları yönetmelerine de olanak sağlar.

## Kullanım
Projeyi yerel ortamınıza klonlayın ve Visual Studio'da açın.
Projeyi derleyin ve çalıştırın.
API denetleyicilerine HTTP istekleri göndererek ilanlar, kategoriler, üyeler ve yorumlar gibi veri işlemleri yapabilirsiniz.

## Katkıda Bulunma
Herhangi bir katkıda bulunmak isterseniz, lütfen bir çekme isteği gönderin. Katkılarınızı memnuniyetle karşılarız!

--- 

Bu README.md dosyası, projenin dosya yapısını, işlevselliğini, nasıl kullanılacağını ve katkıda bulunma yönergelerini açıklar.
