# Ödüllü Yarışma (2014)

+ N soruda(N=20~30) formu dolduran x kişisinin(kullanıcı) maaşını tahmin eden bir anket benzeri web sitesi.

+ Hedef kitlesi: kullanıcılar: programci, bilgisayar mühendisi, vb.

+ Kullanıcıya programlama ile ilgi N tane soru gösterilecek

+ Örnek Sorular:
> - Kullandığınız IDE hangisidir,
> - Çalıştığınız pozisyonun adi nedir?
> - Çalıştığınız ülke?
> - Bildiğiniz programlama dilleri / Teknolojiler?
> - Online hesaplarınız hangileri: [_Github_ , _linkedin_, _StackOverflow_, _facebook_, vb.],
> - Hangi okulda okudunuz?
> - Agile metodoljileri biliyormusunuz?
> - En sevdiğiniz dil nedir?
> - Otomatik test kullanıyormusun
> - Çalıştiğınız projede tek tuş ile deploy yapabiliyormusunuz
> - Günde kaç saat uyuyorsunuz
> - vb. **(Soruları siz seçeceksiniz)**

+ Sorular çoktan seçmeli, dropdown list, serbest metin, boolean (evet/hayır), yada sayı olabilir.

+ Soruların içerisinde kullanıcının şu anki maaşı **sorulmalı**. Maaş tahmini yaparken anketi dolduran kullanıcının maaşına **değil**, daha **önceden maaş belirtmiş kullanıcıların maaşına göre hesaplanmalı**.

+ Anket sonunda, tahmin edilen maaş ve ankete katılanlar hakkında cevaplarının olduğu bir istatistik(sonuç) sayfasi gösterilmeli.

+ Proje adaptif olmalı, yani önceki verilere göre sonuçlar kendini düzeltmeli, bir sonraki maas tahmini bir öncekinden daha isabetli olmalı

+ Kullanıcılar anonim olarak formu doldurabilmeli. (üye olmak zorunda olmamalılar)

