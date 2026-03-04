# MoCKA Civilization

MoCKA Civilization defines the governance doctrine, constitutional principles, and institutional structure of the MoCKA Ecosystem.

It formalizes responsibility boundaries, cryptographic commitments, and the rules under which AI agents operate.

This repository is the doctrinal core of the ecosystem.

## Architecture Overview

Civilization sits above execution and memory layers.
It defines the rules that other repositories must follow.

![MoCKA Architecture Overview](docs/architecture/mocka_architecture_overview.png)

## Security Model

Threat assumptions:

- Undefined responsibility boundaries
- Governance drift
- Unauthorized structural modification
- Ambiguity in cryptographic authority

Controls:

- Explicit constitutional definitions
- Documented governance layers
- Clear separation of institutional roles
- Ed25519-based commitment model
- Traceable revision history

Civilization does not execute.
It defines what is allowed to execute.

## Repository Responsibility

This repository focuses on:

- Governance doctrine and institutional definitions
- Constitutional documents
- Role separation and authority models
- Change management principles

## Relationship to Ecosystem

- MoCKA: implements governed execution
- Knowledge Gate: preserves governed memory
- Transparency: publishes governed proof
- External Brain: operates under defined constraints

---

# MoCKA Civilization（日本語）

MoCKA Civilization は、MoCKA エコシステムの統治思想・憲章原則・制度構造を定義する層です。

責任境界、暗号的コミットメント、AIエージェントが従うべき規範を明文化します。

本リポジトリは思想的中枢です。

## Architecture Overview（全体図）

Civilization は実行層・記憶層の上位に位置します。
他レイヤが従うべき規則を定義します。

![MoCKA Architecture Overview](docs/architecture/mocka_architecture_overview.png)

## Security Model（脅威と対策）

想定脅威：

- 責任境界の曖昧化
- 統治方針の漂流
- 無権限な構造変更
- 暗号的権限の不明確化

対策：

- 明示的な憲章定義
- 文書化された統治層構造
- 役割分離の徹底
- Ed25519 による統治コミット
- 追跡可能な改訂履歴

Civilization は実行しません。
実行の許可条件を定義します。

## 本リポジトリの責務

- 統治思想の定義
- 憲章文書の維持
- 権限モデルの明確化
- 変更管理原則の策定

## エコシステム関係

- MoCKA：統治下で実行
- Knowledge Gate：統治下で保存
- Transparency：統治下で公開
- External Brain：定義された制約下で接続
