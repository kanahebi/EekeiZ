## Table定義

### pays テーブル

|論理名 | 物理名 | データ型|
|------|-------|-------|
|合計金額|total_price|int|
|支払先|payment_destination|string|
|支払日|payment_date|date|
|個数|number|int|
|単価|unit_price|int|
|名前|name|string|

### pay_categories テーブル

|論理名 | 物理名 | データ型|
|------|-------|-------|
|支払ID|pay_id|int|
|分類ID|category_id|int|

### categories テーブル

|論理名 | 物理名 | データ型|
|------|-------|-------|
|名前|name|string|
|コード|code|string|
