# Maintainer: Katherine J. Cumberbatch <stykers@stykers.moe>
pkgname=binfmt-qemu
pkgver=20190725
pkgrel=1
pkgdesc="Register qemu interpreters for various binary formats"
arch=('any')
url="http://www.freedesktop.org/software/systemd/man/binfmt.d.html"
license=('GPL')
optdepends=('qemu-user')
source=("qemu.conf")
md5sums=('33d994fc2569b7f92b38fa935fcd6edf')

package() {
  install -Dm 644 "$srcdir/qemu.conf" "$pkgdir/usr/lib/binfmt.d/qemu.conf"
}

# vim:set ts=2 sw=2 et:
