# Zelda-BotW Linkle Mod Dialogue Fix for Chinese (WiiU)

## How to pack .bnp

- msyt.exe create -d *PATH/TO/PROJECT* --platform wiiu --output *PATH/TO/OUTPUT*
- Rename output folder to `Msg_USen.product`
- Pack the folder with BotW Unpacker, rename the file to `Msg_USen.product.ssarc`
- Yaz0 Encode the file with BotW Unpacker
- Create folder `Bootup_USen\Message`
- Put the file inside `Bootup_USen\Message`
- Pack `Bootup_USen` folder with BotW Unpacker, no need to Yaz0 Encode.
- Rename the output to `Bootup_USen.pack`
- Create folder `output\content\Pack`
- Put the `.pack` file inside that folder
- Pack `output` folder as `.bnp` file using BCML

(There has to be a way to pack everything in command line, I just too lazy to figure it out for now.)

## Install

- 尝试修复了部分，比如`先生`->`小姐`， `小哥哥`->`小姐姐`, etc.

- 基础中文使用的是我[另外一个项目](https://github.com/KrisCris/Zelda-BotW_ChineseLanguagePack)维护的中文包（NS文本移植）。

- Help Wanted!! 欢迎提交PR!

- 请使用release里的链接，不要直接转载

- Install via BCML, please using the following mods loading sequence. 请使用BCML安装，使用下方图片的顺序。

- <img width="800" alt="image" src="https://user-images.githubusercontent.com/38860226/168200651-fd950884-e797-4770-a765-7a6edc8f2fbd.png">

