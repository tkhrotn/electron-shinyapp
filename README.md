# electron-shinyapp

Electronフレームワークとポータブル版Rを使用して、Shinyアプリケーションをデスクトップアプリ化するサンプルプログラムです。

## 使用方法

1. Node.jsのインストール
2. Electronのインストール: `npm install -g electron`
3. Electron Packagerのインストール: `npm install -g electron-packager`
4. packaging.batの実行

「sample-win32-x64」ディレクトリ内にアプリケーションが作成されます。
Shinyアプリのコードは「app/app.R」です。RStudioで開発を行う場合は
「electron-shinyapp.Rproj」を開いてください。

アプリで使用するRのパッケージを追加する場合は、「R-Portable」ディレクトリのR-Portable.exeからポータブル版Rを立ち上げて、install.package()によりインストールします。

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
https://github.com/ksasso/Electron_ShinyApp_Deployment
