# imageEditor.exe

## Overview

imageEditor is a simple image viewer based on the Image class and MFC CImage class.

This application is intended for image viewing and format conversion. Image editing functions are not included.

## Main Features

- Supports JPG, BMP, PNG, and TIFF formats
- Maximum image size: 16000 × 16000 pixels
- Mouse wheel zoom centered on the screen
- Mouse drag scrolling
- Image format conversion and save

## Supported Image Formats

Supported formats:

- JPG
- BMP
- PNG
- TIFF

Maximum image size: **16000 × 16000 pixels**

Images exceeding this limit are automatically resized when loaded.

## Development Environment

- Windows 11
- Visual Studio 2022
- VC++ MFC

## Class Structure

| Class | Description |
|---------|---------|
| CimageViewerDlg | Main MFC dialog |
| Cbutton | Button class |

## Build Instructions

- Open the solution in Visual Studio 2022 or later.
- Configuration: Release/x64 or Debug/x64
- MFC: Use MFC in a Shared DLL
- Runtime Library: /MD (Multi-threaded DLL)

> **Note**
>
> Do not use **/MT (Static Runtime)**.
> It conflicts with the MFC configuration and the project will fail to build.

---

# 日本語

## プログラムの概要

ImageクラスおよびCImageクラスを用いた画像ビューアーです。

編集機能はありません。

## 主な機能

- 対応フォーマット: JPG / BMP / PNG / TIFF
- ロード可能画像サイズ: 16000 × 16000 pixel
- マウスホイールによるスクリーンセンター基準のズーム
- マウスドラッグによるスクロール
- フォーマット変換保存

## 対応画像フォーマット

- JPG
- BMP
- PNG
- TIFF

最大対応サイズ: **16000 × 16000 pixel**

上限を超える画像は自動的にリサイズされます。

## 開発環境

- Windows 11
- Visual Studio 2022
- VC++ MFC

## クラス

| クラス | 説明 |
|---------|---------|
| CimageViewerDlg | MFCメインダイアログ |
| Cbutton | ボタンクラス |

## ビルド方法

- Visual Studio 2022 以降で開きます
- 構成: Release/x64 または Debug/x64
- MFC: Use MFC in a Shared DLL（共有DLL）
- ランタイムライブラリ: /MD（マルチスレッドDLL）

> **注意**
>
> /MT（スタティックランタイム）は使用しないでください。
>
> MFC設定と競合するため、ビルドできません。
