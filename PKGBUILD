# Maintainer: Reily Siegel <mail@reilysiegel.com>
pkgname=whirlpool-gui-bin
pkgver=0.6.4
pkgrel=1
pkgdesc="Desktop GUI for Whirlpool by Samourai-Wallet."
arch=('x86_64')
url="https://github.com/Samourai-Wallet/whirlpool-gui/"
license=('Unlicense')
source=("https://github.com/Samourai-Wallet/whirlpool-gui/releases/download/0.6.4/whirlpool-gui_${pkgver}_amd64.deb")
sha512sums=('acb3003613dfd5478026d15a24745b41308f3fe1911ea07021ef232c2fc774858f7b336909deb71732dee16972745929a448368be8f2da7952f3dbd01266b82b')
depends=('dbus' 'glib2' 'hicolor-icon-theme' 'java-runtime' 'nss')

package(){
  # Extract package data
  tar xf data.tar.xz -C "${pkgdir}"
}
