# ap-Trial-datalogger-for-windows
Trial version of the Academic Pack datalogger for windows

# ソフト説明
JINS MEME Academic Pack専用です。
JINS MEME ACADEMIC PACK公式アプリの「DataLogger」の簡易体験版です．

### 簡易体験版で「JINS_MEME_DataLogger_Trial.exe」制限されている機能
- 連続計測時間：最長２分
- 所望の時刻でデータにアーチファクトを加える「Free Marking」機能が利用できません．
- csv保存なし
- 計測データ再生機能は利用できません．
- 実行ファイルを開いたタイミングでのパラメータ初期設定は以下
      - Select mode : Full
      - Transmission speed : 100Hz
      - Measurment range of Accelerometer : 2g
      - Measurement range of Gyroscope : 250dps
 
- 「Settings(S)」部分を押せない


# 修正依頼中（メモです．）
- Stop Measuremntを押したら，積算計測時間をリフレッシュしたい
　⇒最長120秒の連続計測可能だが，0<計測時間＝mTime＜120sで一度ストップし，スタートすろと 120-mTime分しか連続計測できない．
　
　　
# 修正依頼まだだけど修正したい部分（上間用備忘録）
- iConでトライアルということがわかるようにしたい

# 修正済みリスト
- グラフの色（Acc, gyroについては現状でOK)
   ・EOGの「Left」，「Right」は初期状態ではチェックボックスを外す
     ⇒つまり表示させないようにしたいです．
    ・EOG：DeltaHの色を「赤」へ．Accの[X-ais]の色と同じ色
