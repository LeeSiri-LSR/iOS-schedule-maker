# 日程生成器 Schedule Maker v1.0

一个把日程一键添加到 Apple 日历的网页工具。单文件、纯前端、无需安装，数据保存在本地浏览器。

## 功能

- **单日程**：填表生成，一键跳转 Apple 日历 / Google 日历，或下载 .ics 导入
- **多日程**：粘贴整段中/英文安排，自动识别日期、时间、地点、标题，勾选后批量添加
- **日期识别**：支持相对日期（明天/下周）、时间区间（下午5点到7点）、日期区间（9月1日至9月3日）
- **地点识别**：自动提取「去/在 + 地点」（去chadstone看蜘蛛侠 → 地点 chadstone、事件 看蜘蛛侠）
- **自定义日历**：毛玻璃居中弹窗的高级日历选择器
- **中英文界面**：右上角一键切换，识别器同样支持英文
- 日程保存在浏览器 localStorage，可重复点击添加或删除

## 使用方法

用浏览器直接打开 `index.html` 即可。

## 识别示例

中文：

- 8月20日下午3点在图书馆和导师讨论论文
- 我在周六下午5点到7点有个presentation，周天下午3点钟要去chadstone看蜘蛛侠
- 9月1日至9月3日每天上午9点半上课

English:

- On Saturday from 5 to 7 pm I have a presentation
- Sunday at 3 pm go to Chadstone to watch Spider-Man
- Sep 1st to 3rd at 9:30 am lecture

## 许可证

免费使用，禁止商用。采用 [CC BY-NC 4.0](https://creativecommons.org/licenses/by-nc/4.0/)（署名-非商业性使用）授权，详见 [LICENSE.md](LICENSE.md)。
