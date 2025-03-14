<h1 align="center">Wasabi Modded</h1>
<p align="center"><img src="/assets/logo.svg" width="128"/></p>
<p align="center">Wasabi Modded is a modern and fast real-time MIDI player written in Rust.</p>
<p align="center">
<img alt="GitHub License" src="https://img.shields.io/github/license/BlackMIDIDevs/wasabi">
<img alt="GitHub Release" src="https://img.shields.io/github/v/release/BlackMIDIDevs/wasabi">
<img alt="GitHub Downloads (all assets, all releases)" src="https://img.shields.io/github/downloads/BlackMIDIDevs/wasabi/total">
</p>

## Features

- Extremely fast and optimized rendering using Vulkan
- Easy to use and configurable
- Integrated MIDI synthesizer (XSynth), alongside with KDMAPI and MIDI device support
- Partial support for Zenith color palettes

## Installation

Wasabi is a portable application and does not require an installation.
Your system must support Vulkan.

### Option A *(recommended)*

You can download and run a pre-built binary of Wasabi from the [releases page.](https://github.com/blackmidiuser/wasabi/releases/tag/v1.0-initial-release)

### Option B *(advanced)*

You can build Wasabi yourself by following these steps:

- Clone the repository using `git clone https://github.com/BlackMIDIDevs/wasabi.git` (or [download as a ZIP from GitHub](https://github.com/BlackMIDIDevs/wasabi/archive/refs/heads/master.zip))
- Make sure that the [Rust toolchain](https://rustup.rs/) and the [Vulkan SDK](https://vulkan.lunarg.com/) are both installed on your system
- Inside the project directory run the following command to build Wasabi: `cargo build --release`
    - Optionally you can add `RUSTFLAGS="-C target-cpu=native"` to your environment before compiling to optimize XSynth for your specific CPU
- After the compilation is finished, you will find the binary under `./target/release`
### Option C *(manual)
You can fork the repository by clicking on Fork, then you can customize your forked repository.
## Usage

- Before you can play a MIDI, you need to add soundfonts to the synthesizer by going to `Menu -> Settings -> SoundFonts`
- To open a MIDI, click the folder icon on the top left, or press `Ctrl+O` on your keyboard
- To play, click the play button (or press `spacebar`)
- To pause, click the pause button (or press `spacebar`)
- Find out more of shortcuts by clicking on `Shortcuts`
## Screenshot

<p align="center"><img src="/assets/screenshot.png"/></p>

## License
Wasabi is licensed under the [GNU General Public License v3.0](https://www.gnu.org/licenses/gpl-3.0.en.html#license-text).
