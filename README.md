
### 程序基本介绍
1. 数据抓取自```腾讯新闻```
2. 图表采用Echarts(内部使用了vue-echarts)
3. 支持【省】级地图
4. Vue-cli@3脚手架项目
5. [查看源代码](https://github.com/border-1px/2019-nCov)
6. [线上示例](http://101.200.145.232)

### 快速开始
```
# 安装依赖
npm i

# 抓取腾讯新闻数据
node ./build-data.js

# 开发模式
npm run serve
```

### 未实现
定时执行 build-data.js，抓取最新数据。