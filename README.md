<img width="1918" height="408" alt="Screenshot From 2026-10-10 19-50-09" src="https://github.com/user-attachments/assets/61204829-b280-4b4e-9e06-0b5fb761b5ce" />

# Supermium For Debian
An up-to-date Chromium-based web browser compatible with Debian 7 (Wheezy), 8 (Jessie), 9 (Stretch), 10 (Buster), 11 (Bullseye), and newer.

System Requirements

Minimum Requirement

Debian 7 (Wheezy) or higher

An Intel Pentium 4 processor or later that's SSE2 capable. Hyper-threading or dual-core recommended.

A minimum of 768 MB of RAM. 2 GB or greater is recommended for a smooth browsing experience.

Wine is Required

Recommended

• Processor (CPU): Intel Core 2 Duo / AMD Athlon 64 X2 (or any dual-core 64-bit CPU)

• Memory (RAM): 2 GB RAM (Linux will take ~500 MB, Wine needs some overhead, and Chromium requires the rest)

• Graphics (GPU): Any graphics card with OpenGL 2.1 support (integrated Intel HD graphics from 2010 onwards work fine)

• Storage: 1 GB of free space

• Operating System: Debian 12 (Bookworm) or higher and Wine 8.0 or higher

To install supermium on Wine

Install wine

For Debian 7

sudo dpkg --add-architecture i386

sudo apt-get update

sudo apt-get install wine wine-bin:i386

Download Supermium at https://www.supermium.net/

If 64-bit Setup Does not work for you. You need 32-bit Setup

Then install supermium in wine

For Debian 8 or higher

sudo dpkg --add-architecture i386

sudo apt update

sudo apt install wine wine32

Download Supermium at https://www.supermium.net/

If 64-bit Setup Does not work for you. You need 32-bit Setup

Then install supermium in wine
