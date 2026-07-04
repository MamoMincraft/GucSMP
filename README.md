# GucSMP
Yeni rekabet odaklı Minecraft SMP Plugini


# Eklenti özellikleri

# -Her oyuncu için güç durumu

Güç durumu başlangıçta her oyuncuda 1'dir, Her oyuncu öldürdüğünde bu değer 0.25 artar ve oyuncunun normal verdiği hasar normal değerin 0.25 katına çıkar.

Eğer oyuncu ölürse güç durumu 0.25 azalır. Ve Eğer gücü 0'a düşerse elenir.

Elenme durumunda oyun wither_spawn soundu çalar ve chatte;
"<oyuncu adı> gücünü kaybederek elendi!" yazısı görülür

Elenme durumunda oyuncu sunucudan perma-banlanır.

Oyuncu kendi isteği ile "/guc azalt <güc miktarı>" komudu kullanarak eline wither_star itemi şeklinde üzerinde kırmızı "<Güc Miktarı> Güç" yazan bir item elde eder ve istediği kişiye hediye edebilir. Fakat bu eylem eğer güç durumu 1'in altındaysa kullanılamaz.

Bir oyuncunun elde edebileceği maksimum güç miktarı 3'tür

__________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________

# -Silah Yetenekleri

Silahın yeteneği oyuncu harici mob'lara saldırarak hazır haline getirilinemez, fakat moblara karşı kullanılabilir

Silahın yeteneği hazır olduğunda chatte "(Kırmızı Yazıyla)Yetenek hazır" yazar.

Oyuncunun <Eğilme Tuşu> tuşuna basması ile aktifleşir ve tek seferlik değil ve süreliyse aynı tuşla kapanır. Actionbara sayaç eklenir ve bu sayaç yeteneğin süresini gösterir. Sayacın başında saat simgesi ve geri kalanında kalan süre yazar

# Silahlar ve Yetenekleri;

# Kılıç=
Rakibe toplamda 200 Hasar(100 kalp) verildiğinde kullanılabilir, Rakip eğilme tuşu ile yeteneğini aktif eder ve 10 saniye boyunca rakibine kılıcın verdiği hasar 1.50 katına çıkar.Yetenği tekrar aktifleştirmek için oyuncunun tekrardan 200 Hasar vermesi gerekir

# Balta=
Rakibe 50 Hasar verildiğinde kullanılabilir.Aktifleştirildiğinde rakibe yapılan ilk vuruş hangi şartlar olursa olsun rakibin 5 kalbini götürür. Tek seferliktir. Kalkan ve zırhı aşabilir.

#Yay=
Rakibe 100 Hasar verildiğinde aktif hale gelir.Kullanıldığında gönderilen okun hızı bir railgundan çıkmış gibi hızlı olur ve etrafına kızıltaş parçacıkları saçarak okun merkezinde olduğu 3x3 lük bir alandaki bütün canlılara 100 Hasar verir. 3 shot hakkı vardır

# Üçlü Mızrak=
Aktifleştirilmesi için 50 Hasar verilmelidir.Aktifleştirildiği vakit rakibe verilen hasar 2 katına çıkar. Ve yapılan ilk vuruş fazladan 2 kalp fazla can götürür. 10 saniyeliğine aktif kalır

# Gürz=
Aktifleştiirlmesi için 100 Hasar verilmelidir.Aktifleştirildiği vakit verilen hasar 1,50 katına çıkar ve vuruş zırh ve kalkanı yok sayar. Tek seferliktir. Kullanıldıktan sonra gürz 10 saniyeliğine devre dışı kalır.Yani hiçbir şekilde kullanılamaz ve envanterde normal minecraft cooldown olarak gözükür

__________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________

# -Özel Kısıtlamalar ve Arttırmalar

~TNT Minecartların hasarı maksimum 5 kalptir

~Kaplumbağa iksirinin efektleri 1 seviye düşürüldü, yapım eşyası kaplumbağa kaskından puluna çevirildi

~Anında Sağlık iksirinin seviyesi maksimum 1dir

~Anında Hasar iksirinin seviyesi maksimum 1dir


# BİLGİLENDİRME
Bu özellik listesi pluginin çıkış versiyonu ile değişiklik gösterebilir, ayrıca plugini config dosyasından ayarları ile oynayabileceksiniz :)
