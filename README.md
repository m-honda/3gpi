# 3GPi（Raspberry Pi 対応 3G 通信モジュール）

ここでは 3GPi に関する技術資料等を公開しています。  
ハードウェアおよびソフトウェアの詳細についてはリンク先の wiki をご参照ください。  

基板に 3GPI の表記があるものが 3GPi Ver.1 です。  
基板に 3GPi2 の表記があるものが 3GPi Ver.2 です。  

* [目次](../../wiki#%E7%9B%AE%E6%AC%A1)  
  + [ハードウェア](../../wiki#%E3%83%8F%E3%83%BC%E3%83%89%E3%82%A6%E3%82%A7%E3%82%A2)  
    + 基板  
      - [Ver.2](../../wiki/基板%20Ver.2)  
        - 1. [外形図](../../wiki/基板%20Ver.2#1-%E5%A4%96%E5%BD%A2%E5%9B%B3)  
        - 2. [仕様](../../wiki/基板%20Ver.2#2-%E4%BB%95%E6%A7%98)  
        - 3. [インターフェース](../../wiki/基板%20Ver.2#3-%E3%82%A4%E3%83%B3%E3%82%BF%E3%83%BC%E3%83%95%E3%82%A7%E3%83%BC%E3%82%B9)  
        - 4. [使用ポート](../../wiki/基板%20Ver.2#4-%E4%BD%BF%E7%94%A8%E3%83%9D%E3%83%BC%E3%83%88)  
        - 5. [通信モジュール](../../wiki/基板%20Ver.2#5-%E9%80%9A%E4%BF%A1%E3%83%A2%E3%82%B8%E3%83%A5%E3%83%BC%E3%83%AB)  
      - [Ver.1](../../wiki/基板%20Ver.1)  
        - 1. [外形図](../../wiki/基板%20Ver.1#1-%E5%A4%96%E5%BD%A2%E5%9B%B3)  
        - 2. [仕様](../../wiki/基板%20Ver.1#2-%E4%BB%95%E6%A7%98)  
        - 3. [インターフェース](../../wiki/基板%20Ver.1#3-%E3%82%A4%E3%83%B3%E3%82%BF%E3%83%BC%E3%83%95%E3%82%A7%E3%83%BC%E3%82%B9)  
        - 4. [使用ポート](../../wiki/基板%20Ver.1#4-%E4%BD%BF%E7%94%A8%E3%83%9D%E3%83%BC%E3%83%88)  
        - 5. [通信モジュール](../../wiki/基板%20Ver.1#5-%E9%80%9A%E4%BF%A1%E3%83%A2%E3%82%B8%E3%83%A5%E3%83%BC%E3%83%AB)  
  + [ソフトウェア](../../wiki#%E3%82%BD%E3%83%95%E3%83%88%E3%82%A6%E3%82%A7%E3%82%A2)  
    + システム  
      - [Ver.2](../../wiki/システム%20Ver.2)  
        - 1. [概要](../../wiki/システム%20Ver.2#1-%E6%A6%82%E8%A6%81)  
        - 2. [パッケージ](../../wiki/システム%20Ver.2#2-%E3%83%91%E3%83%83%E3%82%B1%E3%83%BC%E3%82%B8)  
        - 3. [インターフェース](../../wiki/システム%20Ver.2#3-%E3%82%A4%E3%83%B3%E3%82%BF%E3%83%BC%E3%83%95%E3%82%A7%E3%83%BC%E3%82%B9)  
      - [Ver.1](../../wiki/システム%20Ver.1)  
        - 1. [概要](../../wiki/システム%20Ver.1#1-%E6%A6%82%E8%A6%81)  
        - 2. [パッケージ](../../wiki/システム%20Ver.1#2-%E3%83%91%E3%83%83%E3%82%B1%E3%83%BC%E3%82%B8)  
        - 3. [インターフェース](../../wiki/システム%20Ver.1#3-%E3%82%A4%E3%83%B3%E3%82%BF%E3%83%BC%E3%83%95%E3%82%A7%E3%83%BC%E3%82%B9)  
  + [その他](../../wiki#%E3%81%9D%E3%81%AE%E4%BB%96)  
    - [動作確認済み SIM](../../wiki/その他/#%E5%8B%95%E4%BD%9C%E7%A2%BA%E8%AA%8D%E6%B8%88%E3%81%BF-sim)  
    - [アクセスポイントの設定](../../wiki/その他#%E3%82%A2%E3%82%AF%E3%82%BB%E3%82%B9%E3%83%9D%E3%82%A4%E3%83%B3%E3%83%88%E3%81%AE%E8%A8%AD%E5%AE%9A)  
    - [GPS の設定](../../wiki/その他#gps-%E3%81%AE%E8%A8%AD%E5%AE%9A)  

## マニュアル  
  3GPi のマニュアルは下記のリンク先からダウンロードできます。  
  [マニュアル](manual)  

## イメージ  
  OS のイメージファイルは下記のリンク先からダウンロードできます。  
  http://mechatrax.com/data/3gpi/  

  詳細はリンク先のリリースノートをご覧ください。  
  [リリースノート](release)  

## 参考資料  
 + Raspberry Pi ドキュメント  
   http://www.raspberrypi.org/documentation/  
 + Raspberry Pi トラブルシューティング  
   http://elinux.org/R-Pi_Troubleshooting  
 + Raspbian FAQ  
   http://raspbian.org/RaspbianFAQ  
