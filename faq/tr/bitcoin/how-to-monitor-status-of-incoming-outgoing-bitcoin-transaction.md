# Gelen/Giden Bitcoin İşlemlerinin Durumu Nasıl İzlenir

Deus cüzdanı, kullanıcıların işlemlerinin durumunu izlemesine olanak tanır:

- Bir kullanıcı bir Bitcoin işlemi gönderdiğinde, bu işlem hem gönderen hem de alıcı için İşlemler sekmesinde 'beklemede' durumuyla görünür. Bu durum, işlem blok zincirine dahil edilene kadar kalır.

- İşlem blockchain'e dahil edildikten sonra durumu, gönderen için 'gönderiyor', alıcı için 'alıyor' olarak değişir. Bu değişiklik, işlemin ilk onayını aldığını gösteriyor.

- İşlem durumu, en az üç blok geçene kadar hem gönderen hem de alıcı için 'gönderiliyor' olarak kalır; bu, işlemin üç onay aldığı anlamına gelir.

Üç blok geçene kadar Deus, işlem tutarını alıcının bakiyesine yansıtmayacak veya alıcının alınan parayı başka işlemlerde harcamasına izin vermeyecektir.

Kullanıcılar, Deus içindeki işlem durumunu izlemenin yanı sıra, izleme için [btc.com](https://btc.com) gibi halka açık Bitcoin blok araştırmacılarını da kullanabilirler. Harici kaynaklarda bekleyen işlemlerin durumunu takip etmek için kullanıcıların Deus'ta bulunabilecek işlem kimliğine ihtiyacı vardır.