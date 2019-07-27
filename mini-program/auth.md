# 微信登录

## 根据 jsCode 获取用户 session 信息

API:

```php
$app->auth->session(string $code);
```
特别说明，如果用户没有关注公众号，只用了小程序，需要解密才可以获得unionid
