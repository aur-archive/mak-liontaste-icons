# Contributor: Sergio Montesinos <sermonpe@yahoo.es>

pkgname=mak-liontaste-icons
pkgver=0.36a
pkgrel=2
pkgdesc="Icons theme inspired in OSX Lion and Faenza"
arch=('any')
url="http://kde-look.org/content/show.php/MaK-LionTaste+Icons+?content=149051"
license=('CCPL')
source=("http://ftp.desdelinux.net/mak-lion-icons/MakLionTaste.tar.gz")
md5sums=('835de8624ac21f603b6dcd7ed592c713')

build() {
  mkdir -p $pkgdir/usr/share/icons
  chmod 755 -R $pkgdir/usr/share/icons
  cd $srcdir
  tar -zxvf MakLionTaste.tar.gz -C $pkgdir/usr/share/icons
}
