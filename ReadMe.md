# 公開講座「Rによる時空間モデリング入門」：コードまとめ

公開講座で紹介予定の計算コードをセクション毎にアップしました。各コードは、基本的にはRにコピー&ペーストすると回るようになっております。各自お試しいただけると幸いでです。なお、このページは基本的にずっと開けておく予定です。

補足：今回使用するsfやspdepパッケージのインストールには時間がかかる場合があるのですがデフォルトだと60秒経過するとエラーとなってしまうようです。もしパッケージがインストールできない場合はR（またはRStudio）を開いてoptions(timeout=600)を実行（コピペしてエンター）してtimeoutを600秒に伸ばした後にインストール可能かをお試しください。なお、Rが最新版ではない場合もパッケージが使用不可の場合がありますので、Rが最新のバージョンかどうかもご確認ください（2022/10/18時点の最新バージョンはR-4.2.1です；https://cran.r-project.org/ ）。
