# DB定義書

## ER図
　
[ER図はこちら](https://github.com/Aso2001017/2021sys-design/blob/main/ER/er.png)

# DBテーブルカラム詳細一覧

### 顧客データ(customer_data)

|和名|属性名|型|PK|NN|FK|
|:---|:---|:---|:---|:---:|:---:|
|顧客ID|customer_id|int(50)|〇|〇||
|顧客名|name|varchar(30)||〇||

### 個人情報(profile)

|和名|属性名|型|PK|NN|FK|
|:---|:---|:---|:---|:---:|:---:|
|顧客ID|customer_id|int(50)|〇|〇|〇|
|氏名|name|varchar(50)||〇||
|電話番号|phone_number|int(10)||〇||
|住所|address|varchar(50)||〇||
|登録メールアドレス|mail|varchar(30)||〇||


### 登録状況(register_status)

|和名|属性名|型|PK|NN|FK|
|:---|:---|:---|:---|:---:|:---:|
|顧客ID|customer_id|int(50)|〇|〇|〇|
|パスワード|pass|varchar(20)||〇||
|登録状況|status|char(1)||||

### 写真データ(photo_data)

|和名|属性名|型|PK|NN|FK|
|:---|:---|:---|:---|:---:|:---:|
|写真ID|photo_id|varchar(50)|〇|〇||
|お気に入り状況|like_status|char(1)||||


