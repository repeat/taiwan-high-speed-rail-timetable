# Changelog

## v1.17.20220104

* 依照 2021/11/19 發佈的[新聞稿](https://www.thsrc.com.tw/ArticleContent/fed12f98-8200-4747-a0ab-b9b22425f7a6) 更新時刻表 CSV 檔案及 README.md


## v1.16.20211013

* 依照 2021/09/13 發佈的[新聞稿](https://www.thsrc.com.tw/ArticleContent/464ab7d6-b5f3-4484-a178-46f48395c0e4) 更新時刻表 CSV 檔案及 README.md


## v1.15.20210527

* 依照 2021/05/25 發佈的[新聞稿](https://www.thsrc.com.tw/ArticleContent/8ff8baf6-5b74-4a46-889c-37a0be532d6e) 更新時刻表 CSV 檔案及 README.md

## v1.14.20210521

* 依照 2021/05/18 發佈的[新聞稿](https://www.thsrc.com.tw/ArticleContent/61b0d3ba-2bd3-4c2f-b879-f427ffc179bb) 更新時刻表 CSV 檔案及 README.md
* 新增對照增減班用的 diff 檔
* markdown lint

## v1.13.20200703

* 依照 2020/07/03 發佈的[新聞稿](https://www.thsrc.com.tw/ArticleContent/201e511c-e9d9-44a5-8f45-c5d349726fe7) 更新時刻表 CSV 檔案及 README.md
* 移除過期時刻表及對照增減班用的 diff 檔

## v1.12.20200601

* 依照 2020/06/01 發佈的[新聞稿](https://www.thsrc.com.tw/tw/News/Detail/f83fc041-267f-4ed3-b4ac-ecf3b93308cd/4) 更新時刻表 CSV 檔案及 README.md
* 新增 2019/09/01 版本時刻表 CSV ，以方便使用 `diff -U0` 比較調整班次的差異

## v1.11.20200529

* 依照 2020/05/22 發佈的[新聞稿 1](https://www.thsrc.com.tw/tw/News/Detail/eba50b82-103e-4d4b-ad0f-94b36e8279a4/2) 以及 2020/05/29 發佈的[新聞稿 2](http://www.thsrc.com.tw/tw/News/Detail/c1f69455-7846-48ed-bc6e-8aee556e8c3a/2) 更新時刻表 CSV 檔案及 README.md
* 因應頻繁調整班次，修正時刻表 CSV 檔案路徑

## v1.10.20200518

依照 2020/04/17 發佈的[新聞稿](https://www.thsrc.com.tw/tw/News/Detail/502bb127-4b47-45ef-8059-f80c2ce1f72f/2)更新內容及 README.md

## v1.9.20200418

* 依照 2020/03/23 發佈的[新聞稿](https://www.thsrc.com.tw/tw/News/Detail/b6d8f546-984e-42af-99d0-3ace38a9555d/15)更新內容及 README.md
* 因應減班，修正車次邏輯

## v1.8.20190901

更新 1508 車次為 508 （無新聞稿）

## v1.7.20190728

依照 2019/07/23 發佈的[新聞稿](https://www.thsrc.com.tw/tw/News/Detail/7026b831-d491-46cd-b38f-3b3dc65abca3/4)更新內容及 README.md

## v1.6.20190701

依照 2019/05/27 發佈的[新聞稿](http://www.thsrc.com.tw/tw/News/Detail/8bec2026-a098-40a6-a16b-c06515c68f04/7)更新內容及 README.md

## v1.5.20181008

依照 2018/09/07 發佈的[新聞稿](http://www.thsrc.com.tw/tw/News/Detail/c4412e0b-668e-4d5e-9591-ede53c23ef6c/3)更新內容及 README.md

## v1.4.20180701

依照 2018/05/23 發佈的[新聞稿](http://www.thsrc.com.tw/tw/News/Detail/a7f8e8a1-c219-425c-bc5d-a3a112f0814c/4)更新內容及 README.md

## v1.3.20171003

* 修正 CSV 檔案內容
* 修正 CHANGELOG.md, README.md 排版
* 依照 2017/08/31 發佈的[新聞稿](http://www.thsrc.com.tw/tw/News/Detail/b9312bcd-1e27-4266-b5c1-acb4b9bc2a81/2)更新內容及 README.md

## v1.2.20170701

依照 2017/07/01 生效的[官方時刻表](http://www.thsrc.com.tw/UploadFiles/TicketFile/aaaed025-1f36-4a54-afa5-31b642847142.pdf)更新內容及 README.md

## v1.1.20170428

### 新增

* 將 southbound.csv 和 northbound.csv 內容合併的 timetable.csv
* .gitignore

### 修改

依照 2017/04/28 生效的[官方時刻表](http://www.thsrc.com.tw/UploadFiles/TicketFile/1dd47e19-7ff5-485d-9b99-d9eea5ea77a8.pdf)更新內容及 README.md

## v1.0

### 新增

此一 CHANGELOG.md 檔

### 修改

* CSV 檔：
  * 依照 2016/12/02 生效的[官方時刻表](http://www.thsrc.com.tw/UploadFiles/TicketFile/a61ad3a0-7961-4b42-89c2-835cab008c90.pdf)更新內容
  * 改用 `HH:MM` 表示時刻
  * 改用 `--:--` 表示表定通過未停靠
  * 改用 `xxxxx` 表示表定未通過，常見於台中到發車次
* 修正 README.md 車次及停靠站
