# Heist Price Checker

OCR solution for detecting and price checking heist gems in Path of Exile. Heavily inspired by [HeistGemPricechecker](https://github.com/trevorm4/HeistGemPricechecker), this project is aimed to be more compact and easy to use.

# Requirements

- .NET 6.0 Desktop Runtime from [official Microsoft page](https://dotnet.microsoft.com/en-us/download/dotnet/6.0) (or just run executable file, you'll be warned if .NET 6.0 is missing)
- Latest [Runtime for vs2019](https://support.microsoft.com/en-us/help/2977003/the-latest-supported-visual-c-downloads) if you encounter "can not find leptonica/tesseract" errors

# How to install

Grab latest release [here](https://github.com/EpicVertigo/HeistGemPriceChecker/releases/), unzip and run `HeistGemChecker.exe`

# How to use

Press `Shift + F3` while near heist curio boxes and press `Detect gems` button. If detection was unsuccessfull - play with threshold slider and repeat. Press `Price check` to get latest prices from poe.ninja API. You can close any active window by pressing `Escape` button. You can also close program by right-clicking heist coin icon in system tray.

![App usage](data/example.png)

# TODO

- Alternative "lazy" way of detecting gems (without screenshot window and pressing buttons)
- Persistent app settings
