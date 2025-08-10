# Maintainer: Your Name <your.email@example.com>
pkgname=hello
pkgver=1.0
pkgrel=1
pkgdesc="Hello world"
arch=('x86_64')
url=""
license=('GPL')
depends=()
makedepends=('gcc')
source=("hello.c")
md5sums=('SKIP')

build() {
    gcc -o hello hello.c
}

package() {
    install -Dm755 hello "$pkgdir/usr/bin/hello"
}

