# myHomePage

> oldplum 的个人静态主页，基于 [HomePage-Haze](https://github.com/Leapan-01/HomePage-Haze) 定制构建，部署于 Cloudflare Pages。

🌐 **线上访问**：[oldplum.dev](https://oldplum.dev/)

---

## 🌟 特色功能

1. **开屏动画**：左右遮罩拉扯展开动效与方块加载动画
2. **毛玻璃质感**：现代优雅的半透明毛玻璃主卡片背景
3. **交互反馈**：鼠标 3D 视差倾斜悬浮效果、头像 360° 旋转与物理微弹簧按压回弹
4. **视觉动效**：打字机格言动效、鼠标点击粒子扩散与波纹特效
5. **动态数据**：实时建站天数/时/分/秒统计、每日一言（Hitokoto）
6. **配置解耦**：所有个人信息、社交账号、跳转按钮统一于 `js/config.js` 中维护，无需修改 HTML/CSS

---

## 🛠️ 项目结构

```text
├── css/
│   └── style.css            # 页面主样式与动效
├── js/
│   ├── config.js            # 核心配置文件（个人信息、链接、外观在此修改）
│   ├── loading.js           # 开屏加载遮罩动效
│   ├── Tilt-Animation.js    # 主卡片 3D 视差与物理反馈
│   ├── Typewriter.js        # 打字机副标题动效
│   ├── click-particle.js    # 鼠标点击粒子动效
│   ├── Sitetime.js          # 建站运行时长统计
│   └── yiyan.js             # 一言 API 请求与渲染
├── index.html               # 页面结构入口
└── README.md
```

---

## ⚙️ 核心配置说明

本项目支持集中式配置驱动，编辑 [`js/config.js`](js/config.js) 即可快速自定义所有内容：

- **基础站点信息**：网站标题、SEO 描述、Favicon 图标、全屏背景壁纸
- **个人主卡片**：头像图片、站长昵称、开屏大标题、打字机副标题格言
- **社交媒体图标**：自由增减 GitHub、Twitter/X、B站、邮箱等图标与链接
- **快捷导航按钮**：自由配置博客、友链、个人网盘、个人邮箱服务等跳转卡片
- **页脚与统计**：建站起始时间（自动计算并实时刷新运行天数）、萌ICP备、备用站、自增版权年份

---

## 📦 依赖与鸣谢

* **基础主题**：基于 [Leapan-01/HomePage-Haze](https://github.com/Leapan-01/HomePage-Haze) 主题
* **图标库**：[Font Awesome 6](https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.2/css/all.min.css) (CDN by zstatic)
* **字体**：[Google Fonts - Noto Serif SC](https://fonts.googleapis.com/css2?family=Noto+Serif+SC:wght@200..900&display=swap)（思源宋体）
* **API 服务**：[Hitokoto 一言](https://developer.hitokoto.cn/)
* **灵感来源**：[imsyy/home](https://github.com/imsyy/home) & [StarnekOvO/myself-ghpage](https://github.com/StarnekOvO/myself-ghpage)

---

## 📄 许可证

本项目遵循 [GPL-3.0 License](https://www.gnu.org/licenses/gpl-3.0.html) 开源。
