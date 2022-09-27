pkgname=crystal-mirrorlist
pkgver=0.1.0
pkgrel=1
pkgdesc="Crystal Linux Mirrorlist"
arch=(any)
url="https://github.com/crystal-linux/pkgbuild.$pkgname"
license=('MIT')
source=('crystal-mirrorlist')
sha256sums=('117b8e9b62adc8ae4acc5bd6ea6294c3927d52e08bfc2202c317157a0244d9ef')

package () {
    install -Dm755 crystal-mirrorlist "${pkgdir}/etc/pacman.d/crystal-mirrorlist"
}
