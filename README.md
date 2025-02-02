<div align="center">

# Upscayl 🆙

#### Free and Open Source AI Image Upscaler

https://user-images.githubusercontent.com/25067102/186332548-0d53f02f-d159-4804-8b0e-887d96651fdb.mp4

**Upscayl is a cross-platform application built with the Linux-first philosophy. This means that we prioritize Linux builds over others but that doesn't mean we'll break things for other OSes :)**

> Upscayl does not work without a GPU, sorry. You'll need a Vulkan compatible GPU to upscale images.

</div>

# Installation 👨‍💻

## Linux 🐧

1. Go to [releases section](https://github.com/TGS963/upscayl/releases/latest)

2. Download the `.AppImage` file.

3. Right Click AppImage -> Go to Permissions tab -> Check allow file to execute and then double click the file to run Upscayl.

You can also download the flatpak version and double click the flatpak file to install via Store but wait for the full release, we'll be pushing it to Flathub for easy access.

## MacOS 🍎

Coming soon...

## Windows 🐌

Coming soon...

# Roadmap 🤫

- Allow video upscaling
- 2x, 3x upscaling modes
- More models
- Make the whole world use FOSS

# Development 🛠

```
git clone https://github.com/TGS963/upscayl
cd upscayl

# INSTALL DEPENDENCIES
npm install

# RUN THE DEVELOPMENT SERVER LOCALLY
npm run start

# PACKAGE THE APP
npm run dist

# PUBLISH THE APP, MAKE SURE TO ADD GH_TOKEN= IN SHELL
npm run publish-app
```

# Credits ❤

- Real-ESRGAN for their wonderful research work.\
[Real-ESRGAN: Copyright (c) 2021, Xintao Wang](https://github.com/xinntao/Real-ESRGAN/)

- Microsoft™ for their Fluent Emoji used as our logo.

#

<div align="center">

Copyright © 2022 - **Upscayl**\
Made by Nayam Amarshe and TGS963\
using 🖱 & ⌨

</div>
