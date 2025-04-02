# AWS Well-Architected Framework

AWS Well-Architected Framework は、クラウド上でシステムを構築する際のベストプラクティスを集めたフレームワークです。このリポジトリでは、AWS の公式サイトの Well-Architected フレームワークの内容をまとめています。

## 目次

| セクション                                  | 説明                                                                                                                | 公式リンク                                                                                                                 |
| ------------------------------------------- | ------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------- |
| [序章](./introduction/summary.md)           | AWS Well-Architected フレームワークの概要と、クラウドアーキテクチャを設計する際の基本的な考え方について説明します。 | [要約と序章](https://docs.aws.amazon.com/ja_jp/wellarchitected/latest/framework/welcome.html)                              |
| [フレームワークの柱](./pillars/overview.md) | AWS Well-Architected フレームワークを構成する 6 つの柱の概要です。                                                  | [フレームワークの柱](https://docs.aws.amazon.com/ja_jp/wellarchitected/latest/framework/the-pillars-of-the-framework.html) |

### 1. オペレーショナルエクセレンス

| トピック                                                          | 説明                                                       | 公式リンク                                                                                                                     |
| ----------------------------------------------------------------- | ---------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------ |
| [概要](./pillars/operational-excellence/overview.md)              | システムを効率的に運用し、継続的に改善するための能力です。 | [オペレーショナルエクセレンス](https://docs.aws.amazon.com/ja_jp/wellarchitected/latest/framework/operational-excellence.html) |
| [設計原則](./pillars/operational-excellence/design-principles.md) | オペレーショナルエクセレンスを達成するための基本原則です。 | [設計原則](https://docs.aws.amazon.com/ja_jp/wellarchitected/latest/framework/oe-design-principles.html)                       |
| [組織](./pillars/operational-excellence/organization.md)          | 効果的な運用のための組織構造とプロセスについて説明します。 | [組織](https://docs.aws.amazon.com/ja_jp/wellarchitected/latest/framework/oe-organization.html)                                |
| [準備](./pillars/operational-excellence/prepare.md)               | 運用準備のためのプラクティスについて説明します。           | [準備](https://docs.aws.amazon.com/ja_jp/wellarchitected/latest/framework/oe-prepare.html)                                     |
| [運用](./pillars/operational-excellence/operate.md)               | 効率的な運用のためのプラクティスについて説明します。       | [運用](https://docs.aws.amazon.com/ja_jp/wellarchitected/latest/framework/oe-operate.html)                                     |
| [進化](./pillars/operational-excellence/evolve.md)                | 継続的な改善のためのプラクティスについて説明します。       | [進化](https://docs.aws.amazon.com/ja_jp/wellarchitected/latest/framework/oe-evolve.html)                                      |

### 2. セキュリティ

| トピック                                                                  | 説明                                                                 | 公式リンク                                                                                                  |
| ------------------------------------------------------------------------- | -------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------- |
| [概要](./pillars/security/overview.md)                                    | 情報、システム、資産を保護しながら、ビジネス価値を提供する能力です。 | [セキュリティ](https://docs.aws.amazon.com/ja_jp/wellarchitected/latest/framework/security.html)            |
| [設計原則](./pillars/security/design-principles.md)                       | セキュリティを確保するための基本原則です。                           | [設計原則](https://docs.aws.amazon.com/ja_jp/wellarchitected/latest/framework/sec-design.html)              |
| [ID およびアクセス管理](./pillars/security/identity-access-management.md) | ID とアクセス権限の管理について説明します。                          | [ID およびアクセス管理](https://docs.aws.amazon.com/ja_jp/wellarchitected/latest/framework/sec-iam.html)    |
| [データ保護](./pillars/security/data-protection.md)                       | データの機密性と完全性を保護する方法について説明します。             | [データ保護](https://docs.aws.amazon.com/ja_jp/wellarchitected/latest/framework/sec-dataprot.html)          |
| [インシデントへの対応](./pillars/security/incident-response.md)           | セキュリティインシデントに対応する方法について説明します。           | [インシデントへの対応](https://docs.aws.amazon.com/ja_jp/wellarchitected/latest/framework/sec-incresp.html) |

### 3. 信頼性

| トピック                                                                     | 説明                                                             | 公式リンク                                                                                                              |
| ---------------------------------------------------------------------------- | ---------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------- |
| [概要](./pillars/reliability/overview.md)                                    | ワークロードが想定された機能を実行し、障害から回復する能力です。 | [信頼性](https://docs.aws.amazon.com/ja_jp/wellarchitected/latest/framework/reliability.html)                           |
| [設計原則](./pillars/reliability/design-principles.md)                       | 信頼性の高いシステムを構築するための基本原則です。               | [設計原則](https://docs.aws.amazon.com/ja_jp/wellarchitected/latest/framework/rel-dp.html)                              |
| [基礎](./pillars/reliability/foundations.md)                                 | 信頼性の基盤となるインフラストラクチャについて説明します。       | [基礎](https://docs.aws.amazon.com/ja_jp/wellarchitected/latest/framework/rel-found.html)                               |
| [ワークロードアーキテクチャ](./pillars/reliability/workload-architecture.md) | 信頼性の高いワークロードアーキテクチャについて説明します。       | [ワークロードアーキテクチャ](https://docs.aws.amazon.com/ja_jp/wellarchitected/latest/framework/rel-workload-arch.html) |
| [変更管理](./pillars/reliability/change-management.md)                       | 変更を安全に管理する方法について説明します。                     | [変更管理](https://docs.aws.amazon.com/ja_jp/wellarchitected/latest/framework/rel-chg-mgmt.html)                        |
| [障害管理](./pillars/reliability/failure-management.md)                      | 障害への対応と回復について説明します。                           | [障害管理](https://docs.aws.amazon.com/ja_jp/wellarchitected/latest/framework/rel-failmgmt.html)                        |

### 4. パフォーマンス効率

| トピック                                                                           | 説明                                                                                           | 公式リンク                                                                                                               |
| ---------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------ |
| [概要](./pillars/performance-efficiency/overview.md)                               | コンピューティングリソースを効率的に使用し、需要の変化とテクノロジーの進化に対応する能力です。 | [パフォーマンス効率](https://docs.aws.amazon.com/ja_jp/wellarchitected/latest/framework/performance-efficiency.html)     |
| [設計原則](./pillars/performance-efficiency/design-principles.md)                  | パフォーマンス効率を向上させるための基本原則です。                                             | [設計原則](https://docs.aws.amazon.com/ja_jp/wellarchitected/latest/framework/perf-dp.html)                              |
| [アーキテクチャの選択](./pillars/performance-efficiency/architecture-selection.md) | 効率的なアーキテクチャの選択について説明します。                                               | [アーキテクチャの選択](https://docs.aws.amazon.com/ja_jp/wellarchitected/latest/framework/perf-arch.html)                |
| [コンピューティングとハードウェア](./pillars/performance-efficiency/compute.md)    | 効率的なコンピューティングリソースの使用について説明します。                                   | [コンピューティングとハードウェア](https://docs.aws.amazon.com/ja_jp/wellarchitected/latest/framework/perf-compute.html) |
| [データ管理](./pillars/performance-efficiency/data-management.md)                  | 効率的なデータ管理について説明します。                                                         | [データ管理](https://docs.aws.amazon.com/ja_jp/wellarchitected/latest/framework/perf-data.html)                          |
| [ネットワークとコンテンツ配信](./pillars/performance-efficiency/networking.md)     | 効率的なネットワーク構成について説明します。                                                   | [ネットワークとコンテンツ配信](https://docs.aws.amazon.com/ja_jp/wellarchitected/latest/framework/perf-networking.html)  |
| [プロセスと文化](./pillars/performance-efficiency/process-culture.md)              | 効率性を重視した組織文化について説明します。                                                   | [プロセスと文化](https://docs.aws.amazon.com/ja_jp/wellarchitected/latest/framework/perf-process.html)                   |

### 5. コスト最適化

| トピック                                                                                | 説明                                                     | 公式リンク                                                                                                            |
| --------------------------------------------------------------------------------------- | -------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------- |
| [概要](./pillars/cost-optimization/overview.md)                                         | 最低コストでビジネス成果を達成する能力です。             | [コスト最適化](https://docs.aws.amazon.com/ja_jp/wellarchitected/latest/framework/cost-optimization.html)             |
| [設計原則](./pillars/cost-optimization/design-principles.md)                            | コスト最適化のための基本原則です。                       | [設計原則](https://docs.aws.amazon.com/ja_jp/wellarchitected/latest/framework/cost-dp.html)                           |
| [クラウド財務管理を実践する](./pillars/cost-optimization/cloud-financial-management.md) | クラウド財務管理のプラクティスについて説明します。       | [クラウド財務管理を実践する](https://docs.aws.amazon.com/ja_jp/wellarchitected/latest/framework/cost-cfm.html)        |
| [経費支出と使用量の認識](./pillars/cost-optimization/expenditure-awareness.md)          | コスト意識を高めるためのプラクティスについて説明します。 | [経費支出と使用量の認識](https://docs.aws.amazon.com/ja_jp/wellarchitected/latest/framework/cost-aware.html)          |
| [費用対効果の高いリソース](./pillars/cost-optimization/cost-effective-resources.md)     | コスト効率の高いリソース選択について説明します。         | [費用対効果の高いリソース](https://docs.aws.amazon.com/ja_jp/wellarchitected/latest/framework/cost-cereso.html)       |
| [需要を管理しリソースを供給する](./pillars/cost-optimization/manage-demand-supply.md)   | 需要と供給の最適化について説明します。                   | [需要を管理しリソースを供給する](https://docs.aws.amazon.com/ja_jp/wellarchitected/latest/framework/cost-mandem.html) |
| [継続的最適化](./pillars/cost-optimization/continuous-optimization.md)                  | コストを継続的に最適化する方法について説明します。       | [継続的最適化](https://docs.aws.amazon.com/ja_jp/wellarchitected/latest/framework/cost-opti.html)                     |

### 6. 持続可能性

| トピック                                                                                   | 説明                                                           | 公式リンク                                                                                                                                 |
| ------------------------------------------------------------------------------------------ | -------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------ |
| [概要](./pillars/sustainability/overview.md)                                               | 環境影響を最小限に抑えながら、ビジネスニーズを満たす能力です。 | [持続可能性](https://docs.aws.amazon.com/ja_jp/wellarchitected/latest/framework/sustainability.html)                                       |
| [設計原則](./pillars/sustainability/design-principles.md)                                  | 持続可能なクラウド利用のための基本原則です。                   | [設計原則](https://docs.aws.amazon.com/ja_jp/wellarchitected/latest/framework/sus-design-principles.html)                                  |
| [リージョンの選択](./pillars/sustainability/region-selection.md)                           | 持続可能性を考慮したリージョン選択について説明します。         | [リージョンの選択](https://docs.aws.amazon.com/ja_jp/wellarchitected/latest/framework/sus-region-selection.html)                           |
| [需要に合わせた調整](./pillars/sustainability/user-behavior-patterns.md)                   | リソース使用の最適化について説明します。                       | [需要に合わせた調整](https://docs.aws.amazon.com/ja_jp/wellarchitected/latest/framework/sus-user-behavior-patterns.html)                   |
| [ソフトウェアとアーキテクチャ](./pillars/sustainability/software-architecture-patterns.md) | 持続可能なソフトウェア設計について説明します。                 | [ソフトウェアとアーキテクチャ](https://docs.aws.amazon.com/ja_jp/wellarchitected/latest/framework/sus-software-architecture-patterns.html) |
| [データ管理](./pillars/sustainability/data-patterns.md)                                    | 持続可能なデータ管理について説明します。                       | [データ管理](https://docs.aws.amazon.com/ja_jp/wellarchitected/latest/framework/sus-data-patterns.html)                                    |
| [ハードウェアとサービス](./pillars/sustainability/hardware-patterns.md)                    | 持続可能なハードウェア利用について説明します。                 | [ハードウェアとサービス](https://docs.aws.amazon.com/ja_jp/wellarchitected/latest/framework/sus-hardware-patterns.html)                    |
| [プロセスと文化](./pillars/sustainability/development-deployment-patterns.md)              | 持続可能性を重視した開発文化について説明します。               | [プロセスと文化](https://docs.aws.amazon.com/ja_jp/wellarchitected/latest/framework/sus-development-deployment-patterns.html)              |

### その他のセクション

| セクション                                              | 説明                                                                                      | 公式リンク                                                                                                         |
| ------------------------------------------------------- | ----------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------ |
| [レビュープロセス](./review-process/summary.md)         | AWS Well-Architected フレームワークを使ったワークロードのレビュー方法について説明します。 | [レビュープロセス](https://docs.aws.amazon.com/ja_jp/wellarchitected/latest/framework/the-review-process.html)     |
| [付録: 質問とベストプラクティス](./appendix/summary.md) | 各柱ごとの質問事項とベストプラクティスのリストです。                                      | [付録: 質問とベストプラクティス](https://docs.aws.amazon.com/ja_jp/wellarchitected/latest/framework/appendix.html) |
| [リソース](./resources/summary.md)                      | AWS Well-Architected に関連するリソースやツールへのリンク集です。                         | [詳細情報](https://docs.aws.amazon.com/ja_jp/wellarchitected/latest/framework/further-reading.html)                |

## 関連リソース

- [AWS Well-Architected](https://aws.amazon.com/architecture/well-architected/)
- [AWS Well-Architected Tool](https://aws.amazon.com/well-architected-tool/)
- [AWS Well-Architected ラボ](https://www.wellarchitectedlabs.com/)
- [AWS Well-Architected パートナープログラム](https://aws.amazon.com/architecture/well-architected/partners/)
