---
title: VUX 能否在微信小程序里使用
---

# VUX 能否在微信小程序里使用

Sorry，不能。微信小程序是个相对封闭的平台，无法简单地适配也没有计划支持小程序版本。

目前企业主体用户可以使用 `web-view` 组件直接显示 web 页面，间接地使用 VUX。


## mpvue 解决方案能否直接迁移 VUX

目前 [mpvue](http://mpvue.com/) 还不支持 `slot`、`slot-scope`，因此迁移有难度，并且小程序存在较多差异，暂未计划。
