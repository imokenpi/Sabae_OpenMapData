Sabae_OpenMapData
=================

鯖江市のオープンデータ地図情報を多目的に使いやすく整理、改変したファイルを再配布しています。
鯖江市ご提供の地図情報を分類コードごとにSHP形式、GeoJSON形式、及び.osm形式のデータにしました。

同時に、オープンストリートマップへのインポートを現在準備中です。
詳細作業については以下のwikiページに整理しています。
http://wiki.openstreetmap.org/wiki/Sabae


鯖江市域地図データに関して
--------------------------
[鯖江市の地図情報（shape）](http://www.city.sabae.fukui.jp/pageview.html?id=13892)

* 縮尺： 1/2500

* 空間参照系： JGD2000/平面直角座標系6系(EPSG:2448)

* データ作成年： 2008年


注意
　本地図情報は、都市計画関連業務のために作成されたものですが、公共測量等の高度な精度が要求される測量、各種証明等には使用することができません。また、利用者の利用目的に適合しているとは限りませんので、利用者は自らの責任でご自身の利用目的に適合しているかどうかをご判断ください。


提供データ・セットに関して
---------------------------------------
  鯖江市のオープンデータ地図情報を多目的に使いやすく整理、改変したファイルを再配布しています。
  鯖江市ご提供の地図情報を分類コードごとに**SHP形式**、**GeoJSON形式**、及び**.osm形式**のデータにしました。

###CSVデータリスト###
* Sabae_DataList.csvにどんなデータがあるかをリストにまとめました。
* CSVデータはEXCELで作成し、エンコードはShift-JISで保存されています。

###SHPファイルのデータ・セット###
* SabaeClassifiedDataSet_AsSHP.7zにSHPファイル形式のデータ・セットをまとめています。
* 分類コードごとにSHPファイルを作成しています。
* また、SHPファイル作成にあたり、元データの属性テーブルを大幅に加工しています。
* 各SHPファイルのエンコードはShift-JISで保存されています。
* SHP形式のファイルを7z形式でまとめています。

###GeoJSONのデータ・セット###
* SabaeClassifiedDataSet_AsGeoJSONのフォルダにGeoJSON形式のデータ・セットをまとめています。
* SHPファイルからogr2ogrを用いてGeoJSON形式に変換しました。
* [GeoJSONLint](http://geojsonlint.com/)での地図上での動作確認済み
* [GeoJSON -> TopoJSON](http://jeffpaine.github.io/geojson-topojson/)での動作確認済み
* 7102_Lineに関しては100MBを超えるため、7z形式に圧縮してGitHubへアップロードしてます。

###.osmのデータ・セット###
* SabaeClassifiedDataSet_AsOSMのフォルダに.osm形式のデータ・セットにまとめています。
* shpのデータ・セットよりogr2osmを用いて.osmにデータ変換しています。
* 7101_Line.osm及び7102_Line.osmに関しては50MBを超えるため、7z形式に圧縮してGitHubへアップロードしています。

ライセンス
----------
(c)Sabae city, CC BY 
ライセンスは、Creative Commonsの「表示」（CC BY）としています。

