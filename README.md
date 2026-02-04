
# WinRAR_AppImage

 - WinRAR + Wine

WinRAR is a file archiver and compression utility for Microsoft Windows.

https://www.win-rar.com/

## Repository: https://github.com/ryuuzaki42/WinRAR_AppImage
     WinRAR: 7.20

---
### To change font size, change the DPI value in LogPixels.
In the user.reg in `~/.config/WinRAR_AppImage/user.reg`

At the end of block `[Control Panel\\Desktop]`

### Added LogPixels with desire value

#### To 100% text size
`"LogPixels"=dword:00000060`

#### To 125% text size
`"LogPixels"=dword:00000090`

#### To 150% text size
`"LogPixels"=dword:000000144`

---
https://www.win-rar.com/download.html
