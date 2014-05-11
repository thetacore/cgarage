#Bilgi Edinme Komutları

###pwd
Bulunulan dizinin ismini verir.

###hostname
Makinenin ismini verir.

###whoami
Sisteme giriş yaparken yazılan kullanıcı adını verir.

###id [kullanıcı_ismi]
Kullanıcının kullanıcı kimliği, birincil grup kimliği ve üyesi olduğu grupları gösterir.

###date
Sistem tarihibi göstermek ya da değiştirmek için kullanılır. Tarihin yerele özgü gösterim ile basılması istenirse 

`date +%c`

şeklinde kullanılması gerekir.

###time
Belirli bir komutun işlemini bitirmesinin ne kadar süre tuttuğunu gösterir. Örneğin, bir dizinin listelenme süresi time ls ile öğrenilebilir.

###who
O an sistemde bulunan kullanıcıların; kulanıcı isimlerini, hangi uçbirimlerde çalıştıklarını ve sisteme  giriş tarih ve saatlerini gösterir.

###finger [kullanıcı_ismi]
Belli bir kullanıcı hakkında bilgi verir.

###last
Sisteme en son giriş yapmış kullanıcıların bugünden geriye doğru listesi.

###history
Kabuğa en son girilen komutların listesi

###uptime
Makinenin ne kadar süredir açık olduğu bilgisini verir.

###ps
Kullanıcının kullandığı uçbirimde çalıştırmakta olduğu komutların ve süreçlerin listesi.

###ps -ax
Sistemin açılışından beri çalışmakta olan bütün süreçlerin listesi.

###top
Temel sistem durumu, çalışmakta olan süreçler benzeri bilgiler...

###uname -a
Sistem hakkında çekirdek sürümünü, işlemci türü gibi bilgileri basar.

###free
Bellek kullanımını gösterir.

###df -h
Bağlı sabit disk bölümlerinin doluluk oranlarını gösterir.

###du -sk [dizin]
Belirtilen *dizin* in (belirtilmezse, bulunulan dizin) içeriğinin diskte kapladığı alanın KB cinsinden boyutunu verir.

###cat /proc/interrupts
Çekirdek tarafından tanımlanmış olan sistem kesmelerinin listesi.

###cat /proc/version
Linux çekirdeğinin sürüm bilgileri.

###cat /proc/filesystems
Çekirdekte tanımlı kullanılabilecek dosya sistemlerinin listesi.

###cat /etc/printcap
Yazıcıların düzeni.

###lsmod
Yüklü çekirdek modüllerinin listesi.

###set, declare, export
Üçü de kabukta tanımlı ortam değişkenlerinin listesini verir. Tümünü sadece declare verir.

###echo $PATH
PATH ortam değişkeninin değerini gösterir. PATH kullanıcı tarafından çalıştırılabilecek yazılımların aranacakları yerleri kabuğa bildirmek için kullanılır.

###dmesg
Sistem açılışından itibaren çekirdek tarafından üretilen iletiler. Bu iletiler /prc/kmsg dosyasında bulunur ve dmesg komutu sadece tampondaki son iletileri gösterir.
