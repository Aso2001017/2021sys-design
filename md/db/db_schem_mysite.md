
### 顧客データ(customer_data)

|和名|属性名|型|PK|NN|FK|
|:---|:---|:---|:---|:---:|:---:|
|顧客ID|customer_id|int(50)|〇|〇||
|顧客名|name|varchar(30)||〇||

### 登録状況(register_status)

|和名|属性名|型|PK|NN|FK|
|:---|:---|:---|:---|:---:|:---:|
|顧客ID|customer_id|int(50)|〇|〇|〇|
|パスワード|pass|varchar(20)||〇||
|登録状況|status|char(1)||||

### 

