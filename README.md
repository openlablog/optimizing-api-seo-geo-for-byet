![](https://socialify.git.ci/openlablog/optimizing-api-seo-geo-for-byet/image?custom_language=JavaScript&description=1&forks=1&issues=1&language=1&name=1&owner=1&pattern=Solid&pulls=1&stargazers=1&theme=Auto&t=456789)

## 功能

1. 集成slowAES解密算法，解密中转页面
2. 跳过带 ?i=1 的中转页面，实现API请求和搜索引擎蜘蛛（SEO/GEO）能直接访问真实页面内容
3. 替换所有后端域名为前端域名

## 修改_worker.js里的后端域名

```javascript
...
// 这是后端域名，这里替换为你的InfinityFree免费主机的域名，不带 http 和 /
url.host = "how-to-remove-i-1.infinityfree.me";
...
```

## 部署

1. Fork本仓库
2. 创建workers部署即可
