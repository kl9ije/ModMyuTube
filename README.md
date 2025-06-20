# ModMyuTube
This script allows you to apply mods to an original YouTube IPA file.
> [!WARNING]  
> For legal reasons we do **not** provide the original YouTube IPA, you should search for it by yourself. Without the IPA you can't use this script.
## How does it work?
> [!NOTE]  
> This script uses [YTLite](https://github.com/dayanch96/YTLite) as main mod. Credits of the other mods are included below. Give the repo a star, it's really cool.

The script decompresses the original YouTube IPA file, applies the mods, and then recompresses it into a new IPA file using the `cyan` tool.
## Requirements
- `cyan` tool: This tool is used to compress the modified files back into an IPA file.
- `requests` library: This library is used to download  the mods.
- `tk` library: This library is used to select the IPA using a fancy GUI.
- `make` tool: This tool is used to build the final IPA file and the mods.
## Installation
> [!WARNING]  
> Windows is **not supported**. If you want to use the script on Windows you should install WSL (Windows Subsystem for Linux) and run the script from there.

Run these commands on your terminal
### Linux
```
sudo apt update
sudo apt install build-essential
sudo apt install python3-pip python3-tk
python3 -m pip install --user pipx
python3 -m pipx ensurepath
pipx install cyan
pip install requests
```
### MacOS
```
xcode-select --install
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
brew install python
brew install pipx
python3 -m pip install --user pipx
python3 -m pipx ensurepath
pipx install cyan
pip install requests
```
After installing the requirements you can use `python3 modmyutube.py` to run the script.
## Included mods
<details>
  <summary>YouPiP</summary>
  <p>YouPiP is a tweak developed by <a href="https://github.com/PoomSmart">PoomSmart</a> that enables the native Picture-in-Picture feature for videos in the iOS YouTube app.</p>
  <p>Source code and additional information are available <a href="https://github.com/PoomSmart/YouPiP">in its GitHub repository</a>.</p>
</details>

<details>
  <summary>YTUHD</summary>
  <p>YTUHD is a tweak developed by <a href="https://github.com/PoomSmart">PoomSmart</a> that unlocks 1440p (2K) and 2160p (4K) resolutions in the iOS YouTube app.</p>
  <p>Source code and additional information are available <a href="https://github.com/PoomSmart/YTUHD">in PoomSmart's GitHub repository</a>.</p>
</details>

<details>
  <summary>Return YouTube Dislikes</summary>
  <p>Return YouTube Dislikes is a tweak developed by <a href="https://github.com/PoomSmart">PoomSmart</a> that brings back dislikes on the YouTube app.</p>
  <p>Source code and additional information are available <a href="https://github.com/PoomSmart/Return-YouTube-Dislikes">in PoomSmart's GitHub repository</a>.</p>
</details>

<details>
  <summary>YouQuality</summary>
  <p>YouQuality is a tweak developed by <a href="https://github.com/PoomSmart">PoomSmart</a> that allows to view and change video quality directly from the video overlay.</p>
  <p>Source code and additional information are available <a href="https://github.com/PoomSmart/YouQuality">in PoomSmart's GitHub repository</a>.</p>
</details>

<details>
  <summary>DontEatMyContent</summary>
  <p>DontEatMyContent is a tweak developed by <a href="https://github.com/therealFoxster">therealFoxster</a> that prevents the Notch/Dynamic Island from munching on 2:1 video content in the iOS YouTube app.</p>
  <p>Source code and additional information are available <a href="https://github.com/therealFoxster/DontEatMyContent">in therealFoxster's GitHub repository</a>.</p>
</details>