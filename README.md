# 极简作品集网站

这个版本只包含：

- 项目名
- 项目视频
- 手机 / 电脑自适应

## 使用方法

1. 把 MP4 视频放到 `videos` 文件夹。
2. 视频文件名改成：
   - `project-1.mp4`
   - `project-2.mp4`
   - `project-3.mp4`
3. 用文本编辑器打开 `index.html`。
4. 修改 `<h2>...</h2>` 中的项目名称。
5. 双击 `index.html` 即可在浏览器本地预览。

## 增加项目

复制这一段：

```html
<article class="project">
  <h2>你的项目名</h2>
  <video controls preload="metadata" playsinline>
    <source src="videos/your-video.mp4" type="video/mp4" />
  </video>
</article>
```

粘贴到 `<section class="projects">` 内即可。

## 免费上线

可以直接部署到：
- GitHub Pages
- Vercel
- Netlify

静态网站本身不需要服务器。
