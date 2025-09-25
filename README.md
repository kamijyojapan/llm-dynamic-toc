# チャットAI用ダイナミック目次 (LINE風UI) | Dynamic TOC for Chat AI

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

ChatGPT, Claude, Geminiの会話ページに、LINEのようなUIの動的な目次を追加するUserScriptです。長文の会話でも、この目次を使えば瞬時に目的の箇所にジャンプできます。

[English](./README.en.md) | 日本語

![スクリーンショット](https://raw.githubusercontent.com/kamijyojapan/llm-dynamic-toc/main/images/screenshot.png)

## ✨ 主な機能

* **LINE風のUI**: ユーザーの発言は右寄せ（緑）、AIの応答は左寄せ（白）で表示され、会話の流れが一目でわかります。
* **マルチプラットフォーム対応**:
    * **ChatGPT** (`chat.openai.com`, `chatgpt.com`)
    * **Claude** (`claude.ai`)
    * **Gemini** (`gemini.google.com`)
* **動的な自動更新**: 会話が続くたびに、目次が自動で更新されます。
* **現在地のハイライト**: スクロールすると、今画面に表示されている会話の項目がリアルタイムでハイライトされます。
* **柔軟な操作性**:
    * **ドラッグ＆ドロップ**: 目次ウィンドウを好きな場所に移動できます。
    * **最小化・復元**: ウィンドウを最小化して、作業の邪魔にならないようにできます。
    * **閉じる機能**: 不要な場合は閉じることができます（ページをリロードすると再表示されます）。

## 🚀 インストール方法

1.  **Tampermonkeyのインストール**
    お使いのブラウザに、まずUserScriptマネージャーである [Tampermonkey](https://www.tampermonkey.net/) をインストールしてください。
    * [Chrome](https://chrome.google.com/webstore/detail/tampermonkey/dhdgffkkebhmkfjojejmpbldmpobfkfo)
    * [Firefox](https://addons.mozilla.org/en-US/firefox/addon/tampermonkey/)
    * [Edge](https://microsoftedge.microsoft.com/addons/detail/tampermonkey/iikmkjmpaadaobahmlepeloendndfphd)
    * [Safari](https://apps.apple.com/us/app/tampermonkey/id1482490089)

2.  **このUserScriptのインストール**
    下のリンクをクリックすると、Tampermonkeyのインストール画面が開きます。
    
    👉 **[最新版をインストール](https://github.com/kamijyojapan/llm-dynamic-toc/raw/main/llm-dynamic-toc.user.js)**
    
    `[インストール]` ボタンをクリックして、インストールを完了してください。

3.  **確認**
    [ChatGPT](https://chat.openai.com/), [Claude](https://claude.ai/), [Gemini](https://gemini.google.com/) のいずれかのページを開き、画面右上に目次が表示されれば成功です。

## 🔧 開発者向け情報

### ビルド
このプロジェクトはビルドプロセスを必要とせず、単一の `.js` ファイルで動作します。

### 貢献
改善の提案やバグ報告は、[GitHub Issues](https://github.com/kamijyojapan/llm-dynamic-toc/issues) までお気軽にどうぞ。プルリクエストも歓迎します。

## 📄 ライセンス

このスクリプトは [MIT License](https://opensource.org/licenses/MIT) の下で公開されています。

---
Icons by [Google Fonts](https://fonts.google.com/icons).