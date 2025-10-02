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

[["name", "Voxelorama"], ["version", 1.1], ["sha256", "ea82e675097e8c0d08b39695c19a767a368d5c269b14192127482647d355072c"], ["description", "An extension for Pixelorama that generates 3D voxel art out of 2D pixel art."], ["readme", "https://github.com/Orama-Interactive/VoxeloramaExtension/blob/main/README.md"], ["tags", "Tool", "3D"], ["thumbnail", "https://user-images.githubusercontent.com/35376950/185218214-c8356f86-00ed-4f39-b0f8-458a29d0061b.png"], ["download_link", "https://github.com/Orama-Interactive/VoxeloramaExtension/releases/download/v1.1/Voxelorama.pck"]]

[["name", "LospecPaletteImporter"], ["version", 1.2], ["sha256", "0d962a3638065992d721b5b5453a101083a14d9f5302b18580ba1addc26a4753"], ["description", "A Pixelorama extension for downloading and importing palettes directly from Lospec."], ["readme", "https://github.com/OverloadedOrama/Lospec-Palette-Importer/blob/main/README.md"], ["tags", "Palettes"], ["thumbnail", "https://github.com/Variable-ind/Lospec-Palette-Importer/assets/77773850/7ac86623-c428-4409-8f81-c7406527126f"], ["download_link", "https://github.com/OverloadedOrama/Lospec-Palette-Importer/releases/download/v1.2/LospecPaletteImporter.pck"]]

[["name", "OpenDyslexicFont"], ["version", 1.1], ["sha256", "c435fefd9895e3ec20a3de6728b8900dae64790dc9a7bb8048d0c803c93c5554"], ["description", "A Pixelorama extension that sets the OpenDyslexic font as the main font of the user interface."], ["readme", "https://github.com/OverloadedOrama/OpenDyslexic-Pixelorama-Extension/blob/main/README.md"], ["tags", "Fonts"], ["download_link", "https://github.com/OverloadedOrama/OpenDyslexic-Pixelorama-Extension/releases/download/v1.1/OpenDyslexicFont.pck"]]

[["name", "ColorChecker"], ["version", 0.1], ["sha256", "7d71c7d8edb6bce2e6632c06b3d93ff84f2d37ee76fcf78babecf760157d0ba9"], ["description", "An extension for assistance in matching colors while choosing a new color"], ["readme", "https://github.com/Variable-Interactive/PixeloramaColorChecker/blob/master/README.md"], ["thumbnail", "https://github.com/user-attachments/assets/46e34f56-9e07-4472-bf42-ac68c4638617"], ["tags", "UI", "Palettes"], ["download_link", "https://github.com/Variable-Interactive/PixeloramaColorChecker/releases/download/v0.1/ColorChecker.pck"]]

[["name", "ExtensionCreator"], ["version", 1.5], ["sha256", "26b58b2b18e6b2f9dcb4c60cbee527cb5217bcb0b595bbaf0ed1d3c28f0a09d2"], ["description", "Used as a guide by beginers for creating extensions (Open from help menu)"], ["tags", "Tutorial"], ["thumbnail", "https://github.com/user-attachments/assets/44630889-3c0e-467b-85c9-5abf7045ee91"], ["download_link", "https://github.com/Variable-Interactive/ExtensionCreator/releases/download/v1.5/ExtensionCreator.pck"]]

[["name", "QuickDocs"], ["version", 0.3], ["sha256", "32405d8c4d07ff9df301f3080ec6303c9cb0906f4309e56db0b7bb341f458d8b"], ["description", "Provides a way to communicate to the docs from within the editor."], ["readme", "https://github.com/Variable-Interactive/QuickDocks/blob/master/README.md"], ["tags", "Tutorial"], ["thumbnail", "https://github.com/user-attachments/assets/e374093f-879c-490e-8ebc-c2a44677d9cf"], ["download_link", "https://github.com/Variable-Interactive/QuickDocks/releases/download/v0.3/QuickDocs.pck"]]

[["name", "KeyDisplay"], ["version", 1.0], ["sha256", "e1a9dc360141f252e7700acaa92ffe77db53ebce38cf69d3c530b252e4d0f26a"], ["description", "Handy extension to display shortcuts for use in videos etc.)"], ["readme", "https://github.com/Variable-Interactive/KeyDisplay/blob/master/README.md"], ["tags", "UI"], ["thumbnail", "https://github.com/user-attachments/assets/de510a60-9b3b-464d-a025-c38cc8d7b09c"], ["download_link", "https://github.com/Variable-Interactive/KeyDisplay/releases/download/v1.0/KeyDisplay.pck"]]

