# Thrift: スケーラブルで言語横断的なサービスの実装

Mark Slee,
Aditya Agarwal,
Marc Kwiatkowski

Facebook, 156 University Ave, Palo Alto, CA

{mcslee,aditya,marc}@facebook.com

## 要約

Thrift は、効果的でスケーラブルなバックエンドサービスの開発を支援するため、Facebook で開発された、ソフトウェア群、及び、コードジェネレータツール群です。
各言語の共通ライブラリに手を入れる事が必要になりがちな、言語間コミュニケーションを、各言語の一部分を抽象化することによって、効率的かつ信頼性高く可能とする事がその主目的です。
より具体的には、Thrift はデータ型と、サービスのインターフェースを、特定の言語に依存しない形式で記述する事によって、RPC のクライアントとサーバーの実装に必要なすべてのコードを生成する事が出来ます。

当論文では、Thrift の背景にあるモチベーションや、設計上の選択について述べると共に、実装上の興味深い詳細部分について記述します。
当論文は、研究としてというよりは、私たちがやった事、及び、なぜそうのようにしたかの解説として捉えられることを意図したものです。


## 1. 導入

## 2. Types

## 3. Transport

## 4. Protocol

## 5. Versioning

## 6. RPC の実装

## 7. 実装詳細

## 8. Facebook での事例

## 9. まとめ

## 謝辞

Thrift に対するフィードバックを頂いた事について、Martin Smith, Karl Voskuil, Yishan Wong に感謝します。

Thrift は Adam D’Angelo の開発した Pillar というシステムの後継プロジェクトです。Pillar は最初 Caltech で開発され、後に Facebook で開発が継続されました。Thrift は Adam の見識が無ければ存在しなかったでしょう。

## 参考文献

- [1] Kempf, William, “Boost.Threads”, http://www.boost.org/doc/html/threads.html
- [2] Henkel, Philipp, “threadpool”, http://threadpool.sourceforge.net