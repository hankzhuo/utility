# utility
整理 JavaScript 常用方法

## 包含功能

- 防抖 ```utility.debounce(func, wait[, immediate])```
- 节流 ```utility.throttle(func, wait)```
- 数组去重 ```utility.unique(array)```
- 检查类型 ```utility.checkType(obj)```
- Cookie：
  - 获取 ```utility.getCookie(name)```
  - 设置 ```utility.setCookie(name, value[, expires, path, domain, secure])```
  - 删除 ```utility.unsetCookie(name, path, domain, secure)```
- URL：
  - 拼接URL ```utility.encodeURL(url, params)```
  - 获取queryString ```utility.getQueryString(url, name)```