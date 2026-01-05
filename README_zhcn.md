# ValhallaMMO-ItemsAdderFIX
让你的ValhallaMMO资源包不再与ItemsAdder冲突。

[[English README]](README.md)

## 这是什么？
这个神奇的扩展可以让你的ValhallaMMO资源包不再与你的ItemsAdder物品纹理冲突，也对其他使用IA的资源包生效（例如Slimefun资源包）

已测试与ValhallaMMO Premium和ValhallaTrinkets兼容，如果你使用[Piles-ItemsAdderFIX](https://github.com/Shimamura-Tako/Piles-ItemsAdderFIX)的话，也与Piles兼容。

**目前，该扩展不支持1.21.11，因为ItemsAdder尚未更新对它的支持，这不是我的问题。**

## 怎么使用？
0. 下载这个储存库并解压在你的服务器主机上

1. 将`valhallafix`文件夹放置在contents目录下，执行`/iareload`和`/iazip`并加载`generated.zip`资源包

2. 两种方法二选一：

- 从储存库根目录中获取正确版本的修改过后的资源包，并将其加载在游戏中，置于`generated.zip`之上 **(推荐)**

- **或者**修改`ValhallaMMO`资源包，删除压缩包中`assets/minecraft/items`*目录下的所有文件，并将其加载在游戏中，置于`generated.zip`之上

- - (*: 在1.21.3及以下的版本里是`assets/minecraft/models/item/*.json`，并且不要删除同目录下其他文件夹的内容)

3. 完事！现在你可以尽情地创建任何物品，而无需担心它会与ValhallaMMO纹理冲突

4. 建议使用BungeeResourcepacks或其他插件将资源包按正确的顺序发送给玩家

## 我遇到了问题！
请在此储存库下提交issue，而不是跑去ValhallaMMO的储存库，因为这个扩展是由我创建的，而不是Athlaeos。

## 将来的计划
- ~兼容弓和弩~ 2025/12/23
- ~兼容旧版本服务器~ 2026/01/06
<!-- - 将所有的`textures`方法替换成`model_path`方法 (可能不会，因为这不是必须的，并且需要我重写大量配置)-->
