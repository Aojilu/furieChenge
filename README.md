# furieChenge

# 概要
画像のフーリエ変換を表示し、画像をクリックするとその座標を逆変換できるものを作成した。逆変換を続けると元の画像が浮かび上がってくる。

# 使い方
1. 2つ目のセルがメイン処理。メイン処理以外を上から順に実行し、最後にメイン処理を実行するとウインドウが呼び出される
2. ウインドウが起動したら、左上に元画像、真ん中上部にフーリエ変換後の画像が表示される。真ん中下の画像をクリック(orドラッグ)すると、対応した座標のフーリエ逆変換の結果が右下に表示され、左下にこれまでクリックしたものの合計値が表示される。

## 依存ライブラリ
- cv2
- numpy
- tkinter
- PIL

## 参考サイト
- Phythonのguiツールチートシート
https://qiita.com/nanako_ut/items/b5393363b9e21d6342ea
- Canvasの図形や画像をドラッグ・アンド・ドロップで動かす。
https://www.pytry3g.com/entry/2018/02/10/104607
- Tkinter」gridを使用して綺麗に表示しよう（Python）
https://aithii.com/2019/01/11/post-2551/

##実行画像
![act](https://github.com/SaitoSeiji/furieChenge/blob/edit/image/playImage.gif)
