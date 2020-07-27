# Vue项目中的配置

    对比Angular的支持，Vue的支持就像是后妈养的，有很多东西都要自己去配置
    
## 经常遇到的问题

- webpack支持

    对于 Vue-cli 3.x 和 4.x, 将`Preferences | Languages & Frameworks | JavaScript | Webpack` 指向 `node_modules/@vue/cli-service/webpack.config.js`
    
    对于 Vue-cli 2.x, 将`Preferences | Languages & Frameworks | JavaScript | Webpack` 指向 `build/webpack.base.conf.js`
    
        每次都要配置，十分蛋疼，不知道有没有更好的解决方案 🤔
?

- vue文件代码格式化

    用`eslint`+`prettier`+`editorconfig`，不用的话用自带的格式化工具配置起来十分麻烦。
    
    TS项目的配置相对麻烦，样例项目：(🚧有空上传)
    
    最近的2020.1.4版本支持用`prettier`代理默认的格式化工具，舒服多了（VSC早都有的功能等了这么久☹）
