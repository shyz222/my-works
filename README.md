# 目次
- [目次](#目次)
- [目的](#目的)
- [ルール](#ルール)
  - [ディレクトリ・ファイル命名規則](#ディレクトリファイル命名規則)
  - [git戦略](#git戦略)
- [tips](#tips)
# 目的
- 業務またはプライベートで学んだ内容のアウトプット・備忘録
# ルール
## ディレクトリ・ファイル命名規則
- 小文字とハイフン
- 拡張性を考慮した命名をすること
  - サービス単体に関する内容はサービス名
  - 複数のサービスを組み合わせた内容やシナリオ/ユースケースに沿う内容はシナリオ名
  - 認定試験対策で調べた内容は認定試験名
  ```
  {serviceName}
  scenario/{scenarioDetail}
  {certificationExamName}
  ```
  - ex
  ```
  ec2
  lambda
  scenario/how-to-manage-multi-account
  aws-certified-sap
  ```
## git戦略
- 基本はgit-flow
- 開発単位ごとにfeatureブランチを作成し作業（個人用なのでmaster直でも良いがgitの使い方・コマンド忘れないように）
- 個人用なのでdevelop/hotfix/releaseは採用しない
- ブランチ名は小文字とアンダースコア
# tips
- [GitHub AWS Samples](https://github.com/aws-samples)
- [AWS や Azure サービスと Google Cloud を比較する](https://cloud.google.com/free/docs/aws-azure-gcp-service-comparison?hl=ja)
- [要注意な技術英語](https://qiita.com/shibukawa/items/8ae46cff850718e670d7#:~:text=September%2013%2C%202016-,SQL%5B%CB%88si%CB%90kw%C9%99l%5D,%E3%81%A8%E3%81%AA%E3%82%8B%E3%81%A8%E3%81%AE%E3%81%93%E3%81%A8%E3%81%A7%E3%81%99%E3%80%82)