# Laravel Kaynakları ve Açık Kaynak Projeler

Bu repo, [Laravel](https://laravel.com) ile geliştirilmiş faydalı açık kaynak projelerini, GitHub reposu bağlantılarını
ve diğer kaynakları içerir. Laravel ekosistemine dair önemli araçlar, kütüphaneler, eğitim içerikleri ve en iyi
uygulamalar (best practices) hakkında sürekli olarak güncel bilgiler sağlamayı amaçlar.

## İçindekiler

1. [Laravel’e Giriş ve Genel Bilgiler](#laravele-giriş-ve-genel-bilgiler)
2. [Araçlar, Paketler ve Kütüphaneler](#araçlar-paketler-ve-kütüphaneler)
3. [En Popüler Laravel Ekosistem Bileşenleri](#en-popüler-laravel-ekosistem-bileşenleri)
4. [Kullanışlı Spatie Paketleri](#kullanışlı-spatie-paketleri)
5. [Geliştirme Ortamı Seçenekleri](#geliştirme-ortamı-seçenekleri)
6. [Eğitim ve Kaynaklar](#eğitim-ve-kaynaklar)
7. [En İyi Uygulamalar (Best Practices)](#en-iyi-uygulamalar-best-practices)
8. [Güvenlik ve Test](#güvenlik-ve-test)
9. [Topluluk ve Etkinlikler](#topluluk-ve-etkinlikler)
10. [Katkıda Bulunma](#katkıda-bulunma)
11. [Lisans](#lisans)

**[⬆ Başa Dön ⬆](#laravel-kaynakları-ve-açık-kaynak-projeler)**

---

## Laravel’e Giriş ve Genel Bilgiler

- **Resmi Sürüm Takvimi**: Laravel, genellikle yıllık major sürümler (10, 11, 12...) ve ara sürümlerle güncellenir.
- **PHP Versiyonu**: Güncel Laravel sürümleri için en az PHP 8.x veya üzeri kullanmanız tavsiye edilir.
- **Paket Yönetimi**: [Composer](https://getcomposer.org/) aracılığıyla paket kurulumları yapılır.
- **Kod Düzeni**: Laravel projelerinde [PSR-4](https://php-fig.org/psr/psr-4/) standartları benimsenir.

Laravel, **MVC** (Model-View-Controller) mimarisi üzerine kurulu, okunabilir sözdizimi ve zengin ekosistem bileşenleri
sayesinde PHP ile modern web uygulamaları geliştirmenin en popüler yollarından biridir.

**[⬆ Başa Dön ⬆](#laravel-kaynakları-ve-açık-kaynak-projeler)**

---

## Araçlar, Paketler ve Kütüphaneler

Laravel geliştiricilerinin işine yarayacak çeşitli araç, paket ve kütüphaneleri aşağıdaki tabloda bulabilirsiniz. Burada
ağırlıklı olarak **debug/hata ayıklama** ve **performans** odaklı paketlere yer verilmiştir.

| **Proje**               | **Bağlantı**                                                                                 | **Açıklama**                                                                                                                           |
|-------------------------|----------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------|
| **Laravel Telescope**   | [Link](https://laravel.com/docs/telescope)                                                   | Uygulamanızın istekleri, veritabanı sorguları, hata kayıtları ve daha fazlasını izlemek için güçlü bir hata ayıklama asistanı.         |
| **Laravel Horizon**     | [Link](https://laravel.com/docs/horizon)                                                     | Redis tabanlı kuyruklarınızı yönetmek ve izlemek için gelişmiş bir kontrol paneli.                                                     |
| **Laravel Pint**        | [Link](https://laravel.com/docs/pint)                                                        | Laravel projenizde kod stilini otomatik düzeltmek için geliştirilmiş “code style fixer” aracıdır.                                      |
| ---                     | ---                                                                                          | ---                                                                                                                                    |
| **Debugbar**            | [Link](https://github.com/barryvdh/laravel-debugbar)                                         | Uygulamanızın performansını izlemek ve hata ayıklamak için PHP Debug Bar'ı Laravel ile entegre eder.                                   |
| **Query Detector**      | [Link](https://github.com/beyondcode/laravel-query-detector)                                 | N+1 sorgu problemlerini tespit ederek uygulamanızın performansını artırmanıza yardımcı olur.                                           |
| **Clockwork**           | [Link](https://github.com/itsgoingd/clockwork)                                               | Uygulamanızın çalışma zamanını analiz etmek için tarayıcınıza entegre edilen bir geliştirme aracı.                                     |
| **Clockwork Extension** | [Link](https://chrome.google.com/webstore/detail/clockwork/dmggabnehkmmfmdffgajcflpdjlnoemp) | Clockwork verilerini tarayıcınızda görüntülemek için gerekli olan tarayıcı eklentisi.                                                  |
| **Log Viewer**          | [Link](https://github.com/opcodesio/log-viewer)                                              | Laravel loglarınızı hızlı ve güzel bir arayüzle görüntülemenizi sağlar.                                                                |
| **LaraDumps**           | [Link](https://github.com/laradumps/laradumps)                                               | Laravel PHP kodlama ve hata ayıklama deneyiminizi geliştirmek için tasarlanmış kullanıcı dostu bir uygulama.                           |
| **Env Keys Checker**    | [Link](https://github.com/msamgan/laravel-env-keys-checker)                                  | Tüm .env dosyalarınızda gerekli anahtarların mevcut olup olmadığını kontrol eder.                                                      |
| **MicroScope**          | [Link](https://github.com/imanghafoori1/laravel-microscope)                                  | Akıllı kontroller yaparak belirli hataları bulmanıza ve yeniden düzenleme yapmanıza olanak tanır.                                      |
| **WireSpy**             | [Link](https://github.com/wire-elements/wire-spy)                                            | Livewire bileşenleriniz için şık bir hata ayıklama aracı; bileşen durumunu incelemenize ve değişiklikleri takip etmenize olanak tanır. |
| **Laravel Pint**        | [Link](https://laravel.com/docs/pint)                                                        | Laravel projenizde kod stilini otomatik düzeltmek için geliştirilmiş “code style fixer” aracıdır.                                      |

**[⬆ Başa Dön ⬆](#laravel-kaynakları-ve-açık-kaynak-projeler)**

---

## En Popüler Laravel Ekosistem Bileşenleri

Laravel yalnızca bir framework değil, aynı zamanda geniş bir ekosisteme sahiptir. Aşağıdaki projeler, Laravel’e entegre
olarak sıkça kullanılır:

- **[Laravel Breeze](https://laravel.com/docs/starter-kits#laravel-breeze)**: Basit kullanıcı kimlik doğrulama (auth) ve
  başlangıç kitidir.
- **[Laravel Jetstream](https://laravel.com/docs/starter-kits#laravel-jetstream)**: Gelişmiş kimlik doğrulama, kullanıcı
  profili yönetimi ve daha fazlasını sunan başlangıç kitidir.
- **[Laravel Fortify](https://laravel.com/docs/fortify)**: API tabanlı kimlik doğrulama sistemi (Jetstream’in alt
  katmanını oluşturur).
- **[Laravel Spark](https://spark.laravel.com)**: Yazılımınızı hızlıca SaaS’e dönüştürmenizi sağlar.
- **[Socialite](https://laravel.com/docs/socialite)**: Sosyal ağlar (Google, Facebook, Twitter vb.) üzerinden kolay
  kimlik doğrulama sağlar.
- **[Cashier](https://laravel.com/docs/billing)**: Stripe veya Paddle ödemelerini projeye kolayca entegre eder.
- **[Scout](https://laravel.com/docs/scout)**: Uygulamaya tam metin arama (Algolia veya benzeri) eklemek için
  kullanışlıdır.
- **[Passport](https://laravel.com/docs/passport) / [Sanctum](https://laravel.com/docs/sanctum)**: API kimlik
  doğrulaması için OAuth2 (Passport) ve token tabanlı (Sanctum) çözümler sunar.
- **[Octane](https://laravel.com/docs/octane)**: Swoole veya RoadRunner gibi sunucularla yüksek performanslı Laravel
  deneyimi sağlar.
- **[TALL Stack (Tailwind CSS, Alpine.js, Laravel, Livewire)](https://tallstack.dev)**: Modern ve hızlı
  front-end/back-end entegrasyonu sağlar.
- **[Filament](https://filamentphp.com)**: Laravel için hafif bir admin paneli ve form bileşenleri sunar.
- **[Laravel Nova](https://nova.laravel.com)**: Laravel için güçlü bir yönetim paneli oluşturmanıza olanak tanır. (
  Ücretli)

**[⬆ Başa Dön ⬆](#laravel-kaynakları-ve-açık-kaynak-projeler)**

---

## Kullanışlı Spatie Paketleri

[Spatie](https://spatie.be/open-source) topluluğun en çok güven duyduğu geliştirici gruplarından biridir ve Laravel için
birçok faydalı paket üretmiştir:

- **[laravel-permission](https://github.com/spatie/laravel-permission)**: RBAC (Role-Based Access Control) sistemi
  kurmak için idealdir.
- **[laravel-activitylog](https://github.com/spatie/laravel-activitylog)**: Uygulamada gerçekleşen olayları günlüğe
  kaydetmek için kullanılır.
- **[laravel-medialibrary](https://github.com/spatie/laravel-medialibrary)**: Dosya yükleme ve yönetimini kolayca yapmak
  için kullanılır.
- **[laravel-backup](https://github.com/spatie/laravel-backup)**: Veritabanı ve dosyaların otomatik yedeklenmesi ve
  yönetimi için kullanılır.
- **[laravel-analytics](https://github.com/spatie/laravel-analytics)**: Google Analytics verilerini Laravel ile entegre
  etmek için kullanılır.

**[⬆ Başa Dön ⬆](#laravel-kaynakları-ve-açık-kaynak-projeler)**

---

## Geliştirme Ortamı Seçenekleri

### 1. Laragon (Windows)
**Resmi Sitesi:** [https://laragon.org](https://laragon.org)

- **Özellikler**:
  - Windows üzerinde kullanılan, taşınabilir ve hafif bir geliştirme ortamıdır.
  - `Apache` veya `Nginx`, `MySQL/MariaDB`, `Redis`, `Memcached` ve benzeri birçok aracı tek pakette sunar.
- **Avantajlar**:
  - Özellikle Windows kullanıcıları için WAMP/MAMP alternatifi, daha modern ve hızlı bir seçenektir.
  - Otomatik `virtual host` yönetimi ve PHP sürümleri arası kolay geçiş gibi kullanışlı özelliklere sahiptir.

### 2. Laravel Herd (macOS / Windows)
**Resmi Sitesi:** [https://herd.laravel.com](https://herd.laravel.com)

- **Özellikler**:
  - `macOS` ve `Windows` için tasarlanmış, basit ve hafif bir PHP geliştirme ortamıdır.
  - Sisteminize birden fazla PHP sürümünü kolayca kurma ve geçiş yapma olanağı sunar.
- **Avantajlar**:
  - Geliştiricinin yalnızca birkaç tıklama ile hızlı kurulum yapmasına imkân verir.
  - `nginx`, `Redis`, ve `MySQL` gibi yaygın servislerle entegre çalışır.

### 3. Docker / Self-Hosted
**Resmi Sitesi:** [https://docker.com](https://docker.com)

- **Özellikler**:
  - Kendi Docker imajlarınızı oluşturup, Laravel projelerinizi dilediğiniz gibi paketleyebilirsiniz.
  - `docker-compose` ile birden fazla servisi tek bir dosya üzerinden yönetebilirsiniz.
- **Avantajlar**:
  - Servislerinizi (PHP, Nginx, MySQL, vb.) farklı konteynerlarda yönetme imkânı verir.
  - Üretim ortamıyla neredeyse birebir uyumluluğu sağlamak mümkündür.

### 4. Laravel Sail
**Resmi Dokümantasyon:** [Laravel Sail](https://laravel.com/docs/sail)

- **Özellikler**:
  - Docker tabanlı resmi Laravel geliştirme ortamıdır.
  - `MySQL`, `PostgreSQL`, `Redis` gibi servisleri tek komutla ayağa kaldırma imkânı sağlar.
  - Proje içerisinde Docker Compose dosyaları ile birlikte gelir.
- **Avantajlar**:
  - Aynı anda birden fazla servisi yönetmek kolaydır.
  - Üretim ve geliştirme ortamlarının benzer Docker yapılandırmalarıyla çalıştırılabilmesi, sürpriz hataların önüne geçer.

### 5. Laravel Valet (macOS)
**Resmi Dokümantasyon:** [Laravel Valet](https://laravel.com/docs/11.x/valet)

- **Özellikler**:
  - Sadece macOS sistemlerde çalışan hafif, hızlı bir geliştirme ortamıdır.
  - `nginx` ve `dnsmasq` kullanarak `.test` uzantılı alan adlarını otomatik olarak ayarlar.
- **Avantajlar**:
  - Minimal konfigürasyon ile çok hızlı kurulum ve kullanım.
  - Bilgisayarı yormayan, arka planda sürekli çalışan bir servis yapısına sahiptir.

### 6. Homestead (Vagrant | VM)
**Resmi Dokümantasyon:** [Laravel Homestead](https://laravel.com/docs/11.x/homestead)

- **Özellikler**:
  - Vagrant tabanlı (VirtualBox veya VMware) resmi Laravel geliştirme box’ıdır.
  - _PHP, MySQL, PostgreSQL, Redis, Node.js_ vb. birçok servisi önceden yapılandırılmış şekilde sunar.
- **Avantajlar**:
  - Geliştirme ortamını tamamen izole eder.
  - Her projeye özgü sanal makine kurulumu yapılabilir, farklı sürümler paralel çalışabilir.

Bu farklı geliştirme ortamlarının avantajları ve kullanım şekilleri, projelerin gereksinimlerine ve ekibin tercihlerine bağlı olarak değişir.
- Docker/Sail, modern ve üretim-odaklı bir yaklaşıma sahiptir.
- Valet veya Herd, macOS üzerinde hızlı ve minimal bir deneyim sunar.
- Laragon, Windows tarafında kullanım kolaylığı sağlar.
- Homestead ise proje tabanlı izole bir VM yapısını tercih edenler için idealdir.

İhtiyaçlarınızı göz önünde bulundurarak size en uygun geliştirme ortamını seçebilirsiniz.

**[⬆ Başa Dön ⬆](#laravel-kaynakları-ve-açık-kaynak-projeler)**

---

## Eğitim ve Kaynaklar

- **[Resmi Laravel Dokümantasyonu](https://laravel.com/docs)**: Laravel hakkında en kapsamlı resmi kaynaktır.
- **[Laracasts](https://laracasts.com/)**: Jeffery Way tarafından hazırlanan yüzlerce eğitim videosu ve ders
  bulunmaktadır.
- **[Laravel News](https://laravel-news.com)**: Laravel ekosistemiyle ilgili güncel haberler, sürüm duyuruları ve
  makaleler içerir.
- **[Laravel Daily](https://laraveldaily.com)**: Kısa ipuçları, videolar ve blog yazıları yayınlanır.
- **[Youtube Kanalları](https://youtube.com/results?search_query=laravel)**: _DevDojo_, _Traversy Media_, _The Net
  Ninja_ gibi kanallarda Laravel dersleri ve rehber videoları bulabilirsiniz.

**[⬆ Başa Dön ⬆](#laravel-kaynakları-ve-açık-kaynak-projeler)**

---

## En İyi Uygulamalar (Best Practices)

1. **Dizin Yapısını Koruyun**  
   Modeller, Controller’lar, Migrations, Seeders ve Config dosyaları proje düzeni açısından standart alanlarda bulunsun.
2. **.env Dosyası**  
   Üretim ortamındaki hassas bilgileri `.env` dosyasında tutun, asla repo içinde paylaşmayın.
3. **Veritabanı İşlemleri**

- Mümkün olduğunca **Eloquent** kullanın.
- Fazla karmaşık sorgularda **Query Builder** ile netleştirin.
- Performans için **index** kullanmayı ihmal etmeyin.
- N+1 sorgu sorunlarını (örneğin `with()`, `eager loading`) tespit etmek
  için yukarıda önerdiğimiz paketleri kullanın.

4. **Validation (Doğrulama)**  
   Form isteklerini `Request` sınıfları üzerinden doğrulayın.
5. **Dependency Injection**  
   Service Container (IOC Container) yapısını kullanarak bağımlılıkları Controller’lara enjekte edin.
6. **Logging ve İzleme**

- Geliştirme ortamında **Laravel Telescope**, **Laravel Debugbar** gibi araçları kullanın. Üretim ortamında
  hataları/performansı izlemek için [Sentry](https://sentry.io) veya [Bugsnag](https://bugsnag.com)
  gibi servisler de tercih edilebilir.

7. **Versiyon Kontrol**

- Projeyi mutlaka **Git** ile yönetin ve düzenli commit mesajları yazın.
- Deployment süreçlerini otomatikleştirmek için **CI/CD** araçlarını kullanabilirsiniz (GitHub Actions, GitLab CI vb.).

8. **Kod Formatı ve Standartlar**

- [Laravel Pint](https://laravel.com/docs/pint) veya [PHP-CS-Fixer](https://github.com/PHP-CS-Fixer/PHP-CS-Fixer) gibi
  araçlarla kodunuzu düzenli tutun.

**[⬆ Başa Dön ⬆](#laravel-kaynakları-ve-açık-kaynak-projeler)**

---

## Güvenlik ve Test

- **Test**
    - Laravel’de `php artisan test` veya `vendor/bin/phpunit` komutlarını kullanarak testleri çalıştırabilirsiniz.
    - **Feature ve Unit test** ayrımını doğru yaparak her katmanda testler yazmaya özen gösterin.
    - **Mock** ve **Fakes** kullanarak bağımlılıkları izole edin.
- **Siber Güvenlik Önlemleri**
    - XSS (Cross-Site Scripting) ve CSRF (Cross-Site Request Forgery) korumaları Laravel’de varsayılan olarak aktif.
    - Şifreleri mutlaka hash (ör. `bcrypt`) edin.
    - Rate limiting için [Laravel Throttle Middleware](https://laravel.com/docs/rate-limiting) kullanarak API
      isteklerinizi koruma altına alın.
    - HTTPS kullanımını zorunlu kılın ve HSTS gibi ek başlıklar ayarlamayı düşünün.

**[⬆ Başa Dön ⬆](#laravel-kaynakları-ve-açık-kaynak-projeler)**

---

## Topluluk ve Etkinlikler

İstediğiniz kaynakları aşağıda bağlantılarıyla birlikte listeledim:

- **[Laravel Discord](https://discord.gg/laravel)**: Resmi Discord kanalı üzerinden binlerce geliştiriciyle sohbet
  edebilirsiniz.
- **[Laracasts Discuss](https://laracasts.com/discuss)** ve
  **[Laravel GitHub Discussions](https://github.com/laravel/framework/discussions)**: Laravel topluluğu ve
  geliştiricileriyle etkileşime geçebileceğiniz platformlardır.
- **[Laracon](https://laracon.net)**: Laravel’in resmi konferansıdır. Hem çevrimiçi hem de çeşitli ülkelerde fiziksel
  olarak düzenlenir.
- **Twitter/LinkedIn**: [#Laravel](https://linkedin.com/feed/hashtag/laravel) veya [#PHP](https://twitter.com/hashtag/PHP)
  etiketleriyle güncel haber ve paylaşımları takip edebilirsiniz.
- **[Meetup Grupları](https://meetup.com/topics/laravel)**: Bulunduğunuz şehirde veya ülkede Laravel/PHP
  meetuplarını arayın, toplulukla etkileşim halinde olun.

**[⬆ Başa Dön ⬆](#laravel-kaynakları-ve-açık-kaynak-projeler)**

---

## Katkıda Bulunma

Bu proje, topluluk katkılarına açıktır. Eğer bu kaynaklar listesine yeni projeler, araçlar veya dokümanlar eklemek
isterseniz, bir [pull request](https://github.com/AcikKaynakKutuphanesi/mukemmel-laravel-kaynaklari/pulls)
açabilirsiniz.

### Nasıl Katkı Yapılır?

1. Depoyu forklayın.
2. Yeni eklemek istediğiniz kaynağı/dosyayı/düzenlemeyi yapın.
3. Commit mesajlarınızı düzenli ve açıklayıcı yazın.
4. Pull request açarak katkınızı gönderebilirsiniz.

Laravel ekosistemindeki en yeni gelişmeleri takip etmeyi ihmal etmeyin ve katkılarınızla topluluğu
büyütmeye devam edin... Bu repo üzerinden yaptığınız her katkı, Laravel topluluğunun daha kaliteli ve kapsamlı bilgiye erişmesine destek
olacaktır!

**[⬆ Başa Dön ⬆](#laravel-kaynakları-ve-açık-kaynak-projeler)**

---

## Lisans

Bu proje **MIT** lisansı altında lisanslanmıştır. Daha fazla bilgi için [LICENSE](LICENSE) dosyasına göz atabilirsiniz.

**[⬆ Başa Dön ⬆](#laravel-kaynakları-ve-açık-kaynak-projeler)**