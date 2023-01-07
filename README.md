# foobar2k-configs

## Introduction

Rather basic configurations and customizations for Foobar2000

Looks like this...

> The app has $< 1$ opacity so that's my desktop wallpaper which is not included in the configs.

<img width="1920" alt="image" src="https://user-images.githubusercontent.com/37283437/211133539-50f52a38-17a4-4066-9698-0c6da10a25bd.png">

## Usage

One-liner script for PowerShell (Requires `git` installed)

```powershell
git clone https://github.com/aaanh/foobar2k-configs.git; Copy-Item -Recurse foobar2k-configs\* %APPDATA%\foobar2000\
```

Manually

1. Download or clone this repository or the release source file
1. Copy all of its content, barring this `README.md` file
1. Open Explorer and navigate to `%APPDATA%\foobar2000` on the address bar
    1. (<kbd>Win + R</kbd> &rightarrow; `%APPDATA%\foobar2000` &rightarrow; <kbd>Enter</kbd>)
1. Paste in there and overwrite everything
