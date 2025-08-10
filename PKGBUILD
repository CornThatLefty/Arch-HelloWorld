# Maintainer: Your Name <your.email@example.com>
pkgname=hello
pkgver=1.0
pkgrel=1
pkgdesc="A simple Hello, World! program"
arch=('x86_64')
url="https://example.com/hello"  # Change to your program's URL, if applicable
license=('GPL')
depends=()
makedepends=('gcc')
source=("hello.c")
md5sums=('SKIP')  # No need for an MD5 checksum since we're compiling from source

build() {
    # Compile the source code
    gcc -o hello hello.c
}

package() {
    # Install the compiled binary to $pkgdir
    install -Dm755 hello "$pkgdir/usr/bin/hello"
    # Optional: If you have a desktop entry or other files, include them here.
    # install -Dm644 hello.desktop "$pkgdir/usr/share/applications/hello.desktop"
}

