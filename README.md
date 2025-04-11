# 家庭相册网站

一个温馨的家庭相册网站，用于记录和分享家庭的美好时刻。

## 功能特点

- 📸 照片管理：上传、整理和分享家庭照片
- 👨‍👩‍👧‍👦 成员信息：记录家庭成员的基本信息和照片
- 📅 日历记事：记录重要日期和事件
- 🎨 现代化界面：响应式设计，支持各种设备
- 🔒 安全可靠：本地存储，保护隐私

## 项目结构

```
family-album/
├── index.html          # 首页
├── photos.html         # 照片页面
├── members.html        # 成员信息页面
├── calendar.html       # 日历记事页面
├── upload.html         # 照片上传页面
├── css/               # 样式文件
│   └── style.css      # 主样式文件
├── js/                # JavaScript文件
│   └── data.js        # 数据管理
└── images/            # 图片资源
```

## 技术栈

- HTML5
- CSS3
- JavaScript (ES6+)
- Font Awesome 图标
- 响应式设计

## 本地运行

1. 克隆仓库：
```bash
git clone [repository-url]
cd family-album
```

2. 使用本地服务器运行（例如使用 Python）：
```bash
# Python 3
python -m http.server 8000

# Python 2
python -m SimpleHTTPServer 8000
```

3. 在浏览器中访问：
```
http://localhost:8000
```

## 贡献指南

1. Fork 项目
2. 创建特性分支 (`git checkout -b feature/AmazingFeature`)
3. 提交更改 (`git commit -m 'Add some AmazingFeature'`)
4. 推送到分支 (`git push origin feature/AmazingFeature`)
5. 开启 Pull Request

## 许可证

MIT License - 详见 LICENSE 文件 