# Maintainer: Hilton Medeiros <medeiros.hilton@gmail.com>
# Contributor: Andrea Scarpino <andrea@archlinux.org>

pkgname=gcc-docs
pkgver=4.6.2
pkgrel=1
pkgdesc="Set of HTML documentation for GCC"
arch=('any')
url="http://gcc.gnu.org"
license=('GPL')
depends=('gcc')
options=('docs' '!strip')
source=("http://gcc.gnu.org/onlinedocs/gcc-${pkgver}/gcc-html.tar.gz")
md5sums=('d030e9be972015f81f9618658be74440')

package() {
  cd "$srcdir/gcc"
  install -d "$pkgdir/usr/share/doc/gcc"
  cp -rf * "$pkgdir/usr/share/doc/gcc"
}
