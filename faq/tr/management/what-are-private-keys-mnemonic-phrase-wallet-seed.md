# Özel Anahtarları Anlamak

Kripto para dünyasında özel anahtar, anımsatıcı ifade, gizli ifade ve cüzdan tohumu gibi terimler sıklıkla birbirinin yerine kullanılır. Bu terimlerin tümü, Deus gibi saklamaya tabi olmayan kripto para birimi cüzdanlarındaki fonları kontrol etmek için gerekli bilgileri ifade eder.

Saklanmayan bir kripto para birimi cüzdanı kurarken kullanıcılara özel bir anahtar sağlanır. Bu anahtar, kurulum işlemi sırasında oluşturulur ve kullanım kolaylığı sağlamak amacıyla, Deus'ta gizli ifade olarak bilinen 12 (veya daha fazla) basit İngilizce sözcükten oluşan bir dizi olarak sunulur.

Özel anahtar, kullanıcılara cüzdandaki tüm varlıklara erişim ve sahiplik sağlar. Parola kurtarmaya izin veren geleneksel hizmetlerin aksine, saklanmayan cüzdanlar, kaybolan özel anahtarlar için kurtarma seçenekleri sunmaz. Düzgün oluşturulmuş cüzdanlar bu anahtarları kaybettikten sonra geri getiremez.

Özel anahtarlar, cüzdan oluşturma sırasında kullanıcının cihazında rastgele oluşturulur ve cihazdan asla ayrılmaz. M-cüzdan silinirse anahtarlar da silinir, bu da cihaza erişim olmadan kurtarmayı imkansız hale getirir. Bu nedenle cüzdan kurulumu sırasında kullanıcıların özel anahtarlarını yedeklemeleri çok önemlidir. Çoğu cüzdan, kullanıcılardan özel anahtarın bir kopyasını oluşturulduktan hemen sonra yazmalarını ister.

Her Deus çoklu para cüzdanı, 12 sade İngilizce kelime olarak sunulan ve gizli ifade olarak adlandırılan kendi özel anahtarıyla birlikte gelir. Bu anahtar kullanıcıların şunları yapmasına olanak tanır:

- Deus uygulaması silinse bile cüzdan erişimini geri yükleyin.
- Farklı bir cüzdan uygulamasında cüzdana erişimi geri yükleyin.

Gizli ifadeye ek olarak Deus birkaç önemli seçenek daha sunar:

### EVM Özel Anahtarı

Bu anahtar, EVM tabanlı kripto para birimlerinin (Ethereum ve Binance Smart Chain gibi) Deus'tan herhangi bir uyumlu cüzdan uygulamasına aktarılmasını sağlar. Bu anahtara sahip olan herkes EVM tabanlı kripto para birimlerini kontrol edebildiği, ancak aynı cüzdandaki Bitcoin veya EVM olmayan diğer kripto para birimlerini kontrol edemediği için halka açık olarak paylaşılmamalıdır.

### BIP32 Kök Anahtarı

Bu, cüzdanın varlıkları üzerinde tam kontrol sağlayan gizli ifadenin başka bir temsilidir. Güvenli bir şekilde saklanmalı ve asla paylaşılmamalıdır.

### Hesabın Genişletilmiş Genel Anahtarı

Bu anahtar, cüzdandaki Bitcoin ve diğer UTXO tabanlı kripto para birimlerinin (Litecoin ve Bitcoin Cash gibi) salt okunur olarak izlenmesine olanak tanır. Fonları harcamadan izlemek için kullanışlıdır. Örneğin, bir Ledger donanım cüzdanında saklanan Bitcoin'i, güvenlikten ödün vermeden Deus aracılığıyla izleyebilirsiniz. Bu anahtar EVM kripto para birimlerine erişim sağlamaz.

### Hesabın Genişletilmiş Özel Anahtarı

Bu anahtar, Bitcoin ve diğer UTXO tabanlı kripto para birimlerinin Deus'tan başka bir uyumlu cüzdan uygulamasına aktarılmasına olanak tanır. Hesap Genişletilmiş Genel Anahtar ile aynı sahiplik yeteneklerini sağlar ancak fonlar üzerinde kontrol sağlar. Bitcoin ve diğer UTXO tabanlı kripto para birimlerinin yönetimine izin verdiği, ancak EVM kripto para birimlerinin yönetimine izin vermediği için gizli tutulmalı ve asla paylaşılmamalıdır.

Kullanıcılar bu anahtarları ve işlevlerini anlayarak kripto para varlıklarının güvenli ve erişilebilir kalmasını sağlayabilirler.