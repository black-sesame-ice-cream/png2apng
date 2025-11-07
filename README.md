# PNG to APNG

## Recommended Environment
This tool is designed for use on a PC with the Google Chrome browser. Operation on other devices or browsers is not guaranteed.

## 推奨環境
このツールは、PC上のGoogle Chromeブラウザでの使用を想定しています。他のデバイスやブラウザでの動作は保証されていません。

## Demo
You can try this tool on the page below.

https://black-sesame-ice-cream.github.io/png2apng/

## デモ
以下のページでこのツールを試すことができます。

https://black-sesame-ice-cream.github.io/png2apng/

## Overview
This is a web tool that converts multiple PNG files into an Animated PNG (APNG) entirely within your browser.

- **Client-Side Processing:** All conversion processes are completed within the browser. PNG files are not uploaded to a server, ensuring privacy.
- **APNG Preview:** Before downloading, you can check the generated APNG animation in a modal window.
- **Detailed Frame Settings:** You can reorder frames via drag-and-drop and set the display duration (delay) for each frame individually.
- **Conversion Options:** Allows setting the loop count, output dimensions (width/height), and color depth (quantization) for file size reduction.
- **Note**: This tool is intended for relatively light processing. Attempting to process high-resolution images exceeding Full HD or a large number of frames (hundreds) at once may cause the browser to crash depending on your PC's memory.

## 概要
複数のPNGファイルをブラウザ上でアニメーションPNG (APNG) に変換するWebツールです。

- **クライアントサイド完結:** すべての変換処理がブラウザ内で完結します。PNGファイルがサーバーにアップロードされることはないため、プライバシーが保護されます。
- **APNGプレビュー機能:** ダウンロードする前に、生成されるAPNGアニメーションをモーダルウィンドウで確認できます。
- **詳細なフレーム設定:** フレームの順序をドラッグ＆ドロップで並び替えたり、各フレームの表示時間（遅延）を個別に設定したりできます。
- **変換オプション:** ループ回数、出力サイズ（幅・高さ）、およびファイルサイズ削減のための色深度（減色）指定に対応しています。
- **（注）** 比較的軽い処理を想定しています。フルHDを超える高解像度の画像や、数百枚を超える大量のフレームを一度に処理しようとすると、お使いのPCのメモリ量によってはブラウザがクラッシュする可能性があります。

## Usage
1.  Drag and drop PNG files onto the drop zone, or click the zone to select files.
2.  Uploaded files will appear in the "File List". You can sort or delete them here.
3.  Click the "▼ Send to Frames" button to move the files to the "Frame Sequence".
4.  In the "Conversion Options" section, configure settings such as delay time, loop count, output dimensions, and color depth.
    - You can apply the delay time to all frames at once using the "Apply" button.
5.  In the "Frame Sequence" section:
    - Drag and drop list items to reorder the animation frames.
    - Adjust the delay time (ms) for individual frames.
    - Remove specific frames using the 'X' button.
6.  Click the "Preview" button to check the resulting APNG in a modal window. (If settings are unchanged, a cached preview will be shown instantly).
7.  Click the "Save APNG" button to start the conversion and download the file.

## 使い方
1.  PNGファイルをドラッグ＆ドロップゾーンにドロップするか、ゾーンをクリックしてファイルを選択します。
2.  アップロードされたファイルが「ファイルリスト」に表示されます。ここでソートや削除が可能です。
3.  「▼ フレームに送る」ボタンをクリックして、ファイルを「フレームシーケンス」に移動します。
4.  「変換オプション」セクションで、保持時間、ループ回数、出力サイズ、色深度などの設定を行います。
    - 保持時間は「適用」ボタンで全フレームに一括適用できます。
5.  「フレームシーケンス」セクションで以下の操作を行います。
    - リスト項目をドラッグ＆ドロップして、アニメーションの順序を並び替えます。
    - 個別のフレームの保持時間 (ms) を調整します。
    - 「×」ボタンで特定のフレームを削除します。
6.  「プレビュー」ボタンをクリックすると、モーダルウィンドウで結果のAPNGを確認できます。（設定が変更されていなければ、キャッシュされたプレビューが即座に表示されます）。
7.  「APNGを保存」ボタンをクリックすると、変換が開始され、ファイルがダウンロードされます。

## Licenses
Please see below for details.

[License](LICENSE/)

[Third-Party Licenses](THIRD-PARTY-LICENSES.txt/)

## ライセンス
以下を参照してください。

[ライセンス](LICENSE/)

[第三者ライセンス](THIRD-PARTY-LICENSES.txt/)

## Tech Stack
- HTML5
- [Tailwind CSS](https://tailwindcss.com/)
- JavaScript (ES6+)
- [UPNG.js](https://github.com/photopea/UPNG.js)
- [pako.js](https://github.com/nodeca/pako) (Dependency for UPNG.js)
