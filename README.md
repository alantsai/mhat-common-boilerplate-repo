# mhat-common-boilerplate-repo

這個專案的目的是提供一個template，方便建立新專案的時候，包含需要的最基本資訊。

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

指令來說就是：

```powershell
git clone https://github.com/alantsai/mhat-common-boilerplate-repo.git
cd mhat-common-boilerplate-repo
rm .git -Recurse -Force
git init
git add -A
git commit -m "init project"
```

### 包含這個專案的歷史記錄

操作步奏

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