<h1 align="center">
  <img src="https://raw.githubusercontent.com/GreemDev/Ryujinx/master/distribution/misc/Logo.svg" alt="Ryujinx" width="150"></a>
  <br>
  <b>Ryujinx</b>
  <br>
  <sub><sup><b>(REE-YOU-JINX)</b></sup></sub>
  <br>
  <a href="https://github.com/GreemDev/Ryujinx/actions/workflows/release.yml">
     <img src="https://github.com/GreemDev/Ryujinx/actions/workflows/release.yml/badge.svg"
            alt="Build Status">
  </a>
  <a href="https://github.com/GreemDev/Ryujinx/releases/latest">
      <img src="https://img.shields.io/github/v/release/GreemDev/Ryujinx"
            alt="Latest Release">
  </a>
  <a href="https://discord.gg/dHPrkBkkyA">
      <img src="https://img.shields.io/discord/1294443224030511104?color=5865F2&label=Ryubing&logo=discord&logoColor=white"
            alt="Discord Server Invite">
  </a>
</h1>

<p align="center">
  Ryujinx is an open-source Nintendo Switch emulator originally created by gdkchan, written in C#. It aims at providing excellent accuracy and performance, a user-friendly interface and consistent builds.
  <br />
  <br />
  It was written from scratch and development on the project began in September 2017.
  Ryujinx is available under the <a href="./LICENSE.txt" target="_blank">MIT license</a>.
</p>

<p align="center">
    <img src="https://raw.githubusercontent.com/GreemDev/Ryujinx/refs/heads/master/docs/shell.png">
</p>

---
On October 1st 2024, Ryujinx was discontinued as the creator was forced to abandon the project.

This fork is intended to be a QoL uplift for existing Ryujinx users. This is **not a Ryujinx revival project** and **not a Phoenix project**.

If you would like a more preservative fork of Ryujinx, check out <a href="https://github.com/ryujinx-mirror/ryujinx">ryujinx-mirror</a>.

## Documentation 

Refer to the [wiki](https://github.com/GreemDev/Ryujinx/wiki) for the documentation, including how to setup Ryujinx, change settings, and more.

## Compatibility

As of May 2024, Ryujinx has been tested on approximately **4,300** titles;
over **4,100** boot past menus and into gameplay, with roughly **3,550** of those being considered playable.

New game tests are not accepted at this time.

## Usage

To run this emulator, your device must be equipped with at least **8GiB of RAM**. Failing to meet this requirement may result in a poor gameplay experience or unexpected crashes.

## Building

Install version **8.0.10 or higher** of the [.NET SDK](https://dotnet.microsoft.com/download/dotnet).
You will also need to install Git for your platform if it is not already installed.

Clone and navigate into the repository using these commands,
```bat
git clone https://github.com/GreemDev/Ryujinx
cd Ryujinx
```

Then, build the project using the .NET SDK:
```bat
dotnet build -c Release -o build`
```
The built files will be found in the newly created build directory.

## License

This software is licensed under the terms of the [MIT license](LICENSE.txt).
This project makes use of code authored by the libvpx project, licensed under BSD and the ffmpeg project, licensed under LGPLv3.
See [LICENSE](LICENSE.txt) and [THIRDPARTY](distribution/legal/THIRDPARTY.md) for more details.

## Credits

- [LibHac](https://github.com/Thealexbarney/LibHac) is used for our file-system.
- [AmiiboAPI](https://www.amiiboapi.com) is used in our Amiibo emulation.
- [ldn_mitm](https://github.com/spacemeowx2/ldn_mitm) is used for one of our available multiplayer modes.
- [ShellLink](https://github.com/securifybv/ShellLink) is used for Windows shortcut generation.
