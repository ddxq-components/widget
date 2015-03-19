History
==========

## 1.0.0 / 2015-03-16

*  fork of aralejs/widget 1.2.0,
*  修改库的依赖，此库依赖全局变量$, 需要jQuery或Zepto将$注入到全局变量中
*  去除auto-render功能
*  修改_parseDataAttrsConfig,如果对象为null,zepto的extend方法会报错