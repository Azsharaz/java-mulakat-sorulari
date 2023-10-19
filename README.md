# java-mulakat-sorulari

Mülakatlarda En Çok Çıkan 40 Java Sorusu

# 1. Java nedir?
JDK, JRE ve JVM arasındaki fark nedir? Java, Sun Microsystems tarafından geliştirilen yüksek seviyeli, nesne yönelimli bir programlama dilidir. Java, Java Sanal Makinesi (JVM) ile çalışabilen herhangi bir platformda çalışabilme özelliğiyle tanınır. 
# 2. JDK, JRE ve JVM arasındaki fark nedir? 
Java kodlarının herhangi bir platformda çalışabilme özelliği, Java Sanal Makinesi (JVM) ile birlikte gelir.
JDK (Java Geliştirme Kiti), Java uygulama geliştirmek için kullanılır. 
JRE (Java Çalışma Ortamı), Java uygulamalarını çalıştırmak için kullanılır. 
JVM (Java Sanal Makine), Java bytecode'larını yürütür. 
# 3. Java'nın temel özelliklerini açıklayın. 
Java; platformdan bağımsız, object-oriented, güvenli, multi-thread ve yüksek performanslıdır. 
# 4. Soyut classlar (abstract classes) ile arayüzler (interfaces) arasındaki farklar nelerdir? 
Abstrac classların constructorları, alanları (fields) ve methodları olabilir; interfacelerin ise sadece method signatureları(imzaları) vardır. Bir class yalnızca bir abstract class'ı extendleyebilirken birden fazla interface'i kullanabilir. 
# 5. Java, platformdan bağımsız bir dil olmayı nasıl başarır?
Java, kaynak kodunu bytecode'a derleyerek platforma özgü JVM tarafından yürütülmesini sağlayarak platformdan bağımsız çalışır.
# 6.  'final' anahtar kelimesini(keyword) açıklayın. 
 'final' anahtar kelimesi, variableları, methodları veya classları değiştirilemez olarak belirtmek için kullanılır. Bir 'final' değişken yeniden atanamaz, bir 'final' method override edilemez ve bir 'final' class extend edilemez. 
# 7.  'equals()' ve '==' arasındaki fark nedir?
'==' nesne referanslarını karşılaştırırken, 'equals()' nesnelerin içeriğini (değerlerini) karşılaştırır. 
# 8.  Constructor nedir ve neden kullanılır? 
 Constructor, objeleri yaratmak için kullanılan özel bir methoddur. Bir obje oluşturulduğunda çağrılır ve objenin kullanılmasını sağlar. 
# 9. “this' anahtar kelimesi nedir?
 'this', o class içinde olan nesneyi ifade eder. Genellikle aynı isme sahip örnek değişkenlerini ve method parametrelerini ayırt etmek için kullanılır.

# 10.   Java'da Method Overloading ve Method Overriding nedir? 
Method Overloading, aynı class'taki birden fazla methodun aynı adı taşıdığı ancak farklı parametrelere sahip olduğu durumdur. Method Overriding; parent class'ta var olan bir methodun child class'ta spesifik hale getirilmesi için kullanılır.
# 11.  Static keywordü nedir ve ne zaman kullanılır? 
Static, bir instance'a değil class'a aittir. Class adı kullanılarak çağrılabilir ve genellikle instance ile alakalı veri gerektirmeyen methodlar için kullanılır.
# 12.  'super' keywordü nedir? 
'super', method overriding bağlamında parent class'ın constructor'ını çağırmak veya parent class'ın methoduna ya da değişkenine(variable) erişebilmek için kullanılır.
# 13.  Java'da Exception'ı yakalamak için kullanılan 'try-catch-finally' bloğunu    açıklayın. 
'try', exception fırlatabilecek kodu çevrelemek için kullanılır, 'catch', exceptionları düzeltmek/yakalamak kullanılır ve 'finally', bir exception oluşsa da oluşmasa da her zaman çalışacak kodu belirtmek için kullanılır. 
# 14.  Checked ve Unchecked Exceptionlar arasındaki fark nedir? 
 Checked exceptionlar derleme zamanında(compile-time) kontrol edilir ve ya yakalanmalıdır(try-catch) ya da method signature'da 'throws' kullanılarak bildirilmelidir. Unchecked (RuntimeExceptions), derleme zamanında kontrol edilmez. 
# 15.  'NullPointerException'ı tanımlayın ve nasıl handle edileceği hakkında bilgi verin.   
 'NullPointerException', null bir nesnenin methodlarına veya instancelarına erişmeye çalışıldığında meydana gelir. Bunun önlenmesi için, bu nesnelere erişmeden/çağırmadan önce nesne referanslarınn null olmadığından emin olun. 
