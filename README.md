# Bluecord
Source Code for Bluecord

Here lies the full Java source code for Bluecord.

If you enjoy the Bluecord project (of which many dozens of hours were put into), please consider starring this project.

If you are inspired by, or end up copying or using any of the works contained herein, please give credit by linking back to this repository.

[Latest Bluecord Version: 2.2](https://bluesmods.com/bluecord)

# Building / Installing
You will need the following pieces of software:
- APKTool v2.7.0 or higher (I use APK Easy Tool v1.57)
- Android Studio

1) Download / Clone this repository
2) Decompile the Bluecord APK from this repo using APKTool
3) Import the project into Android Studio
4) In the toolbar, click "Build" -> Build Bundle(s) / APK(s) -> Build APK(s)
5) Locate the APK, and decompile it using APKTool
6) Find the "mods" folder in the smali_classes directory of the decompiled APK, and move it to the Bluecord APK you decompiled before **(DELETE the mods folder in the Bluecord APK first)**
7) Re-Compile the Decompiled Bluecord APK, install and enjoy

# Notes
The .smali files I have changed are not present in this repository yet, because I modify them by hand and port them manually to each version using WinMerge, and there is not source control for them yet.

If you would like to help with that part, please consider submitting an issue or a PR with a decent way of automating this task.
