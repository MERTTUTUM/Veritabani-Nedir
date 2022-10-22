

## VERİTABANI NEDİR? 

Veritabanı verilerin muntazam ve organize bir şekilde tutulmasını, yönetilmesini ve güncellenmesini sağlar. Ulaştığımız her veri veritabanlarında tutulur. Günümüzde her bilginin sanal ortama aktarılması verilerin saklanması gereksinimini ortaya koymuştur. Veritabanı, verilerimizi bir dizi tabloda ve içerisinde bulunan satır ,sütun ekseninde modeller . Bu şekilde veriler daha erişilebilir, yönetilebilir, değiştirilebilir ve güncellenebilir hale gelmiştir. 

## Veritabanı'nın Evrimi

1960'lı yılların başlarında ortaya çıkıyor. Hiyerarşik veri tabanları ( ağaç benzeri bir model ) ve ağ veri tabanı ( ilişkili ) verileri saklamak ve güncellemek için kullanılan orijinal sistemlerdi. 1980'li yıllarda ilişkisel veritabanları popüler oldu ve 1990'lı yıllarda nesne odaklı veri tabanları öne çıktı. Gelişen teknoloji ve hızla artış gösteren verilerin işlenmesine duyulan ihtiyaçtan dolayı NoSQL veritabanları geliştirildi. Günümüzde ise bulut veritabanları ve kendi kendini yöneten veri tabanları trendler arasında.

## Veritabanı (Database) Türleri Nelerdir?

