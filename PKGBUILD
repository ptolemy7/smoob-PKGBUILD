#Maintainer: Dalton Sconce <dsconce@protonmail.com>
#packager='Dalton Sconce <dsconce@protonmail.com.invalid>'
pkgname=smoob
pkgver=1.1.0
pkgrel=1
epoch=
pkgdesc="Adds an option to systemd-boot menu to boot into a snapshot"
arch=(any)
url=""
license=('GPL')
groups=()
depends=('systemd' 'snapper' 'sed' 'coreutils' 'bash')
install=
source=("${pkgname}-${pkgver}.tar.gz::https://github.com/ptolemy7/snapper-menu-option/raw/testing/tarball/v${pkgver}.tar.gz")
package() {
  mkdir -p $pkgdir/etc/systemd/system/
  mkdir -p $pkgdir/etc/$pkgname/
  mkdir -p $pkgdir/usr/sbin/
  install -D smoob.service $pkgdir/etc/systemd/system/
  install -D smoob $pkgdir/usr/sbin/snapper-menu-option
}

md5sums=('6764bc0e91df4baab843e9992ab1d340')
