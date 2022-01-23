# Maintainer: Arda Atci<phystecharda@gmail.com>
pkgname=cala-config-phyOS
pkgver=1
pkgrel=1
pkgdesc="calameres config for phyOS"
arch=(x86_64)
url="git://github.com/PhyTech-R0/cala-config-phyOS"
provides=("cala-config-phyOS")
options=('zipman')
source=('git://github.com/PhyTech-R0/cala-config-phyOS')
md5sums=('SKIP')


package() {
	cd "$pkgname"
	mkdir -p $pkgdir/etc
	install -m644 -D etc/* $pkgdir/etc
}
