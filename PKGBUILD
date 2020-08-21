pkgname=iosevka
pkgver=3.4.3
pkgrel=1
pkgdesc="Iosevka is an open-source, sans-serif + slab-serif, monospace + quasi‑proportional typeface family, designed for writing code, using in terminals, and preparing technical documents"
arch=('x86_64')
url="https://be5invis.github.io/Iosevka"
license=('SIL OFL Version 1.1')
source=("https://github.com/be5invis/Iosevka/releases/download/v${pkgver}/ttf-iosevka-${pkgver}.zip")
sha512sums=('24bfcf5f5cef06d465ff00c76fcbcfccf899ff4d25700b2a616f463922e43cb40a79ce4d0459332f1cadda863125823c0778213815fd3285093c1a6953a2ed84')

package() {
    install -d ${pkgdir}/usr/share/fonts/iosevka
    install -m0644 ${srcdir}/ttf/*.ttf ${pkgdir}/usr/share/fonts/iosevka
}