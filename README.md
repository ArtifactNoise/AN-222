# AN-222 USB-TypeC ユニバーサルI2Cテスト基板・青

![商品画像](./img/1024x1024/DSC_3233.png)

# 商品説明

USB-TypeCケーブルを使って、I2Cのテストを行う為のユニバーサル基板です。

マイコンを使用せずに、PC(Windows,Mac,Linux,RaspberryPi)からI2C通信が出来ます。

USBはHIDドライバを使用し、専用ドライバを必要とせず、幅広い言語や環境で動作します。

サンプルのPythonライブラリやC言語ライブラリがあります。

秋月電子通商のBタイプ基板とサイズ互換があります。

CC端子に抵抗を取り付ける事が出来ますので、TypeCタイプの電源アダプタからも5Vを取得できます。

基板にはレギュレータもあり、3.3Vを取得する事が出来ます。

これにより3.3V系のマイコン開発が非常に楽になると思います。

# 仕様

- 基板サイズ
- パッド：両面スルーホール（1mm穴 2mmパッド）
- 基板厚：1.6mm
- ねじ穴:3.2mm　x4
- 追加機能：
   - 変換IC:MCP2221A
      - I2C(3.3Vと5V対応　ジャンパーで切り替え)
      - USB-UART (115200bps)
   - USB-TypeC　上下対応
   - USB2.0規格対応
   - CC端子に対応
   - USB5Vを3.3V@800mAに変換

# 内容物

- 実装済み基板　１枚

# 資料

 - 回路図 & 外形寸法 & 部品表

    ![資料](./AN-222.pdf)

 - Python操作用ライブラリー
   
      - PyMCP2221A
         https://github.com/nonNoise/PyMCP2221A
      
      I2C detectで試すことが出来ます。
      
      https://github.com/nonNoise/PyMCP2221A/blob/master/example/MCP2221_i2cdetect.py