pkgname=crystal-mirrorlist
pkgver=0.1.3
pkgrel=4
pkgdesc="Crystal Linux Mirrorlist"
arch=('any')
url="https://github.com/crystal-linux-packages/${pkgname}"
license=('MIT')
source=("${pkgname}"
        "LICENSE")
sha256sums=('b273a5ae80b5bd0635f7d9f76ab86c43918ecbef28c8fc135fdc0c7ce93da02d'
            'd00321af957a776510ec3d7b5cc9316c50ab928f9231066b532ac8f0cf3ce69c')

package () {
    install -Dm 644 "${pkgname}" "${pkgdir}/etc/pacman.d/${pkgname}"
    install -Dm 644 "LICENSE" "${pkgdir}/usr/share/licenses/${pkgname}/LICENSE"
}
