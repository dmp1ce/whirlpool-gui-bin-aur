# Maintainer: Reily Siegel <mail@reilysiegel.com>
pkgname=whirlpool-gui-bin
pkgver=0.6.4
pkgrel=1
pkgdesc="Desktop GUI for Whirlpool by Samourai-Wallet."
arch=('x86_64')
url="https://github.com/Samourai-Wallet/whirlpool-gui/"
license=('custom:Unlicense')
depends=('dbus' 'glib2' 'hicolor-icon-theme' 'java-runtime' 'nss')
source=("https://github.com/Samourai-Wallet/whirlpool-gui/releases/download/0.6.4/whirlpool-gui_${pkgver}_amd64.deb"
       LICENSE)
sha512sums=('acb3003613dfd5478026d15a24745b41308f3fe1911ea07021ef232c2fc774858f7b336909deb71732dee16972745929a448368be8f2da7952f3dbd01266b82b'
            '1427d76a84c4b09822d080004864f880e326b9d4605797f5b662789c8857615c72014540338cedb694a69e6c4af1af3aa6fbf448ee1a54ba8edccd604b732ec2')

package(){
  # Extract package data
  tar xf data.tar.xz -C "${pkgdir}"

  # Install LICENSE
  mkdir -p "$pkgdir/usr/share/licenses/$pkgname"
  install -Dm644 LICENSE "$pkgdir/usr/share/licenses/$pkgname/LICENSE"
}
