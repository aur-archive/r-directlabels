# Maintainer: Tobias Neumann <mail at tobias dash neumann dot eu>
# Contributor: Nick B <Shirakawasuna at gmail _dot_com>

pkgname=r-directlabels
pkgver=2.9
pkgrel=2
pkgdesc="Direct labels for multicolor plots in lattice or ggplot2"
arch=('i686' 'x86_64')
url="http://cran.r-project.org/web/packages/directlabels/index.html"
license=("GPL3")
depends=('r')
source=(http://cran.r-project.org/src/contrib/directlabels_${pkgver}.tar.gz)

package() {
 mkdir -p $pkgdir/usr/lib/R/library
 cd $srcdir
 R CMD INSTALL -l $pkgdir/usr/lib/R/library ./directlabels
}

md5sums=('97fd631eb849e41048cdc77ac391d791')
