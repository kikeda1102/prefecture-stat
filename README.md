# prefecture-stat

# 都道府県データマップ

<a href="https://prefecture-stat.herokuapp.com" target="_blank">https://prefecture-stat.herokuapp.com</a>	(ロードに時間がかかります)

都道府県ごとの様々な統計データを地図とヒストグラムで可視化します。

元データ:
<a href="https://www.stat.go.jp/data/k-sugata/index.html" target="_blank">総務省統計局データ「統計でみる都道府県のすがた」</a>	

![thumbnail](thumbnail.png "thumbnail")


* app.py

  本体。dashで動作

* data/all_data.csv

  「統計でみる都道府県のすがた2021」全データ

* data/japan.geojson
  
  都道府県のgeojsonファイル

* Procfile
  
  Heroku上で起動するためのコマンドを定義

* requirements.txt
  
  Heroku用　必要ライブラリのリスト

* runtime.txt
  
  Heroku用 pythonバージョンを指定

* test.ipynb
  
  テスト用ノートブック




