# Packer: <csgeek@esamir.com> 

pkgname=activemq-cpp-library
pkgver=3.4.0
pkgrel=1
pkgdesc="CMS is a JMS-like API for C++ for interfacing with Message Brokers such as Apache ActiveMQ."
arch=('i686' 'x86_64')
license=('Apache 2.0')
url="http://activemq.apache.org/cms/"
depends=('autoconf' 'apr-util' )
makedepends=('')
optdepends=()
options=()
provides=('activemq-cpp-library')
conflicts=('activemq-cpp-library')
source=(http://mirror.atlanticmetro.net/apache//activemq/activemq-cpp/source/${pkgname}-${pkgver}-src.tar.gz)
md5sums=('1e476bb5e8b98d095c0ac917ebd31026')



build() 
{
  cd ${pkgname}-${pkgver}
  ./configure
  make
  make DESTDIR=${pkgdir} install
}
