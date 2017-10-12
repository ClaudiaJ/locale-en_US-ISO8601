#Maintainer: Claudia Hardman <claudia at claud dot xyz>
pkgname=locale-en_US-ISO8601
pkgver=2015
pkgrel=1
pkgdesc='English US locale with ISO8601 for use as LC_TIME'
arch=(any)
license=(GPL)
url=""
source=(
  "en_US@iso8601"
)
sha512sums=(
  07d45208503313f71c971f698f5b06134e177dffff47da6cbeda1974a502b87a5deab0b43e59062d21515edf2496ad17740294ea6c6dafffbee0ab160df824af
)
md5sums=(
  2438fac5c0a4454b455cfbd817d95cd5
)
install=locale-en_US@iso8601.install

package () {
  cd -- "$srcdir"
  install -Dm644 "en_US@iso8601" "$pkgdir/usr/share/i18n/locales/en_US@iso8601"
}

# vim: set ts=2 sw=2 et:
