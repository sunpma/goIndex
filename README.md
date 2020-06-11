# GoIndex-备份

# 使用

1.打开 https://install.kenci.workers.dev/ 网站,验证并获取代码

2.将代码部署到 [Cloudflare Workers](https://www.cloudflare.com/)

3.使用 https://cdn.jsdelivr.net/gh/sunpma/goIndex/app.js 替换获取代码中的js
> var html = `
> 
> ......
> <script src="替换"></script>
> 
> ......
> 
> `;

4.app.js的所有链接均连接仓库中的文件
