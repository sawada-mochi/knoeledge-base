# Python実務アプリ開発ロードマップ（Mac環境）

Mac + VSCode + Python3.8.8 環境で
**実務で使えるツールを作りながらPythonを習得するロードマップ**

対象

* Python初〜中級
* 業務ツールを作りたい
* WEBアプリ / デスクトップアプリを作りたい

---

# 開発環境

* Python 3.8.8
* VS Code
* Git / GitHub

推奨ライブラリ

```
pandas
pypdf
openpyxl
PySide6
FastAPI
uvicorn
```

---

# フェーズ1（1〜2週間）

## Python基礎 + 業務自動化ツール

まずは **コマンドラインツール** を作る。

## 作るもの①

### PDF一括処理ツール

機能

* フォルダ内PDF一覧取得
* PDFリネーム
* PDF結合
* CSVからファイル名変更

例

```
scan001.pdf
scan002.pdf
```

↓

```
20260301_山田太郎.pdf
20260301_佐藤花子.pdf
```

使用ライブラリ

```
pypdf
pandas
pathlib
```

学べること

* Python基本文法
* ファイル操作
* CSV処理
* PDF操作

---

## 作るもの②

### Excelデータ集計ツール

健診業務を想定

機能

* Excel読み込み
* 条件判定
* 集計
* 新しいExcel作成

使用ライブラリ

```
pandas
openpyxl
```

例

入力

```
尿糖
尿沈渣
```

↓

出力

```
判定：再検査
```

学べること

* pandas
* データ処理
* 業務ロジック

---

# フェーズ2（2〜3週間）

# デスクトップアプリ開発

PythonでGUIアプリを作る

おすすめ

```
PySide6
```

理由

* 現在の主流
* Pythonと相性が良い
* 商用利用可能

---

## 作るもの

### PDF管理デスクトップアプリ

機能

* PDFドラッグ＆ドロップ
* PDF結合
* ファイル名変更
* プレビュー

構成

```
app/
 ├ ui/
 ├ logic/
 └ main.py
```

---

## EXE化

社内配布用

```
pyinstaller
```

例

```
pyinstaller main.py --onefile
```

---

# フェーズ3（3〜4週間）

# WEBアプリ開発

おすすめフレームワーク

```
FastAPI
```

理由

* 高速
* Pythonのみで書ける
* 将来性が高い

---

## 作るもの

### PDF管理WEBアプリ

機能

* PDFアップロード
* PDF結合
* PDF検索
* ダウンロード

構成

```
FastAPI
SQLite
HTML / CSS
```

フォルダ構成

```
app/
 ├ main.py
 ├ models.py
 ├ database.py
 ├ templates/
 └ static/
```

---

# フェーズ4（1〜2ヶ月）

# 実務システム

ここまで来ると **社内ツールレベル**

---

## 健診データ管理システム

機能

* 受診者登録
* PDF管理
* 判定条件式
* 検索
* レポート生成

構成

```
FastAPI
SQLite
HTML
```

拡張

* PDF自動紐付け
* Excelインポート
* データ分析

---

# 技術スタックまとめ

| 用途       | 技術          |
| -------- | ----------- |
| Python基礎 | Python      |
| データ処理    | pandas      |
| PDF操作    | pypdf       |
| GUI      | PySide6     |
| WEB      | FastAPI     |
| データベース   | SQLite      |
| EXE化     | pyinstaller |

---

# 最終ゴール

### 健診業務支援ツール

機能

* 受診者管理
* PDF自動整理
* 判定ロジック
* レポート作成

すべて **Pythonで構築可能**

---

# 学習順序（重要）

1. Python基礎
2. PDF処理ツール
3. Excelデータ処理
4. デスクトップGUI
5. WEBアプリ

---

# 最初に作るアプリ（おすすめ）

## PDF自動リネームツール

理由

* 実務で使える
* Pythonの基本が学べる
* 約200行で作れる

---

# 今後作るアプリ候補

* PDF自動整理ツール
* 健診データ集計ツール
* 受診者管理システム
* PDF一元管理システム
* WEB版健診管理システム

---

# 参考コマンド

仮想環境作成

```
python -m venv venv
```

有効化

```
source venv/bin/activate
```

ライブラリインストール

```
pip install pandas pypdf openpyxl PySide6 fastapi uvicorn
```

---

# 更新履歴

```
2026-03-14 初版作成
```
