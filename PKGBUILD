# Maintainer: E5H4N <m.eshan@outlook.in>

pkgname=payraos-gnome-config
pkgver=1.0.0
pkgrel=1
arch=('any')
url="https://github.com/payra-os/$pkgname"
license=('GPL')
makedepends=('coreutils')
source=("$pkgname-$pkgver.tar.gz::$url/-/archive/$pkgver/$pkgname-$pkgver.tar.gz")
sha256sums=('SKIP')
pkgdesc='Payra OS Gnome Configuration'
install=$pkgname.install
provides=('payraos-desktop-config')
conflicts=('payraos-desktop-config')
package() {
    install -d $pkgdir/etc
    cp -rf $srcdir/$pkgname-$pkgver/etc $pkgdir
    depends=('payraos-backgrounds'
        'payraos-common-settings'
        'gnome-themes-extra'
        'volantes-cursors'
        'ttf-fira-sans'
        'ttf-firacode-nerd')
}
