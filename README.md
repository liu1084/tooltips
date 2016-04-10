# tooltips

[![](https://jaywcjlove.github.io/sb/ico/stylus.svg)](http://stylus-lang.com/) ![](http://jaywcjlove.github.io/sb/license/mit.svg) [![GitHub issues](https://img.shields.io/github/issues/xurui3762791/tooltips.svg)](https://github.com/xurui3762791/tooltips/issues) [![GitHub forks](https://img.shields.io/github/forks/xurui3762791/tooltips.svg)](https://github.com/xurui3762791/tooltips/network) [![GitHub stars](https://img.shields.io/github/stars/xurui3762791/tooltips.svg)](https://github.com/xurui3762791/tooltips/stargazers)

纯css工具提示  bubbles-tooltips [查看效果](http://xurui3762791.github.io/tooltips/)


# 演示
![tooltips](https://raw.githubusercontent.com/xurui3762791/tooltips/gh-pages/img/picturedemo1.gif)
![tooltips](https://raw.githubusercontent.com/xurui3762791/tooltips/gh-pages/img/picturedemo2.gif)

# 使用

## 在 stylus 中使用

```css
@import "node_modules/tooltips"
```


```html
<button data-tooltips="向上提示" data-tooltips-pos="up">向上提示</button>
向上提示
```

## 常规使用方法

直接在页面中引用`tooltips.min.css`

```html
<link rel="stylesheet" href="tooltips.min.css">
<span data-tooltips="我是提示" data-tooltips-pos="up">tooltips</span>
```


# 开发 

```bash
$ npm run build
$ npm run watch
```

