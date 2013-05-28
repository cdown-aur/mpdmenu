# Maintainer: Chris Down <chris@chrisdown.name>

pkgname=mpdmenu
pkgver=1.0.2
pkgrel=1
pkgdesc="Simple dmenu frontend for MPD"
url="http://github.com/cdown/mpdmenu"
arch=( "any" )
license=( "MIT" )
depends=( dmenu )

source=(
    "https://github.com/cdown/mpdmenu/archive/v${pkgver}.zip"
)
md5sums=('1b7fa7856681cf48ff221fff8a11147d')

package() {
    install -D -m755 \
        "$srcdir/$pkgname-$pkgver/mpdmenu" \
        "$pkgdir/usr/bin/mpdmenu"
}
