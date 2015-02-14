# Maintainer: Daniel Hillenbrand <codeworkx [at] bbqlinux [dot] org>
# Contributor: M0Rf30 
# Contributor: marlock

pkgname=android-udev-rules
pkgver=1.0.6
pkgrel=1
pkgdesc="Android udev rules"
arch=('any')
url="https://github.com/bbqlinux/android-udev-rules"
license=('GPL')
depends=('systemd' 'libmtp')

package() {
    #cd "$pkgdir"

    mkdir -p $pkgdir/usr/lib/udev/rules.d/

    cp $srcdir/usr/lib/udev/rules.d/51-android.rules $pkgdir/usr/lib/udev/rules.d/51-android.rules
    chmod a+r $pkgdir/usr/lib/udev/rules.d/51-android.rules
}
