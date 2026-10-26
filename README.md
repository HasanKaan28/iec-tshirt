# IEC Tişört Sponsorluğu

IEC Engineering Club (Saraybosna) kulüp tişörtünün 3D sponsor sayfası.

**Sayfa:** https://hasankaan28.github.io/iec-tshirt/

Bu sayfa kulübün kendi kullanımı ve sponsorlara sunum içindir. Tişört döndürülür, sponsor alanları seçilir ve sponsorun logosu bu alanlara yüklenip 3D tişörtte gösterilir. Logo yalnızca tarayıcıda kalır, hiçbir yere gönderilmez. "Sunum" düğmesi tişörtü tam ekrana alır; klavyede ← → tişörtü çevirir, F önü, B arkayı gösterir, P sunumu açıp kapatır, Esc çıkar. Sayfa arama motorlarına kapalıdır (noindex).

Tişörtü kulüp üyeleri giyer. Çoğu kulüpten satın alınır; 10 tanesi IEC Pass kartında 10 damga toplayan üyelere ödül olarak verilir.

## Tişört

Kulüp yalnızca siyah tişörtü (G) yapıyor (26 Ekim 2026 kararı). Önünde, sol göğüste beyaz kulüp mührü var. Arkasında IEC harfleri 3B teknik resim olarak çizili; ENGINEERING CLUB × SARAJEVO × 2026 ölçüleri ve slogan da arkada.

![Tişört G](mock/G.jpg)

Sayfada iki seçenek var: siyah tişört ve hediye tişörtü (10/10). Hediye tişörtü, IEC Pass'te 10 damgayı dolduran 10 üyeye verilen siyah tişörttür; yakanın altında IUS baskısının yanında yuvarlak bir IEC PASS damgası vardır. Doğrudan açmak için `?shirt=P` kullanın. Beyaz tişört (B) kodda duruyor ama gösterilmiyor; geri açmak için `index.html` içindeki `ORDER` listesine `'B'` ekleyin. Tişörtü arkadan açmak için linke `?view=back` ekleyin.

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

A 3D page for presenting the IEC Engineering Club shirt (Sarajevo) to sponsors, and for the club's own planning. Turn the black shirt or its gift version for members who fill their IEC Pass, choose sponsor spots and upload a sponsor's logo to see it on the shirt; the logo stays in the browser. Present mode fills the screen (keys: arrows turn, F front, B back, P present, Esc exit). The right chest spot is taken by Alma Ras. The page is in Turkish, English and Bosnian and is not indexed by search engines.
