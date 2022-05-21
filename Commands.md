# 命令

[英文wiki](https://docs.blamejared.com/1.12/en/Commands)


CraftTweaker 添加了一些命令，这些命令可以帮助你创建脚本，并减少编写脚本的开发时间。

命令的前缀是：`/crafttweaker`或`/ct`

你也可以使用这些别名：`/minetweaker`或`/mt`

游戏中的所有命令都可以通过以下方式找到:

`/crafttweaker help`

或者

`/ct help`

## 命令列表

### 生物群系

用法：

`/crafttweaker biomes`

`/ct biomes`

说明:

列出游戏中的所有生物群系。

### 生物群系类型

用法：

`/crafttweaker biomeTypes`

`/ct biomeTypes`

说明:

列出游戏中的所有生物群系类型。

### 方块信息

用法：

`/crafttweaker blockinfo`

`/ct blockinfo`

说明：

启用或禁用方块信息读取器。 在启用方块信息模式下，右键点击方块，将输出方块的名称、元数据和 TileEntity 数据。

### 方块

用法：

`/crafttweaker blocks`

`/ct blocks`

说明：

将游戏中所有的方块名称输出到 crafttweaker.log 文件中。

### 问题追踪

用法：

`/crafttweaker bugs`

`/ct bugs`

说明：

在浏览器中打开 GitHub 错误跟踪器。

### 合成表冲突

用法：

`/crafttweaker conflict`

`/ct conflict`

说明：

将所有冲突的合成表配方输出至 crafttweaker.log 文件中。  
请注意，这只适用于安装了 JEI 的客户端！

### Discord

用法：

`/crafttweaker discord`

`/ct discord`

说明：

在浏览器中打开[Discord 服务器](https://www.discord.blamejared.com/)。

### 文档

用法：

`/crafttweaker docs`

`/ct docs`

说明：

在浏览器中打开这个文档页面 (与 `/ct wiki`相同)。

### 导出脚本修改内容

用法：

`/crafttweaker dumpzs`

`/ct dumpzs`

说明：

将ZenScript转储作为HTML文件输出到minecraft目录中的crafttweaker _ dump文件夹。你可以使用一个或多个将连续执行的转储目标(如果你提供两次目标，它将运行两次)。  
可以使用自动补全(tab键)找到目标。  
默认情况下，`log`、`html`和`json`被注册为目标。  
这将包括所有注册的尖括号引用、ZenTypes、全局函数、ZenExpansions和所有注册的包，包括它们的方法。  
请注意，并非所有这些都可以在脚本中使用！  

### 实体

用法：

`/crafttweaker entities`

`/ct entities`

说明：

将游戏中所有的实体名称输出到 crafttweaker.log 文件中。

### 给予物品

用法：

`/crafttweaker give <minecraft:bedrock>`

`/ct give <minecraft:bedrock>`

说明：

使用CrT的尖括号调用给予玩家物品。  
你也可以通过附加一个 `.withTag()` 来应用标签。  
请注意，这是一个非常简单的解析器，可能并不适用于所有情况！

### 手中

用法：

`/crafttweaker hand`

`/ct hand`

说明：

将你手中的物品名称打印到聊天栏中。

还将名称复制到剪贴板并打印矿辞条目。

### 物品栏

用法：

`/crafttweaker inventory`

`/ct inventory`

说明：

将物品栏中所有的物品名称输出到 crafttweaker.log 文件中。

### JEI类别

用法：

`/crafttweaker jeiCategories`

`/ct jeiCategories`

说明：

将所有注册的JEI类别输出到 crafttweaker.log 文件中。  
需要安装JEI！

### Json

用法：

`/crafttweaker json` `/crafttweaker json escaped`

`/ct json` `/ct json escaped`

说明：

将你手里物品的nbt打印为聊天栏的JSON。  
这种格式不同于CraftTweaker使用的IData格式。  
您可以单击它将其复制到剪贴板。  
如果将 `escaped` 传递给参数，则会自动对字符串进行转义处理。

### 液体

用法：

`/crafttweaker liquids`

`/ct liquids`

说明：

将游戏中所有的液体名称输出到 crafttweaker.log 文件中。

### Log

用法：

`/crafttweaker log`

`/ct log`

说明：

发送一个可点击的链接来打开crafttweaker.log。

### Mod

用法：

`/crafttweaker mods`

`/ct mods`

说明：

将游戏中所有mod名称及其版本输出到crafttweaker.log文件，并在聊天栏中打印出来。

### 物品名

用法：

`/crafttweaker names [category(类别)]`

`/ct names [category]`

说明：

将游戏中所有的物品名称输出到 crafttweaker.log 文件中。  
`category` 参数是可选的，并将根据以下信息扩展列表:

- burntime

- creativetabs

- damageable

- display

- enchantability

- foodvalue

- maxdamage

- maxstack

- maxuse

- modid

- rarity

- repairable

- repaircost

- saturationvalue

- unloc

您还可以使用TAB键自动补全功能查看所有可用的参数。
### Nbt

用法：

`/crafttweaker nbt`

`/ct nbt`

说明：

将你目视方块或你手上物品的NBT输出到crafttweaker.log文件。

### 矿辞

用法：

`/crafttweaker oredict <name>`

`/ct oredict <name>`

说明：

将游戏中所有的矿辞条目名称输出到crafttweaker.log文件中。

如果为<name>提供值，所有注册到该矿辞的物品的名称将被输出到crafttweaker.log文件中。

### 药水

用法：

`/crafttweaker potions`

`/ct potions`

说明：

将游戏中所有的药水名称输出到 crafttweaker.log 文件中。

### 配方名称

用法：

`/crafttweaker recipeNames`  
`/crafttweaker recipeNames [modid]`

`/ct recipeNames`  
`/ct recipeNames [modid]`

说明：

将游戏中所有的配方名称输出到 crafttweaker.log 文件中。  
可以提供<modid>来过滤结果。

### 配方

用法：

`/crafttweaker recipes`

`/ct recipes`

说明：

将游戏中所有的合成配方输出到 crafttweaker.log 文件中。

### 配方(手中)

用法：

`/crafttweaker recipes hand`

`/ct recipes hand`

说明：

将游戏中玩家手中物品的所有合成配方输出到 crafttweaker.log 文件中。

### 配方(熔炉)

用法：

`/crafttweaker recipes furnace`

`/ct recipes furnace`

说明：

将游戏中所有的熔炉配方输出到 crafttweaker.log 文件中。

### 脚本

用法：

`/crafttweaker scripts`

`/ct scripts`

说明：

发送一个可点击的链接来打开脚本目录。  
也可以从命令行将目录的绝对路径输出到日志中。

### 种子

用法：

`/crafttweaker seeds`

`/ct seeds`

说明：

将种子注册表中所有物品的列表输出到 crafttweaker.log 文件中。

### 语法

用法：

`/crafttweaker syntax`

`/ct syntax`

说明：

检测你的全部脚本，并输出它在你的语法中发现的所有错误。请注意，它不会重载你的脚本，你需要重启游戏才能看到它们的效果。

### Wiki

用法：

`/crafttweaker wiki`

`/ct wiki`

说明：

在浏览器中打开这个文档页面 (与 `/ct docs`相同)。

### ZsLint

用法：

`/crafttweaker zslint`

`/ct zslint` 

说明：

启动zslint套接字。

