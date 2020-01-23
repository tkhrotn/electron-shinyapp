# electron-shinyapp

Combine Electron with R-Portable and RStudio Shiny package to deliver Electron Applications that run standalone with R and Shiny.
Electronフレームワークとポータブル版Rを使用して、Shinyアプリケーションをスタンドアロンプログラム化します。

## To Use 使用方法

1. Install Node.js
2. Install Electron: `npm install -g electron`
3. Install Electron Packager: `npm install -g electron-packager`
4. Run packaging.bat

The standalone executable is created in the "sample-win32-x64" directory.

1. Node.jsのインストール
2. Electronのインストール: `npm install -g electron`
3. Electron Packagerのインストール: `npm install -g electron-packager`
4. packaging.batの実行

「sample-win32-x64」ディレクトリ内にアプリケーションが作成されます。

To add R packages to be used in the application, launch the portable version R from R-Portable.exe in the “R-Portable” directory and run `install.packages()`.
アプリで使用するRのパッケージを追加する場合は、「R-Portable」ディレクトリのR-Portable.exeからポータブル版Rを立ち上げて、`install.packages()`によりインストールします。


## References 参考情報

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
