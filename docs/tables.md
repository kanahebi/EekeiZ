## Table定義

### pays テーブル

|論理名 | 物理名 | データ型|
|------|-------|-------|
|合計金額|total||
|支払先|||
|支払日|||
|個数|||
|単価|||
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