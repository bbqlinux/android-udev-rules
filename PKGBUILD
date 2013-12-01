# Maintainer: Daniel Hillenbrand <codeworkx [at] bbqlinux [dot] org>
# Contributor: M0Rf30 
# Contributor: marlock

pkgname=android-udev-rules
pkgver=1.0.4
pkgrel=1
pkgdesc="Android udev rules"
arch=('any')
url="https://github.com/bbqlinux/android-udev-rules"
license=('GPL')

package() {
    cd "$pkgdir"
    install -Dm755 "$srcdir/etc/udev/rules.d/51-android.rules" etc/udev/rules.d/51-android.rules
}
