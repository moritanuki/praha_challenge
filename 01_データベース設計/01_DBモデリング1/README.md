# DMモデリング1

## 補足事項

### データ型について

[PostgreSQLのデータ型](https://www.postgresql.jp/docs/9.2/datatype.html)に基づいて記載

### 記号について

#### カーディナリティ

|  Type  |  記号  |
| ---- | ---- |
|  0か1  |  &#124;o--  |
|  1のみ  |  &#124;&#124;--  |
|  0以上  |  }o--  |
|  1以上  |  }&#124;--  |

#### その他

- テーブル内の罫線上部： 主キー
- \<\<FK>>： 外部キー
- \*（画像だと●）： not null制約

## 課題の回答

### 課題1

![課題1の回答](./01_%E8%AA%B2%E9%A1%8C1/sushi_ordering_schema_01.png)

### 課題2

![課題2の回答](./02_%E8%AA%B2%E9%A1%8C2/sushi_ordering_schema_02.png)

### 課題3

![課題2の回答](./03_%E8%AA%B2%E9%A1%8C3/sushi_ordering_schema_03.png)