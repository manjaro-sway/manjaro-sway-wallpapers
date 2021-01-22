# Maintainer: Jonas Strassel <info@jonas-strassel.de>
pkgname="manjaro-sway-wallpapers"
pkgver=1.0.0
pkgrel=0
pkgdesc="Set of manjaro-related wallpapers"
arch=('any')
url="https://github.com/Manjaro-Sway/manjaro-sway-wallpapers"
license=('MIT')
source=(
    "https://raw.githubusercontent.com/AndreVallestero/sway-art/a94162ed4c2a94354dd6de26567924ba1c3e3a8c/manjaro-sway-small-wallpaper-3840x2160.png"
    "https://raw.githubusercontent.com/AndreVallestero/sway-art/a94162ed4c2a94354dd6de26567924ba1c3e3a8c/manjaro-sway-small-wallpaper-edged-3840x2160.png"
    "https://raw.githubusercontent.com/AndreVallestero/sway-art/a94162ed4c2a94354dd6de26567924ba1c3e3a8c/manjaro-sway-wallpaper-3840x2160.png"
    "https://raw.githubusercontent.com/Manjaro-Sway/manjaro-sway-wallpapers/c9c318a5cc2aee63b5f817cd7a64d9709cae567f/static/gruvbox-dark-manjarosway-3840x2160.png"
    "https://raw.githubusercontent.com/Manjaro-Sway/manjaro-sway-wallpapers/c9c318a5cc2aee63b5f817cd7a64d9709cae567f/static/gruvbox-light-manjarosway-3840x2160.png"
)
md5sums=(
    '30c6e74280fed39ebdb23dc885c68bc1'
    '7d30d981a697535a8927f88e5f4df41f'
    'cc372e11f3e90eeb2c2d4f22deb3933e'
    '4daa396f04a199f5bab8e026e7718c18'
    'f8a52fbb2bd99f2b63924ab883a14fbf'
)

package() {
    install -d $pkgdir/usr/share/backgrounds/manjaro-sway
    cp -r *.png "${pkgdir}/usr/share/backgrounds/manjaro-sway"
}