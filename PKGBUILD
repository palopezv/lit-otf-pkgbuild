# Maintainer: Pedro A. López-Valencia <https://github.com/palopezv>

pkgname=otf-literata
pkgver=2.00
pkgrel=3
pkgdesc="Google's contemporary serif typeface family for long-form reading; default typeface for Play Books. Android distribution."
arch=('any')
url="https://play.google.com/store/apps/details?id=com.google.android.apps.books"
license=('custom:propietary')
makedepends=('git')
replaces=('ttf-literata' 'ttf-literata-opticals' 'ttf-literata-webfonts' 'ttf-literata-webfonts-opticals')
#
# If this doesn't work, please let me know. I may need to find an alternative solution.
#
source=('It is up to you to find the fonts yourself')

b2sums=('SKIP')

package() {
  cd "$srcdir/$pkgname"

  install -dm755 "$pkgdir/usr/share/fonts/OTF"

  install -m644 lit*.otf "$pkgdir/usr/share/fonts/OTF"
}
