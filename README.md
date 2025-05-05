# Video Oyun Koleksiyonu Yönetim Sistemi

> Video Oyun Koleksiyonu Yönetim Sistemi projemi Python ve GUI tasarımı için Tkinter kullanarak hazırladım.
> Bu programın temel amacı oyuncuların program üzerinden eklenmiş oyunlardan seçim yaparak oyunlarını koleksiyonlarına eklemesini sağlamak ve koleksiyonlarındaki oyunlarını puanlamasını sağlamaktadır.


-> Program açıldığında karşımıza çıkan programın görünümü bu şekildedir:

![image](https://github.com/user-attachments/assets/395fa970-e9dc-4226-ab1e-56f12a9948bd)


> Video Oyun Koleksiyonu Yönetim Sistemi -> Oyuncu Yönetimi

**-** Bu kısımdan oyuncu ekleyebiliriz. Oyuncunun adını soyadını veya oyunlarda kullandığı isimi buraya yazabiliriz.

**-** Eklenen oyuncuları da bu kısımdan görüntüleyebiliriz. Eğer eklediğimiz oyunculardan birini silmek istersek oyuncuyu seçip "Seçili Oyuncuyu Sil" butonuna basabiliriz.

![image](https://github.com/user-attachments/assets/56471cfb-027f-48dc-96e5-108ce0778fe6)


> Video Oyun Koleksiyonu Yönetim Sistemi -> Oyun Yönetimi

**-** Oyun Yönetimi kısmından istediğimiz kadar yeni oyun ekleyebiliriz. 

**-** Oyun Adını yazdıktan sonra daha önce kodlarda belirlenen kategoriler (oyun türü ve platformlar) üzerinden seçim yapıyoruz. Oyun türü ve platform seçtikten sonra oyunun çıkış yılını yazıyoruz ve oyunumuzu ekliyoruz.

**-** Bu kısmın alt tarafından oyun seçebilir / güncelleyebilir / seçili oyunu silebiliriz.

![image](https://github.com/user-attachments/assets/09ef75fe-0cee-4729-8a4f-7b5498d60637)


> Video Oyun Koleksiyonu Yönetim Sistemi -> Oyuncu Koleksiyonu

**-** Eklenilen oyunculardan birini listeden arama kısmından arayarak veya kendimiz bularak seçiyoruz. Seçtiğimiz oyuncunun koleksiyonu anında programın "Oyuncu Koleksiyonu" kısmına geliyor.

**-** Eğer bu oyuncuya daha önce bir oyun seçtirilip oyun koleksiyona eklenmişse seçildiği anda koleksiyon kısmında gözüküyor. Oyuncunun koleksiyonuna eklediği oyuna puan vermesi de Değerlendirme ve Öneri kısmında mümkündür.

**-** Oyuncu oyunu koleksiyondan çıkarmak isterse oyunu seçip koleksiyondan çıkar butonuna basabilir.

![image](https://github.com/user-attachments/assets/60f5796e-2751-4511-9ea3-66e942299f1a)


> Video Oyun Koleksiyonu Yönetim Sistemi -> Değerlendirme ve Öneri

**-** Önce oyuncu seçilir, sonrasında oyuncu koleksiyonu kısmından oyuncunun puanlamak istediği oyun seçilir ve Değerlendirme ve Öneri kısmından oyuncu oyuna vermek istediği puanı 1-10 arasında yazarak değerlendirebilir.

**-** Eğer oyuncu koleksiyona eklemek için oyun önerisi almak istiyorsa oyun önerisi al butonuna basarak oyun önerisi alabilir.


![image](https://github.com/user-attachments/assets/bf2ecac3-afbd-4125-b27d-d849a38d7e4b)

![image](https://github.com/user-attachments/assets/0f9b2bae-e887-40f0-94d0-711f77c85e9a)


> Veriler Nasıl Saklanır?

**-** Programda veriler kodun çalıştığı klasörde otomatik olarak data adında bir klasör oluşturularak data.json dosyasında saklanır. Uygulama her açıldığında bu veriler kullanılır.

> Uygulama nasıl yüklenir & nasıl çalıştırılır?

**-** Visual Studio Code uygulamasını indirin.

**-** Visual Studio Code uygulamasında eklentiler (extensions) kısmından Python yazın ve indirin.

**-** Projeyi indirdikten sonra dosyayı rardan çıkartmak istediğiniz yere çıkartın. hastane_randevu isimli dosyayı daha önceden indirmiş olduğumuz Visual Studio Code ile açın.

**-** Sağ üst kısımdan oynatma tuşuna basarak uygulamayı başlatın.
