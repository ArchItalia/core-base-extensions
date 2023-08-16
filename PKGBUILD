# Maintainer: Jonathan Sanfilippo  <jonalinux dot uk at gmail dot com>

pkgname=core-extensions-base
pkgver=1.5
pkgrel=1
pkgdesc="extensions for Core"
arch=('any')
license=('GPL')


package() {
       mkdir -p "$pkgdir/usr/share/gnome-shell/extensions"
       cp -rp  extensions "$pkgdir/usr/share/gnome-shell/"
       chmod -R 755 extensions
}
