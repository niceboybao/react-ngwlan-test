# react-ngwlan-test

## 开始

这是本人的第一个在npm上面发布的包，仅供用来测试package的 `书写` 、 `发布` 过程。

发布流程如下：

- 创建一个npm账号；
- npm login 输入账号、密码、邮箱，在控制台登录；
- 控制台cd到要发布的package下；
- 初始化发布版本为1.0.0，后续每次更新旭修改版本号；
- npm publish;

## demo

```javascript
const sum = function(a, b) {
	return a + b;
};
const sub = function(a, b) {
	return a - b;
};
module.exports = {
	sum: sum,
	sub: sub
};
```
