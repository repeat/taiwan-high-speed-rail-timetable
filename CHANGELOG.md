# Changelog

## 未釋出

### 新增
- 將 southbound.csv 和 northbound.csv 內容合併的 timetable.csv
- .gitignore

### 修改
- CSV 檔：
 - 依照 2017/04/28 生效的[官方時刻表](http://www.thsrc.com.tw/UploadFiles/TicketFile/1dd47e19-7ff5-485d-9b99-d9eea5ea77a8.pdf "官方時刻表")更新內容及 README.md

## v1.0

### 新增
- 此一 CHANGELOG.md 檔
 
### 修改
- CSV 檔：
 - 依照 2016/12/02 生效的[官方時刻表](http://www.thsrc.com.tw/UploadFiles/TicketFile/a61ad3a0-7961-4b42-89c2-835cab008c90.pdf "官方時刻表")更新內容
 - 修正 README.md 車次及停靠站
 - 改用 `HH:MM` 表示時刻
 - 改用 `--:--` 表示表定通過未停靠
 - 改用 `xxxxx` 表示表定未通過，常見於台中到發車次
