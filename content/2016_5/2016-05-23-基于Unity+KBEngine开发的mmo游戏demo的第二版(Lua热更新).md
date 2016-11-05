* 基于Unity+KBEngine开发的mmo游戏demo的第二版，主要工作是将KBE的客户端插件以及大部分游戏逻辑Lua化，实现客户端热更新。
* 运行前需要先点击LuaFramework->Build XXX Resource来创建游戏资源的assetbundle, 并点击Lua->Generate All来wrap一些C#代码到lua，这部分有疑问可以查看ulua官方教程https://github.com/jarjin/LuaFramework_UGUI。
* 目前游戏内容并没有实现完全，可以仿照游戏第一版https://github.com/liuxq/TestGame中的C#逻辑改写Lua代码补全游戏功能。
* 服务器使用kbengine-0.8.2版本，服务器脚本在：https://github.com/liuxq/MyGameServerAssets

* github地址：https://github.com/liuxq/StriveGame

###### lua代码结构说明:
![ui-demo](https://raw.githubusercontent.com/liuxq/StriveGame/master/structure.png)
###### ip、port等配置位置：
![ui-demo](https://raw.githubusercontent.com/liuxq/StriveGame/master/config.png)
###### 游戏截图:
![ui-demo](https://raw.githubusercontent.com/liuxq/StriveGame/master/strivegamedemo.png)