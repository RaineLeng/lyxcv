# 冷语欣个人简历网站

about m, a grad student applying for pm jobs

这是一个基于 React 和 Tailwind CSS 构建的现代交互式简历网站。

## 如何运行

由于这是一个单文件应用（Single File Application），您不需要安装 Node.js 环境。

### 方法 1: 直接打开
双击 `index.html` 文件在浏览器中打开。

### 方法 2: 使用 Python 预览 (推荐)
为了确保所有脚本和图标正常加载，建议使用 Python 启动一个本地服务器：

1. 打开终端 (Terminal)
2. 运行以下命令：
   ```bash
   python3 -m http.server 8000
   ```
3. 在浏览器访问: `http://localhost:8000`

## 技术栈
- **React 18**: 用于构建用户界面组件
- **Tailwind CSS**: 用于原子化样式设计
- **Babel**: 用于浏览器端编译 JSX
- **Intersection Observer**: 用于实现滚动渐显动画
