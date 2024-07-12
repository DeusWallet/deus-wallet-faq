# Ethereum Ağında Gas, Gas Fiyatını ve Gas Limitini Anlamak

Ethereum ağında gezinirken işlem ücretleri Ether (ETH tokenleri) cinsinden hesaplanır ancak Gas birimleri kullanılarak hesaplanır.

İşlem ücretlerini anlamak çoğu kullanıcı için yeterliyken, gaz kavramını derinlemesine incelemek bazılarının merakını giderebilir.

Gaz, Ethereum blok zincirinde yakıt güçlendirici eylemler olarak görev yapar ve işlem ücretlerinin belirlenmesinde ölçüm birimi görevi görür. İki önemli parametreye bağlıdır:

1) Gas Limiti, bir kullanıcının bir işlemi doğrulamak için ödemeyi taahhüt ettiği maksimum Gas miktarını belirtir (minimum 21.000). Tipik olarak ETH transferlerini içeren işlemler için gas limiti 21.000 olarak belirlenir. Cüzdan uygulamaları genellikle bu sınırı işlemin karmaşıklığına göre ölçer. Yetersiz gas limitleri sıklıkla işlem başarısızlıklarına neden olur ve buna "gas bitti" hatası da eşlik eder.

2) Gaz Fiyatı, kullanıcının gaz birimi başına tahsis ettiği miktarı (ETH cinsinden) ifade eder. Bu fiyat ağ etkinliğine göre dalgalanır; Zirve dönemlerinde gaz fiyatları yükselirken, durgunluk dönemlerinde ise düşüyor. Daha yüksek gas fiyatları, madencilerin daha fazla ödül alması nedeniyle Ethereum ağı içindeki işlemin öneminin arttığını gösteriyor. Yetersiz gaz fiyatları sıklıkla işlem bekleme sürelerinin uzamasına neden olur.

Deus cüzdanı, Ethereum ağ işlemleri için hem gas limitini hem de gas fiyatını otomatik olarak ayarlar. Önerilen işlem ücreti, önerilen gaz limiti ile gaz fiyatının çarpılmasıyla elde edilir.

Örneğin, 50.000 birimlik gas limiti ve 20 Gwei (Ether'in bir alt birimi) gas fiyatı ile gönderen, işlemin yürütülmesi için 0,001 ETH harcamayı taahhüt eder.