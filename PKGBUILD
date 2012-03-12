# Maintainer: Kaiting Chen <kaitocracy@gmail.com>

pkgdesc="`cat README`"
url='http://github.com/kaitocracy/Kiwilight-Tools'

pkgname='kwtool'
pkgver='0.0.2'
pkgrel='1'
arch=('any')
license=()
depends=('heimdal' 'expat' 'ca-certificates')
source=('kadlist' 'kchmail' 'kchlpk' 'kchshell')
md5sums=('c097a547d32381888aa2e24d92fc6339'
         '5788f1289a0c2b62c6b4a588bb078ac5'
         '370073c8f926e343b81d5cd9a1c9528e'
         '7fb14c1726aee31d629e031ba89e455a')

build() {
  install -Dm755 $srcdir/kadlist  $pkgdir/usr/sbin/kadlist
  install -Dm755 $srcdir/kchmail  $pkgdir/usr/bin/kchmail
  install -Dm755 $srcdir/kchlpk   $pkgdir/usr/bin/kchlpk
  install -Dm755 $srcdir/kchshell $pkgdir/usr/bin/kchshell
}
