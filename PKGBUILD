# Maintainer: Your mama
pkgname=hello
pkgver=1.0
pkgrel=1
pkgdesc="Hello world"
arch=('x86_64')
url=""
license=('GPL')
depends=()
makedepends=('gcc')

build() {
    cd "$srcdir"
    gcc -o hello hello.c
}

package() {
    install -Dm755 hello "$pkgdir/usr/bin/hello"
}