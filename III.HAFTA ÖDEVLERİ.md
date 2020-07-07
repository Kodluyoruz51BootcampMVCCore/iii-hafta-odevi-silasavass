### III.HAFTA ÖDEVLERİ 

#####    1.Task vs process- task vs Thread vs .. ve c # task vs thread vs .. kıyaslamalarını ve görev haricinde diğer bilgiler nelerdir araştırınız. 

## Görev Nedir?

'.NET' çerçeve iş parçacığı sağlar. Görev sınıfı, görevler oluşturmanızı ve diğer eşzamansız olarak çalıştırmanızı sağlar tanır.

Görev, gerekli olan işler temsil eden bir nesnedir. Görev, işin tamamlanıp tamamlanmadığını ve işlemin bir sonuç döndürürse, boyut sonucu verir. Görev sınıfı, bir değer döndürmeyen ve genellikle zaman uyumsuz olarak tasarlanmıştır tek bir işlemi temsil eder. Görev nesneleri, ilk olarak .NET Framework 4 'te tanıtılan görev tabanlı zaman uyumsuz düzenin merkezi bileşenlerinden oluşur. Bir Görev nesnesi tarafından kullanılır iş, genellikle ana uygulama iş parçacığı üzerinde zaman uyumsuz olarak değil, bir iş parçacığı havuzu iş parçacığı zaman uyumsuz olarak yürütülebildiğinden, bir durum kontrol etmek için, Durumda ve IsCanceled, IsCompletedve IsFaulted bunun de kullanılabilir. En yaygın olarak, bir lambda ifadesi kullanılır.



## Konu Nedir?

'.NET' Framework, sistemde thread ile ilişkili sınıflara sahiptir.Threading alanı. Bir Konu küçük bir çalıştırılabilir talimatlar kümesidir.



### Task'a Neden İhtiyaç Duyulur?

Paralel olarak bir şey yürütmek için de kullanılabilir. 'Async' ve 'await' anahtar kelimelerini kullanarak bir işte Asenkron uygulama kullanıyor.

### Thread'e Neden İhtiyaç Duyulur ?

Uygulama sırasında aynı anda birkaç çalışma için gerekli gerekli zaman geldiğinde.

### Aralarındaki Fark

1. Thread sınıfı, Windows'ta bir 'thread' oluşturmak ve hazırlamak için kullanılır. API olan 'Görev Paralel Kütüphanesi (Görev Paralel Kitaplığı'nın) bir arada.
2. Görev bir sonuç döndürebilir. Bir iş parçacığı sonucu döndürmek için hemen bir mekanizma yoktur.
3. Görev, iptal belirteçleri iptal iptal içindir. Ancak Konu değil.
4. Bir görev'in aynı anda birden çok işlemi olabilir. Thread'lerin aynı anda sadece bir görev olabilir.
5. 'Async' ve 'await' anahtar kelimelerini kullanarak Asenkron'i kullanabilirsiniz uygulayabiliriz.
6. Yeni bir Konu () Konu havuzu ile uğraşmazken; Görev, iş parçacığı havuzunu farklı işler için gerekli. Görev, Thread'den daha üst düzey bir kavramdır.



## Project Nedir?

Projeler genellikle yeni bir yapılandırma tasarımı gibi belirli veya bir kerelik çıktılar vermek için birkaç aşamada ilerler. Projeler, basit olandan (yeni bir uzay roketi inşa etmek) kadar, ancak bazı bittikten sonra projeyi tekrar etmeden değişebilir.

## Prosses Nedir?

Bir işlem sonucu tekrarlanabilir bir şekilde gerçekleştirir. İyi süreç yönetimi, süreç, zamanında, verimsizliği, verimsizliği veya üçünü de sürekli olarak iyileştirme fırsatlarından en iyi şekilde yararlanmanızı içerir. Bir süreçteki koşullu mantık, farklı süreçlerin sonuçlanması, işlemin akışını düzeltmeiye uğratmadan sorunsuz bir şekilde entegre olabilmektedir. Bir dizi denetim gösterilebilir. Diğer kullanıcılar arasında, onun seferinde tüm üslerin uygun şekilde kapsama alınmasını sağlamak için bir müşteri kullanarak çalışan katılımı sayılabilir.

### Görev, Proje Ve Prosses Arasındaki Bağlantı

Görevler, projeler ve süreçler birbiriyle ilişkilidir. Parametreler, bir proje koşulları. her görevin, tamamlanma tarihine uyulması için bir tarih belirlemesi. Bir süreç aynı zamanda bir dizi görev olarak da görülebilir. İşte birlikte, bazı görevlerin yalnızca başlangıçtan sonra bilinebileceği bir projeyle ilgili, bir süreçteki olası görevlerin tümü önceden tanımlanır.

Ayrıca, “her zaman hedefleri belgeyi, sonra paydaşları arasında, ilk proje tanım toplantısını yapın.” Vb.). bir var belirli tanımlamak için projeyi işlemi karmaşıktır ve birkaç kişi içindir, özellikle yinelenen aktivite veya olay işleme için doğru süreç. Görev dizisi tanımı bir kez (proje bölümü) yapılır ve bu şekilde tanımlanır.



#### 2.Extension Nedir?

Genişletme metodları bir tip (integer veya string vb.) üzerinde herhangi bir değişiklik yapmadan o tipi kolayca genişletmemize olanak sağlayan bir yapıdır. Daha basit olarak anlatacak olursak tanımladığımız bu Genişletme Metodları özünde bildiğimiz static metodlardır. .Net Framework 3.5 ile kullanıma gelmişlerdir, .Net Frameworkte içerisinde bulunan ve tanımlamış olduğumuz her tip için uygulanabilmektedir.

Nasıl Genişleme metodu oluşturulur?

Genişletme metodlarını basit bir şekilde tanımlayacak olursak yapmamız gereken adımlar aşağıdaki gibi olacaktır.

1. Public static bir sınıf oluşturulur.
2. Yapmak istediğiniz işlemleri gerçekleştirecek metod yazılır.
3. Fonksiyon genişleme metoduna dönüştürülür.



##### 3.SQLite, bunu doğru şekilde (en güncel yol ile) nasıl kullanmalıyız?

https://stackoverflow.com/questions/59284020/how-do-i-properly-use-my-sqlite-db-in-my-asp-net [-çekirdek-3-1-mVC uygulama kullanılarak](https://stackoverflow.com/questions/59284020/how-do-i-properly-use-my-sqlite-db-in-my-asp-net-core-3-1-mvc-application-using)

