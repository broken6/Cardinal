# Changelog

## 0.7.2+dev(`master`)

### Added
* Timer 增加返回当前服务器时间戳。
* gofmt CI 检查代码。
* README 加入 Sourcegraph 链接。
* README 加入兔小巢链接。
* 发送请求检查版本更新时，加入请求超时时间，适配在无外网环境。
* 管理员前端加入靶机状态信息显示。

### Changed
* 日志包更换为 `unknwon.dev/clog/v2`。

### Removed
* 去除消息队列功能。