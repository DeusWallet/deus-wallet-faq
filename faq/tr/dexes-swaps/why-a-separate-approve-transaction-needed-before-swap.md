# Swap öncesinde neden ayrı bir Onay işlemi gerekiyor?

Aşağıdaki gibi herhangi bir swap işlemine başlamadan önce:

- ERC20'yi ETH'ye dönüştürme
- ERC20'yi başka bir ERC20 ile değiştirme
- BEP20'yi BNB ile değiştirme
- BEP20 jetonlarının değiştirilmesi

Kullanıcıların ayrı bir Onay işlemi yapması gerekmektedir. Bu Onay işlemleri genellikle ekonomiktir ve kullanıcının DEX'in ticaretin gerçekleştirilmesi için belirli miktarda ERC20/BEP20 tokeni kesintisi yapmasına izin verdiğini gösterir.

Onay işlemi sırasında kullanıcılar, DEX'in düşmesine izin verilen token miktarını belirleyebilir. Kullanıcılar ayrıca gelecekteki işlemlere yönelik olarak daha yüksek tutarları yetkilendirme seçeneğine de sahiptir, böylece daha sonraki Onay işlemlerine duyulan ihtiyaç ortadan kalkar.

Bir ticaret için yeterli token miktarının yetkilendirilmemesi, işlemin başarısız olmasına yol açacaktır.