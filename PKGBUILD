pkgname=crystal-mirrorlist
pkgver=0.1.1
pkgrel=1
pkgdesc="Crystal Linux Mirrorlist"
arch=(any)
url="https://github.com/crystal-linux/pkgbuild.$pkgname"
license=('MIT')
source=('crystal-mirrorlist')
sha256sums=('8a1af68d6643319aaf678d77797e9e97b00a9c6b41ef6e1add1d7c6d1f1478b9')

package () {
    install -Dm755 crystal-mirrorlist "${pkgdir}/etc/pacman.d/crystal-mirrorlist"
}
