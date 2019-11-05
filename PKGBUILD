#Maintainer: Dalton Sconce <dsconce@protonmail.com>
pkgname=smoob
pkgver=1.1.1
pkgrel=1
epoch=
pkgdesc="Adds an option to systemd-boot menu to boot into a snapshot"
arch=(any)
url=""
license=('GPL')
groups=()
depends=('systemd' 'snapper' 'sed' 'coreutils' 'bash')
install=
source=("${pkgname}-${pkgver}.tar.gz::https://github.com/ptolemy7/snapper-menu-option/raw/master/tarball/v${pkgver}.tar.gz")
package() {
  mkdir -p $pkgdir/etc/systemd/system/
  mkdir -p $pkgdir/etc/smoob
  mkdir -p $pkgdir/usr/bin/
  install -D smoob.service $pkgdir/etc/systemd/system/
  install -D smoob $pkgdir/usr/bin/
}
md5sums=('352a6cb4229e7e4e81b1293adebdd708')
md5sums=('352a6cb4229e7e4e81b1293adebdd708')
md5sums=('0144e68ddb19dc5217b885e6ddce9532')
md5sums=('0144e68ddb19dc5217b885e6ddce9532')
