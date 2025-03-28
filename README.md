# Three.js 工厂可视化项目

这是一个使用 Three.js 和 Vue.js 构建的 3D 工厂可视化项目。它展示了工厂模型和围绕工厂移动的汽车。

## 功能特点

- 加载并显示 3D 工厂模型（factory.glb）
- 加载并显示 3D 汽车模型（car.glb）
- 汽车围绕工厂沿方形路径匀速运动
- 支持模型查看的轨道控制
- 支持通过变换控制器选择和操作 3D 对象

## 安装和运行

1. 安装依赖：
   ```
   npm install
   ```

2. 启动开发服务器：
   ```
   npm run dev
   ```

3. 构建生产版本：
   ```
   npm run build
   ```

## 添加模型文件

项目需要以下模型文件才能正常工作：

1. `public/models/factory.glb` - 工厂模型
2. `public/models/car.glb` - 汽车模型

您需要将这些模型文件放置在上述指定的位置。如果找不到这些模型，程序会自动创建简单的几何体替代。

## 控制方式

- 鼠标左键：旋转视角
- 鼠标右键：平移视角
- 鼠标滚轮：缩放视角
- 点击对象：选择对象
- G 键：切换到平移模式
- R 键：切换到旋转模式
- S 键：切换到缩放模式
- Esc 键：取消选择
