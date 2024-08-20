// This file is for online use.<br>

## Rules for writing a repository file:
// 1. A repository entry is one large Array (referred to as "entry") consisting of sub-arrays (referred to as "data")<br>
// e.g `[[keyword, ....], [keyword, ....], [keyword, ....], .......]`<br>
// 2. Each data must have a keyword of type `String` at it's first index which helps in identifying what the data represents.<br>
// e.g, ["name", "name of extension"] is the data giving information about "name".<br>
// Valid keywords are `name`, `version`, `sha256`, `description`, `readme`, `tags`, `thumbnail`, `download_link`<br>
// Put quotation marks ("") to make it a string, otherwise errors will occur.<br>
// 3. One repository entry must occupy only one line.<br>
// 4. Comments are supported. You can comment an entire line by placing `#` or `//` at the start of the line. Comments between or at end of line are not allowed.<br>
// 5. Links to another extension_repository file can be placed inside another extension_repository file, and it will get detected as a custom repository file.<br>

## TIPS:
// - `thumbnail` is the link you get by right clicking an image (uploaded somewhere on the internet) and selecting Copy Image Link.<br>
// - `download_link` is usually of the form `{repo}/raw/{Path of extension within repo}`<br>
// e.g, if `https://github.com/Variable-ind/Pixelorama-Extensions/blob/master/Extensions/Example.pck` is the URL path to your extension then replace "blob" with "raw"
// and the link becomes `"https://github.com/Variable-ind/Pixelorama-Extensions/raw/master/Extensions/Example.pck"`<br>

// For further help see the entries below for reference of how it's done
## Entries:

[["name", "Voxelorama"], ["version", 1.0], ["sha256", "36776ae93aeb737129a3d12225edae7767946ffbafb086ed02e30adb374ab665"], ["description", "An extension for Pixelorama that generates 3D voxel art out of 2D pixel art."], ["readme", "https://github.com/Orama-Interactive/VoxeloramaExtension/blob/main/README.md"], ["tags", "Tool", "3D"], ["thumbnail", "https://user-images.githubusercontent.com/35376950/185218214-c8356f86-00ed-4f39-b0f8-458a29d0061b.png"], ["download_link", "https://github.com/Orama-Interactive/VoxeloramaExtension/releases/download/1.0/Voxelorama.pck"]]

[["name", "LospecPaletteImporter"], ["version", "1.1.1"], ["sha256", "6a5a65f53fab8b259fbb1b4ee7f4c9115014e1618e7bad4e6b4402c2d1907635"], ["description", "A Pixelorama extension for downloading and importing palettes directly from Lospec."], ["readme", "https://github.com/OverloadedOrama/Lospec-Palette-Importer/blob/main/README.md"], ["tags", "Palettes"], ["thumbnail", "https://github.com/Variable-ind/Lospec-Palette-Importer/assets/77773850/7ac86623-c428-4409-8f81-c7406527126f"], ["download_link", "https://github.com/OverloadedOrama/Lospec-Palette-Importer/releases/download/v1.1.1/LospecPaletteImporter.pck"]]

[["name", "OpenDyslexicFont"], ["version", 1.0], ["sha256", "94096af670a5a11e7689abb21e6aebdcff14e14190df2550a1953eb4b40d32e2"], ["description", "A Pixelorama extension that sets the OpenDyslexic font as the main font of the user interface."], ["readme", "https://github.com/OverloadedOrama/OpenDyslexic-Pixelorama-Extension/blob/main/README.md"], ["tags", "Fonts"], ["download_link", "https://github.com/OverloadedOrama/OpenDyslexic-Pixelorama-Extension/releases/download/v1.0/OpenDyslexicFont.pck"]]

[["name", "ExtensionCreator"], ["version", 1.0], ["sha256", "01afccf4c39b6458572e75452585021b9001bf76519c367b665f701b72438995"], ["description", "Used as a guide by beginers for creating extensions (Open from help menu)"], ["tags", "Tutorial"], ["thumbnail", "https://user-images.githubusercontent.com/77773850/283574411-952f6032-dadb-4bab-998c-f90c236f7fe8.png"], ["download_link", "https://github.com/Variable-ind/Pixelorama-Extensions/raw/4.0/Extensions/ExtensionCreator.pck"]]

[["name", "Audia"], ["version", 1.0], ["sha256", "5543c88c2d8c026ef2b1d799294daa1a4e7966555bc3c42de4456ee6e56662ca"], ["description", "Allows to play a specific audio on a specific tag."], ["readme", "https://github.com/Variable-Interactive/Audia/blob/master/README.md"], ["tags", "UI", "Exporter", "Audio"], ["thumbnail", "https://github.com/user-attachments/assets/5e670503-5bf1-43d1-82e1-27fefc90f080"], ["download_link", "https://github.com/Variable-Interactive/Audia/releases/download/v1.0/Audia.pck"]]

[["name", "KeyDisplay"], ["version", 1.0], ["sha256", "e1a9dc360141f252e7700acaa92ffe77db53ebce38cf69d3c530b252e4d0f26a"], ["description", "Handy extension to display shortcuts for use in videos etc.)"], ["readme", "https://github.com/Variable-Interactive/KeyDisplay/blob/master/README.md"], ["tags", "UI"], ["thumbnail", "https://github.com/user-attachments/assets/de510a60-9b3b-464d-a025-c38cc8d7b09c"], ["download_link", "https://github.com/Variable-Interactive/KeyDisplay/releases/download/v1.0/KeyDisplay.pck"]]

[["name", "TimeTracking"], ["version", 0.2], ["sha256", "b15f7260040f656a2b87a8e901181f2739a403261108ec59ffc67c0811101215"], ["description", "Saves project statistics in the .pxo file (access with Help>Project Statistics)"], ["readme", "https://github.com/Variable-Interactive/TimeTracking/blob/master/README.md"], ["tags", "Analytics"], ["thumbnail", "https://github.com/user-attachments/assets/9d50f084-6e4e-4706-9f5b-682d91dfb080"], ["download_link", "https://github.com/Variable-Interactive/TimeTracking/releases/download/v0.2/TimeTracking.pck"]]

[["name", "CameraZoomer"], ["version", 0.2], ["sha256", "bf38a4df9c3face6664cd58cffed517a449c6c18ce600d9b4e00d7831493ef68"], ["description", "Lets you set precise zoom values to Canvas Preview"], ["readme", "https://github.com/Variable-Interactive/CameraZoomer/blob/master/README.md"], ["tags", "UI"], ["thumbnail", "https://github.com/user-attachments/assets/8455b398-05ee-453f-8920-aa843a562d2b"], ["download_link", "https://github.com/Variable-Interactive/CameraZoomer/releases/download/v0.2/CameraZoomer.pck"]]

[["name", "LineArt"], ["version", 0.2], ["sha256", "d67a350722fb394b3f5738b88163d83d94b1c7c4f8813761f8da8b57ce523643"], ["description", "It is an extension for pixelorama that adds a lineart shader in the effects menu"], ["readme", "https://github.com/Variable-Interactive/LineArt/blob/master/README.md"], ["tags", "Image Effect"], ["thumbnail", "https://github.com/user-attachments/assets/322c96ec-83e7-4775-9cd1-6b5bb3857d79"], ["download_link", "https://github.com/Variable-Interactive/LineArt/releases/download/v0.2/LineArt.pck"]]

// Template for adding new entry:
//[["name", ""], ["version", 0.0], ["sha256", ""], ["description", ""], ["readme", ""], ["tags", ""], ["thumbnail", ""], ["download_link", ""]]
