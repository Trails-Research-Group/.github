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
- Scena scripts editing: ★★☆☆☆ [FC, SC, 3rd] | [Guide](https://docs.google.com/document/d/1Nflb-dBPLLl0yWwk3MJTo0UxNyRPZDgy5zPanSrtotM/edit), [Tool](https://github.com/Ouroboros/EDDecompiler), [alternative tool](https://github.com/Kyuuhachi/Aureole)
- Texture injection/extraction: ★☆☆☆☆ [FC] | [Tool](https://github.com/Kaplas80/TranslationFramework2)
- Sprite extraction/injection: ★☆☆☆☆ [FC, SC, 3rd] | [Tool](https://github.com/Sewer56/Kiseki-Texture-Tool)
- Model extraction/injection: UNKNOWN [FC, SC, 3rd]
- Animation Scripts editing: ★★★☆☆ [FC] | [Tool FC](https://github.com/TwnKey/ED6ASDecompiler), [Tool 3rd](https://github.com/akatatsu27/FalcomToolsCollection/releases/tag/AS_Converter)
- Monster Scripts (MS.DT files) ★★☆☆☆ [3rd] | [Tool](https://github.com/akatatsu27/Falcom_Data_Formats/releases/tag/release)
- Table editing: ★☆☆☆☆ [FC] | [Tool](https://github.com/Kaplas80/TranslationFramework2)
- Font Creation: ★★☆☆☆ [FC, SC, 3rd] |[Tool](https://github.com/ZhenjianYang/SoraTranslation-Tools)
- BGM/OST extraction: ☆☆☆☆☆ [FC, SC, 3rd] | BGM folder contains all music files
- Replace BGM: ★☆☆☆☆ [FC, SC, 3rd] | [Guide](https://github.com/Trails-Research-Group/Doc/wiki/How-to:-Extract-and-replace-BGM)

### Crossbell series
- Scena/Animation Scripts editing: ★★☆☆☆ [Zero, Azure] | [Guide](https://docs.google.com/document/d/1Nflb-dBPLLl0yWwk3MJTo0UxNyRPZDgy5zPanSrtotM/edit), [Tool](https://github.com/AGraber/EDDecompiler), [alternative tool](https://github.com/Kyuuhachi/Aureole)
- Texture injection/extraction: ★★☆☆☆ [Zero, Azure] | [Tool](https://github.com/GeofrontTeam/EDDecompiler/blob/master/Decompiler/png32toitx.py), [DDS To 32Bits ITP](https://gist.github.com/Kyuuhachi/5af2b9c2036ae8e9b474e43b2854eef3)
- Sprite extraction/injection: ★★☆☆☆ [Zero, Azure] | [Tool](https://github.com/GeofrontTeam/EDDecompiler/blob/master/Decompiler/png32toitx.py)
- Model extraction/injection: UNKNOWN [Zero, Azure]
- Table editing: ★★★★★ [Zero, Azure] (Public tools might exist but they're scattered everywhere and don't support every table)
- Font Creation: ★☆☆☆☆ [Zero (NISA)] | [Tool](https://github.com/TwnKey/FalcomFontCreator)

### Trails of Cold Steel series
- Scena/Animation Scripts editing: ★★★☆☆ [CS, CS2] ★★☆☆☆ [CS3, CS4, Reverie] | [CS1, CS2](https://github.com/TwnKey/SenScriptsDecompiler), [CS3](https://github.com/Ouroboros/Falcom/tree/master/Decompiler2/Falcom/ED83), [CS4](https://github.com/Ouroboros/Falcom/tree/master/Decompiler2/Falcom/ED84), [Reverie](https://github.com/Ouroboros/Falcom/tree/master/Decompiler2/Falcom/ED85) | [SenScripts Guide](https://docs.google.com/document/d/1YVjFSkPsj9M0UgsI6_de4TSz35MeL_rGuhSQDtRTXxw/edit?usp=sharing)
- Texture injection/extraction: ★☆☆☆☆ [CS, CS2, CS3, CS4, Reverie] | [Guide](https://forums.dolphin-emu.org/Thread-custom-texture-tool-ps-v50-1?pid=482262#pid482262)
- Model extraction: ★★☆☆☆ [CS, CS2, CS3, CS4, Reverie] | [Tool](https://github.com/uyjulian/ed8pkg2glb)
- Model injection: ★★★★★ [CS3, CS4, Reverie] | [Tool (Maya)](https://github.com/Trails-Research-Group/Doc/releases/tag/v0.0) [Guide](https://github.com/Trails-Research-Group/Doc/wiki/How-to:-Import-custom-models-to-Cold-Steel-IV), [Tool (Blender, etc)](https://github.com/eArmada8/ed8pkg2gltf/releases)
- Table editing: ★☆☆☆☆ [CS, CS2, CS3, CS4] ★★★☆☆ [Reverie] | [Tool](https://git.sr.ht/~quf/tocs/tree/trunk/tbled/README.md) [Documentation](https://github.com/nnguyen259/SenSchema/wiki) (No public tool exists for Reverie, manageable through hex editing)
- Effect editing: ★★★★★ [CS, CS2, CS3, CS4, Reverie]\(No public tool exists and hardly manageable through hex editing)
- Font Creation: ★☆☆☆☆ [CS, CS2, CS3, CS4, Reverie] | [Tool](https://github.com/TwnKey/FalcomFontCreator)
- BGM/OST extraction: ☆☆☆☆☆ [CS, CS2, CS3, CS4, Reverie] | data/bgm folder contains all music files
- Replace BGM: ★☆☆☆☆ [CS3] | [Guide](https://github.com/Trails-Research-Group/Doc/wiki/How-to:-Extract-and-replace-BGM)
- Voice extraction: ★☆☆☆☆ [CS, CS2, CS3, CS4, Reverie] | data/voice folder contains all voice lines, but finding a specific one requires some effort

### Calvard series
- Scena/Action Scripts editing: ★★★☆☆ [Kuro] | [Tool](https://github.com/nnguyen259/KuroTools), [Guide on scena editing](https://docs.google.com/document/d/19ajbTZzda54i5xZWDLXOq0oOVQrhJYXU9rmgz3Ya3Bc/edit?usp=sharing), [Guide on AI scripting](https://docs.google.com/document/d/1ofetrdRn3BY8GIqfnzWrutw9MnyNEfLYZ6NOgxZzg8A/edit)
- Table editing: ★★☆☆☆ [Kuro]| [Tool](https://github.com/nnguyen259/KuroTools) [Guide](https://docs.google.com/document/d/19ajbTZzda54i5xZWDLXOq0oOVQrhJYXU9rmgz3Ya3Bc/edit?usp=sharing)
- Texture injection/extraction: ☆☆☆☆☆ [Kuro]
- Model extraction: ★☆☆☆☆ [Kuro] | [Exe](https://github.com/nnguyen259/KuroTools) [Python (uyjulian)](https://gist.github.com/uyjulian/9a9d6395682dac55d113b503b1172009) [Python (eArmada8)](https://github.com/eArmada8/kuro_mdl_tool)
- Model injection: ★★☆☆☆ [Kuro] ([Exe](https://github.com/nnguyen259/KuroTools), [Guide](https://github.com/Trails-Research-Group/Doc/wiki/How-to:-Import-custom-models-to-Kuro-no-Kiseki)) [Python](https://github.com/eArmada8/kuro_mdl_tool)
- Font Creation: ★★★☆☆ [Kuro] | [Tool](https://github.com/TwnKey/ED9FontConverter)

## FAQ

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

Note: This is a general list of mods.
We are not involved with all of these, so please direct any questions about the mods to their respective authors.
If your mod is missing from this list, feel free to [file an issue](https://github.com/Trails-Research-Group/.github/issues).

### Trails in the Sky (XSeed PC version)

- [Trails in the Dub](https://trailsinthedub.wixsite.com/dubbed): Fandub project for Trails in the Sky, not yet finished but still active.
- [SoraVoice by ZhenjianYang](https://github.com/ZhenjianYang/SoraVoice): Adds Japanese voice acting from the Evolution version.
- [HD textures by TwnKey](https://github.com/TwnKey/FC_HD)
- [Trails of Josette by akatatsu27](https://github.com/akatatsu27/TrailsOfJosette): Josette

### Trails in the Sky SC (XSeed PC version)

- [SoraVoice by ZhenjianYang](https://github.com/ZhenjianYang/SoraVoice): Adds Japanese voice acting from the Evolution version.
- [Josette rebalance mod by Hopyoprop](https://www.reddit.com/r/Falcom/comments/qtgh3z/mod_josette_rebalance_other_small_things/): Makes Josette less terrible in combat plus other changes.
- [Trails of Gilbert Second Chapter by akatatsu27](https://github.com/akatatsu27/TrailsOfGilbertSC): Gilbert


### Trails in the Sky the 3rd (XSeed PC version)

- [SoraVoice by ZhenjianYang](https://github.com/ZhenjianYang/SoraVoice): Adds Japanese voice acting from the Evolution version.
- [Josette rebalance mod by Hopyoprop](https://www.reddit.com/r/Falcom/comments/qtgh3z/mod_josette_rebalance_other_small_things/): Makes Josette less terrible in combat plus other changes.
- [Trails of Gilbert the 3rd by akatatsu27](https://github.com/akatatsu27/TrailsOfGilbertThe3rd): Gilbert

### Trails from Zero (NISA PC version)

- [Additional portraits mod by ShinKiseki](https://github.com/shinkiseki/MorePortraitsInZero).
- [Difficulty mod by SoftBrilliant](https://www.reddit.com/r/Falcom/comments/y55sx6/trails_from_zero_difficulty_mod_official_rerelease/)
- [Inevitable Zero by Kyuuhachi](https://github.com/Kyuuhachi/Inevitable-Zero). Ports over additional quests from the Evolution ports.

### Trails to Azure (NISA PC version)

- [Azure Vitality by Kyuuhachi](https://github.com/Kyuuhachi/Azure-Vitality). Ports over additional quests from the Evolution ports.

### Trails of Cold Steel (XSeed PC version)

- [SenPatcher by AdmiralCurtiss](https://github.com/AdmiralCurtiss/SenPatcher): various bugfixes and QoL features
- [HD textures by Bighead](https://steamcommunity.com/app/538680/discussions/0/2579854400755735260/)
- [Difficulty mod by SoftBrilliant](https://www.reddit.com/r/Falcom/comments/c0o756/cs1_difficulty_pack_v12/)
- [Randomizer by hell259](https://github.com/nnguyen259/ColdSteelRandomizer): Randomizer for stats, crafts, chest contents, orbment layouts.
- [Menu edits mod by EnDavio](https://steamcommunity.com/app/538680/discussions/0/3115920924819767678/): Various text fixes and improvements.
- Evolution Boss mod by NZerker12: Adds various playable characters and abilities, plus a few miscellaneous changes. [Download via the discord](https://discord.gg/XpFrXWht6j).

### Trails of Cold Steel II (XSeed PC version)

- [SenPatcher by AdmiralCurtiss](https://github.com/AdmiralCurtiss/SenPatcher): various bugfixes and QoL features
- [HD textures by Bighead](https://steamcommunity.com/app/748490/discussions/0/2860219962081641200/)
- [Difficulty mod by Bison](https://steamcommunity.com/app/748490/discussions/0/1696045708664951845/)
- [Female Rean mod by StargazingSketcher](https://www.reddit.com/r/Falcom/comments/qh5mek/the_updated_shenanigans_of_female_rean_mod/)

### Trails of Cold Steel III (NISA PC version)

- [SenPatcher by AdmiralCurtiss](https://github.com/AdmiralCurtiss/SenPatcher): various bugfixes and QoL features
- [Difficulty mod by SoftBrilliant](https://www.reddit.com/r/Falcom/comments/gu5no5/trails_of_cold_steel_3_difficulty_mod_v_10_release/)
- [Randomizer by hell259](https://github.com/nnguyen259/ColdSteel3Tools): Randomizer for stats, crafts, brave orders, and character models.
- [Friendly fire mod by Hüllenoperator](https://git.sr.ht/~quf/cs3ffm)

### Trails of Cold Steel IV (NISA PC version)

- [SenPatcher by AdmiralCurtiss](https://github.com/AdmiralCurtiss/SenPatcher): various QoL features
- [Twilight Rebalance mod by SoftBrilliant](https://www.reddit.com/r/Falcom/comments/qnlowv/cs4_twilight_rebalance_a_difficultybalance_mod/)
- Evolution mod by anonymous, download via the [modding discord](https://discord.gg/XpFrXWht6j): Makes various characters playable, adds crafts, various other changes

### Trails into the Reverie (NISA PC version)

Not released yet

### Other games

- CS1/CS2 Vita: [Backport of additional english voices from the PC version](https://www.reddit.com/r/Falcom/comments/fbgw8d/trails_of_cold_steel_i_ii_pc_voices_backported_to/)
- CS1 Switch (Kai): [English translation mod by MasaGratoR & Graber](https://github.com/masagrator/ToCS1-ENX)
- CS2 Switch (Kai): [English translation mod by MasaGratoR & Graber](https://github.com/masagrator/ToCS2-ENX)

## Showcases
- [Shizuna's backport to CSIV](https://www.youtube.com/watch?v=mJz8IeevlDw&ab_channel=Twn)
- [Playable/Transformable McBurn in CSIV](https://www.youtube.com/watch?v=2tHkFzYEoik&ab_channel=NBigboyC2)
- ["Ogre unleashed" in CS1](https://www.youtube.com/watch?v=BCwvs3dekz8&ab_channel=NBigboyC2)
- [Laura "Radiant Dance" craft from CS1, ported to CSIII](https://www.youtube.com/watch?v=cC9knrPk4sQ&ab_channel=NBigboyC2)

