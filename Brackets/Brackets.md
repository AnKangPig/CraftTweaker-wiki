# 尖括号引用

[英文wiki](https://docs.blamejared.com/1.12/en/Brackets/Brackets)

ZenScript 使用尖括号引用游戏中诸如物品、实体、矿物词典等游戏对象。

## 如何使用尖括号

ZenScript 中的尖括号包含 `<` 和 `>` 字符。在这两个字符间的任意字符串均被定义为尖括号引用。

尖括号引用的经典示例是物品尖括号引用，用于访问游戏内的物品。

## 示例

一个[物品尖括号引用](/Vanilla/Brackets/Bracket_Item/)的例子：

```zenscript
<minecraft:apple>
```

这将允许你访问游戏中的 `苹果` [物品](/Vanilla/Items/IItemStack/)。

一个[矿物词典尖括号引用](/Vanilla/Brackets/Bracket_Ore/)的例子：

```zenscript
<ore:ingotIron>
```

这将使你可以访问[矿物词典条目](/Vanilla/OreDict/IOreDictEntry/)中的 `ingotIron` 条目。
