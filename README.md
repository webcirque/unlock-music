# Unlock Music
- Unlock encrypted music files inside browsers. 
- The project "unlock-music" is created with the purpose of learning of researching. Any modification and redistribution must obey the [license](https://github.com/ix64/unlock-music/blob/master/LICENSE).
- Demo is no longer provided considering underlying legal disputes and abuse. CLI version of unlock-music is under development.
- [Other beta tools](https://github.com/ix64/unlock-music/wiki/%E5%85%B6%E4%BB%96%E9%9F%B3%E4%B9%90%E6%A0%BC%E5%BC%8F%E5%B7%A5%E5%85%B7)
    
[![Build Status](https://ci.ixarea.com/api/badges/ix64/unlock-music/status.svg)](https://ci.ixarea.com/ix64/unlock-music)

# Features
## Supported formats
- [x] QQMusic common formats (.qmc0/.qmc2/.qmc3/.qmcflac/.qmcogg/[.tkm](https://github.com/ix64/unlock-music/issues/9))
- [x] MooMusic common formats ([.bkcmp3/.bkcflac](https://github.com/ix64/unlock-music/issues/11))
- [x] QQMusic Tm formats (.tm0/.tm2/.tm3/.tm6)
- [x] New QQMusic formats (experimental support)
    - [x] .mflac 
    - [x] [.mgg](https://github.com/ix64/unlock-music/issues/3)
- [x] Netease Cloud Music format (.ncm)
    - [x] Automatically adds ID3 metadata to the decrypted file.
- [x] Xiami Music format (.xm) (β phase)
- [x] Kuwo Music format (.kwm) (β phase)
- [x] Kugou Music format (.kgm) ([α phase](https://github.com/ix64/unlock-music/wiki/%E5%85%B6%E4%BB%96%E9%9F%B3%E4%B9%90%E6%A0%BC%E5%BC%8F%E5%B7%A5%E5%85%B7#%E9%85%B7%E7%8B%97%E9%9F%B3%E4%B9%90-kgmvpr%E8%A7%A3%E9%94%81%E5%B7%A5%E5%85%B7))

## Other features
- [x] Decrypt inside browsers
- [x] Drag-and-drop(inside PWA)
- [x] Play on the go(inside PWA)
- [x] Batch decryption(inside PWA)
- [x] PWA
- [x] Multi-threaded


# Usage
## Use builds
- Get builds from [GitHub Release](https://github.com/ix64/unlock-music/releases/latest).
- Decompress before deploying or using.（**DO NOT RUN SOURCE CODE DIRECTLY**）

## Build requirements
- Environment
    - nodejs
    - npm
1. Install dependencies with command `npm install` after fetching source code.
2. Build with command `npm run build`, then builds will show up in the `dist` directory.
- Command `npm run serve` can be used while developing.