# 16.   Exception engellemede 'finally' bloğunun amacı nedir? 
 'finally' bloğu, exception oluşup oluşmadığına bakılmaksızın, dosyaları kapatma gibi temel temizlik kodlarının çalıştığını sağlamak için kullanılır. 
# 17.  Java'da Collections Framework'ü nedir ve neden önemlidir? 
 Collections, nesnelerin koleksiyonlarıyla çalışmak için kullanılan bir dizi class ve interface sağlar. Java uygulamalarında verilerin verimli bir şekilde işlenmesi ve depolanması için önemlidir. 
# 18.  ArrayList ve LinkedList arasındaki farkı açıklayın.
 ArrayList, hızlı ve rasgele erişime izin veren dinamik bir List'tir, LinkedList ise sık sık ekleme ve silme işlemleri için daha uygundur ve insertion ordera göre sıralanır.
# 19.  Java'da 'hashCode()' methodu ne için kullanılır?
 'hashCode()', bir nesnenin hash kodunu hesaplamak için kullanılır ve genellikle HashMap ve HashSet gibi veri yapılarında verilerin verimli saklanması ve kullanılması için kullanılır.  
# 20.   Java, Multithread'i nasıl yapar ve Multithread ile ilgili olası sorunlar nelerdir?  
Java, multithreadleri 'Thread' classı ve 'Runnable' interface'i aracılığıyla destekler. Olası sorunlar arasında erişim çakışması (race conditions), kilitlenmeler (deadlocks) ve iş parçacığı müdahalesi (thread interference) bulunur ve bu sorunlar senkronizasyon kullanılarak çözülmelidir.
# 21.  Java'da senkronizasyon nedir ve nasıl sağlanır? 
 Senkronizasyon, yalnızca bir thread'in bir kod bloğuna veya bir methodae aynı anda erişmesini sağlamak için kullanılır. Bu, 'synchronized' anahtar kelimesi kullanılarak veya senkronize bloklar kullanılarak sağlanabilir. 
# 22.  Java'da 'volatile' anahtar kelimesini açıklayın. 
 “volatile” anahtar kelimesi, değişkenin sakladığı değerin Thread'ler tarafından okunmaya çalışıldığında ve degisken uzerinde bir değişiklik olduguna diğer threadler tarafindan görünmesini/visibility garanti eder. 
# 23.  Java'da 'thread-safe' kavramı nedir ve bir class nasıl thread-safe yapılır? 
Thread-safe bir class metodlarının birden fazla thread tarafından kullanılmasında veri bozulmasına veya tutarsızlıklara neden olmadan güvenli bir şekilde gerçekleştirildiğinden emin olur. Bir class'ı thread-safe yapmak için senkronizasyon, kilit(lock)veya eşzamanlı veri yapıları(concurrent data structure) kullanılabilir.
# 24.  Java'da thread senkronizasyonu için kullanılan 'wait' ve 'notify' methodlarını açıklayın. 
 'wait', bir threadi, aynı obje üzerinde başka bir thread'in 'notify' veya 'notifyAll' methodu çağırılana dek kadar bekletmek için kullanılır, bekleyen thread(ler) uyandırılır. 
# 25.  Java Bellek Modeli (Java Memory Model - JMM) nedir ve multithread ile nasıl ilişkilidir? 
JMM, threadlerin bellekle etkileşimini ve değişkenlere ilişkin değişikliklerin diğer threadlere görünür olduğunu tanımlar. Bu, JVM'nin bellek görünürlülüğüne uyum sağlamasını sağlar. 
# 26.  Java'da 'garbage collector' nedir ve nasıl çalışır?
 Garbage collector (çöp toplama),  kullanılmayan, işgal edilen belleği otomatik olarak tanımlama ve temizleme işlemidir. Generational, işaretleme-temizleme ve G1 gibi farklı çöp toplama algoritmaları kullanır. 
# 27.  Java'da finalize() nedir? 
Silinecek dataları, Garbage Collector gelmeden önce, imha edilecek hale getirmek için Java tarafından kullanılan bir metottur.
# 28.  Java'da Assert statement'ının amacı nedir? 
Assertion, geliştiricilerin hataları gidermek ve düzeltmek için programlarındaki varsayımları test etmelerini sağlar.  Bundan ötürü assert kelimesini kullanıp test aşamasında sadece önlenebilecek hataları bulmakta kullanılır. Assertion mekanizmasi basit bir şekilde çalışır. İlgili assertion şartı true olmazsa exception(error) fırlatır. (AssertionError) Eğer true dönecekse her şey yolunda olacak ve kod akışı devam edecektir. 

