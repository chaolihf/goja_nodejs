goja_nodejs
====
filebeat使用	github.com/dop251/goja_nodejs => github.com/dop251/goja_nodejs v0.0.0-20171011081505-adff31b136e6，导致无法使用最新版本的goja_nodejs，所以重新fork一个新goja_nodejs模块

# 修改内容
go.mod 中 module github.com/dop251/goja_nodejs => github.com/chaolihf/goja_nodejs
全局替换
github.com/chaolihf/goja_nodejs/为github.com/chaolihf/goja_nodejs/
github.com/chaolihf/goja/为github.com/chaolihf/goja/
"github.com/chaolihf/goja"为"github.com/chaolihf/goja"