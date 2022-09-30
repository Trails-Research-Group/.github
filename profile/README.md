## The group
This group is made of modders of the Trails games who aim to make modding accessible to everyone. 
Our goal is to offer a quick presentation of the modding scene, including available tools, guides and general documentation that has been established over the years.
We will also try to promote the work of other modders as much as possible, be it tools or actual mods.

The philosophy of our group is that we don't answer questions directly, but will consider writing a guide so that we don't have to repeat ourselves, as the questions in the modding community usually end up being more or less the same every time. And this is due to the fact that barely anyone documents their work among the modders and tool makers.

## To newcomers
To people wanting to get into modding the Trails games, you might want to start looking at the "What is currently doable" section, which will give you hints on what you can currently achieve with the limited knowledge you have (as a newcomer to the scene), as well as guides and tools to achieve your goals. 

Please also have a look at the FAQ section which contains the most frequently asked questions regarding mods, there is a good chance you will find your answer there. Finally, if nothing here helps, please feel free to drop by the various modding discords, forums and communities and ask your question there.

## What is currently doable
We define a difficulty scale for each item which reads like this:

☆☆☆☆☆ : straightforward, nothing difficult, takes literal minutes to be done\
★☆☆☆☆ : simple manipulation, no or very little coding background required\
★★☆☆☆ : a little more advanced, usually involves setting up a special environment like Python\
★★★☆☆ : a bit hard but still manageable for someone who has some background in programming and can interpret binary data\
★★★★☆ : pretty hard. not accessible to everyone. little to no documentation exist. A tool might exist but it is very rough\
★★★★★ : either a very difficult process with many complex and time consuming steps, or no tool exists (to our knowledge), you're on your own

