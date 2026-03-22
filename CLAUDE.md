# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Overview

asahi — gitコミット履歴からデイリースタンドアップレポートを生成する Claude Code スキル。

## Structure

- `SKILL.md` — スキル本体。frontmatter（name, description）+ 手順書
- `README.md` — ユーザー向けドキュメント
- `LICENSE` — MIT

## Skill開発のルール

- `SKILL.md` の frontmatter (`name`, `description`) は必須。descriptionはトリガー条件の説明に使われる
- スキルの手順は `SKILL.md` 内に記述する。Claude Code自身が実行するので外部APIは不要
- 配布は `.skill` ファイルにパッケージして GitHub Releases に置く
