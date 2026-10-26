# IEC Tişört Sponsorluğu

IEC Engineering Club (Saraybosna) kulüp tişörtünün 3D sponsor sayfası.

**Sayfa:** https://hasankaan28.github.io/iec-tshirt/

Sponsorlar tişörtü döndürür, logolarını koymak istedikleri alanları işaretler ve kulübe gönderecekleri hazır mesajı alır. Sayfa kendi başına bir şey göndermez: mesaj iusengclub@gmail.com adresine e-postayla gider.

Tişörtü kulüp üyeleri giyer. Çoğu kulüpten satın alınır; 10 tanesi IEC Pass kartında 10 damga toplayan üyelere ödül olarak verilir.

## Tişört

Kulüp yalnızca siyah tişörtü (G) yapıyor (26 Ekim 2026 kararı). Önünde, sol göğüste beyaz kulüp mührü var. Arkasında IEC harfleri 3B teknik resim olarak çizili; ENGINEERING CLUB × SARAJEVO × 2026 ölçüleri ve slogan da arkada.

![Tişört G](mock/G.jpg)

Beyaz tişört (B) kodda duruyor ama sayfada gösterilmiyor. Geri açmak için `index.html` içindeki `ORDER` listesine `'B'` ekleyin. Tişörtü arkadan açmak için linke `?view=back` ekleyin.

3D tişört bir kumaş simülasyonundan gelir: ön ve arka kalıp dikiş yerlerinden birleştirilir ve görünmez bir mankenin üzerinde yerçekimiyle oturtulur. Kıvrımlar bu yüzden kendiliğinden oluşur. Her nokta kalıptaki yerini bildiği için baskılar kumaş üstünde gerçek ölçüleriyle görünür. Simülasyonun sonucu `garment.json` dosyasındadır.

## Sponsor alanları (yetişkin L beden)

| Alan | Ölçü |
| --- | --- |
| Ön göğüs, ana sponsor | 25 × 8 cm |
| Sağ göğüs | 8.5 × 3.5 cm |
| Sırt altı | 23 × 5.5 cm |
| Sol kol | 7.5 × 7.5 cm |
| Sağ kol | 7.5 × 7.5 cm |

Sırtın üstünde, yakanın altında sponsor yoktur. Orada her tişörtte IUS arması ve IUS yazısı vardır: beyaz tişörtte yazı turuncu, siyah tişörtte beyazdır. Ödül olarak verilen 10 tişörtte bunun yanında küçük, yuvarlak bir IEC PASS damgası da vardır.

Sağ göğüs Alma Ras'ındır: sayfada orada Alma Ras logosu görünür ve alan "Dolu" olarak gösterilir.

İki tişörtte de alanlar aynıdır. Satılan bir alanı sayfada "Dolu" göstermek için `index.html` içindeki `TAKEN` listesine alanın kimliğini ekleyin (`front`, `chest`, `lower`, `lsleeve`, `rsleeve`). Sponsorun logosunun tişörtte görünmesi için `SPONSOR_LOGOS` listesine o alan için iki logo dosyası ekleyin: beyaz tişörte koyu, siyah tişörte açık renkli, şeffaf arka planlı PNG (`art/` klasöründe).

## English

A 3D page for sponsors of the IEC Engineering Club shirt in Sarajevo. Members buy the shirt from the club, and 10 shirts go as prizes to members who collect 10 stamps on their IEC Pass. Sponsors turn the black club shirt, choose the spots for their logo and get a ready message to send to iusengclub@gmail.com. The flat pattern is wrapped around the body, so prints show at their real size. The right chest spot is taken by Alma Ras, whose logo the page shows there. The page is available in Turkish, English and Bosnian.
