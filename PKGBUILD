#
# Maintainer: Mahmoud Mohamed (00xWolf) <mmsaeed509@gmail.com> , <https://github.com/mmsaeed509>
#

pkgname=exodia-cursors
pkgver=1.0
pkgrel=4
pkgdesc="Cursors For Exodia OS"
arch=('any')
url="https://github.com/Exodia-OS/exodia-cursors"
license=('GPL3')
groups=("exodia-artworks")

prepare() {

	cp -af ../cursor/. ${srcdir}

}

package() {

	local cursor_dir=${pkgdir}/usr/share/icons
	mkdir -p "$cursor_dir"
	cp -r ${srcdir}/* "$cursor_dir"

}
