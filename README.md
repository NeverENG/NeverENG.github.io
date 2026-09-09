# 林默 · 随笔与观察

这是一个使用 Hugo 构建的个人博客，采用无第三方主题的轻量模板，强调长文阅读、个人介绍与清晰导航。

## 本地运行

```bash
hugo server -D
```

然后打开 `http://localhost:1313/`。

## 内容

- `content/posts/`：文章内容
- `content/about/`：个人信息
- `assets/css/main.css`：站点视觉与响应式样式
- `static/images/avatar.svg`：默认编辑风格头像，可替换为你的 QQ / 微信头像

个人资料集中在 `hugo.toml` 的 `[params]` 中，可修改邮箱、GitHub、QQ 和微信信息。

文章分类用于表达长期主题：`读书`、`日常`、`技术本质`、`技术与工具`、`AI 思考`。`tags` 只用于补充更具体的关键词。
