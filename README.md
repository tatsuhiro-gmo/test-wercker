# test-wercker
sandbox

== release flow

masterへのpushをトリガにwerckerがビルドを実行します。

version.txtに書かれているバージョンがgithubのtagより大きければ、そのバージョンでReleaseを作成します。

同じか低い場合はwerckerでエラーとなり、Releaseへの登録はしません。

