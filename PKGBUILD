pkgname=crystal-mirrorlist
pkgver=0.1.3
pkgrel=3
pkgdesc="Crystal Linux Mirrorlist"
arch=('any')
url="https://github.com/crystal-linux-packages/${pkgname}"
license=('MIT')
source=("${pkgname}"
        "LICENSE")
sha256sums=('6ab56fd86a28599d7a6926c6036cfa86f0385a4a61dd59615eb642b9027bd84b'
            'd00321af957a776510ec3d7b5cc9316c50ab928f9231066b532ac8f0cf3ce69c')

package () {
    install -Dm 644 "${pkgname}" "${pkgdir}/etc/pacman.d/${pkgname}"
    install -Dm 644 "LICENSE" "${pkgdir}/usr/share/licenses/${pkgname}/LICENSE"
}
