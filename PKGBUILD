pkgname=crystal-mirrorlist
pkgver=0.1.3
pkgrel=2
pkgdesc="Crystal Linux Mirrorlist"
arch=('any')
url="https://github.com/crystal-linux-packages/${pkgname}"
license=('MIT')
source=("${pkgname}")
sha256sums=('6ab56fd86a28599d7a6926c6036cfa86f0385a4a61dd59615eb642b9027bd84b')

package () {
    install -Dm 644 "${pkgname}" "${pkgdir}/etc/pacman.d/${pkgname}"
    install -Dm 644 "LICENSE" "${pkgdir}/usr/share/licenses/${pkgname}/LICENSE"
}
