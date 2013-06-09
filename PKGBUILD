# Maintainer: Daniel Hillenbrand <codeworkx@bbqlinux.org>

pkgname=android-udev-rules
pkgver=1.0.3
pkgrel=1
pkgdesc="Android udev rules"
arch=('any')
url="https://github.com/bbqlinux/android-udev-rules"
license=('GPL')

package() {
    cd "$pkgdir"
    install -Dm755 "$srcdir/etc/udev/rules.d/51-android.rules" etc/udev/rules.d/51-android.rules
}
