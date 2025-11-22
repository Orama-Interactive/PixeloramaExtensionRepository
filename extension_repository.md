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

[["name", "Voxelorama"], ["version", 1.2], ["sha256", "02d4edb80343dd2e43d22413fc489c379accbf68e81d1be7453cc03acfbf4347"], ["description", "An extension for Pixelorama that generates 3D voxel art out of 2D pixel art."], ["readme", "https://github.com/Orama-Interactive/VoxeloramaExtension/blob/main/README.md"], ["tags", "Tool", "3D"], ["thumbnail", "https://user-images.githubusercontent.com/35376950/185218214-c8356f86-00ed-4f39-b0f8-458a29d0061b.png"], ["download_link", "https://github.com/Orama-Interactive/VoxeloramaExtension/releases/download/v1.2/Voxelorama.pck"]]

[["name", "LospecPaletteImporter"], ["version", 1.3], ["sha256", "e62534d1446fdceccdf55ff601d0f2dd7a453d01b75944ac520814dfa5b0199d"], ["description", "A Pixelorama extension for downloading and importing palettes directly from Lospec."], ["readme", "https://github.com/OverloadedOrama/Lospec-Palette-Importer/blob/main/README.md"], ["tags", "Palettes"], ["thumbnail", "https://github.com/Variable-ind/Lospec-Palette-Importer/assets/77773850/7ac86623-c428-4409-8f81-c7406527126f"], ["download_link", "https://github.com/OverloadedOrama/Lospec-Palette-Importer/releases/download/v1.3/LospecPaletteImporter.pck"]]

[["name", "OpenDyslexicFont"], ["version", 1.2], ["sha256", "a78b6f0f4fb197337d9b076bc60a05627d779c8c62591c744574aa1ef72b3f78"], ["description", "A Pixelorama extension that sets the OpenDyslexic font as the main font of the user interface."], ["readme", "https://github.com/OverloadedOrama/OpenDyslexic-Pixelorama-Extension/blob/main/README.md"], ["tags", "Fonts"], ["download_link", "https://github.com/OverloadedOrama/OpenDyslexic-Pixelorama-Extension/releases/download/v1.2/OpenDyslexicFont.pck"]]

[["name", "ColorChecker"], ["version", 0.2], ["sha256", "38c08318bec03dca9ebbbb352de97ee668f2fd04dca372b959283d659c4c94d5"], ["description", "An extension for assistance in matching colors while choosing a new color"], ["readme", "https://github.com/Variable-Interactive/PixeloramaColorChecker/blob/master/README.md"], ["thumbnail", "https://github.com/user-attachments/assets/46e34f56-9e07-4472-bf42-ac68c4638617"], ["tags", "UI", "Palettes"], ["download_link", "https://github.com/Variable-Interactive/PixeloramaColorChecker/releases/download/v0.2/ColorChecker.pck"]]

[["name", "ExtensionCreator"], ["version", 1.6], ["sha256", "246a6a78241a4b6dabc3dd7a71a0628d34633c26cf9983017c13a5c67da7a679"], ["description", "Used as a guide by beginers for creating extensions (Open from help menu)"], ["tags", "Tutorial"], ["thumbnail", "https://github.com/user-attachments/assets/44630889-3c0e-467b-85c9-5abf7045ee91"], ["download_link", "https://github.com/Variable-Interactive/ExtensionCreator/releases/download/v1.6/ExtensionCreator.pck"]]

// [["name", "QuickDocs"], ["version", 0.3], ["sha256", "32405d8c4d07ff9df301f3080ec6303c9cb0906f4309e56db0b7bb341f458d8b"], ["description", "Provides a way to communicate to the docs from within the editor."], ["readme", "https://github.com/Variable-Interactive/QuickDocks/blob/master/README.md"], ["tags", "Tutorial"], ["thumbnail", "https://github.com/user-attachments/assets/e374093f-879c-490e-8ebc-c2a44677d9cf"], ["download_link", "https://github.com/Variable-Interactive/QuickDocks/releases/download/v0.3/QuickDocs.pck"]]

[["name", "KeyDisplay"], ["version", 1.1], ["sha256", "06fb9c10fa4b75fd204ef9d2b8f25bf864e65909c47c5a8db497a89193ca2602"], ["description", "Handy extension to display shortcuts for use in videos etc.)"], ["readme", "https://github.com/Variable-Interactive/KeyDisplay/blob/master/README.md"], ["tags", "UI"], ["thumbnail", "https://github.com/user-attachments/assets/de510a60-9b3b-464d-a025-c38cc8d7b09c"], ["download_link", "https://github.com/Variable-Interactive/KeyDisplay/releases/download/v1.1/KeyDisplay.pck"]]

