# A 股风险看板（手机公开版）

这是一个只读静态版手机看板。仓库与页面为公开内容，`arisk_data.json` 是公开行情与宏观数据；不要放入个人持仓、账号信息或 API 密钥。

## 自动更新

GitHub Actions 在工作日北京时间 11:00（UTC 03:00）运行 `update_arisk_data.py`，然后发布 `index.html` 和 `arisk_data.json` 到 GitHub Pages。也可以在 Actions 页面手动运行 `Refresh and deploy`。

数据源可能限流或暂时不可用；脚本会按各字段的日期和 stale 标记显示数据新鲜度。GitHub Pages 在中国大陆的访问速度和可用性不作保证。

