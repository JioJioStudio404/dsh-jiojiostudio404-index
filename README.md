# dsh-jiojiostudio404-index

JioJioStudio404 开源的 DeepSeek Harness 插件索引。添加到 DeepSeek Harness 后，可以在插件页的「发现」中浏览、安装这些插件，并在有新版本时收到提示。

## 添加索引

1. 打开 DeepSeek Harness 的**插件**页，在**实验性插件**中打开**自定义插件索引**。
2. 切换到**发现**，点击**添加索引源**，填入：

   ```
   https://raw.githubusercontent.com/JioJioStudio404/dsh-jiojiostudio404-index/main/index.json
   ```

3. 在列表中选择插件并确认安装。安装后请重启 DeepSeek Harness。

从索引安装的插件，发布新版本后会显示**有新版本**，可在应用内更新。

## 收录的插件

| 插件 | 说明 |
|---|---|
| [国内模型（dsh-cn-models）](https://github.com/JioJioStudio404/dsh-cn-models) | 国内模型厂商接入：多 Key、余额与套餐额度、自动切换 Key |
| [国际模型（dsh-intl-models）](https://github.com/JioJioStudio404/dsh-intl-models) | 国际模型厂商与开源模型托管平台接入：多 Key、每个 Key 的消费、自动切换 Key |
| [自定义模型（dsh-custom-models）](https://github.com/JioJioStudio404/dsh-custom-models) | 接入自己的 API 站点：多 Key、余额与计费记录、模型发现、模型核验 |
| [模型选择器（dsh-model-picker）](https://github.com/JioJioStudio404/dsh-model-picker) | 对话输入框的级联模型选择器：服务商 › 模型 › 推理等级 |
| [上下文占用条（dsh-context-bar）](https://github.com/JioJioStudio404/dsh-context-bar) | 输入框状态栏中的上下文占用条，标出自动压缩的位置 |

## 兼容性

索引中的每个版本都声明了兼容的 DeepSeek Harness 版本（`engines.dsh`），「发现」只推荐与当前 DeepSeek Harness 兼容的版本，安装时 DeepSeek Harness 会再次检查。每个版本固定到对应 GitHub Release 的提交。

## English

A DeepSeek Harness plugin index of JioJioStudio404's open-source plugins. In DeepSeek Harness, open **Plugins**, turn on **Custom plugin indexes** under the experimental plugins, then in **Discover** add the index source `https://raw.githubusercontent.com/JioJioStudio404/dsh-jiojiostudio404-index/main/index.json`. Each listed version declares the DeepSeek Harness versions it supports (`engines.dsh`) and pins its GitHub release commit.

## 许可证

MIT
