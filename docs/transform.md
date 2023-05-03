---
hide:
  - toc
---

<!-- https://steamcommunity.com/sharedfiles/filedetails/?id=2955645316 -->

![transform](./image/transform.png)


### 変形領域の中にカーソルがある場合

クリックすることで自由に動かすことができます。

![transform_move](./image/transform_move.gif)

Shift + クリックすることで水平方向のみまたは垂直方向のみ動かすことができます。

![transform_move_shift](./image/transform_move_shift.gif)


### 変形領域の外にカーソルがある場合

クリックすることで回転させることができます。

![transform_rotate](./image/transform_rotate.gif)

Ctrl + クリックすることでアンカーを中心にして回転させることができます。

![transform_rotate_ctrl](./image/transform_rotate_ctrl.gif)


### アンカーの上にカーソルがある場合

クリックすることでアンカーのみ動かすことができます。

![transform_anchor](./image/transform_anchor.gif)


### 上下左右の辺 ( □ ) の上にカーソルがある場合

クリックすることでその辺を動かすことができます。

![transform_edge](./image/transform_edge.gif)

Alt + クリックすることで中心を固定して2つの辺を同時に動かすことができます。

![transform_edge_alt](./image/transform_edge_alt.gif)

Ctrl + クリックすることでその辺を自由に動かすことができます。

![transform_edge_ctrl](./image/transform_edge_ctrl.gif)

Ctrl + Shift + クリックすることで辺の方向に沿ってその辺を動かすことができます。

![transform_edge_ctrlShift](./image/transform_edge_ctrlShift.gif)


### 4つの頂点 ( □ ) の上にカーソルがある場合

クリックすることでその頂点を動かすことができます。

![transform_vert](./image/transform_vert.gif)

Alt + クリックすることで拡大縮小・回転させることができます。

![transform_vert_alt](./image/transform_vert_alt.gif)

Shift + クリックすることで均一に拡大縮小させることができます。

![transform_vert_shift](./image/transform_vert_shift.gif)

Shift + Alt + クリックすることで中心を固定して均一に拡大縮小させることができます。

![transform_vert_shiftAlt](./image/transform_vert_shiftAlt.gif)

---

Ctrl + クリックすることでその頂点だけを自由に動かすことができます。 <br />
この場合は3つのやり方によって見た目が変わります。

#### 「変形」を実行して Ctrl + クリックの場合

![transform_vert_ctrl](./image/transform_vert_ctrl.gif)

#### 「遠近感ありの変形」を実行して「遠近感」をオフにした時の Ctrl + クリックの場合

![transform_persp_off_vert_ctrl](./image/transform_persp_off_vert_ctrl.gif)

#### 「遠近感ありの変形」を実行して「遠近感」をオンにした時の Ctrl + クリックの場合

![transform_persp_on_vert_ctrl](./image/transform_persp_on_vert_ctrl.gif)


__"リセット"__ ボタンを押すことで変形前の状態に戻すことができます。

* 変形(キャンバスサイズ)
* 移動拡大回転(キャンバスサイズ)
* 遠近感ありの変形
* ゆがみフィルター
* レタッチフィルター

これら5つのやり方は変形内容を保存することができます。 <br />
もし保存したなら、別のレイヤーに同じ変形を適用させることができます。

数値を指定して変形させる場合は __"移動拡大回転"__ を使ってください。 <br />
例えば 50 % になるように縮小したい場合や 45 度回転させたい場合などです。
