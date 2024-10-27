1. Sistem dili
 Grafiksel yükleyiciye girdikten sonra, yükleyicide ve sistemde kullanmak istediğiniz dili seçin ve   ardından Continue. tıklayın.   

![1](https://github.com/user-attachments/assets/e959fe7b-f4d8-4417-96f5-4ad29bfb6233)


2. Klavye düzeni
Uygun klavye ayarını seçin ve tuşuna basın.Continue

![2](https://github.com/user-attachments/assets/57777a65-6c43-4181-8ab6-4181b1aa98bf)

3. Kurulum türü
Aşağıdaki iki seçenekten birini seçebilirsiniz:

Normal kurulum normal installation: Web tarayıcısı, sistem araçları, ofis paketi, bazı oyunlar ve multimedya oynatıcılar dahil tüm programları yükler.
Minimum kurulum minimal installation: Minimum yazılım yani web tarayıcısı ve temel sistem araçlarını kurar.
Bu aşamada kurulum sırasında güncellemeleri indirme seçeneğini ve ses ve video codec paketlerine ek olarak kablosuz ağ kartı ve grafik kartı gibi bazı donanım sürücüleri olan üçüncü taraf uygulamaları yükleme seçeneğini de seçebilirsiniz. son seçeneği etkinleştirmeniz önerilir.

Seçenekleri belirlemeyi tamamladıktan sonra, Continue

![3](https://github.com/user-attachments/assets/845662b1-f2bd-4075-91f6-1a2d408b7843)

4. Sabit diski bölümlere ayırın
Bu, kurulumun en önemli adımıdır ve dikkat edilmesi gerekir. Üç seçenek var:
İlk seçenek, sistemin veri kaybı olmadan önceden kurulmuş sistemin yanına kurulmasına olanak tanır;
İkinci seçenek bir seçimdir Erase disk and install Ubuntu Kaçınmanız gereken şey budur çünkü tüm sabit disk bölümlerini ve üzerlerindeki verileri siler.
Üçüncü seçenek bir seçimdir Something else Diski manuel olarak bölümlendireceğiz, bunu seçeceğiz
Ayarladıktan sonra Something else üzerine tıklıyoruz Continue.

![4](https://github.com/user-attachments/assets/481f0ce3-4839-4613-9f49-81ca6d2e8ef4)

Boş alanı seçip + işaretine basıyoruz
![5](https://github.com/user-attachments/assets/4c0dbc14-3258-4498-91d3-2f8a21de3302)

İlk önce bir EFI bölümü oluşturuyoruz. Bu bölüm zaten mevcutsa, örneğin Windows cihazda oluşturduysa, oluşturmanıza gerek yoktur ve doğrudan bir sonraki bölüme gitmeniz gerekir.

Size alanından 1024 MB olan partition boyutunu belirliyoruz, ardından Use as kısmından partition tipini yani EFI System Partition’ı belirliyoruz ve OK’e tıklıyoruz.

![6](https://github.com/user-attachments/assets/58a01896-ddc8-457e-8a23-9ddf7017b9fd)

Bölüm oluşturma işlemi tamamlanana kadar bekleyip ardından boş alanı tekrar seçip + işaretine tıklıyoruz

![7](https://github.com/user-attachments/assets/35481068-4900-4d73-8cb2-e7f47375e490)

Şimdi Swap bölümünü oluşturuyoruz. Size kısmından bir önceki tabloya göre partition boyutunu belirliyoruz, ardından Use as kısmından swap alanını seçiyoruz ve OK butonuna tıklıyoruz.

![8](https://github.com/user-attachments/assets/44c6688c-7a61-4b98-b3be-22c311d30b80)

Bölüm oluşturma işlemi tamamlanana kadar bekleyip ardından boş alanı tekrar seçip + işaretine tıklıyoruz

![9](https://github.com/user-attachments/assets/2a2c17e7-2caf-4038-841f-ec6f637eb607)

Şimdi kök bölümünü oluşturuyoruz. Boyut'tan bölüm boyutunu seçiyoruz, tercihen en az 30 GB, ardından Kullan olarak Ext4 günlük kaydı dosya sistemini seçiyoruz, ardından Bağlama noktası'ndan / işaretini seçip Tamam'a basıyoruz.

![10](https://github.com/user-attachments/assets/b03f9f7c-7eec-4219-a543-1c357256d9b5)

Bölüm oluşturma işlemi tamamlanana kadar bekleyip ardından boş alanı tekrar seçip + işaretine tıklıyoruz

![11](https://github.com/user-attachments/assets/41963d10-8751-48eb-b389-c915973bf000)

Artık Home bölümünü oluşturuyoruz. Size bölümünden bölüm boyutunu seçiyoruz ve kalan tüm alanı ona vermek için boyutu olduğu gibi bırakacağım, ardından Use as Ext4 günlük kaydı dosya sistemini seçiyoruz, ardından Mount point'ten home/ seçeneğini seçiyoruz ve ardından Tamam'a tıklıyoruz.

![12](https://github.com/user-attachments/assets/863d5151-cc88-4eb2-bc82-54d93c694ddc)

Bölüm oluşturma işlemi tamamlanana kadar bekliyoruz. Bölme sonucu resimdeki gibidir.

![13](https://github.com/user-attachments/assets/a23fa4d3-8469-4957-9642-67b060865e42)

Önyükleyicinin resimde gösterildiği gibi doğru sabit sürücüye kurulacağını doğrulayın ve ardından Şimdi Kur'a tıklayın.

![14](https://github.com/user-attachments/assets/596917e9-1e4b-4c14-bd33-bf8c1f0bee5a)

Değişiklikleri doğruladıktan sonra Devam'a tıklayın.

![15](https://github.com/user-attachments/assets/218c917d-59f1-45e7-9082-8c64bf080dcc)

5. Saat dilimi
Bölgeniz için saat dilimini seçin ve ardından Devam'a basın.

![16](https://github.com/user-attachments/assets/324bba13-3923-402e-8fe7-8ef207dc954e)

6. Kullanıcı bilgileri
Alanları kişisel bilgilerinizle doldurun, ardından oturuma parola olmadan otomatik erişim mi istediğinizi veya parolayı mı girmek istediğinizi seçin ve Devam'a tıklayın.

![17](https://github.com/user-attachments/assets/b8458e19-ab83-45b0-98c8-4b45d1d8284d)

7.Ubuntu kurulum işlemi
Kurulum işleminin tamamlanmasını bekleyin.

![18](https://github.com/user-attachments/assets/e4777c85-f839-43b0-8665-1d5e1b4c7685)

Kurulum tamamlandıktan sonra, dağıtımı canlı oturumda test etmeye devam etmek için Teste Devam Et'e veya bilgisayarı yeniden başlatıp USB anahtarını bilgisayardan çıkarmak için Şimdi Yeniden Başlat'a tıklayın.

![19](https://github.com/user-attachments/assets/18cc444c-0127-4eba-a29a-bc9dd874f588)

Adım 7: Ubuntu kullanıma hazır

![20](https://github.com/user-attachments/assets/1d9b1ee3-6d20-465c-add5-d781b6446493)
