# Beijing Rental Happiness Research

一个用于北京共同居住选址的 Codex skill：把双方通勤、早晚高峰、租金、配套和住户真实评价统一成可核验的小区排名与“居住幸福指数”。

## 使用

将其放在 Codex 用户 skill 目录，例如：

`C:/Users/<用户名>/.codex/skills/beijing-rental-happiness-research/`

使用时提供：

- 每位居住成员的工作地点和出行方式；
- 出发时段及可接受通勤时间；
- 租金、户型、租期和明确排除项；
- 可选：高德 Web 服务 Key（建议通过 `AMAP_WEB_API_KEY` 提供）。

## 安全

- 仓库不保存任何高德 Key、登录 Cookie 或个人敏感地址。
- Skill 不以绕过登录、验证码或平台限制为目标。
- 通勤时间会区分平台估算、高峰预测、住户反馈和推断，不承诺固定到达时间。
