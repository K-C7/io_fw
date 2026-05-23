# io_fw

IMRC向けIO基板のSTM32用ファームウェアです。

16個のIOポートに対する入力監視および出力制御を行い、
CAN通信を利用して外部ノードとデータを送受信します。

---

## 機能

- 16ch IO入力監視
- 16ch IO出力制御
- CAN通信送受信
- 外部制御ノードとの連携

---

## システム構成

```text
[External Sensors]
        │
        ▼
[IO Board(STM32)]
        │ CAN
        ▼
[Robot Main Controller]
````

---

## 使用技術

* STM32
* CAN通信
* GPIO制御
* Embedded C

---

## 用途

* センサ入力収集
* アクチュエータ制御
* ロボット機体IO管理

