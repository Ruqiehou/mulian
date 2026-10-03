# 慕联门户网站

天狐慕氏联邦帝国官方门户网站，提供区划查询、交通票价、金价行情等公共服务。

## 功能特性

- **区划查询** - 查询帝国行政区划（府、道、总督区等）
- **铁路票价** - 计算各站点间最便宜路线及票价
- **机票票价** - 查询机场航线及机票价格
- **金价行情** - 查看每日金价走势

## 项目结构

```
mulian/
├── index.html              # 主页
├── pages/
│   ├── quhua_query.html    # 区划查询
│   ├── price_railway.html  # 铁路票价
│   ├── price_flight.html   # 机票票价
│   ├── gold.html           # 金价行情
│   └── tiaoli.html         # 条例公示
├── data/
│   ├── quhua.json          # 行政区划数据
│   ├── price_railway.json  # 铁路票价数据
│   ├── price_flight.json   # 机票票价数据
│   └── gold_prices.js      # 金价数据
├── assets/
│   └── common.css          # 公共样式
└── photos/                 # 图片资源
```

## 技术栈

- 纯静态页面（HTML + CSS + JavaScript）
- 无需后端服务，可直接打开或部署到静态托管

## 运行方式

### 本地运行

直接用浏览器打开 `index.html` 即可。

### 部署

将整个目录上传至任意静态网站托管服务（GitHub Pages、Vercel、Netlify 等）。

## 开发者

- 何嘉庆
- 慕轩岚

## 版权

版权所有 © 2019-2026 天狐慕氏联邦帝国  
慕联皇帝 慕怀宸
