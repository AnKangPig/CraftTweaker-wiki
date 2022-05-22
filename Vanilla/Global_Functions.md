# 全局函数

[英文wiki](https://docs.blamejared.com/1.12/en/Vanilla/Global_Functions)

全局函数是不需要[导入](/AdvancedFunctions/Import/)就可以调用的函数。  
这是列表：

## print

将字符串信息打印到CraftTweaker的日志中。

```zenscript
//print(字符串信息);
print("Hello World!");
```
不返回任何内容。

## totalActions
```zenscript
//totalActions();
totalActions();
```
返回一个int，显示注册了多少个全局函数。

## enableDebug

启用调试模式。  
不过，最好还是用[调试预处理器](/AdvancedFunctions/Preprocessors/DebugPreprocessor/)。

```zenscript
//enableDebug();
enableDebug();
```
不返回任何内容。

## isNull

检查给定对象是否为空。  
对数据类型无效！

```zenscript
//isNull(Object o);
isNull(<minecraft:dirt>);
```
返回一个boolean  
注意：如果这个函数对您不起作用，请尝试将对象转换为bool  
`<minecraft:dirt> as bool`


## instanceof(类型判断)

```zenscript
entity instanceof IEntity;
```
返回一个boolean


## max

```zenscript
//max(int number1, int number2);
max(10, 11);
```
返回更大的那个数字

## min

```zenscript
//min(int number1, int number2);
min(10, 11);
```
返回更小的那个数字

## pow(次方)

```zenscript
//pow(double number1, double number2);
pow(2.0, 4.0);
```
返回一个double



## 全局字段

| 字段      | 描述                                                                                    |
|------------|------------------------------------------------------------------------------------------------|
| brewing    | 请访问[Brewing Handler](/Vanilla/Recipes/Recipes_Brewing_Stand/)                        |
| client     | 请访问[client Methods](/Vanilla/Game/IClient/)                                              |
| events     | 请访问[Event Handler](/Vanilla/Events/IEventManager/)                                   |
| format     | 请访问[Formatting Handler](/Vanilla/Utils/IFormatter/)                                  |
| furnace    | 请访问[Furnace Handler](/Vanilla/Recipes/Furnace/Recipes_Furnace/)                      |
| game       | 请访问[Game functions](/Vanilla/Game/IGame/)                                                |
| itemUtils  | 请访问[ItemUtils Handler](/Vanilla/Utils/IItemUtils/)                                   |
| loadedMods | 请访问[loaded Mods list](/Vanilla/Game/Mods/)                                           |
| logger     | 请访问[logger](/Vanilla/Utils/Logger/)                                                  |
| oreDict    | 请访问[oreDictionary Handler](/Vanilla/OreDict/IOreDict/)                               |
| recipes    | 请访问[Recipe Handler](/Vanilla/Recipes/Crafting/Recipes_Crafting_Table/)               |
| server     | 请访问[server Methods](/Vanilla/Game/IServer/)                                              |
| vanilla    | 请访问原版函数(目前仅[vanilla.seeds](/Vanilla/Recipes/Seeds/)可用) |
