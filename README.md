# GoIndex-美化魔改版

# 使用

1.打开 https://install.kenci.workers.dev 验证并获取代码

2.将代码部署到 [Cloudflare Workers](https://www.cloudflare.com)

3.使用 https://cdn.jsdelivr.net/gh/sunpma/goIndex/app.js 替换掉刚才获得代码中的js链接，大概26行左右
> var html = `
> 
> ......
> <script src="替换"></script>
> 
> ......
> 
> `;
