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
	install -dm755 "$pkgdir"/etc/calamares/{modules,branding/phyos/lang}
	install -D -m644 etc/calamares/branding/phyos/lang/* "$pkgdir/etc/calamares/branding/phyos/lang"
	install -D -m644 etc/calamares/branding/phyos/*.{desc,png,qss,qml} "$pkgdir/etc/calamares/branding/phyos/"
	install -D -m644 etc/calamares/modules/* "$pkgdir/etc/calamares/modules"
	install -D -m644 etc/calamares/settings.conf "$pkgdir/etc/calamares/"
}
