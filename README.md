# Spring_Boot_Turkish

>**Pes ettiğin an bahane aramaya başlarsın.Başarabildiğini düşündüğün an bir yolunu bulursun.** _-RDTK_
<br>

<img align="left" src="https://www.vectorlogo.zone/logos/springio/springio-icon.svg" width="28" height="28"> <img align="left" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/java/java-original.svg" alt="java" width="28" height="28">
<br>

 **_[Medium](https://medium.com/@bornthiseda)_ ve _[Youtube](https://www.youtube.com/channel/UCcL288xeuXnGSx1QFw4Wuwg/videos)_ adreslerime bu linklerden ulaşabilirsiniz.**
 <br>
 <br>
 Bir süredir Spring Boot(Java) çalışıyorum,çalışırken öğrendiklerimide paylaşıyorum.Bu repoda da Türkçe notlarımı paylaşacağım.
 <br>
 Medium ve Youtube hesaplarımda da paylaşım yapmıştım.Amacım daha çok paylaşım yapmak ve insanlarada faydamın olması.
<br>
<br>
Bir Spring projesi için [SpringInitializr](https://start.spring.io/) 'dan gerekli paketleri _Add Dependencies_ kısmından yüklüyoruz.Generate diyerek de indirmiş oluyoruz.
<br>
<br>
Artifact: jar yada war paketinin ismini belirler
<br>
Description: projenin kısa açıklamasıdır
<br>
Jar: bütün dosyalarını içinde barındıran özel bir paket yapısı
<br>
War: bir web projesi için html,javascript dosyaları gibi önyüz tarafından diğer dosyaları içinde barındırır.
<br>
<br>
Eğer ki daha sonra başka bir kütüphaneye ihtiyacımız olursa ise(ben Maven kullanıyorum) [Maven](https://mvnrepository.com/)  sitesine giriyoruz ve ihtiyacımız olan kütüphaneyi aratıyoruz.
<br>
Mesela örnek olarak benim projemde "webjar bootstrap" kütüphanesine ihtiyacım var onun için gerekli olan adımlar:
<br>
[Maven](https://mvnrepository.com/) sitesine giriyorum.
<br>
<br>
![image](https://user-images.githubusercontent.com/61595808/146385828-801adb79-cb63-4fcb-b6ef-d688210afb0b.png)
<br>
<br>
<br>
![image](https://user-images.githubusercontent.com/61595808/146385935-f379ae27-049b-4f41-ae24-9a32330f8615.png)
<br>
<br>
Hangi versiyonu seçeceğinize karar verip tıklıyorsunuz.Ben _5.1.3_ seçiyorum ve tıklıyorum.Tıkladıktan sonra bu ekran karşıma çıkıyor,ben Maven kullandığım için Maven'i seçiyorum.
<br>
<br>
![image](https://user-images.githubusercontent.com/61595808/146386255-75dc0b6e-fd36-4d81-ba4f-2f918d2d3440.png)
<br>
<br>
Kopyalandıktan sonra intelliJ'deki projemde _pom.xml_  <dependencies> ... </dependencies> arasına yapıştırıyoruz.
<br>
<br>
![image](https://user-images.githubusercontent.com/61595808/146386821-44107cd5-0c29-4dc7-9166-e5b6ca650ccd.png)
<br>
<br>
Ben daha önce eklediğim için hata vermiyor.Ama var olmasaydı kırmızı olacaktı örnek olarak şu anda ihtiyacım olmayan kütüphaneyi _pom.xml_ e yapıştırdım.
<br>
<br>
![image](https://user-images.githubusercontent.com/61595808/146387145-c1306e54-f622-41b3-9492-e36099e9afbf.png)
<br>
<br>
Bu şekilde görünecek idi.
<br>
<br>
Bundan sonraki adımımız
<br>
<br>
_pom.xml_ sağ tıkladıktan sonra
<br>
<br>
![image](https://user-images.githubusercontent.com/61595808/146387455-807cdbab-8500-4c26-b607-f81196798ac0.png)
<br>
<br>
Bu ekran karşımıza geliyor burada Maven'e tıklıyoruz.
<br>
<br>
![image](https://user-images.githubusercontent.com/61595808/146387570-a1f0bba1-a385-4dfe-a7d7-0d11ab03d00e.png)
<br>
<br>
![image](https://user-images.githubusercontent.com/61595808/146387661-ad199b2a-57cd-430b-abdc-cfe2403afd0b.png)
<br>
<br>
_Reload project_ diyoruz.
<br>
<br>
![image](https://user-images.githubusercontent.com/61595808/146387936-220c1ac2-6954-47d5-96f4-a5d65ab88896.png)
<br>
<br>
Ve yüklenme tamamlanıyor.
<br>
<br>
![image](https://user-images.githubusercontent.com/61595808/146388019-6392148a-39d1-4902-89d6-384a653638f3.png)
<br>
<br>
<br>
Medium'da paylaşmış olduğum örneklerim :
<br>
SpringFramework Thymeleaf Bootstrap Student Crud Example  - https://medium.com/@bornthiseda/springframework-thymeleaf-mysql-bootstrap-student-crud-example-11bc845a7184
<br>
Spring Boot Java MVC Thymeleaf ile Öğrenci Kaydetme Örneği   -https://medium.com/@bornthiseda/spring-boot-java-thymeleaf-ile-%C3%B6%C4%9Frenci-kaydetme-%C3%B6rne%C4%9Fi-edaf316dfa81?p=edaf316dfa81
<br>
<br>
<br>
<br>
**Çalışırken yararlandığım Kaynaklar**
<br>
https://spring.io/guides/gs/spring-boot/
<br>
https://www.tutorialspoint.com/spring_boot/spring_boot_introduction.htm
<br>
https://thecodeprogram.com/java-springboot-nedir-
<br>
https://kodedu.com/2014/09/jpa-2-1-entity-graph/
<br>
https://blog.burakkutbay.com/spring-boot-dersleri.html/
<br>
https://mrpehlivan.medium.com/springboot-ile-proje-olu%C5%9Fturma-2c16ce806a4f
<br>
https://medium.com/kodgemisi/spring-boot-ile-%C3%B6rnek-web-uygulamas%C4%B1-914c94c9099f
<br>
https://medium.com/kodluyoruz/spring-boot-kurulumu-ve-i%CC%87lk-proje-70c23b1dbe0d
<br>
https://medium.com/@springbootturkiye
<br>
https://www.youtube.com/watch?v=5Bj1ZEvsTWI
<br>
https://www.youtube.com/user/Kindson01
<br>
https://www.youtube.com/channel/UC1Be9fnFTlcsUlejgfqag0g
<br>
https://www.youtube.com/user/codejavanet
<br>

