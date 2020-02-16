# z-react

## z-react是什么

基于react，react-router，antd，mobx的前端脚手架。您可以使用[z-cli](https://github.com/zhonggithub/z-cli)工具初始化您的项目工程. 可配合后端脚手架z-app使用。

1，FetchStore与FetchBase已经封装好了访问基于restful风格的后端api：create、upate、list、listAll、treeList、retrieve、updaeStatus。自定义资源或方法时只需要集成该类

2，ZAppLayout，ZAppTopNav，ZSdieNavigation，ZFooter是基础布局组件，如有自定义需求可修改这几个组件。

3，appStore实现了登录，动态获取左侧菜单功能

4，错误提示使用i18n

## 如何使用

* zcli init z-react@github
* input your project name
* cd your project
* npm install
* npm run build:dll
* npm run start

## 问题反馈

在使用中有任何问题，欢迎反馈给我，可以用以下联系方式跟我交流

* 邮件: quitjie@gmail.com
* QQ: 1006817093
