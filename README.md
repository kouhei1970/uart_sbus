# uart_sbus
SBUS受信機読み取り

## ビルド手順

念の為

`export PICO_SDK_PATH=../../pico-dsk`


pico-sdkディレクトリがある場所で

```
git clone https://github.com/kouhei1970/hello_pwm.git
mkdir build
cd build
cmake ..
make
```

## 接続

トランジスタ等を用いたインバータ回路を介して、Picoの1番ピンと受信機を接続する。

### Picoのピンアサイン

- Pin 0:TX
- Pin 1:RX
