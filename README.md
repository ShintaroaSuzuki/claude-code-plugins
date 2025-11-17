# shintaroasuzuki-plugins

Claude Code用のカスタムプラグインコレクション

## インストール

Claude Codeで以下のコマンドを実行してください：

```bash
/plugin marketplace add https://github.com/ShintaroaSuzuki/shintaroasuzuki-plugins
```

## 利用可能なプラグイン

### frontend-design

**Version:** 1.0.0

**説明:** 高品質なフロントエンドインターフェースを作成するためのスキルプラグインです。独創的で洗練されたデザインを実現し、一般的なAI生成デザインとは一線を画すプロダクションレベルのコードを生成します。

**主な機能:**
- 独創的で記憶に残るデザインの実装
- タイポグラフィ、カラー、モーション、レイアウトへの細やかな配慮
- HTML/CSS/JS、React、Vueなどのフレームワークに対応
- プロダクショングレードの実装品質
- アクセシビリティとパフォーマンスへの配慮

**使い方:**
Claude Codeでフロントエンド実装を依頼する際、このスキルが自動的に適用されます。

```
「ポートフォリオサイトのヒーローセクションを作成して」
「ダークテーマのダッシュボードUIを実装して」
```

**デザインの特徴:**
- 🎨 大胆で意図的な美的方向性
- ✨ 高品質なタイポグラフィと配色
- 🎭 独創的なレイアウトと空間構成
- 🎬 洗練されたアニメーションとマイクロインタラクション
- 🎯 コンテキストに応じた適切な実装

## 開発

### ディレクトリ構造

```
claude-code-plugins/
├── README.md
├── plugins/
│   └── frontend-design/
│       ├── .claude-plugin/
│       │   └── plugin.json
│       └── skills/
│           └── frontend-design/
│               └── SKILL.md
```

### 新しいプラグインの追加

1. `plugins/` ディレクトリに新しいフォルダを作成
2. `.claude-plugin/plugin.json` を設定
3. スキルやコマンドを実装
4. README.mdを更新

## ライセンス

個々のプラグインのライセンスについては、各プラグインのドキュメントを参照してください。

## コントリビューション

Issue や Pull Request は歓迎します。

## 作者

**ShintaroaSuzuki**
- GitHub: [@ShintaroaSuzuki](https://github.com/ShintaroaSuzuki)
