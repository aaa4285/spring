#### README

簡単な例と一緒にあなたのSpringMVCプロジェクトを始めましょう！

##### 実行方法
- プロジェクトがTomcatのパスに配置されるために、ビルドをまずした後、実行する必要があります。
- ビルド後に実行をすると、プロジェクトに接続されたドメインで実行結果を確認することができます。

##### ビルド
- ビルド時に、.warファイルの作成と既存の配布されたapplicationの削除、作成された.warファイルをTomcatのwebapps directoryに展開する処理が行われます。
- サーバーの実行中にビルドする場合、ビルド完了後しばらくするとTomcatが自動的にapplicationを再起動します。

##### 環境変数の設定
- Tomcat、Mavenパスなどの環境変数は、〜/.profileファイルに作成されていて、直接settingが必要な場合vimなどのエディタで開いて変更します。

##### Directory Role設定
- Sources Rootパスは、src/main/javaがデフォルトで設定されており、プロジェクトのプロパティで「ソースパス」を変更して設定することができます。