Tor, internet üzerindeki gizliliğinizi, internet ile Tor arasındaki bağlantıyı gizleyerek korur.
Tor'un makul olduğuna inanıyoruz.
İnternet adresiniz ve kullandığınız hizmetler güvenlidir, 
ancak lütfen talimatları okuduğunuzdan ve doğru şekilde yapılandırdığınızdan emin olun.

## Yapı

Tor'u kaynaktan derlemek için:

```
./configure
make
make install
```

Tor'u yeni klonlanmış bir git deposundan derlemek için:

```
./autogen.sh
./configure
make
make install
```

## Sürümler

Tarball'lar, sağlama toplamları ve imzalar burada bulunabilir: https://dist.torproject.org

- Sağlama: `<tarball-name>.sha256sum`
- İmzalar: `<tarball-name>.sha256sum.asc`

### Takvim

Yayın takvimimize buradan ulaşabilirsiniz:
- https://gitlab.torproject.org/tpo/core/team/-/wikis/NetworkTeam/CoreTorReleases

### İbranameyi imzalayabilecek anahtarlar.

Aşağıdaki anahtarlar bu deponun bakımcılarıdır. Bunlardan biri veya birçoğu
bu anahtarlar ibranameleri imzalayabilir, hepsini beklemeyin:

- Alexander Færøy:
    [514102454D0A87DB0767A1EBBE6A0531C18A9179](https://keys.openpgp.org/vks/v1/by-fingerprint/1C1BC007A9F607AA8152C040BEA7B180B1491921)
- David Goulet:
    [B74417EDDF22AC9F9E90F49142E86A2A11F48D36](https://keys.openpgp.org/vks/v1/by-fingerprint/B74417EDDF22AC9F9E90F49142E86A2A11F48D36)
- Nick Mathewson:
    [2133BC600AB133E1D826D173FE43009C4607B1FB](https://keys.openpgp.org/vks/v1/by-fingerprint/2133BC600AB133E1D826D173FE43009C4607B1FB)

##  Geliştirme

[doc/HACKING/](./doc/HACKING) adresindeki hackleme belgelerimize bakın.

## Kaynaklar

Ana Sayfa:

- https://www.torproject.org/

Yeni sürümleri indirin:

- https://www.torproject.org/download/download.html

Kurulum ve ayar talimatlarına bağlantılar içeren dokümantasyon:

- https://www.torproject.org/docs/documentation.html

Sıkça Sorulan Sorular:

- https://www.torproject.org/docs/faq.html

