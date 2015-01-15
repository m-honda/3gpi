# 3GPI（Raspberry Pi対応3G通信モジュール）

![3GPI on Raspberry Pi Model B+](image/3GPIonModelBplus-320x208.jpg)  

ここでは3GPIに関する技術資料等を公開しています。

## 詳細  
ハードウェアおよびソフトウェアの詳細についてはリンク先をご参照ください。  
* [目次](../../wiki)  
  * [ハードウェア](../../wiki/ハードウェア)  
    * 1. [3GPI基板](../../wiki/ハードウェア#1-3gpi%E5%9F%BA%E6%9D%BF)  
      * 1.1 [外形図](../../wiki/ハードウェア#11-%E5%A4%96%E5%BD%A2%E5%9B%B3)  
      * 1.2 [仕様](../../wiki/ハードウェア#12-%E4%BB%95%E6%A7%98)  
      * 1.3 [インターフェース](../../wiki/ハードウェア#13-%E3%82%A4%E3%83%B3%E3%82%BF%E3%83%BC%E3%83%95%E3%82%A7%E3%83%BC%E3%82%B9)  
      * 1.4 [使用ポート](../../wiki/ハードウェア#14-%E4%BD%BF%E7%94%A8%E3%83%9D%E3%83%BC%E3%83%88)  
    * 2. [通信モジュール](../../wiki/ハードウェア#2-%E9%80%9A%E4%BF%A1%E3%83%A2%E3%82%B8%E3%83%A5%E3%83%BC%E3%83%AB)  
      * 2.1 [通信方式](../../wiki/ハードウェア#21-%E9%80%9A%E4%BF%A1%E6%96%B9%E5%BC%8F)  
      * 2.2 [測位方式](../../wiki/ハードウェア#22-%E6%B8%AC%E4%BD%8D%E6%96%B9%E5%BC%8F)  
      * 2.3 [備考](../../wiki/ハードウェア#23-%E5%82%99%E8%80%83)  
    * 3. [動作確認済みSIM](../../wiki/ハードウェア#3-%E5%8B%95%E4%BD%9C%E7%A2%BA%E8%AA%8D%E6%B8%88%E3%81%BFsim)  
  * [ソフトウェア](../../wiki/ソフトウェア)  
    * 1. [システム](../../wiki/ソフトウェア#1-%E3%82%B7%E3%82%B9%E3%83%86%E3%83%A0)  
      * 1.1 [パッケージ](../../wiki/ソフトウェア#11-%E3%83%91%E3%83%83%E3%82%B1%E3%83%BC%E3%82%B8)  
      * 1.2 [リリースノート](../../wiki/ソフトウェア#12-%E3%83%AA%E3%83%AA%E3%83%BC%E3%82%B9%E3%83%8E%E3%83%BC%E3%83%88)  
    * 2. [各種設定](../../wiki/ソフトウェア#2-%E5%90%84%E7%A8%AE%E8%A8%AD%E5%AE%9A)  
      * 2.1 [アクセスポイントの設定](../../wiki/ソフトウェア#21-%E3%82%A2%E3%82%AF%E3%82%BB%E3%82%B9%E3%83%9D%E3%82%A4%E3%83%B3%E3%83%88%E3%81%AE%E8%A8%AD%E5%AE%9A)  
      * 2.2 [起動時の設定](../../wiki/ソフトウェア#22-%E8%B5%B7%E5%8B%95%E6%99%82%E3%81%AE%E8%A8%AD%E5%AE%9A)  

## ダウンロード
 * [マニュアル](manual)
 * [3gpi-utils](../../../3gpi-utils)
 * [3gpi-network-manager](../../../3gpi-network-manager)

## 参考資料  
 + Raspberry Pi ドキュメント  
   http://www.raspberrypi.org/documentation/  
 + Raspberry Pi トラブルシューティング  
   http://elinux.org/R-Pi_Troubleshooting  
 + Raspbian FAQ  
   http://raspbian.org/RaspbianFAQ  
