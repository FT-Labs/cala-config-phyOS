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
	install -dm755 "$pkgdir"/etc/calamares/{modules,branding/archlinuxgui/lang}
	install -D -m644 etc/calamares/branding/archlinuxgui/lang/* "$pkgdir/etc/calamares/branding/archlinuxgui/lang"
	install -D -m644 etc/calamares/branding/archlinuxgui/.* "$pkgdir/etc/calamares/branding/archlinuxgui/"
	install -D -m644 etc/calamares/modules/* "$pkgdir/etc/calamares/modules"
	install -D -m755 etc/calamares/launch.sh "$pkgdir/etc/calamares/"
	install -D -m644 etc/calamares/settings.conf "$pkgdir/etc/calamares/"
}
