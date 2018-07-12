# 项目介绍
> 本项目属于winchain官网项目；包含H5页面和其他相关页面

## 技术栈:
- jQuery 
- NodeJs
- swiper
- js原生

## 目录结构

```bash
├── server.js                       // 项目启动文件 (node命令启动该脚本)
├── public                          // 资源文件
│   └── css                         // css样式文件
│   └── font                        // font字体文件
│   └── image                       // 图片资源（所有的图片都得经过压缩）
│   └── img                         // 图片资源
│   └── img_web                     // img_web资源文件
│   └── js                          // js脚本文件
│   └── pdf                         // pdf文件
├── package.json                    // 本项目简介文件
├── .gitignore                      // Git提交被忽略设置文件
└── views                           // 所有页面文件资源
    └── winchain.html               // winchain介绍文件英文 (用于xx使用)
    └── winchain_cn.html            // winchain介绍文件中文 (用于xx使用)
    

```

## 搭建项目步骤

### 1.准备工作

本机已经安装 [node.js](https://nodejs.org/en/) ; 如果没有安装请自行安装 ; 安装完成以后自带 `npm` 包 ; 国内的`npm`速度较慢 ; 可以外挂`淘宝镜像cnpm` 将下面的代码复制到命令行执行 ;
**npm install -g cnpm --registry=https://registry.npm.taobao.org** ;
```
node -v     # 查看安装node版本号
npm -v      # 查看npm版本号
cnpm -v     # 查看cnpm版本号
```

### 2.运行项目

建立在`第一步已经准备好`之上并且代码已经 `clone`完毕

```
· **npm install**   安装(更新)依赖包
· **npm run dev**   启动node服务在浏览器查看效果
```


## 开发注意



## 版本迭代





