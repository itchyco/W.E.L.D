# W.E.L.D
A quick functional TAP-and-Go external hard drive system. 

# STILL WORKING ON MOVING MORE STUFF TO GITHUB 

TapNAS: tap to connect, tap to unlock, tap to transfer

The pitch: A pocket-sized, battery-powered storage hub that makes moving files as easy as a contactless payment. No cables, no passwords, no setup screens.

How it works

Tap your phone on the device. An NFC tag on the case joins its private Wi-Fi hotspot instantly.
Tap your card to unlock your personal folder. The card is a blank credit-card-sized NFC card, so it feels like paying but never touches real bank data.
Drop files in or pull them out through a simple web page on the device’s own network. Nothing needs to be installed on the phone or laptop.

Features

Per-user cards: each card opens its own private space, so a team or family can share one device.
Guest drop box: a “visitor” card lets someone upload or download files without seeing anyone else’s.
Read-only cards: hand a client a card that can only download a specific project folder.
Auto-backup: your phone’s photos can sync when you tap in.
Status display: LEDs or a tiny screen show battery, storage left, and who’s connected.

Security

Cards use secure NFC chips (such as NTAG 424 DNA), which can’t be copied the way basic card IDs can.
Optional PIN on top of the tap for sensitive folders.
Storage is encrypted, so a lost device doesn’t mean lost files.

Hardware

Raspberry Pi Zero 2 W for the first version, with a Pi 4 or 5 as the faster upgrade later.
NFC sticker for the Wi-Fi tap, plus a PN532 reader for card unlock.
SD card or small SSD, a power bank or battery HAT, and a 3D-printed or off-the-shelf case.

Build phases

Phase 1: hotspot, file server, and the Wi-Fi tap sticker. This alone makes a working, demo-ready device.
Phase 2: add the card reader and per-user folders.
Phase 3: add the PIN, encryption, auto-backup, status display, and a proper case.
