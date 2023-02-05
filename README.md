## 用于 debug 源码
debug-demo 目录是使用 vite 起的用于 debug 源码的项目。
```bash
# 安装依赖
yarn install
# 将源码打包到 build 目录
yran build:debug

# 将源码添加到 link
cd build/react
yarn link
cd ../react-dom
yarn link

# 进入 debug-demo 项目
cd ../../debug-demo

# link 到 debug-demo 项目
yarn link react
yarn link react-dom

# 安装依赖
yarn install

# 启动 debug-demo 项目
yarn dev
```
