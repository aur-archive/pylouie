# Maintainer:  TDY <tdy@archlinux.info>
# Contributor: Paul Nicholson <brenix@gmail.com>
# Contributor: crazy <francois.cojean@gmail.com>
# Contributor: Jon Kristian Nilsen <jokr.nilsen@gmail.com>

pkgname=pylouie
pkgver=1.1
pkgrel=2
pkgdesc="A straightforward way to dispatch signals between objects in a wide variety of contexts"
arch=('any')
url="http://louie.berlios.de/"
license=('BSD')
depends=('python2-distribute' 'python2-nose>=0.8.3')
source=(http://pypi.python.org/packages/source/L/Louie/Louie-$pkgver.tar.gz)
md5sums=('46a61f7a88c624433c96f28ae30aa1a4')

package() {
    cd "$srcdir/Louie-$pkgver"
    python2 setup.py install --root="$pkgdir/" --optimize=1
}

# vim:set ts=2 sw=2 et:
