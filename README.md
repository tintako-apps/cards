<img src="icon.svg" width="128" alt="Cards icon">

# Cards

An offline wallet for static barcodes, made for E Ink: loyalty, library, gym and club cards. Your cards sit in one stack showing only their names; tap one to bring its code to the front. Until version 1.0.6 the app was called Wallet; the repository was renamed from `wallet` to `cards` with version 1.1.

[![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/tintako)

## What it can do

- **Add cards** with the camera, from an image (PNG, JPEG, WebP) or by typing them in
- **Show real codes** drawn sharply for E Ink, in pure black and white
- **Manage cards:** edit, move up or down, delete and search by name
- **Add details:** subtitle, category, notes and expiry date
- **Handle many cards:** the stack is paged, and the volume keys turn pages
- **Favourites:** mark up to 4 cards with a heart; on Tintako Launcher they appear in the Quick cards widget, by name only
- **Flashlight** in the scanner for dark places

**Read and display (13 formats):** QR Code, Aztec, PDF417, Data Matrix, Code 128, Code 39, Code 93, EAN-8, EAN-13, UPC-A, UPC-E, ITF, Codabar

**Read only:** GS1 DataBar, GS1 DataBar Expanded, MaxiCode. These are saved as a value, or as the original image crop when imported from an image.

**Languages:** Croatian, English, German, French, Spanish, Italian, Portuguese, Dutch, Polish, Czech. The app name follows the phone's language (Kartice, Cards, Karten, Cartes, Tarjetas, Carte, Cartões, Kaarten, Karty).

## Permissions

- **Camera:** to read a card's code. The app offers it once, the first time you scan; you can also turn it on in Settings › General. Camera images are used only to read the code and are never saved.

## Privacy

- Fully offline: the app has no internet permission
- Every card is encrypted on the phone with AES-256-GCM
- No account, no analytics, no ads
- Screenshot protection is on by default
- The Quick cards widget on Tintako Launcher shows only the names of your favourite cards, never a number or code; no other app can read them
- Details: [PRIVACY.md](PRIVACY.md) · [TERMS.md](TERMS.md) · [LICENSES.md](LICENSES.md)

## Good to know

- Cards shows static codes only. It doesn't support payment cards, NFC or rotating codes
- Not every shop scanner reads codes from a screen

## Install

Download the latest APK from [Releases](../../releases/latest) and install it on your device. It installs over Wallet, and your cards stay.

Made by Tintako · app@tintako.com
