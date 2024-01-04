# furusato_nouzei_calc with leafex

ふるさと納税計算システムです。

2023年用です。

## install

### 環境設定

javaの実行環境が必要です。

https://www.oracle.com/jp/java/technologies/downloads/

Windows11では、自動でPathの設定がされる。

Windows10などでは、Pathの設定が必要です。


### ダウンロード

ファイルを３つ（leafex_ver002.jar,ふるさと納税_ver002.mm,ふるさと納税入出力_ver002.xlsm）ダウンロードしてください。

※leafex_ver001.jar,ふるさと納税_ver001.mm,ふるさと納税入出力_ver001.xlsmは、古いバージョンなので不要です。

`leafex_ver002.jar`と`ふるさと納税_ver002.mm`の２つのファイルは、同じフォルダに保存してください。

`ふるさと納税入出力_ver002.xlsm`は、別のフォルダに保存することができます。

`ふるさと納税入出力_ver002.xlsm`の`設定`シートの`B2`のセルに、上記２つのファイルを保存したフォルダ名を入力します。

## 実行

`ふるさと納税入出力_ver002.xlsm`をExcelで開きます。マクロが設定されています。

`入出力`シートの金額、人数などを入力します。`配偶者の有無`などは、`0`や`1`（半角数字）などで指定します。

`計算`ボタンをクリックします。

黒いウィンドゥが開きますが、数十秒で消えます。

Excelで、「このシートは完全に削除されます。続けますか？」と表示されますので、`削除`をクリックします。

`入出力`シートに計算結果（自己負担額、ふるさと納税上限額など）や計算過程が出力されます。

（必要ならば）ファイルを保存します。

## その他

`ふるさと納税入出力_ver002.xlsm`は、コピーしてファイル名を変更することができます。

`入出力`シートの各セルの書式変更や移動も可能です。ただし、セルのコメント（メモ）は変更しないでください。

## バージョン

### version0.02

６５歳以上の場合の公的年金等の計算ができなかった点を修正

住民税の配当控除の計算が誤っていた点を修正

円未満の端数処理を修正

計算過程の表示誤りを修正

### version0.03

６５歳以上の場合の公的年金等の計算ができなかった点を修正

計算過程の表示誤りを修正

