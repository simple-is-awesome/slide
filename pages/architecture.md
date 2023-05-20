## System Architecture

![System Architecture](https://vip2.loli.io/2023/05/19/jc8h1kLxlK6y5me.webp)

访客访问网站，先来到cloudflare处，如果请求的是ssg静态生成的页面，则cloudflare直接将结果响应给用户；如果请求的是
ssr服务器端渲染生成的页面，则cloudflare起到前置代理的作用，转发请求、转发响应。