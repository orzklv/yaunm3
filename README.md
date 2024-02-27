<header>
<p align="center">
  <img src="./.github/assets/header.png" alt="header picture">
</p>
<h1 align="center">Yaunm3</h1>
<p align="center">Repository to maintain personal flipper zero "Yaunm3". I keep copy of latest firmware and personal patches & modifications for firmware. Also repo includes personal applications and additions I wrote for Flipper.</p>
</header>

# Components

- [Firmware](./firmware) - Automatically fetched latest version of official firmware. Branch can be changed [here](https://github.com/orzklv/yaunm3/blob/e2ee36a0c8a842d2a40cff41a1dae39ab97ab18e/.github/workflows/update.yml#L34C16-L34C28)

# Documentation & Resources

After doing many researches, I came to conclusion that 

# Development

As you know, Flipper Zero is all about IoT stuff and it requires moderate C programming skills. Indeed, I'm using CMake and Clang for development and leave production release to [ufbt](https://github.com/flipperdevices/flipperzero-ufbt) "the official micro build tool by Flipper".  

> [!IMPORTANT]
> <img src="./.github/assets/animation.gif" alt="">
> 
> If you run into issues while compiling & running, please consider leaving issues on this repository. Would be glad to work on them together. 