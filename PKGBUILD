# Maintainer: Chris Down <chris@chrisdown.name>

pkgname=mpdmenu
pkgver=1.0.0
pkgrel=2
pkgdesc="Simple dmenu frontend for MPD"
url="http://github.com/cdown/mpdmenu"
arch=( "any" )
license=( "MIT" )
depends=( dmenu )

source=(
    "https://github.com/cdown/mpdmenu/archive/v${pkgver}.zip"
)
md5sums=('046466baa220c82dae0df0605304a85e')

package() {
    install -D -m755 \
        "$srcdir/$pkgname-$pkgver/mpdmenu" \
        "$pkgdir/usr/bin/mpdmenu"
}
