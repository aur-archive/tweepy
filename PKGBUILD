# Maintainer: alejandrogomez <alejandroogomez@gmail.com>

pkgname=tweepy
pkgver=1.13
pkgrel=2
pkgdesc="A Python library for accessing the entire Twitter API."
arch=('any')
url="http://pypi.python.org/pypi/tweepy/"
license=('MIT')
depends=('python2-simplejson')
source=(http://pypi.python.org/packages/source/t/$pkgname/$pkgname-$pkgver.tar.gz)
md5sums=('5814a206010de0cc575e9f5c325ca64a')

build() {
   cd "$srcdir/$pkgname-$pkgver"

   python2 setup.py install --root="$pkgdir/" --optimize=1
}
