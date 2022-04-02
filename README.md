# Environment-install-of-vue
VUE环境配置

## 安装脚手架@vue/cli
npm install -g @vue/cli
vue -V

## 更换淘宝源(2022/04/02)
npm install -g cnpm --registry=https://registry.npmmirror.com

## 创建一个项目测试环境
#### 直接使用create创建
vue create project-test
#### 使用图形页面创建
vue ui

## 安装必要插件(vue-router,vuex)
可在图形界面一键操作
vue-cli-plugin-axios非必要，以使用以下axios依赖为主

## 安装必要依赖(axios)

## 关闭eslint校验
打开package.json，在rules下添加
"no-unused-vars": "off"
