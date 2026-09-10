# Xiaohongshu Image Post Skill

[中文](#中文) | [English](#english)

## 中文

将用户提供的文字、图片或链接转成可发布的小红书图文内容。

### 能做什么

- 先提炼主题、核心观点、受众、页面结构和文案方向；
- 生成统一视觉的图片、标题与发布文案；
- 页面需要文字时，将确认后的文案直接排入图片；
- 保留来源链接，并标出无法核实的信息；
- 不会未经授权改图或发布到小红书。

### 安装

将 `.agents/skills/xiaohongshu-image-post/` 复制到你的项目根目录的 `.agents/skills/` 下，然后在 Codex 中输入 `$xiaohongshu-image-post`，或直接提出符合描述的图文创作请求。

### 适用场景

```text
把这篇公司介绍链接做成 5 张小红书图文，文字直接放进图片，附发布文案。
```

### 注意

- 链接无法读取、需要登录或验证码时，Skill 会停止并请求原文、截图或替代链接。
- 使用图片时，未经授权不会改变原图风格。
- 此仓库不包含示例生成图、用户资料或访问凭据。

## English

Turn user-provided text, images, or links into publication-ready Xiaohongshu image posts.

The skill summarizes sources, separates facts from creative choices, generates a consistent visual set with in-image text when needed, and returns a title, caption, source notes, and verification status. It does not restyle user images or publish to an external platform without explicit authorization.

## License

[MIT](LICENSE)
