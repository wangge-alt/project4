# Phong 光照模型实验
这是计算机图形学课程中，基于 Taichi 实现的 Phong 局部光照模型实验。

## 🎯 实验目标
- 理解并实现 Phong 光照模型的三大分量：环境光（Ambient）、漫反射（Diffuse）、镜面高光（Specular）
- 通过光线投射（Ray Casting）渲染三维场景，并实现深度测试
- 通过 UI 交互面板实时调节光照参数，观察渲染效果变化

## 📦 运行环境
- Python 3.8+
- Taichi 1.7.0+

安装依赖：
```bash
pip install taichi
