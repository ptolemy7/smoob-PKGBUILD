#Maintainer: Dalton Sconce <dsconce@protonmail.com>
pkgname=smoob
pkgver=1.1.2
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
md5sums=('c8904bf18fc10d72a502d2dd72cb8973')
md5sums=('c8904bf18fc10d72a502d2dd72cb8973')
