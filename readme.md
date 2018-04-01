# ABOUT
> 通过nodejs express 构建后台服务,模拟接受请求

## Step
- 使用`express`初始化模板,如果临时搭建首先需要安装`express`框架,安装完成后初始化项目,
    - npm install -g express-generator@4(全局安装express 指定版本)
    - npm install express --save
- 使用`express`初始化模板.这里使用`ejs`模板
    + express --view=ejs ./(当前目录)
- 安装相关依赖
    + npm install
-  启动服务 
    - npm start(`start` 是 `package.json` 中的`script`配置)

## 注意
- `ejs`中 <%= %> 与 <%- %> 其中前者不转义html标签,后者转义

    
