# Maintainer: Bouteiller a2n Alan <a2n.dev@pm.me>
pkgname=postier
pkgver=1.1.0
pkgrel=1
pkgdesc="Fully free & open-source API client"
arch=('x86_64')
url="https://github.com/bouteillerAlan/postier"
license=('GPL')
depends=('cairo' 'desktop-file-utils' 'gdk-pixbuf2' 'glib2' 'gtk3' 'hicolor-icon-theme' 'libsoup3' 'pango' 'webkit2gtk-4.1')
options=('!strip' '!emptydirs')
install=${pkgname}.install
source_x86_64=("${url}/releases/download/v1.2.0-beta/Postier_"${pkgver}"_amd64.deb")
sha256sums_x86_64=('bf90904e07bcf3afd938093a55e5f9ca72120dcd85d111069419624914d67a19')
package() {
  # Extract package data
  tar -xz -f data.tar.gz -C "${pkgdir}"
}
