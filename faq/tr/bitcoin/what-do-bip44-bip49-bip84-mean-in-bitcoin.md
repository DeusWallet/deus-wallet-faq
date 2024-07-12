# Bitcoin'de BIP44 / BIP49 / BIP84 Ne Anlama Geliyor?

Bitcoin, ödeme almak için yaygın olarak kullanılan üç adres biçimini kullanır. Genellikle kripto para cüzdanları bu formatlardan yalnızca birini destekler, ancak bazıları birden fazla formatı da destekleyebilir.

Bununla birlikte Deus, her üç adres formatını da destekleyerek kullanıcıların tek bir çok paralı cüzdanda her format için ayrı Bitcoin bakiyeleri ve işlemleri sürdürmelerine olanak tanıyor. Bu, Deus'ta oluşturulan bir cüzdanın, diğer kripto para birimlerinin yanı sıra ayrı kripto para birimleri olarak işlev gören üç farklı Bitcoin cüzdanına sahip olabileceği anlamına gelir.

Bu çeşitli adres formatları, Bitcoin işlemleri arttıkça, işlem boyutlarını azaltmak ve ağın blok başına daha fazla işlem işlemesini sağlamak için tasarlanan daha yeni formatlarla birlikte ortaya çıktı.

## Eski Adresler (BIP44)

BIP44 olarak bilinen en eski adres formatı genellikle "1" ile başlar. Orijinal formatta çoğu cüzdan bu adreslere hem ödeme gönderip hem de alabilir. Ancak Eski Adresleri kullanan işlemler, diğer formatlara kıyasla daha yüksek ücretlere tabidir.

## SegWit Adresleri (BIP49)

Daha yeni bir format olan BIP49 genellikle "3" ile başlar. Birçok yeni cüzdan uygulaması SegWit adreslerini destekler ve SegWit adreslerini kullanan cüzdanlardan yapılan işlemler Eski Adresleri kullananlara göre daha ucuzdur.

## Yerel SegWit Adresleri (BIP84)

En yeni ve uygun maliyetli format olan BIP84, "bc1" ile başlayan bech32 adres formatını kullanır. Yerel SegWit Adreslerini kullanan işlemler en düşük ücretlere sahiptir.

Bir cüzdanın hangi formatı desteklediğini belirlemek için cüzdan uygulamasında alıcı adresin ilk birkaç karakterini kontrol edin. Bazı cüzdan uygulamalarında Bitcoin cüzdanını geri yüklerken adres biçimini anlamak da önemlidir.

Deus cüzdanı, bu üç adres formatından herhangi birinde çalışan cüzdanlar oluşturabilir ve geri yükleyebilir.