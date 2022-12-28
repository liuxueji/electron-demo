# electron-todolist

## 基于Vue CLI Plugin Electron Builder创建electron桌面端项目

### 项目创建步骤
- `vue create electron-demo`
- `cd electron-demo`
- `vue add electron-builder`
  > 会提示你选择electron版本，选择最新的

- 启动程序 `npm run electron:serve`
此时，项目启动成功，一个最简单的桌面端项目就完成了
![image-20221228135055686](https://liuxueji.oss-cn-guangzhou.aliyuncs.com/img/image-20221228135055686.png)

- 目录结构
  > 和vue基本没什么差别，就多了一个background.js文件
  ![image-20221228134956927](https://liuxueji.oss-cn-guangzhou.aliyuncs.com/img/image-20221228134956927.png)

### electron 优势
技术栈基本和前端相似，所以前端使用electron基本没什么门槛；开发速度快；界面定制性强

### electron 劣势
打包文件很大，因为需要包括chromium；卡，不流畅；
使用electron需要花时间做优化