// [["name", "TimeTracking"], ["version", 0.5], ["sha256", "19dcd7f89fea8e83ed7a72e1654e77c20d70e092082ec0f54c83f97a1a691402"], ["description", "Saves project statistics in the .pxo file (access with Project>Project Statistics)"], ["readme", "https://github.com/Variable-Interactive/TimeTracking/blob/master/README.md"], ["tags", "Analytics"], ["thumbnail", "https://github.com/user-attachments/assets/9d50f084-6e4e-4706-9f5b-682d91dfb080"], ["download_link", "https://github.com/Variable-Interactive/TimeTracking/releases/download/v0.5/TimeTracking.pck"]]

[["name", "CameraZoomer"], ["version", 0.4], ["sha256", "ab8d66b1801e76c05270bdb066f8479790b5f13968f3e7204bc4257a34354573"], ["description", "Lets you set precise zoom values to Canvas Preview"], ["readme", "https://github.com/Variable-Interactive/CameraZoomer/blob/master/README.md"], ["tags", "UI"], ["thumbnail", "https://github.com/user-attachments/assets/8455b398-05ee-453f-8920-aa843a562d2b"], ["download_link", "https://github.com/Variable-Interactive/CameraZoomer/releases/download/v0.4/CameraZoomer.pck"]]

// [["name", "DiscordRPC"], ["version", 0.1], ["sha256", "6cdd4eb2cd6514d4e07923e5406b30a4a2e3e5880b2408ce341b12ecbe27156d"], ["description", "A Discord rich presence extension for pixelorama."], ["readme", "https://github.com/Variable-Interactive/PixeloramaDiscordRPC/blob/master/README.md"], ["tags", "Discord"], ["thumbnail", "https://github.com/user-attachments/assets/73d4c075-0166-4962-ba6f-f59c7d466c68"], ["download_link", "https://github.com/Variable-Interactive/PixeloramaDiscordRPC/releases/download/v0.1/DiscordRPC.pck"]]

[["name", "LineArt"], ["version", 0.5], ["sha256", "727e6e7326df0e3c3a2ad49eeb74e95fc4a7d05696172e28a6900f0327e176ea"], ["description", "It is an extension for pixelorama that adds a lineart shader in the effects menu"], ["readme", "https://github.com/Variable-Interactive/LineArt/blob/master/README.md"], ["tags", "Image Effect"], ["thumbnail", "https://github.com/user-attachments/assets/322c96ec-83e7-4775-9cd1-6b5bb3857d79"], ["download_link", "https://github.com/Variable-Interactive/LineArt/releases/download/v0.5/LineArt.pck"]]

// [["name", "LegacyColorPicker"], ["version", 0.2], ["sha256", "3a70eeb4a302c34644f7c79a6953ccc7aa193ef255280c010471cad3f2c97665"], ["description", "This Extension brings back the old color picker used by Pixelorama 0.11.x (and before)"], ["readme", "https://github.com/Variable-Interactive/PixeloramaLegacyColorPicker/blob/master/README.md"], ["tags", "UI"], ["thumbnail", "https://github.com/user-attachments/assets/e2a35aa5-2826-4e4c-84fc-9152b6d78fe6"], ["download_link", "https://github.com/Variable-Interactive/PixeloramaLegacyColorPicker/releases/download/v0.2/LegacyColorPicker.pck"]]

[["name", "LocalCheckerSize"], ["version", 0.2], ["sha256", "7d00c1aee165d89c8f1ed327ab9fc240ae9dc04cbc22f4b2495514d5db38a5ae"], ["description", "This extension allows separate checker sizes for separate projects."], ["readme", "https://github.com/Variable-Interactive/PixeloramaLocalCheckerSize/blob/master/README.md"], ["tags", "UI"], ["thumbnail", "https://github.com/user-attachments/assets/fbb4532d-ef89-4ce4-89db-ebe587a07072"], ["download_link", "https://github.com/Variable-Interactive/PixeloramaLocalCheckerSize/releases/download/v0.2/LocalCheckerSize.pck"]]

[["name", "Skeletor"], ["version", 0.15], ["sha256", "c7c0b597f0614486575c2aefa4ddaed76fe4f2cdde259bcbab7c1c525750d416"], ["description", "This extension adds basic skeletal animation capabilities to pixelorama."], ["readme", "https://github.com/Variable-Interactive/Skeletor/blob/master/README.md"], ["tags", "Animation"], ["thumbnail", "https://github.com/user-attachments/assets/3f5ec294-600e-4cd4-9049-7c0124801662"], ["download_link", "https://github.com/Variable-Interactive/Skeletor/releases/download/v0.15/Skeletor.pck"]]

// Template for adding new entry:
//[["name", ""], ["version", 0.0], ["sha256", ""], ["description", ""], ["readme", ""], ["tags", ""], ["thumbnail", ""], ["download_link", ""]]
