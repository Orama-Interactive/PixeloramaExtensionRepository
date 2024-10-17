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

[["name", "LospecPaletteImporter"], ["version", 1.2], ["sha256", "0d962a3638065992d721b5b5453a101083a14d9f5302b18580ba1addc26a4753"], ["description", "A Pixelorama extension for downloading and importing palettes directly from Lospec."], ["readme", "https://github.com/OverloadedOrama/Lospec-Palette-Importer/blob/main/README.md"], ["tags", "Palettes"], ["thumbnail", "https://github.com/Variable-ind/Lospec-Palette-Importer/assets/77773850/7ac86623-c428-4409-8f81-c7406527126f"], ["download_link", "https://github.com/OverloadedOrama/Lospec-Palette-Importer/releases/download/v1.2/LospecPaletteImporter.pck"]]

[["name", "OpenDyslexicFont"], ["version", 1.1], ["sha256", "c435fefd9895e3ec20a3de6728b8900dae64790dc9a7bb8048d0c803c93c5554"], ["description", "A Pixelorama extension that sets the OpenDyslexic font as the main font of the user interface."], ["readme", "https://github.com/OverloadedOrama/OpenDyslexic-Pixelorama-Extension/blob/main/README.md"], ["tags", "Fonts"], ["download_link", "https://github.com/OverloadedOrama/OpenDyslexic-Pixelorama-Extension/releases/download/v1.1/OpenDyslexicFont.pck"]]

[["name", "ExtensionCreator"], ["version", 1.3], ["sha256", "3bf7cd3298804cd06e2c805129ad76dcf2583d1fc6f8c12c9d4bbdd6ab457f3c"], ["description", "Used as a guide by beginers for creating extensions (Open from help menu)"], ["tags", "Tutorial"], ["thumbnail", "https://github.com/user-attachments/assets/44630889-3c0e-467b-85c9-5abf7045ee91"], ["download_link", "https://github.com/Variable-Interactive/ExtensionCreator/releases/download/v1.3/ExtensionCreator.pck"]]

[["name", "Audia"], ["version", 1.1], ["sha256", "4118e44b21a8415cf5b3dc792ddd82c3537378a60c0ec1a02e6ce410035d91de"], ["description", "Allows to play a specific audio on a specific tag."], ["readme", "https://github.com/Variable-Interactive/Audia/blob/master/README.md"], ["tags", "UI", "Exporter", "Audio"], ["thumbnail", "https://github.com/user-attachments/assets/5e670503-5bf1-43d1-82e1-27fefc90f080"], ["download_link", "https://github.com/Variable-Interactive/Audia/releases/download/v1.1/Audia.pck"]]

[["name", "KeyDisplay"], ["version", 1.0], ["sha256", "e1a9dc360141f252e7700acaa92ffe77db53ebce38cf69d3c530b252e4d0f26a"], ["description", "Handy extension to display shortcuts for use in videos etc.)"], ["readme", "https://github.com/Variable-Interactive/KeyDisplay/blob/master/README.md"], ["tags", "UI"], ["thumbnail", "https://github.com/user-attachments/assets/de510a60-9b3b-464d-a025-c38cc8d7b09c"], ["download_link", "https://github.com/Variable-Interactive/KeyDisplay/releases/download/v1.0/KeyDisplay.pck"]]

[["name", "TimeTracking"], ["version", 0.3], ["sha256", "a6c7405638688ded4203066b1a9d731681e18f923fe6bf046a53bccfa7580a62"], ["description", "Saves project statistics in the .pxo file (access with Help>Project Statistics)"], ["readme", "https://github.com/Variable-Interactive/TimeTracking/blob/master/README.md"], ["tags", "Analytics"], ["thumbnail", "https://github.com/user-attachments/assets/9d50f084-6e4e-4706-9f5b-682d91dfb080"], ["download_link", "https://github.com/Variable-Interactive/TimeTracking/releases/download/v0.3/TimeTracking.pck"]]

[["name", "CameraZoomer"], ["version", 0.3], ["sha256", "20e75e434cabe7226fbd04c73a13b69fec509673594a23bebfba662de62179ab"], ["description", "Lets you set precise zoom values to Canvas Preview"], ["readme", "https://github.com/Variable-Interactive/CameraZoomer/blob/master/README.md"], ["tags", "UI"], ["thumbnail", "https://github.com/user-attachments/assets/8455b398-05ee-453f-8920-aa843a562d2b"], ["download_link", "https://github.com/Variable-Interactive/CameraZoomer/releases/download/v0.3/CameraZoomer.pck"]]

[["name", "DiscordRPC"], ["version", 0.1], ["sha256", "6cdd4eb2cd6514d4e07923e5406b30a4a2e3e5880b2408ce341b12ecbe27156d"], ["description", "A Discord rich presence extension for pixelorama."], ["readme", "https://github.com/Variable-Interactive/PixeloramaDiscordRPC/blob/master/README.md"], ["tags", "Discord"], ["thumbnail", "https://github.com/user-attachments/assets/73d4c075-0166-4962-ba6f-f59c7d466c68"], ["download_link", "https://github.com/Variable-Interactive/PixeloramaDiscordRPC/releases/download/v0.1/DiscordRPC.pck"]]

[["name", "LineArt"], ["version", 0.3], ["sha256", "d91dc88f0126086b441d3fb17c3f3e29e0aba87755ba979faa018465b71ee97a"], ["description", "It is an extension for pixelorama that adds a lineart shader in the effects menu"], ["readme", "https://github.com/Variable-Interactive/LineArt/blob/master/README.md"], ["tags", "Image Effect"], ["thumbnail", "https://github.com/user-attachments/assets/322c96ec-83e7-4775-9cd1-6b5bb3857d79"], ["download_link", "https://github.com/Variable-Interactive/LineArt/releases/download/v0.3/LineArt.pck"]]

// Template for adding new entry:
//[["name", ""], ["version", 0.0], ["sha256", ""], ["description", ""], ["readme", ""], ["tags", ""], ["thumbnail", ""], ["download_link", ""]]
