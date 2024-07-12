# Kripto Para Takası ile İlişkili Riskler

Deus cüzdanı, karmaşıklıkların üstesinden gelerek ve takas ayarlarını otomatik olarak yapılandırarak kripto para birimlerini takas etme sürecini basitleştirirken, takas işlemlerine girerken akılda tutulması gereken çeşitli hususlar vardır.

1. İşlem Maliyetleri

Merkezi olmayan borsalarda (DEX'ler) takas yaparken, kullanıcılar hem işlem ücretini (Ethereum blok zincirindeki madencilere ödenen) hem de takas ücretini (işlemi kolaylaştıran DEX'e gönderilen) karşılamakla yükümlüdür. Bu ücretler tek bir takas işleminde farklı kuruluşlara ödenir. Swap ücreti emir büyüklüğüne göre değişirken, işlem ücreti ağ koşullarına göre dalgalanmaktadır.

Ethereum blok zincirinin yüksek trafik yaşadığı gibi tıkanıklık zamanlarında işlem ücretleri önemli ölçüde artabilir. Tersine, Binance Smart Chain'de takas gerçekleştirmek genellikle Ethereum'a kıyasla daha düşük maliyetlere neden olur. Kullanılan DEX'e bakılmaksızın swap ücretleri genellikle işlem tutarının %0,3'ü civarındadır.

Ek olarak, farklı blockchainlerdeki DEX'lerin farklı işlem çiftleri ve likidite seviyeleriyle çalıştığını bilmek önemlidir.

2. İşlem Son Tarihleri

Tipik olarak bir takas işlemi, blok zincirine gönderildikten sonra yaklaşık 20 dakika boyunca geçerli kalır. Bu nedenle, Ethereum gibi sıkışık bir blok zincirinde DEX kullanırken, takas işleminin son tarihe kadar yeterli bir işlem ücreti içerdiğinden emin olmak çok önemlidir. Düşük ücretle bir takas işlemi göndermek, işlemin son tarihin ötesinde beklemede kalmasına ve takas işleminin başarısız olmasına neden olabilir.

3. Fiyat Kayması

Fiyat kayması, takas emrinin verilmesi ile blok zincirindeki işlemin tamamlanması arasındaki token fiyatındaki farkı ifade eder. Bu fark, fiyat değişiminin yönüne bağlı olarak pozitif veya negatif olabilir. Emir gönderimi ile blockchain doğrulaması arasındaki dönemde piyasa koşullarındaki dalgalanmalar fiyat kaymasına katkıda bulunuyor.

Deus cüzdanı, kullanıcıların takas işleminden bekleyebilecekleri tahmini ve garantili token tutarlarını görüntüleyerek bu riski azaltır. Kullanıcılar ayrıca işlemleri gönderirken kabul edilebilir kayma seviyelerini de belirtebilirler; ancak mümkün olan en düşük kaymayı tercih etmek işlemin başarısız olma olasılığını artırabilir.

4. Kayma Toleransı

Kayma toleransı, bir kullanıcının bir işlem için kabul etmeye hazır olduğu fiyat kaymasının derecesini ifade eder. Kullanıcılar, bir kayma toleransı ayarlayarak, fiyatın dalgalanması durumunda kabul edecekleri token sayısı için minimum bir eşik belirler. Bu tolerans toplam takas değerinin yüzdesi olarak ifade edilir.

5. Swap İşlem Ücretleri

Ethereum blok zincirinde işlem yapmanın maliyeti, özellikle küçük miktarlar için çok yüksek olabilir. 10.000 ABD Doları değerindeki kriptoyu takas etmek, 100 ABD Doları işlem ücretini haklı gösterse de, 500 ABD Doları veya daha az gibi daha küçük miktarlar için aynı ücret ekonomik olarak uygun olmayabilir.

6. Onay İşlemleri

ERC20 veya BEP20 tokenlerini satarken kullanıcıların öncelikle bir Onay İşlemi gerçekleştirmesi gerekir. Bu işlem, DEX'e, bir işlem sırasında kullanıcının bakiyesinden tokenları düşürme yetkisi verir. Bu onay işlemi olmadan DEX, kullanıcının tokenlarını işlemlerde kullanamaz.