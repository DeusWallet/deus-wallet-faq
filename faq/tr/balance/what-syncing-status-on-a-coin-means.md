# Bir madalyonun 'senkronizasyon' durumu ne anlama geliyor?

Coin üzerindeki 'senkronizasyon' durum göstergesi, Deus uygulamasının kendisini belirli bir blockchain ile senkronize etmeye çalıştığını gösterir. Çoğu durumda bu durumun kısaca gösterilmesi gerekirken, önemli ölçüde daha uzun süre kalabileceği birçok geçerli durum vardır:
- Cüzdanı Bitcoin, Bitcoin Cash, Dash, Litecoin ve Zcash kripto para birimleriyle geri yüklerken ilk senkronizasyon sırasında. Kullanıcı, cüzdanı 3. taraf API hizmeti yerine bir blockchain'den geri yüklemeyi seçerse, her para için birkaç saatlik senkronizasyon beklenir. Ne kadar çok para geri yüklenirse, o kadar uzun sürer.

- Cüzdan kurulumundan sonra Bitcoin, Bitcoin Cash, Dash, Litecoin ve Zcash kripto para birimlerini 1. kez etkinleştirirken.

- Cüzdan uygulamasının son açılışından bu yana günler veya haftalar geçtikten sonra açılması.

- Kötü ağ koşulları ve genel olarak yavaş internet.

- Ethereum ve Binance Smart Chain RPC sağlayıcıları için gecikmeli veya yavaş yanıt süreleri. Genellikle birkaç dakika beklemeniz veya cüzdan uygulamasını yeniden başlatmayı denemeniz önerilir. Bu aşamada Deus, RPC hizmetlerine bağımlıdır çünkü bu iki blok zinciri için doğrudan iletişim çözümleri şu anda zayıf kullanılabilirliğe neden olmaktadır.

Unutmayın, Deus uygulaması senkronizasyon sürecini yalnızca Deus açık kaldığında çalışır durumda tutar. Uygulama kapatılırsa senkronizasyon işlemi duraklatılır ve yalnızca uygulama tekrar açıldığında devam eder.