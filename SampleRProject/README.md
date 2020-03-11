覚書
===========
以下の参考サイトを参考に、pom.xmlを作成。Java⇒JRI⇒Rが動作するところまで確認。
## 前提条件
+ Rがインストールされていること
+ R toolがインストールされていること
+ install.packages('rJava')はR Studioで入れちゃった
+ Rがパスに入っていること
+ pom.xmlのr.pathプロパティは環境に合わせて変更しましょ
+ r.path/library\rJava\jri 直下のjri.dllはIAアーキテクチャのものなので、パソコン使うならr.path/library\rJava\jri\x64配下のものを使いましょう
## 参考サイト
https://hamadakoichi.hatenadiary.org/entry/20100111/1263227076
