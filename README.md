# 2025订单生产地图看板

这是一个静态 GitHub Pages 看板，用于展示 2025 年订单生产表中的国家/地区、产品销量与订单等级关系。

## 使用方式

将本目录所有文件上传到 GitHub 仓库根目录或 `docs/` 目录，然后在仓库 Settings -> Pages 中选择对应分支和目录发布。

入口文件：

- `index.html`

## 数据口径

- 销量：出货数量
- 订单等级：按唯一订单号统计
- 地图：只展示可识别国家/地区，未定位值在数据质量表中列出

## 文件说明

- `index.html`：看板页面
- `dashboard_data.json`：聚合后的看板数据
- `assets/leaflet.css`、`assets/leaflet.js`：本地 Leaflet 地图库资源
