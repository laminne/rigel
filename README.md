# Rigel
![image](https://user-images.githubusercontent.com/40442980/117563905-0651fa80-b0e4-11eb-87e0-b36dcaf99f9d.png)

Python で書かれた CotTyan(v2.x)の一部を Ruby で書き直すプロジェクト

## 起動方法

1. `.env`を作成し、

```
TOKEN="<Discord Bot token>"
CLIENT_ID="<Discord Bot Client ID>"
CHANNEL_ID="<Discord Channel ID>"
TRANSFER="<Discord Channel ID>"
```

環境に合わせ適宜書き換えてください

2. `bundle install`を実行(Gem のインストール)
3. `ruby main.rb`を実行  
   ※discordrb は libsodium への依存関係が存在しているようなので事前にインストールしておく必要があります