-  [Dağıtık Veritabanı](#dağıtık-veritabanı)
-  [ilişkisel Veritabanı](#ilişkisel-veritabanı)
-  [Merkezi Veritabanı](#merkezi-veritabanı)
-  [Bulut Veritabanı](#bulut-veritabanı)
-  [Nesneye Yönelik Veritabanı](#nesneye-yönelik-veritabanı)
-  [Açık Kaynak Veritabanı](#açık-kaynak-veritabanı)
-  [NoSQL Veritabanı](#nosql-veritabanı)
-  [Grafik Veritabanı](#grafik-veritabanı)




# Dağıtık Veritabanı

Bu veritabanı bilgileri farklı veri tabanlarında tutar. Her bir veritabanı da bilgisayar ağlarıyla birbirine bağlıdır. Dağıtık sistemlerin ortaya çıkış sebebi kaynakları paylaşma ihtiyacı. Aynı anda birden fazla veritabanı üzerinde işlem yapmayı sağlıyor. Farklı bilgisayarlardaki donanım araçlarını kullanarak verilerimizi daha performanslı tutmayı sağlar. Avantajları ise Esneklik, Şeffaflık, Parçalama, Erişilebilirlik gibi özellikleri barındırır.

# ilişkisel Veritabanı

Günümüzde en çok tercih edilen veritabanı türüdür. Verilerin birbiriyle ilişkili noktalarını baz alarak işlem yapmaya olanak sağlar. E.F. Codd tarafından 1970 yılında geliştirilmiş 1980 yılından itibaren kullanılmaya başlanmıştır. Bu tür veritabanlarında bire-bir , bire-çok , çoka-çok ilişkilendirme yapılabilmektedir.
Yapılandırılmış bilgilere en verimli ve hızlı bir şekilde erişim imkanı sunar.

# Merkezi Veritabanı

Dağıtık veritabanı'nın aksine toplanan tüm verileri tek bir veri tabanında saklar. Avantajları ise verilerimizin tek bir otorite tarafından kullanıcılarına verilen erişim yetkileri ile kontrol edilebilmesidir. Dağıtık veritabanları'nın getirdiği karmaşıklığı ortadan kaldırır.

# Bulut Veritabanı

DBaaS olarak tanımlanır. Bulut platformu üzerinde kurulan ve erişilen veritabanıdır. İş operasyonlarını desteklemek ve verinin kullanılabilirliğini artırmak amacıyla bir kurum tarafından ücretli abonelik sistemleriyle özel, genel veya hibrit bir bulut ortamında oluşturulan ,erişilen veritabanıdır. Avantajları ise esneklik, erişilebilirlik, performans.

# Nesneye Yönelik Veritabanı

Bu veritabanında veriler nesne tabanlı programlamada olduğu gibi nesneler biçiminde ifade edilir. Nesne yönelimli programlama dilleri kullanılarak oluşturulan verilerin depolanması için uygundur. Fakat bu veriler genellikle ilişkisel veritabanlarında depolanıyor. Ses, video, yazı vb. veriler düzenlenebilir.

# Açık Kaynak Veritabanı

Adından da anlaşılacağı gibi erişime açık ve açık kaynak kodlu üzerinde çeşitli işlemler yapmamıza olanak sağlayan ücretsiz veritabanı türüdür. Farklı kaynaklardan edinilen veriler çeşitli kuruluşlarca yayınlanır. Genel olarak makine öğrenmesi ve veri ön işleme gibi alanlar için uygundur. 

# NoSQL Veritabanı

İlişkilendirilmiş veritabanları çalıştığı zaman çok fazla transaction(işlem) gerçekleşir bu da sistemimize ağır yük bindiriyor. Bu sorunu ortadan kaldırmak için NoSQL geliştiriliyor. Yarı yapılandırılmış ve yapılandırılmamış verileri işlemek için kullanılır.Genel olarak mobil uygulamalar, IOT, içerik yönetimi, gerçek zamanlı büyük veri vb. alanlarda kullanılır.

# Grafik Veritabanı

Bu veritabanı türünde verilerin depolanması ve sorgulanması grafik teorisi üzerinden yapılır. İki öğe den oluşur ; "Node" varlıkları temsil eder.(müşteri,çalışan) ve "Edge" ilişkiyi temsil eder. Genel olarak sosyal ağ oluşturmada, ürün önerileri, ağ analizi gibi alanlarda kullanabiliriz.




## Veritabanı Bileşenleri Nelerdir?

- [Veri](#veri)
- [Yazılım](#yazılım)
- [Donanım](#donanım)
- [Veritabanı Sorgulama Dili](#veritabanı-sorgulama-dili)



# Veri

İşlenmemiş gerçek enformasyon parçacığı. Bir Konu ile ilgili gerçeklerdir. Örneğin Resim, Dosya, Ses, Harfler, Semboller vb. Ayrıca veriler tek başına bir anlam taşımazken bir araya getirilip işlenerek anlamlı bilgiler oluşturur. Kişinin kayıt etmeye değer bulduğu her şey veridir.


# Yazılım

Bir veritabanını organize etmek veya yönetebilmek için gerekli programlar bu kategoridedir. Örneğin bir şirketin metinlerini kaydetmek ve düzenlemek için Word gibi programa ihtiyaç duyuyorsak veritabanını muntazam hale getirmek için de çeşitli yazılımlara ihtiyaç duyarız.


# Donanım

Veritabanın'da kullanılan her türlü cihaz bu kategoridedir. (Bilgisayar, elektronik cihazlar vb.) Verilerimizi fiziki olarak bu donanımlar üzerinde saklarız.


# Veritabanı Sorgulama Dili

Verilerimize ulaşmak için bir dizi komut ve sorgu dili kullanmamız gerek. Bu sorgular sayesinde veritabanımız'dan anlamlı ve ilişkili veriler çekebiliriz.





## Veritabanı Yönetim Sistemleri Çeşitleri

- [MySQL](#mysql)
- [SQLite](#sqlite)
- [MariaDB](#mariadb)
- [MongoDB](#mongodb)
- [Oracle](#oracle)
- [PostgreSQL](#postgresql)
- [Microsoft SQL Server](#microsoft-sql-server)



# MySQL

ASP, PHP gibi web programlama dilleri ile kullanılabilir. Dünyada En çok bilinen açık kaynaklı ilişkisel veritabanı yönetim sistemidir. Hızlı ve esnek bir yapısı vardır. Altı milyondan fazla sistemde yüklüdür. Windows, unix gibi işletim sistemleri için ücretsizdir. Ticari kullanım için ayrı bir lisans alınması gerek bu lisans ise Oracle tarafından sunulmaktadır. 


# SQLite

D.Richard Hipp tarafından 2000 yılında C/C++ dilleri ile Amerikan Donanması için geliştiriliyor daha sonra açık kaynak kodlu olarak herkesin kullanımına sunuluyor. Herhangi bir program(sunucu gereksinimi olmadan) yüklemeden web tabanlı olarak çalışabilir. Linux, Windows ve MacOS işletim sistemleri ile uyumludur.   


# MariaDB

İlişkisel veritabanı sistemi olan MySQL kaynak kodundan türemiş C/C++ dilleri ile geliştirilmiş ve kullanımı ücretsiz açık kaynak kodlu olan bir veritabanı yönetim sistemidir. AlibabaCloud, Wikipedia, Microsoft, Google gibi şirketler tarafından desteklenmektedir. MariaDB kâr amacı gütmediği için bugün olduğu gibi gelecektede ücretsiz olacaktır.


# MongoDB

MongoDB Inc. tarafından C++ dili ile geliştirilmiş açık kaynak kodlu NoSQL veritabanı uygulamasıdır. Verileri JSON tipinde doküman olarak saklayan bir veritabanı türüdür. İlişkisel veritabanları'nın yetişemediği ağır ve yavaş durumlarda daha çok MongoDB kullanılır. Milyarlarca veri içerisinden istedğimiz veriyi çağırarak düzenlemeler,analizler yapabilme imkanı sunar.


# Oracle 

Oracle şirketi tarfından C/C++ dilleri ile geliştirilmiş ilişkisel veritabanı yönetim sistemidir. Kurumsal alanda kullanılan yaygın bir veritabanıdır. Büyük boyuttaki verileri barındırıp aynı anda birçok kişinin erişebilmesini sağlıyor. Tüm işletim sistemleri ile uyumlu ayrıca haftalarca kapatılmadan 24 saat boyunca çalışabilmekte.


# PostgreSQL

Açık kaynak kodlu hem ilişkisel hem de ilişkisel olmayan (JSON) sorgulamayı destekler.


# Microsoft SQL Server








# Veritabanına Yönelik Zorluklar 

* Verilerin güvenliğini sağlama
* Veritabanı'nın altyapı ve bakımı
* Ölçeklenebilirlik
* Veri hakimiyeti




