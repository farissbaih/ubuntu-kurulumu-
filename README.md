1. Sistem dili
         Grafiksel yükleyiciye girdikten sonra, yükleyicide ve sistemde kullanmak istediğiniz dili seçin ve  ardından Continue. tıklayın.   


![p'cture1](https://github.com/user-attachments/assets/282f6868-a6ee-414b-997a-dec30ea5efdc)








2. Klavye düzeni
Uygun klavye ayarını seçin ve tuşuna basın.Continue

3. Kurulum türü
Aşağıdaki iki seçenekten birini seçebilirsiniz:

Normal kurulum normal installation: Web tarayıcısı, sistem araçları, ofis paketi, bazı oyunlar ve multimedya oynatıcılar dahil tüm programları yükler.
Minimum kurulum minimal installation: Minimum yazılım yani web tarayıcısı ve temel sistem araçlarını kurar.
Bu aşamada kurulum sırasında güncellemeleri indirme seçeneğini ve ses ve video codec paketlerine ek olarak kablosuz ağ kartı ve grafik kartı gibi bazı donanım sürücüleri olan üçüncü taraf uygulamaları yükleme seçeneğini de seçebilirsiniz. son seçeneği etkinleştirmeniz önerilir.

Seçenekleri belirlemeyi tamamladıktan sonra, Continue



4. Sabit diski bölümlere ayırın
Bu, kurulumun en önemli adımıdır ve dikkat edilmesi gerekir. Üç seçenek var:
İlk seçenek, sistemin veri kaybı olmadan önceden kurulmuş sistemin yanına kurulmasına olanak tanır;
İkinci seçenek bir seçimdir Erase disk and install Ubuntu Kaçınmanız gereken şey budur çünkü tüm sabit disk bölümlerini ve üzerlerindeki verileri siler.
Üçüncü seçenek bir seçimdir Something else Diski manuel olarak bölümlendireceğiz, bunu seçeceğiz
Ayarladıktan sonra Something else üzerine tıklıyoruz Continue.


Bölümleme adımı için sabit diskte boş alan bırakılması önerilir.





Boş alanı seçip + işaretine basıyoruz

İlk önce bir EFI bölümü oluşturuyoruz. Bu bölüm zaten mevcutsa, örneğin Windows cihazda oluşturduysa, oluşturmanıza gerek yoktur ve doğrudan bir sonraki bölüme gitmeniz gerekir.

Size alanından 1024 MB olan partition boyutunu belirliyoruz, ardından Use as kısmından partition tipini yani EFI System Partition’ı belirliyoruz ve OK’e tıklıyoruz.

Bölüm oluşturma işlemi tamamlanana kadar bekleyip ardından boş alanı tekrar seçip + işaretine tıklıyoruz

Şimdi Swap bölümünü oluşturuyoruz. Size kısmından bir önceki tabloya göre partition boyutunu belirliyoruz, ardından Use as kısmından swap alanını seçiyoruz ve OK butonuna tıklıyoruz.





Bölüm oluşturma işlemi tamamlanana kadar bekleyip ardından boş alanı tekrar seçip + işaretine tıklıyoruz

Şimdi kök bölümünü oluşturuyoruz. Boyut'tan bölüm boyutunu seçiyoruz, tercihen en az 30 GB, ardından Kullan olarak Ext4 günlük kaydı dosya sistemini seçiyoruz, ardından Bağlama noktası'ndan / işaretini seçip Tamam'a basıyoruz.


Bölüm oluşturma işlemi tamamlanana kadar bekleyip ardından boş alanı tekrar seçip + işaretine tıklıyoruz

Artık Home bölümünü oluşturuyoruz. Size bölümünden bölüm boyutunu seçiyoruz ve kalan tüm alanı ona vermek için boyutu olduğu gibi bırakacağım, ardından Use as Ext4 günlük kaydı dosya sistemini seçiyoruz, ardından Mount point'ten home/ seçeneğini seçiyoruz ve ardından Tamam'a tıklıyoruz.


Bölüm oluşturma işlemi tamamlanana kadar bekliyoruz. Bölme sonucu resimdeki gibidir.

Önyükleyicinin resimde gösterildiği gibi doğru sabit sürücüye kurulacağını doğrulayın ve ardından Şimdi Kur'a tıklayın.


Değişiklikleri doğruladıktan sonra Devam'a tıklayın.

5. Saat dilimi
Bölgeniz için saat dilimini seçin ve ardından Devam'a basın.

6. Kullanıcı bilgileri
Alanları kişisel bilgilerinizle doldurun, ardından oturuma parola olmadan otomatik erişim mi istediğinizi veya parolayı mı girmek istediğinizi seçin ve Devam'a tıklayın.

7.Ubuntu kurulum işlemi
Kurulum işleminin tamamlanmasını bekleyin.


Kurulum tamamlandıktan sonra, dağıtımı canlı oturumda test etmeye devam etmek için Teste Devam Et'e veya bilgisayarı yeniden başlatıp USB anahtarını bilgisayardan çıkarmak için Şimdi Yeniden Başlat'a tıklayın.


Adım 7: Ubuntu kullanıma hazır

