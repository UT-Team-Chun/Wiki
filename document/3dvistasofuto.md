---
description: 3DVista Virtual Tourの使い方, Edit by Chun
icon: cube
---

# 3DVista使用説明\_ソフト編

## はじめに

{% hint style="info" %}
橋梁例
{% endhint %}



![](../.gitbook/assets/0.png)

<mark style="color:red;">**New Project**</mark>を実行

![](../.gitbook/assets/1.png)

<mark style="color:red;">**Import Skin**</mark>で，別ファイルとして渡した「skin\_3dvista\_1.vts」を読み込み，<mark style="color:red;">**Select**</mark>

![](../.gitbook/assets/2.png)

<mark style="color:red;">**Import Panorama**</mark>を選択

![](../.gitbook/assets/3.png)

<mark style="color:red;">**Standard Panorama**</mark>を選択

![](../.gitbook/assets/4.png)

読み込む画像ファイルをまとめて選択→<mark style="color:red;">**開く**</mark>

![](../.gitbook/assets/5.png)

このWarningが出たら，<mark style="color:red;">**Apply to All Panoramas**</mark>にチェックを入れて<mark style="color:red;">**Yes**</mark>

そしてProjectタブをクリックすると，このように読み込んだ写真が出てくる．

![](../.gitbook/assets/6.png)

ここで，Project Name：というところに，橋の名前をいれる（今回は仮にSample Bridgeと入れます）

### 言語の変更

必要に応じて日本語化する．Edit→Language→日本語

![](../.gitbook/assets/7.png)

パノラマタグに戻り，起点となり得る画像を開く．橋梁上面が望ましい．

![](../.gitbook/assets/8.png)

右の枠にあるAdvanced Optionsというのを開く．

![](../.gitbook/assets/9.bmp)

ここで，Zoom Settingsの最小を150, 初期状態も150にする．ローテーション速度のオートマチックを０にする．下のほうにあるオートプレイの設定のループ再生のチェックを外す．

これを，全ての画像に対して行う（大変ですが・・・）

![](../.gitbook/assets/10.png)

そして画角を真ん中のビューでドラッグで指定後，右のパノラマ設定から，ビューを書記点として設定，をクリックする．

次に，パノラマの下のタブのホットスポットを選択，そして同じく橋梁上面の別画像を，その移動位置にドラッグアンドドロップする（ホットスポットをクリックしたら出てくるかもしれない解説動画も参考）．

![屋外, 建物, 乗る, ランプ が含まれている画像

自動的に生成された説明](../.gitbook/assets/11.png)

そうすると，こんなポップアップが出てくるので，Create Return Hotspotにチェックが入っていることを確認後，右の3×3の升目みたいなものをクリックする．

![](../.gitbook/assets/12.bmp)

移動先を表すアイコンの選択画面になるので，arrow01を選ぶ．

![](../.gitbook/assets/13.png)

そうすると，移動先画像が開くので，移動元が，その移動先画像の中でどの部分にあるか，水色の●を移動させて指定し，そして追加をクリックする．

![](../.gitbook/assets/14.png)

そうすると，元画像でもこのように行き先が現れるとともに

![](../.gitbook/assets/15.png)

移動先でもこのように元画像へ戻るリンクができる．

![](../.gitbook/assets/16.png)

以降はこのようにallow1のショートカットが作成されている．

![](../.gitbook/assets/17.png)

プレビューで確認してクリックしたときの移動をチェックする．

損傷をホットスポットとして含める．右上の![](../.gitbook/assets/18.png)マークをクリック

![パソコンの画面

中程度の精度で自動的に生成された説明](../.gitbook/assets/19.png)

損傷を囲う

![](../.gitbook/assets/20.png)

線の色を黄色，厚さ3.0, 不透明度0.01にする．



## スキンの編集



<figure><img src="../.gitbook/assets/グラフィックス1.png" alt=""><figcaption></figcaption></figure>

