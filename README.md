# 每日英语词本

一个自己用的背单词 + 日常英语短语网站。

- **听**：单词、短语、例句都能朗读，可选英音 / 美音，可调语速，有慢速播放。
- **拼写练习**：听读音后用键盘打字，字母实时对错提示。
  - `Enter` 检查 / 下一个
  - `Esc` 重听
  - `Tab` 提示一个字母
  - 拼错要照着答案再打对一遍；错过的词进「错题本」。
- **自己的词库**：可以单条添加或批量导入（每行 `英文 | 中文 | 例句`），保存在浏览器本地。

## 在线使用

开启 GitHub Pages 后访问：https://siyuan-she2026.github.io/English-Practice/

## 修改内置词库

打开 `index.html`，找到 `const WORDS` 和 `const PHRASES` 两个列表，按同样格式增删即可。

朗读使用浏览器自带的语音（Web Speech API），推荐 Chrome、Edge 或 Safari。
