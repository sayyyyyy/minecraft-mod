
## 環境構築
1. Forge Mdkのダウンロード
2. Gradleのダウンロード
3. gradlew.bat.exampleをコピーしてgradlew.batファイルを作成する
4. 31行目のJAVA_HOMEに自身の環境のpathを記述
5. `gradle build`を実行し、ビルドを行う
6. build/libs/に作成されたjarファイルをminecraft modフォルダに入れてminecraftを起動する

[こちら](https://blog.takunology.jp/entry/2020/02/24/164120)のサイトを参照



Mapping Names:
=============================
By default, the MDK is configured to use the official mapping names from Mojang for methods and fields 
in the Minecraft codebase. These names are covered by a specific license. All modders should be aware of this
license, if you do not agree with it you can change your mapping names to other crowdsourced names in your 
build.gradle. For the latest license text, refer to the mapping file itself, or the reference copy here:
https://github.com/MinecraftForge/MCPConfig/blob/master/Mojang.md

Additional Resources: 
=========================
Community Documentation: https://docs.minecraftforge.net/en/1.19.x/gettingstarted/
LexManos' Install Video: https://youtu.be/8VEdtQLuLO0
Forge Forums: https://forums.minecraftforge.net/
Forge Discord: https://discord.minecraftforge.net/
