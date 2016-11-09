# ap-Trial-datalogger-for-windows
Trial version of the Academic Pack datalogger for windows

# ソフト説明
JINS MEME Academic Pack専用です。
JINS MEME ACADEMIC PACK公式アプリの「DataLogger」の簡易体験版です．

### 簡易体験版で制限されている機能
- 連続計測時間：最長２分
- 所望の時刻でデータにアーチファクトを加える「Free Marking」機能が利用できません．
- csv保存なし
- 計測データ再生機能は利用できません．
 

# 修正対応中（メモです．）
- 同じく添付の「Settings(S)」部分を押せないようにしていただけますか？
 csvは保存できないので，保存先の決めるのは不要かと考えています．
 
- 実行ファイルを開いたタイミングでの初期設定
    ・設定パラメータのデフォルト値      
      - Select mode : Full
      - Transmission speed : 100Hz
      - Measurment range of Accelerometer : 2g
      - Measurement range of Gyroscope : 250dps

       ※こちらは公式版についても修正したい．

- グラフの色（Acc, gyroについては現状でOK)
   ・EOGの「Left」，「Right」は初期状態ではチェックボックスを外す
     ⇒つまり表示させないようにしたいです．
    ・EOG：DeltaHの色を「赤」へ．Accの[X-ais]の色と同じ色
　　

# 修正依頼まだだけど修正したい部分（上間用備忘録）
- iConでトライアルということがわかるようにしたい
- 実行ファイルの名前を決める「JINS_MEME_DataLogger_Trial.exe」