# 29.  Java'da 'enum' türünü ve avantajlarını açıklayın. 
'Enum', bir dizi sabit değeri tanımlayan özel bir veri türüdür. Type güvenliği sağlar, okunabilirliği artırır ve switch ifadelerinde kullanılabilir. 
-> enum Day { SUNDAY, MONDAY, TUESDAY, WEDNESDAY, THURSDAY, FRIDAY, SATURDAY } 
# 30.  'autoboxing' ve 'unboxing' özelliği nedir?
Autoboxing, data type'ı primitive olanın wrapper class'a otomatik olarak dönüştürülmesidir ve unboxing ise tersi işlemdir. Örneğin, 'int'i 'Integer''a dönüştürmek veya tam tersi. 
# 31.  Java'da "annotations" (işaretlemeler) nedir ve nasıl kullanılırlar?
Annotations, kod hakkında metadata sağlar ve genellikle classlara, methodlara veya değişkenlere bilgi eklemek için kullanılır. Genellikle yapılandırma, belgeleme ve kod üretimi için kullanılırlar. Örneğin JUnit ile unit test yazarken methodun başına “@Test” yazarak o metodu test metodu haline getirebiliriz. Detaylı bilgi için buradan faydalanabilirsiniz (CTRL+sol tık)
# 32.   Java'da kaynak yönetimi için 'try-with-resources' ifadesini açıklayın. 
'try-with-resources', dosyalar, soketler veya veritabanı bağlantıları gibi kaynakları artık gerekli olmadığında otomatik olarak kapatmak için kullanılır. Kaynak yönetimini basitleştirir ve kaynak sızıntılarını önler. 
# 33.  Java'da fonksiyonel programlama nasıldır ve Lambda nedir?
 Java, fonksiyonel programlamayı Lambda expressions(ifadeler) aracılığıyla destekler. Lambda expressions, işlevsel programlamayı kolaylaştırır ve geliştirmeyi çok basitleştirir. Koleksiyondan verilerin yinelenmesine, filtrelenmesine ve çıkarılmasına yardımcı olur.  Daha öz ve anlamlı kod yazmak için kullanılırlar. 
# 34.  'Stream' nedir ve veri işleme için nasıl kullanılır? 
'Stream' API,  pek çok datanın fonksiyonel bir şekilde işlenebilmesini sağlar. Verilerin istenen şekilde işlenebilmesi için filtering, mapping, reducing ve collecting gibi methodlar sunar.  
# 35.  Java'da 'Optional' class'ını ve amacını açıklayın.
 'Optional', ya bir değeri taşıyabilen ya da boş olabilen bir container class'tır. Bu, NullPointerException'ları önlemek ve bir değerin var olup olmadığını göstermek için kullanılır. 
# 36.  'StringBuilder' class'ı nedir ve 'String'den farkı nedir?
 'StringBuilder', değiştirilebilir iken 'String' değiştirilemezdir. 'StringBuilder', yeni nesneler oluşturmadan verimli bir şekilde String manipulationları kullanabilmeyi sağlar. 
# 37.   Java'da serialization nedir ve nasıl uygulanır? 
Seri hale getirme (serialization), bir nesneyi verilerin taşınabilirliği veya kalıcı depolama amacıyla stream'e dönüştürme işlemidir. Seri hale getirme işlemi, bir nesneyi ikincil depolama ortamlarına (örneğin diske) kaydetmek, ağ üzerinden iletmek veya nesneyi farklı platformlar arasında paylaşmak için kullanılır. 
# 38.  Java'da 'Reflection' API'ını açıklayın. 
'Reflection' API'ı, RunTime'da classları, methodları, fieldları ve objeleri incelemenize ve işlemenize olanak tanır. Genellikle dinamik kod üretimi ve test için kullanılır. 
# 39.  'inner class' ile bir 'nested class' arasındaki fark nedir? 
İç içe class (inner class), başka bir class içinde tanımlanan statik olmayan bir classken, gömülü class (nested class), başka bir class içinde tanımlanan herhangi bir classtır. İç içe classlar, kapsayıcı classın üyelerine(variable, method) erişim sağlar. 
# 40.  Java'da 'Executor' Framework'ü nedir ve thread yönetimini nasıl kolaylaştırır?
'Executor', threadleri yönetmek için daha yüksek bir düzey soyutlama(abstraction) sağlar. Özellikle multithread programları geliştirirken, 'executors' thread yönetimi için önemli bir araçtır. 


