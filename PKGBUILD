pkgname=crystal-mirrorlist
pkgver=0.1.3
pkgrel=1
pkgdesc="Crystal Linux Mirrorlist"
arch=(any)
url="https://github.com/crystal-linux/pkgbuild.$pkgname"
license=('MIT')
source=('crystal-mirrorlist')
sha256sums=('6ab56fd86a28599d7a6926c6036cfa86f0385a4a61dd59615eb642b9027bd84b')

package () {
    install -Dm755 crystal-mirrorlist "${pkgdir}/etc/pacman.d/crystal-mirrorlist"
}
