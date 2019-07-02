# Maintainer: Reily Siegel <mail@reilysiegel.com>
pkgname=whirlpool-gui-bin
pkgver=0.7.0
pkgrel=1
pkgdesc="Desktop GUI for Whirlpool by Samourai-Wallet."
arch=('x86_64')
url="https://github.com/Samourai-Wallet/whirlpool-gui/"
license=('custom:Unlicense')
depends=('dbus' 'glib2' 'hicolor-icon-theme' 'java-runtime' 'nss')
source=("https://github.com/Samourai-Wallet/whirlpool-gui/releases/download/${pkgver}/whirlpool-gui_${pkgver}_amd64.deb"
       LICENSE)
sha512sums=('9af8cdbad7b49563b95a54a3ccdbadef1ff27fbf6a48a16639f5bc5381d8db7dee1d52937f7f9c015aca56b5e619432fc22e94cd11812980a11e5c18ea17f399'
            '1427d76a84c4b09822d080004864f880e326b9d4605797f5b662789c8857615c72014540338cedb694a69e6c4af1af3aa6fbf448ee1a54ba8edccd604b732ec2')

package(){
  # Extract package data
  tar xf data.tar.xz -C "${pkgdir}"

  # Install LICENSE
  mkdir -p "$pkgdir/usr/share/licenses/$pkgname"
  install -Dm644 LICENSE "$pkgdir/usr/share/licenses/$pkgname/LICENSE"
}