[["name", "TimeTracking"], ["version", 0.4], ["sha256", "aa340b72e1eb65590214c4964b107d23e7b83e3c0b1ec21dd09f8de97e1849eb"], ["description", "Saves project statistics in the .pxo file (access with Project>Project Statistics)"], ["readme", "https://github.com/Variable-Interactive/TimeTracking/blob/master/README.md"], ["tags", "Analytics"], ["thumbnail", "https://github.com/user-attachments/assets/9d50f084-6e4e-4706-9f5b-682d91dfb080"], ["download_link", "https://github.com/Variable-Interactive/TimeTracking/releases/download/v0.4/TimeTracking.pck"]]

[["name", "CameraZoomer"], ["version", 0.3], ["sha256", "20e75e434cabe7226fbd04c73a13b69fec509673594a23bebfba662de62179ab"], ["description", "Lets you set precise zoom values to Canvas Preview"], ["readme", "https://github.com/Variable-Interactive/CameraZoomer/blob/master/README.md"], ["tags", "UI"], ["thumbnail", "https://github.com/user-attachments/assets/8455b398-05ee-453f-8920-aa843a562d2b"], ["download_link", "https://github.com/Variable-Interactive/CameraZoomer/releases/download/v0.3/CameraZoomer.pck"]]

[["name", "DiscordRPC"], ["version", 0.1], ["sha256", "6cdd4eb2cd6514d4e07923e5406b30a4a2e3e5880b2408ce341b12ecbe27156d"], ["description", "A Discord rich presence extension for pixelorama."], ["readme", "https://github.com/Variable-Interactive/PixeloramaDiscordRPC/blob/master/README.md"], ["tags", "Discord"], ["thumbnail", "https://github.com/user-attachments/assets/73d4c075-0166-4962-ba6f-f59c7d466c68"], ["download_link", "https://github.com/Variable-Interactive/PixeloramaDiscordRPC/releases/download/v0.1/DiscordRPC.pck"]]

[["name", "LineArt"], ["version", 0.4], ["sha256", "b50f7acaf3fcf21d2c42c92396ea6c17d97dcb075018617ee66d108695e2def3"], ["description", "It is an extension for pixelorama that adds a lineart shader in the effects menu"], ["readme", "https://github.com/Variable-Interactive/LineArt/blob/master/README.md"], ["tags", "Image Effect"], ["thumbnail", "https://github.com/user-attachments/assets/322c96ec-83e7-4775-9cd1-6b5bb3857d79"], ["download_link", "https://github.com/Variable-Interactive/LineArt/releases/download/v0.4/LineArt.pck"]]

[["name", "LegacyColorPicker"], ["version", 0.2], ["sha256", "3a70eeb4a302c34644f7c79a6953ccc7aa193ef255280c010471cad3f2c97665"], ["description", "This Extension brings back the old color picker used by Pixelorama 0.11.x (and before)"], ["readme", "https://github.com/Variable-Interactive/PixeloramaLegacyColorPicker/blob/master/README.md"], ["tags", "UI"], ["thumbnail", "https://github.com/user-attachments/assets/e2a35aa5-2826-4e4c-84fc-9152b6d78fe6"], ["download_link", "https://github.com/Variable-Interactive/PixeloramaLegacyColorPicker/releases/download/v0.2/LegacyColorPicker.pck"]]

[["name", "LocalCheckerSize"], ["version", 0.1], ["sha256", "d5c00389cbc259d5f10f879106b5b4d2bb19e809cc591f1273be5d546d8f1eea"], ["description", "This extension allows separate checker sizes for separate projects."], ["readme", "https://github.com/Variable-Interactive/PixeloramaLocalCheckerSize/blob/master/README.md"], ["tags", "UI"], ["thumbnail", "https://github.com/user-attachments/assets/fbb4532d-ef89-4ce4-89db-ebe587a07072"], ["download_link", "https://github.com/Variable-Interactive/PixeloramaLocalCheckerSize/releases/download/v0.1/LocalCheckerSize.pck"]]

[["name", "Skeletor"], ["version", 0.12], ["sha256", "b517422116ea723e8f9cd5f8faa350486f95b5c3e31d270c97321f9314aedec5"], ["description", "This extension adds basic skeletal animation capabilities to pixelorama."], ["readme", "https://github.com/Variable-Interactive/Skeletor/blob/master/README.md"], ["tags", "Animation"], ["thumbnail", "https://github.com/user-attachments/assets/3f5ec294-600e-4cd4-9049-7c0124801662"], ["download_link", "https://github.com/Variable-Interactive/Skeletor/releases/download/v0.12/Skeletor.pck"]]

// Template for adding new entry:
//[["name", ""], ["version", 0.0], ["sha256", ""], ["description", ""], ["readme", ""], ["tags", ""], ["thumbnail", ""], ["download_link", ""]]
