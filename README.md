# mhat-common-boilerplate-repo

[![Gitter](https://img.shields.io/gitter/room/nwjs/nw.js.svg)](https://gitter.im/alantsai/mhat-common-boilerplate-repo?utm_source=share-link&utm_medium=link&utm_campaign=share-link)

這個專案的目的是提供一個template，方便建立新專案的時候，包含需要的最基本資訊。

每一個資料夾或者檔案的作用詳細說明可以參考我的部落格[該怎麼開專案的資料夾結構？每個專案應該要有的資料夾結構和檔案](http://to.alantsai.net/20170723-blog-github)

在使用的時候，quote (>作為開頭的文字)都可以刪掉，那些是說明用途。

> 這個部分的內容主要簡短介紹這個專案的目的。有些時候會在這個部分放上一些標章（例如建制情況等）和專案的logo。

## 安裝 (install)

這個專案並無安裝的前置條件

> 這個部分寫的是開始使用的前置條件 - 例如用`npm`或者`nuget`安裝的指令。

## 快速使用 (getting started)

使用這個專案有兩種模式：  
1. 不包含這個專案的歷史記錄
2. 包含這個專案的歷史記錄

### 不包含這個專案的歷史記錄

可以直接下載最新版本的zip檔案：

[下載最新的zip](https://github.com/alantsai/mhat-common-boilerplate-repo/archive/master.zip)

或者可以 ：

1. clone專案
2. 刪除.git資料夾
3. 重新git init（新的版控記錄）

Powershell指令來說就是：

```powershell
git clone https://github.com/alantsai/mhat-common-boilerplate-repo.git
cd mhat-common-boilerplate-repo
rm .git -Recurse -Force
git init
git add -A
git commit -m "init project"
```

### 包含這個專案的歷史記錄

操作步驟

1. clone專案
2. 刪掉origin的位置
3. 調整origin到新的位置

```powershell
git clone https://github.com/alantsai/mhat-common-boilerplate-repo.git
cd mhat-common-boilerplate-repo
git remote rm origin
git remote add origin {new repo url}
```

> 這個部分告訴大家如何開始使用你的這個專案。一般來說提供一個hello world範例之後，會提供鏈接到詳細的doc說明。

## 幫助 (support)

如果有任何問題，可以透過[開issue](https://github.com/alantsai/mhat-common-boilerplate-repo/issues/new) 或者 可以在 [gitter](https://gitter.im/alantsai/mhat-common-boilerplate-repo?utm_source=share-link&utm_medium=link&utm_campaign=share-link)上面發問。

## 參與修改 (Contributing)

歡迎任何形式的參與，更多資訊請參考  
[CONTRIBUTING.md](CONTRIBUTING.md)

## 貢獻者 (Contributors)

> 如果有任何要感謝的貢獻者，可以專門寫到 `CONTRIBUTORS.md` 檔案，或者直接在這個檔案裡面列出來。

## 作者 (Authors)

> 假設需要列出專案的作者（和版權有關），那麼可以列在 `AUTHORS.md` 裡面。

## 感謝 (Acknowledgements)

> 如果專案有使用到一些第三方的library或者一些資源想要感謝可以卸載這裡，或者如果內容比較多可以列在 `ACKNOWLEDGMENTS.md` 裡面。

## 授權 (License)

本專案屬於 MIT License，更多資訊請看 [LICENSE.md](LICENSE.md)
