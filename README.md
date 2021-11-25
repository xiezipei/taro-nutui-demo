# taro-nutui-demo

[toc]

```sh
# 1. 初始化项目
taro init [项目名]

# 2. 进入项目目录
cd [项目名]

# 3. 跑起项目
yarn run dev:h5

# 4. 修改配置 
修改 `config/index.js` 中 `outputRoot` 的值 `dist` 为 `dist/${process.env.TARO_ENV}`，让多端打包后共存
```
