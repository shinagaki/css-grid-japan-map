# CSS Grid シンプル日本地図

CSS Gridを使って作るシンプルな日本都道府県マップのデモプロジェクトです。

## 🌐 ライブデモ

**GitHub Pages**: https://shinagaki.github.io/css-grid-japan-map/

## 📋 サンプルファイル

### 🎨 basic-three-versions.html
**基本的な3つのバリエーションを1つのファイルで提供**
- **単色版**: シンプルなブルーグラデーション
- **地域別カラー版**: 8地域の色分け表示
- **aタグ版**: リンク化とキーボード対応

- [ライブデモ](https://shinagaki.github.io/css-grid-japan-map/samples/basic-three-versions.html)
- [ソースコード](./samples/basic-three-versions.html)

### ♿ accessibility-enhanced.html
**アクセシビリティ完全対応版**
- WCAG 2.1 AA準拠
- スクリーンリーダー完全対応
- キーボードナビゲーション
- レスポンシブデザイン
- 高コントラストモード対応
- アニメーション無効化対応

- [ライブデモ](https://shinagaki.github.io/css-grid-japan-map/samples/accessibility-enhanced.html)
- [ソースコード](./samples/accessibility-enhanced.html)



## ✨ 主な特徴

- ⚡ **軽量・高速**: HTML + CSS のみで実装、JavaScript不要
- 📱 **レスポンシブ**: スマートフォンからデスクトップまで自動調整
- ♿ **アクセシブル**: WCAG 2.1準拠のアクセシビリティ対応
- 🎨 **カスタマイズ容易**: CSS変数で簡単に色やサイズを変更可能
- 🔧 **保守性**: シンプルな構造で理解・修正が容易

## 🛠️ 技術仕様

| 項目 | 詳細 |
|------|------|
| **グリッドシステム** | 12列×16行のCSS Grid |
| **ブラウザ対応** | Chrome 57+, Firefox 52+, Safari 10.1+, Edge 16+ |
| **ファイルサイズ** | HTML + CSS 約15KB |
| **パフォーマンス** | JavaScript不要で高速描画 |

## 📁 プロジェクト構成

```
css-grid-japan-map/
├── index.html                    # GitHub Pagesランディングページ
├── samples/                      # サンプルファイル
│   ├── basic-three-versions.html # 基本3バージョン（学習・プロトタイプ用）
│   └── accessibility-enhanced.html # アクセシビリティ完全対応版（本格運用用）
├── _config.yml                  # Jekyll設定
└── README.md                    # このファイル（完全版ドキュメント）
```

## 📂 ファイル詳細

### 🎨 basic-three-versions.html
**学習・プロトタイプ向けの基本実装**

#### 含まれる3つのバージョン:
1. **単色版**: シンプルなブルーグラデーション
2. **地域別カラー版**: 8地域の色分け表示  
3. **aタグ版**: リンク化とtabindex対応

#### 特徴:
- 軽量でシンプルな実装
- 1ファイルで3パターン確認可能
- 基本的なホバーアニメーション
- 12×4グリッドレイアウト

### ♿ accessibility-enhanced.html
**本格運用向けのアクセシビリティ完全対応版**

#### アクセシビリティ機能:
- **WCAG 2.1 AA準拠**: 完全なアクセシビリティ対応
- **スクリーンリーダー対応**: ARIA属性とsr-onlyテキスト
- **キーボードナビゲーション**: 視覚的配置順でのtabindex
- **スキップリンク**: メインコンテンツへの直接移動
- **高コントラストモード**: `prefers-contrast: high`対応
- **アニメーション無効化**: `prefers-reduced-motion`対応

#### 追加機能:
- **レスポンシブデザイン**: タブレット・スマートフォン対応
- **動的情報パネル**: 都道府県選択時の詳細表示
- **インタラクティブ機能**: クリック・フォーカス・選択状態管理

## 🎯 適用に向いているケース

- 📊 **データ可視化**が主目的
- ⚡ **軽量・高速**が重要
- 🔧 **保守性**を重視
- 📱 **レスポンシブ**対応が必要
- ♿ **アクセシビリティ**対応が必要

## 🚫 避けるべきケース

- 🗾 **地理的精度**が最重要
- 🎨 **複雑な形状**表現が必要
- 🏝️ **離島の詳細**表示が重要

## 📄 ライセンス

MIT License

## 📞 お問い合わせ

- GitHub Issues: [Issues](https://github.com/shinagaki/css-grid-japan-map/issues)
- ブログ: [creco.net](https://creco.net)
- Email: shinagaki@gmail.com
