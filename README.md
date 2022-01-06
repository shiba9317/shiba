# shiba
## This is a my repository.

2021年度ロボットシステム学：課題1「myled.c」

目的：Ubuntu18.04にRaspberry Pi 3 を使用し、LEDを光らせる事を目的とする。

動作環境：
Ubuntu18.04（OS）
Raspberry Pi 3×1
LED×1
ブレットボード×1
配線×2
抵抗×1

実行操作：

1．Ubuntu18.04を立ち上げる

2．Raspberry Pi 3 に電源を入れ、Ubuntu18.04に接続する

3．ブレットボードにLEDと配線と抵抗を設置する

4．ブレットボードの配線をRaspberry Pi 3のGPIO25とGroundに接続する

5．vi myled.cと打ち込み、ファイルを作る

6．myled.cにプログラムを書き込む

7．wqでファイルを保存する

8．makeと打ち込み、ファイルをコンパイルする

9．コマンドsudo install myled.koを実行する

10．コマンドsudo chmod 666 /dev/myled0を実行する

11．echo 1 > /dev/myled0と打ち込み、ファイルを実行する
