# nerves_phoenix_sample1
Poncho project : Nerves + Phoenix. 

https://github.com/nerves-project/nerves_examples/tree/master/hello_phoenix

をベースにして、phoenixプロジェクト側を少しカスタマイズしてみている。

ファームウェア書き込みのコマンド`firmware.burn`の省略のため、`mix firmware.gen.script`コマンドを実行し、`upload.sh`を作成している。

作成場所は、`firmware`ディレクトリ直下。

プログラム更新時には、`mix firmware && ./upload.sh <IP address>`を実行する。


## 追加したPhoenix側のページ

http://nerves.local/newworld

http://nerves.local/newworld/uramasu
