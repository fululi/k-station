# K-STATION 仓库工作规则（任何 AI 会话/窗口必读）

1. **同一时间只允许一个会话修改本仓库。** 开始改之前先 `git pull --rebase origin main`，确认拿到最新代码。
2. 改完本地验证（JS 语法检查 + 截图渲染）后，提交并 `git push origin HEAD:main`；推送需走系统代理 `http://127.0.0.1:7897`。
3. 线上地址：https://fululi.github.io/k-station/ ，推送后约 1 分钟生效。
4. 不要删除他人（其他会话）已加的功能；有冲突以合并保留双方功能为原则。
5. 全部功能在单文件 `index.html` 内，保持单文件结构，不引入构建工具。
