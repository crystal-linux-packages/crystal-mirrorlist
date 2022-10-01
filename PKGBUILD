pkgname=crystal-mirrorlist
pkgver=0.1.2
pkgrel=1
pkgdesc="Crystal Linux Mirrorlist"
arch=(any)
url="https://github.com/crystal-linux/pkgbuild.$pkgname"
license=('MIT')
source=('crystal-mirrorlist')
sha256sums=('68156ee28938cfdefae7eeba81ce0196070b2943921f3c183a97e31828f9c2af')

package () {
    install -Dm755 crystal-mirrorlist "${pkgdir}/etc/pacman.d/crystal-mirrorlist"
}
