### 課題
wallNodeをobjectsNodeとして、Node内にappleを付け加えた。
壁とりんごが被らないように、１秒おきに交互に出てくるようにした。

得点は、Apples: として表示し、Best ScoreはscoreとappleScoreの合計点とした。

サウンドの再生は、フレームワークAVFoundationを用いた。

### 疑問
- 壁とりんごを同じNodeに置かなくても、被らないように出現させる方法は？
- 衝突判定時の、オブジェクトの判別方法がわかりにくいのでは？(なんでビットを使わないといけないのか)
- 今回はAVFoundationというものを用いたが、他にも音声・動画を埋め込むライブラリがある？