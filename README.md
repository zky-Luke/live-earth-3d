# 🌍 Live Earth 3D - 实时活动地球

一个基于 Three.js 构建的实时 3D 地球可视化站点，展示全球活动热点与动态效果。

![Live Earth 3D](https://img.shields.io/badge/Three.js-r128-blue?style=flat-square&logo=three.js)
![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-Live-brightgreen?style=flat-square&logo=github)
![License](https://img.shields.io/badge/License-MIT-yellow?style=flat-square)

## ✨ 特性

- 🌏 **高精度地球模型** - 基于真实地球纹理，含法线贴图和高光贴图
- 🌃 **夜晚城市灯光** - 展示全球城市夜间灯光分布
- ☁️ **动态云层** - 独立旋转的半透明云层效果
- ✨ **星空背景** - 8000+ 粒子构成的星空
- 🌊 **大气层光晕** - Shader 实现的动态大气光晕
- 📍 **活动热点** - 全球主要城市活动脉冲动画
- 🔗 **网络连接** - 城市间动态连接线

## 🎮 交互功能

| 功能 | 说明 |
|------|------|
| **自动旋转** | 控制地球自转开关 |
| **活动脉冲** | 显示/隐藏全球活动热点 |
| **卫星视角** | 切换到近距离侧面视角 |
| **云层效果** | 显示/隐藏云层 |
| **鼠标拖拽** | 自由旋转视角 |
| **滚轮缩放** | 调整观察距离 |

## 🚀 在线预览

**🔗 https://zky-luke.github.io/live-earth-3d/**

## 🛠️ 本地运行

```bash
# 克隆仓库
git clone https://github.com/zky-Luke/live-earth-3d.git
cd live-earth-3d

# 启动本地服务器
python3 -m http.server 8080
# 或
npx serve .

# 打开浏览器访问
open http://localhost:8080
```

## 📦 技术栈

- [Three.js](https://threejs.org/) - WebGL 3D 库
- [OrbitControls](https://threejs.org/examples/?q=orbit#misc_controls_orbit) - 相机轨道控制
- [GitHub Pages](https://pages.github.com/) - 静态站点托管

## 📝 资源来源

地球纹理来自 Three.js 官方示例：
- `earth_atmos_2048.jpg` - 地球大气纹理
- `earth_specular_2048.jpg` - 高光贴图
- `earth_normal_2048.jpg` - 法线贴图
- `earth_lights_2048.png` - 夜晚灯光
- `earth_clouds_1024.png` - 云层纹理

## 📄 许可证

MIT License © 2026

---

> Made with ❤️ using Three.js
