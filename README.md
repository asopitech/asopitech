# あそぴてっく / asopitech 👋

個人開発者として、分散システム・データベース・プログラミング言語・AI 検索基盤にまたがる OSS エコシステムを設計・実装しています。試作は各 Organization として公開し、手応えのあったものをプロダクトや企業向け機能へ育てています。

An independent developer designing and building an OSS ecosystem across distributed systems, databases, programming languages, and AI retrieval. Prototypes are published under dedicated organizations and, when they hold up, grown into products and enterprise features.

## 🚧 今つくっているもの / What I'm building right now

- **[Alopex DB](https://github.com/alopex-db/alopex)** — SQL・ベクトル検索(HNSW)・列指向を1つのRustエンジンに統合。embeddedから分散クラスタまで同じコアでスケール。[![crates.io](https://img.shields.io/crates/v/alopex-core.svg)](https://crates.io/crates/alopex-core)
  A unified Rust engine combining SQL, Vector Search (HNSW), and columnar storage — scaling from embedded to distributed on the same core.
- **[jv-lang](https://github.com/project-jvlang/jv-lang)** — Java 25をターゲットにしたゼロランタイム言語。純粋なJavaファイルへ変換し、Python/Kotlin並みの使い勝手を目指す。
  A zero-runtime language targeting Java 25, transpiling to plain Java with Python/Kotlin-level ergonomics.
- **[HC GraphRAG](https://github.com/asopitech/graphrag-anthropic-llamaindex)** — Microsoft GraphRAGをAWS Bedrock + Anthropic向けに移植。高速プロトタイピング用のPython(LlamaIndex)実装と、本番向けの[Java(ONNX)実装](https://github.com/hc-graphrag/java-core)の2系統。
  Microsoft GraphRAG ported to AWS Bedrock + Anthropic, with a Python (LlamaIndex) prototype and a production-oriented Java (ONNX) implementation.

より詳しい紹介は [asopi.tech](https://asopi.tech) を参照してください。 / See [asopi.tech](https://asopi.tech) for a fuller product overview.

## 運営している Organization / Organizations I run

| Organization | 概要 / Summary | Status |
| --- | --- | --- |
| [asopitech-labs](https://github.com/asopitech-labs) | 新しい技術を試作・検証する R&D ラボ / R&D lab prototyping new technologies（Nimino, Nimculus, Theatora, GUDGEON など） | 🔬 Ongoing experiments |
| [alopex-db](https://github.com/alopex-db) | Alopex DB / Skulk / Chirps を開発する Rust データベースエコシステム / The Rust database ecosystem behind Alopex DB, Skulk, and Chirps | 🚧 In development |
| [project-jvlang](https://github.com/project-jvlang) | jv-lang の言語仕様・コンパイラ・ドキュメントを管理 / Language spec, compiler, and docs for jv-lang | 🚧 In development |
| [hc-graphrag](https://github.com/hc-graphrag) | HC GraphRAG の Java(ONNX) 本番実装を管理 / Home of the HC GraphRAG Java (ONNX) production implementation | 🚧 In development |

構想・準備中の企業向け機能（Alopex Enterprise、TUBUSA/備 など）は [asopi.tech](https://asopi.tech) で紹介しています。 / Enterprise-facing concepts in design (Alopex Enterprise, TUBUSA/備, etc.) are introduced on [asopi.tech](https://asopi.tech).

## リンク / Links

- 🌐 asopi.tech: <https://asopi.tech>
- 📝 Zenn（技術記事）: <https://zenn.dev/asopitech>
- 🐦 X: <https://x.com/asopitech_iot>
- ❤️ GitHub Sponsors: <https://github.com/sponsors/asopitech>
- ☕ Buy Me a Coffee: <https://buymeacoffee.com/asopitechia>
