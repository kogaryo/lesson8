# 輪郭抽出

# 経過画像
## 3D
シェーダを書き替えて、横を向いている法線をふちにする<br>
![結果画像:シェーダを書き替えて、横を向いている法線をふちにする](result1.png)<br>

オブジェクト空間で膨らませたモデルを裏面で黒く描画<br>
![結果画像:オブジェクト空間で膨らませたモデルを裏面で黒く描画](result2.png)<br>

スクリーン空間で膨らませたモデルを裏面で黒く描画<br>
![結果画像:スクリーン空間で膨らませたモデルを裏面で黒く描画](result3.png)<br>

フルスクリーンでの輪郭抽出や今までの方法を自分なりに工夫しよう<br>
![結果画像:フルスクリーンでの輪郭抽出や今までの方法を自分なりに工夫しよう](result4.png)<br>

## 2D
Gather法で輪郭を抽出してみよう<br>
![結果画像:Gather法で輪郭を抽出してみよう](result5.png)<br>

Scatter法で輪郭を抽出してみよう<br>
![結果画像:Scatter法で輪郭を抽出してみよう](result6.png)<br>

## spine
spineモデルを描画する<br>
![結果画像:spineモデルを描画する](result7.png)<br>

レンダーテクスチャにもspineモデルを描画する<br>
![結果画像:レンダーテクスチャにもspineモデルを描画する<](result8.png)<br>

Gather法でspineモデルに輪郭を追加する<br>
![結果画像:Gather法でspineモデルに輪郭を追加する](result9.png)<br>


# 補足
授業で作成したプロジェクトファイルをforkしたプロジェクトに上げてください。

1_3D, 2_2D, 3_spineフォルダにプロジェクトのファイルを入れてください。
.gitignore を反映させて、無駄なファイルをアップロードしないようにしてください。

工程に応じて、result+.pngファイルを置いてください(表示されることを確認すること)。

データの著作権に気を付けてください。

翌日以降の提出の際はプルリクを投げてください。
