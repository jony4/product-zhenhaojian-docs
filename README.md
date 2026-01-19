# 帧好剪文档

帧好剪官方文档，基于 [Mintlify](https://mintlify.com) 构建。

## 文档结构

```
docs/
├── index.mdx                    # 首页
├── docs.json                    # 文档配置文件
├── guide/                       # 用户指南
│   └── quick-start.mdx          # 快速开始
├── solutions/                   # 场景化剪辑
│   ├── smart-remix.mdx          # 智能混剪
│   ├── short-drama.mdx          # 短剧创作
│   ├── live-highlights.mdx      # 直播切片
│   └── multi-pic-commentary.mdx # 多图配音
├── tools/                       # AI 工具
│   ├── compliance.mdx           # 内容风控
│   ├── video-summary.mdx        # 视频摘要
│   ├── subtitle.mdx             # 智能字幕
│   ├── video-translation.mdx    # 视频翻译
│   ├── audio-separation.mdx     # 音频分离
│   └── smart-cutout.mdx         # 智能抠图
├── examples/                    # 场景示例
│   ├── corporate-video.mdx      # 企业宣传片
│   ├── product-showcase.mdx     # 产品展示视频
│   ├── social-media.mdx         # 社交媒体内容
│   └── education.mdx            # 教育培训视频
├── api/                         # API 手册
│   └── introduction.mdx         # API 介绍
├── faq/                         # 常见问题
│   └── general.mdx              # 通用问题
├── changelog/                   # 更新公告
│   └── index.mdx                # 产品公告
├── legal/                       # 条款与协议
│   ├── terms.mdx                # 服务条款
│   └── privacy.mdx              # 隐私政策
├── images/                      # 图片资源
│   └── tools/                   # 工具相关图片
└── css/                         # 样式文件
    └── global.css               # 全局样式
```

## 文档导航

### 用户指南
- **开始使用**
  - 首页介绍
  - 快速开始指南

- **场景化剪辑**
  - 智能混剪：AI 自动剪辑，快速生成精彩视频
  - 短剧创作：多模态 AI 辅助短剧创作
  - 直播切片：自动提取直播精彩片段
  - 多图配音：图片配音，快速生成视频

- **AI 工具**
  - 内容风控：智能检测违规内容
  - 视频摘要：自动生成视频摘要
  - 智能字幕：自动识别并生成字幕
  - 视频翻译：多语言视频翻译
  - 音频分离：人声/背景音分离
  - 智能抠图：AI 自动抠图

- **常见问题**
  - 通用问题解答

### 场景示例
- **营销推广**
  - 企业宣传片：快速制作专业企业宣传视频
  - 产品展示视频：打造吸引眼球的产品展示内容

- **内容创作**
  - 社交媒体内容：适配各大平台的短视频制作
  - 教育培训视频：专业的在线课程和教学视频

### API 手册
- API 介绍和接入指南

### 更新公告
- 产品功能更新和公告

### 条款与协议
- 服务条款
- 隐私政策

## 本地开发

### 安装 Mintlify CLI

```bash
npm i -g mintlify
```

### 本地预览

```bash
cd docs
mintlify dev
```

文档将在 `http://localhost:3000` 启动。

### 文档编写规范

1. **文件命名**
   - 使用小写字母和连字符：`quick-start.mdx`
   - 避免使用空格和特殊字符

2. **Front Matter**
   ```yaml
   ---
   title: "页面标题"
   description: "页面描述"
   ---
   ```

3. **Mintlify 组件**
   - `<Card>`: 卡片组件
   - `<CardGroup>`: 卡片组
   - `<Tabs>`: 标签页
   - `<Accordion>`: 折叠面板
   - `<Steps>`: 步骤指引
   - `<Tip>`: 提示信息
   - `<Warning>`: 警告信息
   - `<Frame>`: 图片框架

4. **内部链接**
   ```markdown
   [链接文字](/path/to/page)
   ```

5. **图片引用**
   ```markdown
   ![图片描述](/images/example.png)
   ```

## 部署

文档通过 Mintlify 平台自动部署，推送到主分支后自动更新。

访问地址：https://docs.cutcut.video

## 更新日志

### 2026-01-19
- ✨ 新增场景示例模块
  - 企业宣传片制作指南
  - 产品展示视频制作指南
  - 社交媒体内容制作指南
  - 教育培训视频制作指南
- 🔧 优化文档导航结构
- 📝 完善各场景的最佳实践和制作流程

### 历史版本
- 初始版本：用户指南、AI 工具、API 手册等基础文档

## 贡献指南

1. 在 `docs/` 目录下创建或编辑 `.mdx` 文件
2. 在 `docs.json` 中更新导航配置
3. 本地预览确认无误
4. 提交代码并推送

## 相关链接

- 官网：https://cutcut.video
- 产品地址：https://video.cutcut.video
- 文档地址：https://docs.cutcut.video
- Mintlify 文档：https://mintlify.com/docs
