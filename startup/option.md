# MODの設定

- 右下のコイン表示をウォレットの合計金額にする

1. 起動構成の`config/lightmanscurrency-client.lcconfig`を適当なエディタで開く
2. `[wallet_hub]`の`displayType`を`TEXT`にする

- 陳列棚の描画を軽くする

1. 同じく`config/lightmanscurrency-client.lcconfig`の`[quality]`で`itemTraderRenderLimit`を`1`にする