# Felix 的技术博客

> 嵌入式 Linux 软件开发技术分享 —— 关注网络应用、中间件与系统内核。

本仓库是 [Felix 的技术博客](https://alanfelixchen.github.io) 的源码，基于 **Jekyll + minima** 主题构建，通过 **GitHub Pages** 发布。

---

## 🌐 在线访问

| 内容 | 地址 |
| --- | --- |
| 博客主页 | https://alanfelixchen.github.io |
| **简历模板（点击即用）** | https://alanfelixchen.github.io/assets/doc/3-5-years-resume-template.html |
| RSS 订阅 | https://alanfelixchen.github.io/feed.xml |

---

## ⭐ 亮点：3-5 年经验简历模板

仓库里除博客文章外，还带一份**可直接在浏览器里编辑**的简历模板，面向 3-5 年经验的技术岗位，重点适配嵌入式 Linux 方向。

打开链接即可填写、导出，**无需安装、无需登录、无需联网**。

**主要特性**

- **三档自适应**：按「3-4 年 / 4-5 年 / 接近 5 年」三档，自动调整篇幅上限、项目结构与技能栈写法
- **三种版式**：经典单栏（投递首选，机器可读性最好）、科技蓝（双栏，邮件直投）、简约极简（打印干净）
- **双格式导出**：一键导出 PDF（标准 A4）与 Word（.docx）；另可复制纯文本，粘贴进网申表单
- **本地自动保存**：输入内容只留在你自己的浏览器里，不上传、不外发
- **打印零泄漏**：编辑提示、档位徽章与版权行都不会印进最终成品

配套文档与本模板口径一致：**《个人简历制作指南（3-5年经验）》**、**《个人简历模板与使用说明（3-5年经验）》**，均可在[博客主页](https://alanfelixchen.github.io)阅读。

![简历模板预览](assets/images/resume-template-preview.png)

---

## 📚 博客内容

围绕嵌入式 Linux 软件开发，目前沉淀的方向包括：

- **中间件与通信**：ZeroMQ 通信实践
- **工程化构建**：嵌入式 C/C++ 项目的 CMake 构建实践
- **日志组件**：spdlog 从入门到最佳实践
- **求职工具**：简历制作指南与可交互简历模板
- **站点本身**：博客搭建流程

完整文章列表见[博客主页](https://alanfelixchen.github.io)。

---

## 📁 目录结构

```
.
├── _posts/                                  # 博客文章
├── assets/
│   ├── doc/
│   │   └── 3-5-years-resume-template.html   # 简历模板（单文件，零依赖）
│   └── images/                              # 文章配图
├── _config.yml                              # Jekyll 站点配置
├── index.markdown                           # 首页
├── about.markdown                           # 关于页
├── 404.html                                 # 404 页面
├── Gemfile / Gemfile.lock                   # Ruby 依赖声明
├── LICENSE.md                               # 许可协议（内容 + 代码分层授权）
└── README.md                                # 本文件
```

---

## 🛠 本地运行

需要 **Ruby 3.x** 与 **Bundler**：

```bash
# 1. 安装依赖
bundle install

# 2. 启动本地服务
bundle exec jekyll serve

# 3. 浏览器访问
# http://127.0.0.1:4000
```

> 提示：修改 `_config.yml` 后需要重启服务，Jekyll 不会自动重载该文件。

---

## 📄 许可与版权

本仓库内容与代码**分层授权**，完整条款见 [LICENSE](LICENSE.md)：

| 内容 | 授权方式 |
| --- | --- |
| **博客文章与原创图文** | 采用 [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/deed.zh-hans) 协议：转载须署名并附原文链接，**禁止商业使用**，衍生作品须以相同协议共享 |
| **简历模板与站点代码** | © 2026 AlanFelixChen（GitHub: [@AlanFelixChen](https://github.com/AlanFelixChen)）。**个人求职使用免费**，可自由修改；**禁止转售、二次分发或商用集成**；商业授权请另行联系 |

> 简历模板为工具，**不对求职结果作任何承诺或保证**。
>
> 商业授权与合作咨询请发送至 **chenze_hust@foxmail.com**，完整条款以 [LICENSE](LICENSE.md) 为准。

---

## 📬 联系方式

- **Email**：chenze_hust@foxmail.com
- **GitHub**：[@AlanFelixChen](https://github.com/AlanFelixChen)
- **博客**：[alanfelixchen.github.io](https://alanfelixchen.github.io)

---

<sub>© 2026 AlanFelixChen · 保留所有权利</sub>
