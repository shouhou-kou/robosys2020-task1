# robosys2019 課題1
raspberry pi3を使ってデバイスドライバーを作成

## 作成したドライバについて
### 使用方法
~~~
sudo make
sudo insmod myled.ko
sudo chmod 666 /dev/myled0
echo [コマンド] > /dev/myled0
sudo rmmod myled
~~~
### コマンドの種類及び動作
- r : 時計回りにledが点灯する
- l : 反時計回りにledが点灯する 
- 1 : すべてのledが点灯して消える
