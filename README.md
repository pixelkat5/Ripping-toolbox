# Ripping-toolbox (new updates should be coming soon, sorry for the wait. :/)

A public resource for anything model ripping. That being a list of tools and what they do to just a general purpose ripping resources aimed at people just getting into model ripping. (and I guess reverse engineering) 

> [!CAUTION]
> **Note: I don't have much time (and my GitHub activity reflects this...) -BUT I will try to get updates out when I can.**

-------

# QuickBMS by Luigi Auriemma [[DOWNLOAD]](https://aluigi.altervista.org/quickbms.htm "QuickBMS homepage")
"universal script-based files extractor and reimporter. QuickBMS supports tons of games and file formats, archives, encryptions, compressions, obfuscations and other algorithms."

QuickBMS is basically a CLI program that lets you extract game models with the help of plugins in the form of **.BMS** files. 

# Noesis by "Richard Whitehouse" [[DOWNLOAD]](https://richwhitehouse.com/index.php?content=inc_projects.php&showproject=91 "Noesis home/download page")
"Noesis is a tool for previewing and converting between hundreds of model, image, and animation formats. It utilizes a robust plugin system, with support for native extension modules and Python scripts. The plugin/script API features hundreds of functions and interfaces which assist in developing new formats, tools, and visualization aids. Noesis also features processing, conversion, and visualization options for many different types of volume data, including medical imaging formats such as Analyze 7.5, NifTI-1, and DICOM."

Noesis is a great utility for converting things like .DDS files to .PNG's. It can also be used for viewing file types before you commit to converting something useless. Its also great as you can install plugins for formats that aren't already supported.

# ![Unity](https://img.shields.io/badge/unity-%23000000.svg?style=for-the-badge&logo=unity&logoColor=white) Asset ripper. [[download]](https://assetripper.github.io/AssetRipper/) or the [[Github]](https://github.com/AssetRipper/AssetRipper/releases/tag/latest) release.
Asset ripper is an all in one, easy to use GUI for ripping and converting Unity mesh's, images, Terrain, scripts, audio, sprite, textasset, script content levels, shaders, bundled assets, and the option of selecting a language that'll be used for decompiling said unity scripts. 
All you've got to do is go to file and slect the game root directory. You can find all your games root directories at ```C:\Program Files (x86)\Steam\steamapps\common\```. Past that, Asset ripper will automatically sort all the files by their file use/type. Then you can just hit the export button and that's it.

# ![Unity](https://img.shields.io/badge/unity-%23000000.svg?style=for-the-badge&logo=unity&logoColor=white) Asset Studio GUI - A better alternative to Asset ripper.
Pretty similar to Asset ripper though you have more of a GUI than with ripper. Most of the same things apply here as they did with asset ripper, just put the root directory ```File -> Load folder```
**I'll work on this later but most is self explanatory..**

<details><summary><strong>Game exclusive resources</strong></summary>

CAUTION: Most of this is just game exclusive so unlike the other tools, these/this will really only work for one or two games.

**Pokemon ripping guide by Random Talking Bush** [[BLOG]](https://www.vg-resource.com/thread-25872.html)

> There are many neat tools here but the one I've used is [**THIS**](https://mega.nz/file/ekRjwTjQ#6Cgvwr9Duj7U8JjpcLiotN6nMiQKU2SzfV8lRdxSfXs), it's a .BMS plugin/script that you load into QuickBMS to swiftly convert BNTX, BFRES, and BFFNT to .DDS in a batch. Note: .DDS files are files you can think of as fancy images. If you are submitting something for [The Model Resource](https://www.models-resource.com/) you want to convert these.DDS files to **.PNG's**. That is unless you wish for your submission to be rejected...

>> Adding onto this, if you wish to import .TRMDL (model file) files then you'll need [ChicoEevee and Bogdan Padalko's Blender plugin](https://github.com/ChicoEevee/Pokemon-Switch-V2-Model-Importer-Blender/) or if you actually pay for software/are based and pirate your software then you can use [RTB's .GFBMDL/.TRMDL Model MAXScript](https://github.com/RandomTBush/RTB-3DSMax-Scripts/blob/main/Scripts/PokemonSwitch_GFBMDL-TRMDL.ms). If you don't wish to rip the models from the game itself then use [**THIS**](https://mega.nz/folder/elJhVC5D#NU-yzmXuTlsIIzXAMLKVaA) MEGA upload (maintained and owned by [Random Talking Bush](https://www.vg-resource.com/user-7.html) 

</details>