+ Sorular N adımlı sihirbaz(wizard) türunde olmalı, bütün sorular aynı anda gösterilmemeli (J numaralı soru gösterildikten sonra, J+1'ci soru gösterilmeli) 

+ Kolayca yeni soru eklene bilmeli.

+ Görsel tasarımdan daha çok kullanıcı deneyimi ***(UX design)*** önemli.

+ Maaş tahmininde istediğiniz yöntemi kullanabilirsiniz, ***machine learning*** teknikleri yada diğer ***istatistiksel methodlar*** dahil. 

+ Böyle bir web sitesinde olmasını gerektiğini düşündüğünüz diğer bütün özelliklerde olmalı (Bu sizin kararınıza kalmış, değerlendirmede dikkate alınacak).  örneğin:Input fieldlerde autocomplate kullanılmalı mı? Google Analytics eklenmeli mi? Admin paneli olmalı mı? Anketi dolduranların listesini admin göre bilmeli mi? (not: Vakit sınırsız değildir, değerlidir ve verimli kullanılmalıdır bu yüzden; gereksiz özellik eklemek değerlendirmede eksi puan getirebilir)






Ödüller:
--------
##### 1. Olan Proje
+ Yaz staji (İstanbul icin geçerli)
+ [IntelliJ Idea Ultimate] lisansı  (500TL değerinde yaklaşik)
+ Volkan Özçeliğin [JavaScript Interview Questions] adlı kitabı


##### 2. Olan Proje
+ Yaz staji (İstanbul icin geçerli)
+ Volkan Özçeliğin [JavaScript Interview Questions] adlı kitabı

Kriterler:
----------
+ Programın çalışıp çalışmadığı
+ Kod kalitesi, kodun anlaşılabilinirliği ve dökümantasyonu
+ UX design (Kullanıcı Deneyimi)
+ Viral olarak paylaşıma uygun mu? bu konuda neler yapılmış?
+ restFull API, yada vertx'in [Eventbus]'ını kullananmak artı puan
+ Ne kadar mobil uyumlu olduğu (Mobile first mü?)
+ [AngularJs], [Ember], [Backbone], [Knockout] gibi bir javascipt frameworkü kullanmak artı puan
+ Takım halinde yapanlar için: commitlere bakılacak ve bireysel olarak değerlendirilecek
+ Git kullanımı becerileri. Değerlendirilirmede commit geçmişinizede bakılacak.  Örneğin bütün projeyi devasa bir commit ile yollarsanız eksi puan alacaksınız. Değişiklik yaptıkca commit etmeniz lazım 

Şartlar:
--------
+ **[Vertx.io] kullanmak (vertx in desteklediği şu dilleri kullanabilirsiniz: java, groovy, phyton, ruby ve javascipt)**
Vertx dışında başka bir application server yada container  (Servlet, JSP, JSF, Spring, Tomcat, NodeJs vs. ) kullanmak yasak. Web server olarak da vertx kullanılmalı. Embeded olarak başka bir java programında çalıştırılmamalı.
+ Program jurinin erişebileceği bir domainde çalışıyor olmalı.
+ Database olarak [MongoDb] kullanmak
+ Proje github da barındırılmalı ve açık bir lisansa sahip olmalı 
+ Yarişmaya katılmak için [bu repository]'i clonelamanız lazım ve projeyi clonladığınız repository de yapmaniz gerekli. Değerlendirme sırası repositorinin clonelanma tarihi ile FIFO olarak yapılacak.
+ ***28 Şubat 2014*** tarihi yarışmanın son günü.  Bu tarihe kadar yaptığınız çalışma değerlendirilecek. Proje tamamlandığında pull request yollanmalı.
+ Bireysel yada takim olarak yapabilirsiniz.
+ Kopya çekmek serbest, atıfta bulunduğunuz sürece.
+ Proje size ait istediğiniz gibi daha sonra kullanabilirsiniz.
+ Bu yarışmanın şartları ileri ki bir zamanda değişebilir. 



Faydalı Bağlantılar:
--------------------
+ [injavawetrust]: Facebook java topluluğu; takıldığınız bir yer olursa burada ki iyi insanlar size yardımcı olabilir
+ [AngularJs] : Javascipt Framework'ü
+ [Bootstrap3] : Hızlı prototiplemek için; html, css framework, mobile first destekliyor, kullanılması tavsiye edilir   
+ [IntelliJ Idea Ultimate] : Ödüllerden bir tanesi, gelmiş geçmiş en iyi IDE
+ [Vertx.io] : JVM üzerinde çalışan hızlı, polygot (birden fazla programlama dili desteği olan), node.js den esinlenmiş, application patformu 
+ [MongoDb] : nosql database 

Başka bir sorunuz var ise yarışma hakkında şura da sorabilirsiniz:
<https://www.facebook.com/groups/injavawetrust>


=======================================================================
Yarışmaya katılmak istiyorum. Yukarı da ki şartları okudum ve kabul ediyorum

ADINIZ SOYADINIZ: (DOLDURULACAK)
> eğer takım olarak çalışıyor iseniz lütfen takımda bulunan bütün takım üyelerinin isimlerini yazınız



[injavawetrust]: https://www.facebook.com/groups/injavawetrust
[Vertx.io]: Vertx.io
[AngularJs]: http://angularjs.org/
[IntelliJ Idea Ultimate]: http://www.jetbrains.com/idea/
[Bootstrap3]: http://getbootstrap.com/
[Ember]: http://emberjs.com/
[Backbone]: http://backbonejs.org/
[Knockout]: http://knockoutjs.com/
[MongoDb]: http://www.mongodb.org/
[JavaScript Interview Questions]: http://o2js.com/interview-questions
[Eventbus]: http://vertx.io/core_manual_java.html#the-event-bus 
[bu repository]: https://github.com/sumnulu/challenge

