# IconLipSync_public
ネットワークを介して、複数枚の画像でリップシンクするアプリ

# 使い方
1. 一度起動すると、以下のパスにフォルダが作成されます
  
  `C:\Users\<ユーザー名>\AppData\LocalLow\TyounanMOTI\IconLipSync`
  
2. 上記フォルダに`<Twitter ID>.json`ファイルを作成
3. `<Twitter ID>.json`ファイルに以下のコードを貼り付け

```
{
  "name": "<Twitter ID>",
  "visemes": {
    "sil": "<黙っているときの画像>.png",
    "aa": "<「あ」のときの画像>.png",
    "E": "<「え」のときの画像>.png",
    "ih": "<「い」のときの画像>.png",
    "oh": "<「お」のときの画像>.png",
    "ou": "<「う」のときの画像>.png",
    "consonant": "<子音のときの画像>.png"
  },
  "filter": "Trilinear"
}
```

4. 上記JSONファイルを編集する
  
  filterは`"Trilinear"`または`"Point"`を指定できます。
  
5. 画像ファイルをJSONファイルと同じフォルダに配置する
6. IconLipSyncアプリの Streamer Name に Twitter ID を入力する（「@」抜き）
7. IconLipSyncアプリの Room Name に参加したい部屋の名前を入力する
8. 「ルームへ参加」ボタンを押す
9. 参加したいルームがある場合は、そのルーム名を入力して参加する
