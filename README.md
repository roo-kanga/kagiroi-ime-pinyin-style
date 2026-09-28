# kagiroi-ime-pinyin-style

# kagiroi 日语输入法 · 拼音输入法式配置

基于 [小狼毫（Rime）](https://github.com/rime/weasel) 和 [kagiroi](https://github.com/rimeinn/rime-kagiroi) 的日语输入法配置，用法接近汉语拼音输入法：打字直接出候选，数字键选词，空格上屏第一个。

A Pinyin-style Japanese input setup for Weasel (Rime) on Windows, based on rime-kagiroi.

## 功能

- **整句转换**：用 Mozc 的词典和连接代价做整句转换
- **预测转换**：打满 3 个假名后给出预测词，例如 `ariga` → ありがとうございます
- **打错纠正**：打错一个键导致后面的字母卡住时，自动给出纠正结果，例如 `arigtou` → ありがとう
- **商务用语**：140 多条邮件定型文，例如 `osewaninatteorimasu` → お世話になっております
- **分段输入修正**：减少「だけよ → 焚けよ」「だますき → 玉好き」这类误转换
- **按键**：数字选词、空格上屏、`=` / `-` 翻页（`-` 平时仍打长音「ー」）、`.` 直接出「。」、Shift+6 出「……」、Ctrl+i 转片假名

## 下载与安装

1. 安装小狼毫 0.17.4：<https://github.com/rime/weasel/releases>
2. 在本仓库的 [Releases](../../releases) 页面下载 `kagiroi-share.zip`
3. 解压后双击 `install.bat`，按提示完成
4. 按 Win+空格 切到小狼毫，使用「日语・整句」

详细用法（按键表、自己加词、卸载）见压缩包里的「使用说明.txt」。

## 许可

- kagiroi：GPL-3.0。本配置对其做了修改，修改内容见压缩包里的 `licenses/修改说明.txt`
- 词典数据：[Google Mozc](https://github.com/google/mozc)
- 本仓库以 GPL-3.0 发布
