
# So Serene...


Serene is a portable set of pre-configured software for generative artists.

Now contains:
- [Stable Diffusion WebUI by AUTOMATIC111111](https://github.com/AUTOMATIC1111/stable-diffusion-webui).

System Requirements:
- At least:
  - Windows,
  - 15 GB of free space.
- For comfortable use:
  - Windows 10 or 11,
  - NVidia GeForce RTX-3060 12GB or more of VRAM,
  - SSD with 100GB of free space.

Based on [Stable Diffusion Portable](https://github.com/serpotapov/stable-diffusion-portable).



## Installation


1. Download [Serene archive file](https://github.com/okeangel/serene/archive/refs/heads/main.zip).
2. Unzip the `serene-main` folder to any convenient location. The root directory on the SSD is preferred, and the path should not contain spaces or Cyrillic characters. For example: `C:\Apps\serene` or `%UserProfile%\serene`.
3. Run the `webui-user-first-run.cmd` command to start the deployment. This may take a few minutes. Wait for the process to complete.

You will end up with a folder containing everything you need: software, models, settings. It can be moved to any location that meets your system requirements. Reconfiguration is not required.

Once the installation is complete, an interface tab will automatically open in your browser. You can start generating immediately.

When finished, close both the browser tab and the terminal window.



## Filling with assets


When the `models` folder appears (when cmd is running), place any model (e.g. [Deliberate](https://huggingface.co/XpucT/Deliberate/resolve/main/Deliberate_v2.safetensors)) in the `models\Stable-diffusion` directory. An example of the full path is `C:\Apps\serene\models\Stable-diffusion\Deliberate_v2.safetensors`.

Folders can be populated with new assets on the fly.



## Usage


The Stable Diffusion WebUI can be started using the `webui-user.bat` file.

When finished, close both the browser tab and the terminal window.
