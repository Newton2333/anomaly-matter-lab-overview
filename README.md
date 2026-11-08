# ANOMALY

A small experiment in fluid, light and motion by **Newton Quan**.

[在线体验 / Live demo](https://anomaly-matter-lab.vercel.app/) · Desktop browser · English / 中文

水银流动、玻璃折光、星尘聚散。移动鼠标牵引，长按聚拢，松手散开，也可以调节活跃程度或暂停留下一帧。

## 制作思路

从粒子模拟出发，把鼠标操作变成牵引、聚拢和释放，再用不同的材质与光照表现水银、玻璃和星尘。圆环和界面尽量克制，让注意力留在物质的变化上。画质会根据设备性能调整。

## 使用的技术

- Three.js：三维场景、材质和光照
- WebGPU / WebGL：实时渲染与浏览器兼容
- JavaScript / TypeScript、Vite：交互与构建

流体部分基于 Daniel Greenheck 的 [Three.js Particle Fluids](https://github.com/dgreenheck/threejs-particle-fluids) 调整。这里只记录项目思路和使用的技术。
