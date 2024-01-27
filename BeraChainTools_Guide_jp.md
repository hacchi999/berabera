
BeraChainToolsを使用する前に、必要な依存関係がすべてインストールされていることを確認してください。

依存関係をインストールするには、次のコマンドを実行してください：

```
pip install -r requirements.txt
```

### 設定ガイド

#### 1. エージェントの設定

- `.env`ファイルを開きます。
- `PROXY_URL`を見つけて、プロキシの抽出リンクに置き換えます。抽出形式がテキストで、抽出数が1に設定されていることを確認してください。

  例：
  ```
  PROXY_URL=http://example.com/get-proxy?nums=1
  ```
  
#### 2. YesCaptchaキーの設定
YesCaptchaアカウントをまだお持ちでない場合は、まずこちらで登録してください：yescaptcha registration link。

YesCaptchaのクライアントキーを取得します。

`.env`ファイルでYesCaptchaClientKeyを見つけ、あなたのClientKeyで埋めます。

例：

```
YesCaptchaClientKey=YOUR_CLIENTKEY_HERE
```

#### 3. MaxWorkersの設定
`.env`ファイルでMaxWorkersを見つけ、設定したいスレッドの数を記入します。

例：
```
MaxWorkers=8
```

### 機能と使用方法
#### BeraChain Collateral Water
`drip_tokens.py`は水を受け取るためのアドレスを作成または指定します。

アクセスリンク：BeraChain water collection
ステータス：完了

#### BEXとのインタラクション
`bex_swap.py`はトークンの交換と流動性の向上をサポートします。

リンク：BEXとのインタラクション
ステータス：完了

#### ハニーとのインタラクション
`honey_swap.py`はマイニングとバイバックをサポートします。

アクセスリンク：ハニーとのインタラクション
ステータス：完了

#### ベンドとのインタラクション
BeraChainのbendサービスとのインタラクションに使用されます。

リンク：ベンドとのインタラクション
ステータス：進行中

#### ベルプスとのインタラクション
BeraChainのberpsサービスとのインタラクションに使用されます。

アクセスリンク：ベルプスとのインタラクション
ステータス：進行中

#### ステーションとのインタラクション
BeraChainのステーションサービスとのインタラクションに使用されます。

アクセスリンク：ステーションとのインタラクション
ステータス：予定

BeraChainToolsをご利用いただきありがとうございます！ご質問や提案がございましたら、GitHub Issuesを通じてお問い合わせください。
