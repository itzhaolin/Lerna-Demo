### lerna的使用

1. 全局安装lerna `cnpm install lerna -g`

2. 创建文件夹`my-lerna`

3. 初始化`lerna init`,  获得packages,lerna.json,package.json三个文件

4. 在packages中创建module1, module2文件夹, `npm init -y`初始化package文件

5. 用脚手架创建项目, 拖至module2内部

6. 使用`lerna bootstrap`各自模块安装依赖, `lerna bootstrap --hoist`安装依赖至根目录

7. 启动module2的项目`lerna run start --scope=module2`

