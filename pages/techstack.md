## Main Tech Stack

2.1、<logos-nextjs class="w-20 mx-auto" />

<div class="text-sm mr-5 mt-5">

<logos-nextjs class="w-10 mx-auto" /> 是一个基于 React<logos-react />的开源框架，用于构建服务端渲染（SSR）和静态站点生成（SSG）的 Web 应用。主要优势如下：

- SSR（服务端渲染）：可以在服务器端直接渲染 React<logos-react />组件，提高首屏加载速度，优化 SEO 效果。
- SSG（静态站点生成）：在构建时生成静态HTML<logos-html-5 /> 文件，提高网站性能，减少服务器压力。
- 路由：<logos-nextjs class="w-10 mx-auto" /> 提供了基于文件系统的路由，自动将项目中的页面文件转换为路由，简化开发流程。

<img src="https://vip2.loli.io/2023/04/25/tOUPaKn93cFrs56.webp" alt="服务器端渲染" class="w-4/5 mx-8 mr-8" />

</div>

::right::

2.2、<logos-tailwindcss class="w-30" /> + <logos-supabase class="w-30" />

<div class="text-sm mt-5">

<logos-tailwindcss class="w-16 mx-auto" /> 是一个实用类优先的 CSS<logos-css-3 /> 框架，用于快速构建响应式界面。主要特点如下：

- 原子类设计：通过组合原子类快速创建自定义样式。
- 响应式设计：内置响应式功能，方便开发适配不同设备的样式。

<br>

<logos-supabase class="w-16 mx-auto" /> 是一个开源的 Firebase<logos-firebase />替代品，提供实时数据库、身份验证和存储等后端服务。在本博客系统中，我们主要使用了以下功能：

- 实时数据库：基于 PostgreSQL<logos-postgresql />的实时数据库服务，用于存储和获取评论数据。
- 匿名访问（Anon）：匿名用户可以访问评论数据，无需注册或登录，方便用户快速查看评论。
- 插入数据：使用 <logos-supabase class="w-16 mx-auto" /> API 在数据库中插入新评论，简化后端开发流程。
</div>