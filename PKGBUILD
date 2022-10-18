pkgname=ttf-minecraft
pkgver=1.008
pkgrel=3
pkgdesc='A sans-serif typeface that is pleasant to read on screens by Sorkin Type Co'
arch=('any')
url='https://fonts.google.com/specimen/Merriweather+Sans'
source=("minecraft.ttf::https://github.com/SorkinType/Merriweather-Sans/raw/${_commit}/fonts/ttfs/MerriweatherSans-Black.ttf")

package() {
  install -m 644 minecraft.ttf "${pkgdir}/usr/share/fonts/TTF/minecraft.ttf"
}