#
# electron-shinyapp
#

Electronフレームワークとポータブル版Rを使用して、Shinyアプリケーションを
デスクトップアプリ化するサンプルプログラムです。
まずは以下の手順でアプリ化に使用するプログラムをインストールしてください。

1. Node.jsのインストール

2. Electronのインストール（以下のコマンドを実行）
   > npm install -g electron

3. Electron Packagerのインストール（以下のコマンドを実行）
   > npm install -g electron-packager


その後「packaging.bat」を実行すると「sample-win32-x64」ディレクトリが作成されます。
このディレクトリ中の「sample.exe」を実行するとアプリケーションが起動します。

Shinyアプリのコードは「app.R」です。RStudioで開発を行う場合は
「electron-shinyapp.Rproj」を開いてください。

アプリで使用するRのパッケージを追加する場合は、「R-Portable」ディレクトリの
R-Portable.exeからポータブル版Rを立ち上げて、install.package()によりインストールします。
（PCにインストールしたRからは独立しているので、再度インストールする必要があります）


参考情報：

Node.js
https://nodejs.org/ja/

Electron
https://electronjs.org/

Electron Packager
https://www.npmjs.com/package/electron-packager

R Portable
https://sourceforge.net/projects/rportable/

Electron_ShinyApp_Deployment
(そのままでは動かなかったのでスクリプトを修正しました)
https://github.com/ksasso/Electron_ShinyApp_Deployment