<figure><img src="../.gitbook/assets/グラフィックス2.png" alt=""><figcaption></figcaption></figure>



## FloorPlanの追加

ToolBarの2番目にFloorPlanのボタンをクリックすると、FloorPlan Viewerのパネルが出てくる．（３Dマップ、レーダーの機能をしている）

FloorPlan Viewer特に設定する必要がなく、右から3番目のFloor Plansとリンク自動リンクしている。Floor Plansを設定することで、各レイヤーのレーダー情報が出てくる。次の節でFloor Plans（レーダー）の設定方法に参考してください。

<figure><img src="../.gitbook/assets/image.png" alt=""><figcaption></figcaption></figure>

### Dropdownバーの活用

DropdownをクリックするとFloorPlanの各レイヤーを選択でき、特定の画像にもジャンプできる。

<figure><img src="../.gitbook/assets/image (3).png" alt=""><figcaption></figcaption></figure>

<div data-full-width="true">

<figure><img src="../.gitbook/assets/image (4).png" alt=""><figcaption></figcaption></figure>

</div>

損傷へのジャンプというところをクリックして，プロパティのAdvanced Optionsのメディアを見る：というところをカスタムに．そしてそこの横の歯車をクリックして，損傷のホットスポットを含むパノラマ画像を選ぶ．

<figure><img src="../.gitbook/assets/image (5).png" alt=""><figcaption></figcaption></figure>

<figure><img src="../.gitbook/assets/グラフィックス3.png" alt=""><figcaption></figcaption></figure>

裏面図というところをクリックして，プロパティのAdvanced Optionsのメディアを見る：というところを平面図のみ，に．また，アクションの下になにかぶらさがっていたら☓印を押して消す．

## レーダーを作る

<figure><img src="../.gitbook/assets/グラフィックス4.png" alt=""><figcaption></figcaption></figure>

平面図タブに行き，平面図を追加する．

<figure><img src="../.gitbook/assets/グラフィックス5.png" alt=""><figcaption></figcaption></figure>

上面図.pngと裏面図.pngを読み込む．ただし橋梁の状況によっては追加図作成が必要になるため，それについてはお絵かきソフトで適宜作成する．

<figure><img src="../.gitbook/assets/グラフィックス6.png" alt=""><figcaption></figcaption></figure>

平面図タブの下のレーダータブをクリックする．

<figure><img src="../.gitbook/assets/グラフィックス6 (1).png" alt=""><figcaption></figcaption></figure>

ホットスポットをクリックして，写真を配置していく．

<figure><img src="../.gitbook/assets/グラフィックス7.png" alt=""><figcaption></figcaption></figure>

この画面で，右上の![](<../.gitbook/assets/グラフィックス15 (1).png>)をクリックする．

<figure><img src="../.gitbook/assets/グラフィックス9.png" alt=""><figcaption></figcaption></figure>

赤丸を使うといいかもしれないです．

<figure><img src="../.gitbook/assets/グラフィックス10.png" alt=""><figcaption></figcaption></figure>

サイズは60px x 60px

アクションのところから，該当画像をロードする．

<figure><img src="../.gitbook/assets/グラフィックス11.png" alt=""><figcaption></figcaption></figure>

パノラマを開く

<figure><img src="../.gitbook/assets/グラフィックス12.png" alt=""><figcaption></figcaption></figure>

選択．

<figure><img src="../.gitbook/assets/グラフィックス13.png" alt=""><figcaption></figcaption></figure>

例えば合計２つ，上の画像のようになる．

<figure><img src="../.gitbook/assets/グラフィックス14.png" alt=""><figcaption></figcaption></figure>

レーダー，というタブをクリックする．そして右上の画像ファイル名をクリックする．

そして，レーダーの右側のボタンを押す．

そうするとレーダーが出てくるので，向きを合わせる．半径の長さは0.2，色は黄緑で．

橋梁裏面も同様に．

そしてファイル保存．

## エキスポート

ファイル→Create Project Backup with Mediaで，フォルダを作って指定．