### Trails in the Sky series
Event editing: ★★☆☆☆ [FC, SC, 3rd] | [Guide](https://docs.google.com/document/d/1Nflb-dBPLLl0yWwk3MJTo0UxNyRPZDgy5zPanSrtotM/edit), [Tool](https://github.com/Ouroboros/EDDecompiler)\
Texture injection/extraction: ★☆☆☆☆ [FC] | [Tool](https://github.com/Kaplas80/TranslationFramework2)\
Sprite extraction/injection: ★☆☆☆☆ [FC, SC, 3rd] | [Tool](https://github.com/Sewer56/Kiseki-Texture-Tool)\
Model extraction/injection: UNKNOWN [FC, SC, 3rd]\
Craft editing: ★★★☆☆ [FC] | [Tool](https://github.com/TwnKey/ED6ASDecompiler)\
Table editing: ★☆☆☆☆ [FC] | [Tool](https://github.com/Kaplas80/TranslationFramework2)\
Font Creation: ★★☆☆☆ [FC, SC, 3rd] |[Tool](https://github.com/ZhenjianYang/SoraTranslation-Tools)\
BGM/OST extraction: ☆☆☆☆☆ [FC, SC, 3rd] | BGM folder contains all music files\
Replace BGM: ★☆☆☆☆ [FC, SC, 3rd] | [Guide](https://github.com/Trails-Research-Group/Doc/wiki/How-to:-Extract-and-replace-BGM)

### Crossbell series
Event editing: ★★☆☆☆ [Zero, Azure] | [Guide](https://docs.google.com/document/d/1Nflb-dBPLLl0yWwk3MJTo0UxNyRPZDgy5zPanSrtotM/edit), [Tool](https://github.com/GeofrontTeam/EDDecompiler) (Note that multiple forks of EDDecompiler exist and this one is probably the most advanced one, including scripts for Zero and Azure Kai versions)\
Texture injection/extraction: UNKNOWN [Zero, Azure]\
Sprite extraction/injection: UNKNOWN [Zero, Azure]\
Model extraction/injection: UNKNOWN [Zero, Azure]\
Table editing: ★★★★★ [Zero, Azure] (Public tools might exist but they're scattered everywhere and don't support every table)\
Font Creation: ★☆☆☆☆ [Zero (NISA)] | [Tool](https://github.com/TwnKey/FalcomFontCreator)\

### Trails of Cold Steel series
Event editing: ★★★☆☆ [CS, CS2] ★★☆☆☆ [CS3, CS4, Reverie] | [CS1, CS2](https://github.com/TwnKey/SenScriptsDecompiler), [CS3](https://github.com/Ouroboros/Falcom/tree/master/Decompiler2/Falcom/ED83), [CS4](https://github.com/Ouroboros/Falcom/tree/master/Decompiler2/Falcom/ED84), [Reverie](https://github.com/Ouroboros/Falcom/tree/master/Decompiler2/Falcom/ED85) | [SenScripts Guide](https://docs.google.com/document/d/1YVjFSkPsj9M0UgsI6_de4TSz35MeL_rGuhSQDtRTXxw/edit?usp=sharing)\
Texture injection/extraction: ★☆☆☆☆ [CS, CS2, CS3, CS4, Reverie] | [Guide](https://forums.dolphin-emu.org/Thread-custom-texture-tool-ps-v50-1?pid=482262#pid482262)\
Model extraction: ★★☆☆☆ [CS, CS2, CS3, CS4, Reverie] | [Tool](https://github.com/uyjulian/ed8pkg2glb)\
Model injection: ★★★★★ [CS4] | [Tools](https://github.com/Trails-Research-Group/Doc/releases/tag/v0.0) [Guide](https://github.com/Trails-Research-Group/Doc/wiki/How-to:-Import-custom-models-to-Cold-Steel-IV)\
Table editing: ★☆☆☆☆ [CS, CS2, CS3, CS4] ★★★☆☆ [Reverie] | [Tool](https://git.sr.ht/~quf/tocs/tree/trunk/tbled/README.md) [Documentation](https://github.com/nnguyen259/SenSchema/wiki) (No public tool exists for Reverie, manageable through hex editing)\
Effect editing: ★★★★★ [CS, CS2, CS3, CS4, Reverie]\(No public tool exists and hardly manageable through hex editing)\
Font Creation: ★☆☆☆☆ [CS, CS2, CS3, CS4, Reverie] | [Tool](https://github.com/TwnKey/FalcomFontCreator)\
BGM/OST extraction: ☆☆☆☆☆ [CS, CS2, CS3, CS4, Reverie] | data/bgm folder contains all music files\
Replace BGM: ★☆☆☆☆ [CS3] | [Guide](https://github.com/Trails-Research-Group/Doc/wiki/How-to:-Extract-and-replace-BGM)\
Voice extraction: ★☆☆☆☆ [CS, CS2, CS3, CS4, Reverie] | data/voice folder contains all voice lines, but finding a specific one requires some effort

### Calvard series
Event editing: ★★★☆☆ [Kuro] | [Tool](https://github.com/nnguyen259/KuroTools) [Guide](https://docs.google.com/document/d/19ajbTZzda54i5xZWDLXOq0oOVQrhJYXU9rmgz3Ya3Bc/edit?usp=sharing)\
Table editing: ★★☆☆☆ [Kuro]| [Tool](https://github.com/nnguyen259/KuroTools) [Guide](https://docs.google.com/document/d/19ajbTZzda54i5xZWDLXOq0oOVQrhJYXU9rmgz3Ya3Bc/edit?usp=sharing)\
Texture injection/extraction: ☆☆☆☆☆ [Kuro]\
Model extraction: ★☆☆☆☆ [Kuro] | [Exe](https://github.com/nnguyen259/KuroTools) [Python](https://gist.github.com/uyjulian/9a9d6395682dac55d113b503b1172009)\
Model injection: ★★★★★ [Kuro] (No public tool exists)\
Font Creation: ★★★☆☆ [Kuro] | [Tool](https://github.com/TwnKey/ED9FontConverter)

## FAQ
- *How to backport characters from the latest game to a previous entry (usually Kuro to CS, CS2 to CS1, CS4 to CSX)?*\
Backporting is currently one of the most complex tasks in Trails modding. It is also not documented at all. You will currently not find help anywhere, but we are planning to write a guide for Kuro to CSIV if possible, depending on several factors.

## Places we recommend checking out
**[The Kiseki Modding Server](https://discord.gg/wYkWS33NQt)**

A fairly populated modding discord server with mod previews and notable people from the community; if you have a specific question that you can't find in any guide or FAQ, you can try to ask it here. 

**[The Kiseki Difficulty Modding Server](https://discord.gg/EHhzrFGaRp)** 

A discord server mainly focused on difficulty mods. Managed by [SoftBrilliant](https://github.com/SoftBrilliant).

**[The Trails/Kiseki modding GBATemp thread](https://gbatemp.net/threads/trails-kiseki-modding.476713/)**

Contains a list of ressources and useful links. Managed by [uyjulian](https://github.com/uyjulian)

**[The "Falcom" Github Repository](https://github.com/Ouroboros/Falcom)**

Contains a list of several tools gathered over the years. Managed by [Ouroboros](https://github.com/Ouroboros).

**[Trails in the Database](https://trailsinthedatabase.com/)** 

Database containing the script for all the Trails games, sorted by script files, which can sometimes be of use for modding. Managed by [the database](https://github.com/the-database).

## Released Mods
## Showcases
- [Shizuna's backport to CSIV](https://www.youtube.com/watch?v=mJz8IeevlDw&ab_channel=Twn)
- [Playable/Transformable McBurn in CSIV](https://www.youtube.com/watch?v=2tHkFzYEoik&ab_channel=NBigboyC2)
- ["Ogre unleashed" in CS1](https://www.youtube.com/watch?v=BCwvs3dekz8&ab_channel=NBigboyC2)
- [Laura "Radiant Dance" craft from CS1, ported to CSIII](https://www.youtube.com/watch?v=cC9knrPk4sQ&ab_channel=NBigboyC2)

