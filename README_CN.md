# WeatherPainting 

中文｜[English](README.md)

![alt text](src/weather_forecast.svg)

WeatherPainting 是一个使用JavaScript结合Github workflow实现的绘制7日天气预报的程序,每天自动刷新4次，自动更新天气信息。

##  所以这有什么用处呢？

- 你可以像我一样将它放置到Github个人readme中，就像下面这样

![alt text](image.png)

是不是很酷？ 所以如何将它安装到你的readme中呢？接着往下看吧


## 如何使用？

1. 克隆这个项目,并为你克隆到的项目创建Github Page(由于Github的安全策略，我们需要使用Github Page这种方式去存放我们生成的SVG图片)
2. 配置好仓空Github workflow相关的配置项
3. 修改src/index.js中的参数(已经用TODO注释好)，修改成你自己的参数，并提交到Github
4. 当Github Page和Github workflow都配置完成后，在你的readme中添加如下代码

```markdown
<img src="https://youname.github.io/WeatherPainting/src/weather_forecast.svg" />
```
