# 基金净值看板

单文件静态页，打开即自动拉取当天数据。无后端、无构建。

- 数据源：腾讯财经（指数行情）、天天基金（基金历史净值）
- 回撤档位按基金风险等级分三套阈值，配置见 HTML 内 `FUND_TIER`

## 更新方式

1. 修改本地 `基金净值.html`
2. 复制覆盖 `deploy/index.html`
3. 重新推送 `main` 分支

## 部署

GitHub Pages：Settings → Pages → Source 选 `Deploy from a branch` → `main` / `/ (root)`
