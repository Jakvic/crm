## 打开项目等它自己下载安装依赖的包和插件
## 中途下载mysql,redis,ngnix
## mysql: 在`application-druid.yml`填写mysql root密码
## nginx: 把dist放到html目录
## 编译失败？提示nogoal？在`huike-parent`目录的`pom.xml`文件的`build`标签里加上
`<defaultGoal>install</defaultGoal>`
## 参考 https://www.bilibili.com/video/BV1uK411p7Bp