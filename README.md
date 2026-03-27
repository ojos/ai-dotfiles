# Dotfiles Layer

このディレクトリは、全プロジェクト共通の AI 開発設定を管理するための領域です。

## 運用方針
- この層は本来、別リポジトリ（dotfiles repo）を Source of Truth として管理します。
- 本リポジトリには、参照しやすいようにスナップショットを配置しています。

## 対象
- `ai/common/shared-ai-rules.md`
- `ai/common/claude-instructions.md`
- `ai/common/gemini-instructions.md`

## 更新ルール
- 共通ルールを変更する場合は、まず dotfiles 側で更新する。
- 各プロジェクトへは同期（submodule/subtree/コピー）で反映する。