## postalaa.exe v.1.0.1 Beta (TÜRKÇE)
Program hakkında kısa açıklama: 

Çok sayıdaki dosyaları çok sayıdaki alıcılara (her bir maile alıcının kendisi ile ilgili olan dosya otomatik ataçlanır.) tek defada iletebilmek için tasarlanmıştır. Gönderilecek dosyaların bulunduğu klasör ile program veri tabanındaki alıcılar isim veya farklı bir ID no ile otomatik eşleştirilir ve her dosya ilgili alıcısına gönderilir. Kullanım şekline bir örnek verecek olursak: Mükelleflerinin onaylanmış beyannamelerini ve bunlara ait tahakkuk fişlerini bilgisayarındaki klasöre topluca indirmiş olan postalaa.exe kullanıcısı, bu dosyaların ilgilisi olan mükelleflerinin bilgilerini program veri tabanına(...\postalaa\2-Sys\P.xlsx dosyası) kaydetmişse,  LİSTELE > Mail Konu ve Mesaj Gir(Tüm alıcılara hitaben ortak bir mesaj) > HAZIRLA  > GÖNDER butonlarına tıklayarak tüm dosyaları sahiplerine iletmiş olacaktır. 

KURULUM : 
postalaa.exe dosyasını masaüstünde çalıştırmanız yeterlidir. Oluşacak Veri tabanınıza (P.xlsx) alıcılarınızın bilgilerini girmeniz gereklidir. Kurulum sırasında outlook kişilerinizin program veritabanına otomatik aktarılması mümkündür. Kullanım kılavuzu için YARDIM butonu tıklanmalıdır. Program GNU lisans ile dağıtılmaktadır. Ücretsizdir. Kullanıcılardan görüş, eleştiri ve eklenti isteği göndermeleri beklenmektedir.

ÖNEMLİ !!! : Kurulum sırasında "Unexpected Error" alınıyorsa bilgisayarınızda VB6 uygulamalarının çalışabilmesi için gerekli olan "comctl32.ocx" dosyasının register edilmesi gerekir. Bunun için aşağıdaki adımları uygulayın.

                            32 Bit Windows işletim sistemi için;
[1.Adım] Orijinal dosyayı Microsoft sitesinden indirin ve C:\Windows\System32 içerisine kopyalayın                           
[2.Adım] Başlat > Çalıştır > CMD > Ctrl+Shift+Enter ile yönetici olarak komut istemini çalıştırın.      
[3.Adım] regsvr32 comctl32.ocx yazıp enter girin.

                            64 Bit Windows işletim sistemi için;
[1.Adım] Orijinal dosyayı Microsoft sitesinden indirin ve C:\Windows\SysWOW64 içerisine kopyalayın                           
[2.Adım] Başlat > Çalıştır > CMD > Ctrl+Shift+Enter ile yönetici olarak komut istemini çalıştırın.                            
[3.Adım] C:\Windows\SysWOW64\regsvr32 C:\Windows\SysWOW64\comctl32.ocx yazıp enter girin.


Sistem Gereksinimleri :  WINDOWS xp/2000/ME/Vista/7/8/10 - MICROSOFT EXCEL

## postalaa.exe v.1.0.1 Beta (ENGLISH) 

Brief description of the program: 

It is designed to deliver a large number of files to multiple recipients at once. With the folder containing the files to be sent, the recipients in the program database are automatically paired with the name or a different ID number and each file is sent to the corresponding recipient. To give an example of how to use: Postalaa.exe user, who has downloaded certified declarations of their taxpayers and their accrual receipts to the folder on his computer, informs the taxpayers of these files to the program database (... \ postalaa \ 2-Sys \ P.xlsx file) If you have saved LIST> Mail Subject and Send Message (add a common message addressed to all recipients)> PREPARE> SEND button will be forwarded to the owners of all the files.

INSTALLATION: 
Just run the postalaa.exe file on the desktop. It is necessary to enter your recipients' information into your database (P.xlsx). It is possible to automatically transfer your Outlook contacts to the program database during setup. Please click HELP button for user manual. The program is distributed GNU licence. Used free of charge. Users are expected to submit comments, criticism and add-on requests.

System requirements : WINDOWS xp/2000/ME/Vista/7/8/10 - MICROSOFT EXCEL

