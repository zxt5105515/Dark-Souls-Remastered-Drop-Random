# Dark-Souls-Remastered-Drop-Random

## 简介
这里是给`《黑暗之魂：重制版》`pc版安装随机mod（肉鸽之魂）的教程，随机mod就是将所有掉落物品的掉落位置打乱（针对老手甚至可以将重要钥匙放到boss的断尾掉落里），然后能极大地提高游戏重玩的乐趣和刺激感  
由于重制版的数据文件是单独放的，并没有打成一个文件，所以安装流程相比原版是很简单的

## 安装随机mod

1. 你得先安装好游戏
2. 下载DarkSoulsItemRandomizer.exe，打开，选择适合的难度，点击`Scramble Items & Export`导出一个`ItemLotParam.param`文件，这个文件就是将掉落打乱后的掉落文件
3. 别关exe，再点击`Generate Cheatsheet`导出一个`cheatsheet.txt`文件，这个文件是作弊列表，里面有所有物品的掉落位置，在你实在找不到某个钥匙/物品的掉落时可以做个弊看看，硬核玩家可以不导出(注意这个exe程序本身有小概率出bug然后导致你卡关，所以...)
4. 下载DeS-BNDBuild-2016-10-17-23.exe，复制【游戏安装目录】\param\GameParam\GameParam.parambnd.dcx 到这个exe同目录下，打开exe，将刚刚复制的GameParam.parambnd.dcx拖入exe上面的输入框，点击`Extract`，会在本目录生成若干文件，将生成的`GameParam.parambnd`拖入exe上面的输入框,再次点击`Extract`，会在本目录生成名为`GameParam.parambnd.extract`的文件夹，将1步骤生成的`ItemLotParam.param`复制到 GameParam.parambnd.extract\FRPG\data\INTERROOT_x64\param\GameParam下，系统会提示是否覆盖，选择是，
5. 点击`Rebuild`，会生成新的`GameParam.parambnd`，再次将GameParam.parambnd.dcx拖入exe上面的输入框，点击`Rebuild`,这会生成新的`GameParam.parambnd.dcx`，将这个文件复制回【游戏安装目录】\param\GameParam\覆盖老的文件
6.打开游戏开始受苦之路吧

## 还原随机mod
在**安装随机mod**4步骤中会生成一个`GameParam.parambnd.dcx.bak`的文件，将它改名为`GameParam.parambnd.dcx` ,然后复制回【游戏安装目录】\param\GameParam\覆盖老的文件
