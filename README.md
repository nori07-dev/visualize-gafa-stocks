# GAFA株価ビジュアライザー - GAFA Stock Visualizer

![My Image](image/demo.gif)



## 📘 概要 - Overview

本アプリは、米国の主要IT企業（GAFA：Google, Apple, Facebook, Amazon）の株価変動をグラフ形式で可視化するツールです。
Streamlit を使って、簡単に Web ブラウザで動作します。

This is a visualization tool that displays stock price fluctuations of major U.S. tech companies (GAFA: Google, Apple, Facebook, Amazon) in graph format.
Built with Streamlit, it runs easily in your web browser.

---

## 🛠️ 事前準備 - Installation

以下の手順でアプリを実行できます：

1. Python 環境が整っていることを確認してください。
2. Streamlit をインストールします：

```bash
pip install streamlit
```

---

## 🚀 実行方法 - How to Run

メインファイル `app.py` を使用します。
以下のコマンドでアプリを起動してください：

```bash
streamlit run app.py
```

起動後、ブラウザでアプリが開き、GAFAの株価が表示されます。

Once started, the app will open in your browser and display GAFA stock trends.

---

## ⛔ Streamlitの終了方法 - How to Stop Streamlit

▶️ ターミナル・コマンドラインで起動した場合（`streamlit run app.py`）

### ⏰ 終了方法:

ターミナルで **Ctrl + C** を押すだけです！

* **Mac / Linux**: `control + C`
* **Windows**: `Ctrl + C`

これでStreamlitサーバーが停止し、アプリが終了します。

### 🩼 忽のためキャッシュもクリアしたい場合（オプション）

```bash
streamlit cache clear
```

### 📍 VSCodeターミナルを使っている場合

ターミナルを止める方法は以下のいずれかです：

* `Ctrl + C`
* ターミナルパネルの右上にある「ゴミ箱アイコン」(終了) をクリック

---

## 📄 補說 - Notes

* 本アプリはデモ目的であり、実際の投資判断には利用しないでください。
* GAFAの株価情報は外部APIまたはCSVファイルを利用して取得している場合があります。

This app is for demo purposes only and should not be used for investment decisions.

---