# Maintainer: Daniel Hillenbrand <codeworkx [at] bbqlinux [dot] org>
# Contributor: M0Rf30 
# Contributor: marlock

pkgname=android-udev-rules
pkgver=1.0.9
pkgrel=1
pkgdesc="Android udev rules"
arch=('any')
url="https://github.com/bbqlinux/android-udev-rules"
license=('GPL')
depends=('systemd' 'libmtp')

package() {
    mkdir -p $pkgdir/usr/lib/udev/rules.d/

    cp $srcdir/usr/lib/udev/rules.d/51-android.rules $pkgdir/usr/lib/udev/rules.d/51-android.rules
    chmod 644 $pkgdir/usr/lib/udev/rules.d/51-android.rules
}
