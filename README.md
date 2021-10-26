# STM_MotorController
STM_MotorSystem用のstm32f303k8nucleoを用いたコントローラ

|peripheral|pin|
|---|---|
|canrx|PA11(D10)|
|cantx|PA12(D2)|

## MX設定
|config|parameter|
|---|---|
|prescaler|4|
|TQB1|5|
|TQB2|2|
|RSJ|1|
|BaudRate|1Mbps|
|TTC|0|
|ABusOffM|1|
|AWakeUpM|1|
|ARetransission|1|
|RFL|0|
|TFP|0|
|OperatingM||

## 追記
割り込みの有効化忘れないでにゃん（RX0を有効化すればいいんだにゃん）

