#
# Contribuidor: Pablo Henrique <pablohenriquedev32@gmail.com>
#

pkgname=screenfetch
pkgver=3.9.1
pkgrel=1
pkgdesc="Script CLI Bash para mostrar informações do sistema/tema em capturas de tela"
arch=('any')
url="http://localhost/ScreenFetch"
license=('GPL')
depends=('bash' 'bc' 'xorg-xdpyinfo' 'xorg-xprop')
makedepends=('git')
optdepends=('scrot: to take screenshot')
source=("screenFetch.tar.gz")
md5sums=('SKIP')

package()
{
    cd screenFetch
    install -Dm755 "screenfetch-dev" "$pkgdir/usr/bin/screenfetch"
    install -Dm644 "screenfetch.1" "$pkgdir/usr/share/man/man1/screenfetch.1"
}
