# repo-monitor-reports

Ascend 仓库中文字数变化监控的**自动发布站点**（单文件 HTML 报表，无外部依赖）。

- 报表：<https://gomico.github.io/repo-monitor-reports/latest.html>
- 内容：每个仓在「前一天 19:00 → 当天 19:00」窗口内，指定路径下的中文净增字数、命中文件数、图片数（每张按 200 字折算）与近 7 天变化。
- 本仓库由 `repo-monitor` 采集程序**每天自动覆盖推送** `latest.html`（只保留最新一份，7 天窗口都嵌在该文件内），请勿手工编辑。
