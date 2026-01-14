# Spacebar Clicker - CPSTestGo

Spacebar Clicker - CPSTestGo 是一个专业的点击速度与反应能力训练平台，提供多种测试项目，支持多语言，记录历史成绩。

## 在线演示

- **在线演示**: [https://cpstestgo.com](https://cpstestgo.com)

## 主要功能

### 点击测试
- **单点击测试**: 支持1秒、2秒、5秒、10秒、15秒、30秒、60秒测试
- **双击测试**: 测试双击速度
- **三击测试**: 测试三击速度
- **Kohi点击测试**: 专业的Minecraft点击测试
- **空格点击测试**: 测试空格键点击速度

### 反应测试
- **简单反应时间测试**: 测试基本反应速度
- **颜色反应测试**: 测试颜色识别和反应速度
- **按键反应测试**: 测试按键反应速度

### 鼠标相关测试
- **鼠标拖动测试**: 测试鼠标拖动精度和速度
- **鼠标滚动测试**: 测试鼠标滚动速度

### 键盘测试
- **键盘按键测试**: 测试键盘按键功能
- **打字测试**: 支持1分钟、3分钟、5分钟、10分钟、15分钟测试

### 游戏类测试
- **目标消除游戏**: 测试反应速度和手眼协调能力
- **空格键点击游戏**: 通过点击键盘空格键，获取点击次数，解锁强力BUFF，购买BUFF获得更多点击次数

## 技术栈

- **前端框架**: Vue 3 + TypeScript
- **构建工具**: Vite
- **路由管理**: Vue Router 4
- **国际化**: 自定义i18n方案
- **UI组件**: 自定义组件
- **样式**: CSS3
- **打包优化**: Vite Plugin Compression

## 快速开始

### 安装依赖

```bash
npm install
```

### 开发模式

```bash
npm run dev
```

### 构建生产版本

```bash
npm run build
```

### 预览生产构建

```bash
npm run preview
```

## 部署方式

### 静态部署

将 `dist` 目录部署到任何静态网站托管服务：
- GitHub Pages
- Vercel
- Netlify
- 阿里云OSS
- 腾讯云COS

### Nginx部署

```nginx
server {
    listen 80;
    server_name your-domain.com;
    root /path/to/your/dist;
    index index.html;

    location / {
        try_files $uri $uri/ /index.html;
    }
}
```

## 多语言支持

- 简体中文 (zh-CN)
- 英语 (en)
- 日语 (ja)
- 韩语 (ko)

## 贡献指南

欢迎提交 Issue 和 Pull Request！

## 许可证

MIT License
