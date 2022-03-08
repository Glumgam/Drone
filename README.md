# ドローンを自作するにあたってのメモ  
ざっくりと大雑把な説明  
間違っていても知らない  
## 必要なパーツ  
### FC (Flight Contololler)  
パソコンでいうところのCPUになるところ  
ドローンの心臓部  
F0～F7とH7があり、数値が上がるほど性能が上がる  
  
### ESC (Electric Speed Controller)  
配電盤のような役割  
  
### VTX (Video transmitters)  
カメラの映像をFPVゴーグルへ送信するためのパーツ  
5.8GHz帯を使用する為、電波法に基づく免許が必要  
ゴーグルを使用せずに飛行するなら必要ない
  
### FC + ESC + VTX  
この3個のパーツがセットになったものをAIO(All In One)やStackという  
"AIO"と書かれていれば1つの基盤に全て搭載されている  
TinyWhoop系のドローンが該当  
"Stack"は3つの基盤がスタックを積むように積み重なっている  
基本的にはStackタイプを購入する事になる  
いずれもマウントサイズに注意  
16×16や20×20などマウントサイズがフレーム毎に異なる  
対応するサイズを買う事  
  
### フレーム  
ドローンの形を決めるフレーム  
基本的にカーボン製  
購入する時にメーカーの説明をよく見る事  
特に  
モーターサイズ  
FCのマウントサイズ  
の2つは確認する事  

### モーター  
プロペラを回転させるためのパーツ  
様々なサイズがある  
表記方法について調べても中々情報が出てこないパーツ
1206 6000kv と表記されていれば  
12 => コイル直径
06 => コイルの高さ
6000kv => 1v当たりの回転数。kvが低ければ高トルク低回転。高ければ低トルク高回転  

###プロペラ  
揚力を得る為に必要なパーツ  

