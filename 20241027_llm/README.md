# 目次
- [目次](#目次)
- [目的](#目的)
- [背景](#背景)
- [参考](#参考)
- [内容](#内容)
  - [AWS](#aws)
    - [Amazon Bedrock Overview 【Amazon Bedrock Series #01】](#amazon-bedrock-overview-amazon-bedrock-series-01)
    - [Amazon Bedrock モデル推論 a.準備編 【Amazon Bedrock Series #02a】](#amazon-bedrock-モデル推論-a準備編-amazon-bedrock-series-02a)
    - [Amazon Bedrock モデル推論 b.実践編 【Amazon Bedrock Series #02b】](#amazon-bedrock-モデル推論-b実践編-amazon-bedrock-series-02b)
    - [Amazon Bedrock Agents 自律型 AI の実現に向けて: 検討編 【Amazon Bedrock Series #04a】](#amazon-bedrock-agents-自律型-ai-の実現に向けて-検討編-amazon-bedrock-series-04a)
    - [Amazon Bedrock Knowledge Bases](#amazon-bedrock-knowledge-bases)
  - [GCP](#gcp)
    - [GenOps: 生成 AI 向けに MLOps が進化](#genops-生成-ai-向けに-mlops-が進化)
    - [GenOps: マイクロサービスと従来の DevOps の世界から学ぶ](#genops-マイクロサービスと従来の-devops-の世界から学ぶ)
  - [Azure](#azure)
    - [LLMOps:ΔMLOps by MS ito shunta](#llmopsδmlops-by-ms-ito-shunta)
    - [Azure ベースライン OpenAI エンドツーエンド チャット リファレンス アーキテクチャ](#azure-ベースライン-openai-エンドツーエンド-チャット-リファレンス-アーキテクチャ)
    - [Azure OpenAI モデルのログと監視を実装する](#azure-openai-モデルのログと監視を実装する)
    - [Azure Databricks を使用して MLOps を調整する](#azure-databricks-を使用して-mlops-を調整する)
    - [マルチモーダル/AI Agent/LLMOps 3つの技術トレンドで理解するLLMの今後の展望](#マルチモーダルai-agentllmops-3つの技術トレンドで理解するllmの今後の展望)
    - [ChatGPT - LLMシステム開発大全](#chatgpt---llmシステム開発大全)
    - [AOAI Dev Day LLMシステム開発 Tips集](#aoai-dev-day-llmシステム開発-tips集)
    - [Introducing Azure AI Agent Service(2024/11/19)](#introducing-azure-ai-agent-service20241119)
    - [Azure AI Document Intelligence を使用した取得拡張生成](#azure-ai-document-intelligence-を使用した取得拡張生成)
  - [RAI/セキュリティ/攻撃と対策](#raiセキュリティ攻撃と対策)
    - [OWASP Top 10 for LLM Applications 2025](#owasp-top-10-for-llm-applications-2025)
    - [AzureのRAI・セキュリティ関連](#azureのraiセキュリティ関連)
    - [GDPR(General Data Protection Regulation, EU一般データ保護規則)](#gdprgeneral-data-protection-regulation-eu一般データ保護規則)
# 目的
- LLMOpsの勉強
# 背景
# 参考
- [プロンプトエンジニアリングによる、Amazon Bedrock でのセキュアな RAG アプリケーション](https://aws.amazon.com/jp/blogs/news/secure-rag-applications-using-prompt-engineering-on-amazon-bedrock/)
- [【AWS】BedrockのAgentを使ったら1時間弱でRAGを構築できた](https://zenn.dev/ncdc/articles/41bf6e7735ec9f)
- [RAG の精度を向上させる Advanced RAG on AWS の道標](https://aws.amazon.com/jp/blogs/news/a-practical-guide-to-improve-rag-systems-with-advanced-rag-on-aws/)
- [サクッと始めるプロンプトエンジニアリング【LangChain / ChatGPT】](https://zenn.dev/umi_mori/books/prompt-engineer)
- [Azure AI services Blog](https://techcommunity.microsoft.com/category/ai/blog/azure-ai-services-blog)
  - [Azure AI Search: Outperforming vector search with hybrid retrieval and reranking](https://techcommunity.microsoft.com/blog/azure-ai-services-blog/azure-ai-search-outperforming-vector-search-with-hybrid-retrieval-and-reranking/3929167)
  - [Prep your Data for RAG with Azure AI Search: Content Layout, Markdown Parsing & Improved Security](https://techcommunity.microsoft.com/blog/azure-ai-services-blog/prep-your-data-for-rag-with-azure-ai-search-content-layout-markdown-parsing--imp/4303538)
# 内容
## AWS
### [Amazon Bedrock Overview 【Amazon Bedrock Series #01】](https://pages.awscloud.com/rs/112-TZM-766/images/AWS-Black-Belt_2024_Amazon-Bedrock-Overview_v1.pdf)
- <p align='center'><img src='./img/README-template_2024-10-27-14-16-29.png' width='70%'></p>
- <p align='center'><img src='./img/README-template_2024-10-27-14-32-03.png' width='70%'></p>
- <p align='center'><img src='./img/README-template_2024-10-27-15-24-11.png' width='70%'></p>
- <p align='center'><img src='./img/README-template_2024-10-27-15-18-23.png' width='70%'></p>
- <p align='center'><img src='./img/README-template_2024-10-27-15-18-49.png' width='70%'></p>
- <p align='center'><img src='./img/README-template_2024-10-27-15-19-12.png' width='70%'></p>
- <p align='center'><img src='./img/README-template_2024-10-27-15-20-58.png' width='70%'></p>
- <p align='center'><img src='./img/README-template_2024-10-27-15-21-47.png' width='70%'></p>
- <p align='center'><img src='./img/README-template_2024-10-27-15-40-18.png' width='70%'></p>
- <p align='center'><img src='./img/README-template_2024-10-27-15-40-45.png' width='70%'></p>
- <p align='center'><img src='./img/README-template_2024-10-27-15-41-32.png' width='70%'></p>
- <p align='center'><img src='./img/README-template_2024-10-27-16-00-42.png' width='70%'></p>
- <p align='center'><img src='./img/README-template_2024-10-27-16-01-41.png' width='70%'></p>
- <p align='center'><img src='./img/README-template_2024-10-27-16-02-41.png' width='70%'></p>
- <p align='center'><img src='./img/README-template_2024-10-27-16-13-18.png' width='70%'></p>
- <p align='center'><img src='./img/README-template_2024-10-27-16-13-44.png' width='70%'></p>
- <p align='center'><img src='./img/README-template_2024-10-27-16-14-00.png' width='70%'></p>
- <p align='center'><img src='./img/README-template_2024-10-27-16-14-20.png' width='70%'></p>
- cross-regionについて(別資料)
  - <p align='center'><img src='./img/README-template_2024-10-27-16-17-43.png' width='70%'></p>
  - <p align='center'><img src='./img/README-template_2024-10-27-16-18-08.png' width='70%'></p>
  - <p align='center'><img src='./img/README-template_2024-10-27-16-18-37.png' width='70%'></p>
  - <p align='center'><img src='./img/README-template_2024-10-27-16-18-54.png' width='70%'></p>
- <p align='center'><img src='./img/README-template_2024-10-27-16-39-25.png' width='70%'></p>
- <p align='center'><img src='./img/README-template_2024-10-27-16-39-43.png' width='70%'></p>
### [Amazon Bedrock モデル推論 a.準備編 【Amazon Bedrock Series #02a】](https://pages.awscloud.com/rs/112-TZM-766/images/AWS-Black-Belt_2024_Amazon-Bedrock-Model-Inference-a_0909_v1.pdf)
- <p align='center'><img src='./img/README_2024-11-02-17-57-24.png' width='70%'></p>
- <p align='center'><img src='./img/README_2024-11-02-17-57-52.png' width='70%'></p>
- <p align='center'><img src='./img/README_2024-11-02-17-58-12.png' width='70%'></p>
- <p align='center'><img src='./img/README_2024-11-02-17-58-50.png' width='70%'></p>
- <p align='center'><img src='./img/README_2024-11-02-17-59-25.png' width='70%'></p>
- <p align='center'><img src='./img/README_2024-11-02-18-00-09.png' width='70%'></p>
- <p align='center'><img src='./img/README_2024-11-02-18-00-26.png' width='70%'></p>
- <p align='center'><img src='./img/README_2024-11-02-18-01-10.png' width='70%'></p>
- <p align='center'><img src='./img/README_2024-11-02-18-01-25.png' width='70%'></p>
- <p align='center'><img src='./img/README_2024-11-02-18-01-41.png' width='70%'></p>
- <p align='center'><img src='./img/README_2024-11-02-18-03-08.png' width='70%'></p>
- <p align='center'><img src='./img/README_2024-11-02-18-03-39.png' width='70%'></p>
- <p align='center'><img src='./img/README_2024-11-02-18-04-17.png' width='70%'></p>
- <p align='center'><img src='./img/README_2024-11-02-18-04-31.png' width='70%'></p>
### [Amazon Bedrock モデル推論 b.実践編 【Amazon Bedrock Series #02b】](https://pages.awscloud.com/rs/112-TZM-766/images/AWS-Black-Belt_2024_Amazon-Bedrock-Model-Inference-b_0909_v1.pdfs)
- <p align='center'><img src='./img/README_2024-11-02-18-05-25.png' width='70%'></p>
- <p align='center'><img src='./img/README_2024-11-02-18-09-52.png' width='70%'></p>
- <p align='center'><img src='./img/README_2024-11-02-18-10-18.png' width='70%'></p>
- <p align='center'><img src='./img/README_2024-11-02-18-10-54.png' width='70%'></p>
- <p align='center'><img src='./img/README_2024-11-02-18-11-29.png' width='70%'></p>
- <p align='center'><img src='./img/README_2024-11-02-18-11-52.png' width='70%'></p>
- <p align='center'><img src='./img/README_2024-11-02-18-14-15.png' width='70%'></p>
- <p align='center'><img src='./img/README_2024-11-02-18-14-29.png' width='70%'></p>
- <p align='center'><img src='./img/README_2024-11-02-18-15-12.png' width='70%'></p>
- <p align='center'><img src='./img/README_2024-11-02-18-15-43.png' width='70%'></p>
- <p align='center'><img src='./img/README_2024-11-02-18-16-11.png' width='70%'></p>
- <p align='center'><img src='./img/README_2024-11-02-18-16-59.png' width='70%'></p>
- <p align='center'><img src='./img/README_2024-11-02-18-17-13.png' width='70%'></p>
- <p align='center'><img src='./img/README_2024-11-02-18-17-57.png' width='70%'></p>
### [Amazon Bedrock Agents 自律型 AI の実現に向けて: 検討編 【Amazon Bedrock Series #04a】](https://pages.awscloud.com/rs/112-TZM-766/images/AWS-Black-Belt_2024_Amazon-Bedrock-Agents_0930_v1.pdf)
- <p align='center'><img src='./img/README_2024-11-03-14-51-47.png' width='70%'></p>
- <p align='center'><img src='./img/README_2024-11-03-14-52-11.png' width='70%'></p>
- <p align='center'><img src='./img/README_2024-11-03-14-52-29.png' width='70%'></p>
- <p align='center'><img src='./img/README_2024-11-03-14-52-44.png' width='70%'></p>
- <p align='center'><img src='./img/README_2024-11-03-14-54-21.png' width='70%'></p>
- <p align='center'><img src='./img/README_2024-11-03-15-00-23.png' width='70%'></p>
- <p align='center'><img src='./img/README_2024-11-03-15-01-34.png' width='70%'></p>
- <p align='center'><img src='./img/README_2024-11-03-15-01-51.png' width='70%'></p>
- <p align='center'><img src='./img/README_2024-11-03-15-02-12.png' width='70%'></p>
- <p align='center'><img src='./img/README_2024-11-03-15-04-41.png' width='70%'></p>
- <p align='center'><img src='./img/README_2024-11-03-15-04-53.png' width='70%'></p>
- <p align='center'><img src='./img/README_2024-11-03-15-05-08.png' width='70%'></p>
- <p align='center'><img src='./img/README_2024-11-03-15-07-14.png' width='70%'></p>
- <p align='center'><img src='./img/README_2024-11-03-15-07-27.png' width='70%'></p>
- <p align='center'><img src='./img/README_2024-11-03-15-07-45.png' width='70%'></p>
- <p align='center'><img src='./img/README_2024-11-03-15-07-59.png' width='70%'></p>
- <p align='center'><img src='./img/README_2024-11-03-15-08-16.png' width='70%'></p>
### [Amazon Bedrock Knowledge Bases](https://pages.awscloud.com/rs/112-TZM-766/images/AWS-Black-Belt_2024_Amazon-Bedrock-Knowledge-Bases_0920_v1.pdf)
- <p align='center'><img src='./img/README_2024-11-03-15-34-33.png' width='70%'></p>
- <p align='center'><img src='./img/README_2024-11-03-15-36-33.png' width='70%'></p>
- <p align='center'><img src='./img/README_2024-11-03-15-35-46.png' width='70%'></p>
- <p align='center'><img src='./img/README_2024-11-03-15-35-58.png' width='70%'></p>
- <p align='center'><img src='./img/README_2024-11-03-15-37-01.png' width='70%'></p>
- <p align='center'><img src='./img/README_2024-11-03-15-41-57.png' width='70%'></p>
- <p align='center'><img src='./img/README_2024-11-03-15-42-11.png' width='70%'></p>
- <p align='center'><img src='./img/README_2024-11-03-15-42-26.png' width='70%'></p>
- <p align='center'><img src='./img/README_2024-11-03-15-43-03.png' width='70%'></p>
- <p align='center'><img src='./img/README_2024-11-03-15-43-16.png' width='70%'></p>
- <p align='center'><img src='./img/README_2024-11-03-15-43-51.png' width='70%'></p>
- <p align='center'><img src='./img/README_2024-11-03-15-44-05.png' width='70%'></p>
- <p align='center'><img src='./img/README_2024-11-03-15-44-19.png' width='70%'></p>
- <p align='center'><img src='./img/README_2024-11-03-15-52-02.png' width='70%'></p>
- <p align='center'><img src='./img/README_2024-11-03-15-52-16.png' width='70%'></p>
- <p align='center'><img src='./img/README_2024-11-03-16-07-41.png' width='70%'></p>
- <p align='center'><img src='./img/README_2024-11-03-16-08-21.png' width='70%'></p>
- <p align='center'><img src='./img/README_2024-11-03-16-09-45.png' width='70%'></p>
- <p align='center'><img src='./img/README_2024-11-03-16-10-05.png' width='70%'></p>
- <p align='center'><img src='./img/README_2024-11-03-16-15-45.png' width='70%'></p>
- <p align='center'><img src='./img/README_2024-11-03-16-16-00.png' width='70%'></p>
- <p align='center'><img src='./img/README_2024-11-03-16-22-35.png' width='70%'></p>
- <p align='center'><img src='./img/README_2024-11-03-16-29-43.png' width='70%'></p>
- <p align='center'><img src='./img/README_2024-11-03-16-30-19.png' width='70%'></p>
- <p align='center'><img src='./img/README_2024-11-03-16-30-31.png' width='70%'></p>
- <p align='center'><img src='./img/README_2024-11-03-16-30-45.png' width='70%'></p>
- <p align='center'><img src='./img/README_2024-11-03-16-31-00.png' width='70%'></p>
- <p align='center'><img src='./img/README_2024-11-03-16-31-12.png' width='70%'></p>
- <p align='center'><img src='./img/README_2024-11-03-16-33-31.png' width='70%'></p>
- <p align='center'><img src='./img/README_2024-11-03-16-34-30.png' width='70%'></p>
- <p align='center'><img src='./img/README_2024-11-03-16-34-41.png' width='70%'></p>
- <p align='center'><img src='./img/README_2024-11-03-16-35-03.png' width='70%'></p>
- <p align='center'><img src='./img/README_2024-11-03-16-35-16.png' width='70%'></p> 
- <p align='center'><img src='./img/README_2024-11-03-16-39-57.png' width='70%'></p>
- <p align='center'><img src='./img/README_2024-11-03-16-40-10.png' width='70%'></p>
- <p align='center'><img src='./img/README_2024-11-03-16-40-40.png' width='70%'></p>
- <p align='center'><img src='./img/README_2024-11-03-16-40-54.png' width='70%'></p>
- <p align='center'><img src='./img/README_2024-11-03-16-41-15.png' width='70%'></p>
## GCP
### [GenOps: 生成 AI 向けに MLOps が進化](https://cloud.google.com/blog/ja/products/ai-machine-learning/learn-how-to-build-and-scale-generative-ai-solutions-with-genops)
- <p align='center'><img src='./img/README_2024-11-09-14-14-47.png' width='70%'></p>
- <p align='center'><img src='./img/README_2024-11-09-14-17-09.png' width='70%'></p>
- <p align='center'><img src='./img/README_2024-11-09-14-24-31.png' width='70%'></p>
- <p align='center'><img src='./img/README_2024-11-09-14-25-57.png' width='70%'></p>
### [GenOps: マイクロサービスと従来の DevOps の世界から学ぶ](https://cloud.google.com/blog/ja/products/devops-sre/genops-learnings-from-microservices-and-traditional-devops)
- <p align='center'><img src='./img/README_2024-11-09-14-56-04.png' width='70%'></p>
- <p align='center'><img src='./img/README_2024-11-09-14-56-32.png' width='70%'></p>
- <p align='center'><img src='./img/README_2024-11-09-15-02-22.png' width='70%'></p>
- <p align='center'><img src='./img/README_2024-11-09-15-05-08.png' width='70%'></p>
- <p align='center'><img src='./img/README_2024-11-09-15-05-23.png' width='70%'></p>
## Azure
### [LLMOps:ΔMLOps by MS ito shunta](https://speakerdeck.com/shuntaito/llmops-dmlops)
- <p align='center'><img src='./img/README_2024-10-27-17-04-10.png' width='70%'></p>
- <p align='center'><img src='./img/README_2024-10-27-17-11-48.png' width='70%'></p>
- <p align='center'><img src='./img/README_2024-10-27-17-12-43.png' width='70%'></p>
- <p align='center'><img src='./img/README_2024-11-02-16-48-05.png' width='70%'></p>
- <p align='center'><img src='./img/README_2024-11-02-16-48-36.png' width='70%'></p>
- <p align='center'><img src='./img/README_2024-11-02-16-49-31.png' width='70%'></p>
- <p align='center'><img src='./img/README_2024-11-02-16-52-35.png' width='70%'></p>
- <p align='center'><img src='./img/README_2024-11-02-16-52-59.png' width='70%'></p>
- <p align='center'><img src='./img/README_2024-11-02-16-55-02.png' width='70%'></p>
- <p align='center'><img src='./img/README_2024-11-02-16-56-42.png' width='70%'></p>
- <p align='center'><img src='./img/README_2024-11-02-16-59-45.png' width='70%'></p>
- <p align='center'><img src='./img/README_2024-11-02-17-01-14.png' width='70%'></p>
- <p align='center'><img src='./img/README_2024-11-02-17-02-21.png' width='70%'></p>
- <p align='center'><img src='./img/README_2024-11-02-17-02-56.png' width='70%'></p>
- <p align='center'><img src='./img/README_2024-11-02-17-04-05.png' width='70%'></p>
- <p align='center'><img src='./img/README_2024-11-02-17-05-53.png' width='70%'></p>
- <p align='center'><img src='./img/README_2024-11-02-17-13-23.png' width='70%'></p>
- <p align='center'><img src='./img/README_2024-11-02-17-14-06.png' width='70%'></p>
- <p align='center'><img src='./img/README_2024-11-02-17-15-04.png' width='70%'></p>
- <p align='center'><img src='./img/README_2024-11-02-17-22-29.png' width='70%'></p>
- <p align='center'><img src='./img/README_2024-11-02-17-22-47.png' width='70%'></p>
- <p align='center'><img src='./img/README_2024-11-02-17-23-10.png' width='70%'></p>
- <p align='center'><img src='./img/README_2024-11-02-17-24-54.png' width='70%'></p>
- <p align='center'><img src='./img/README_2024-11-02-17-29-51.png' width='70%'></p>
- <p align='center'><img src='./img/README_2024-11-02-17-30-34.png' width='70%'></p>
- <p align='center'><img src='./img/README_2024-11-02-17-31-56.png' width='70%'></p>
- <p align='center'><img src='./img/README_2024-11-02-17-32-24.png' width='70%'></p>
- <p align='center'><img src='./img/README_2024-11-02-17-33-28.png' width='70%'></p>
- <p align='center'><img src='./img/README_2024-11-02-17-34-14.png' width='70%'></p>
- <p align='center'><img src='./img/README_2024-11-02-17-36-43.png' width='70%'></p>
- <p align='center'><img src='./img/README_2024-11-02-17-38-02.png' width='70%'></p>
- <p align='center'><img src='./img/README_2024-11-02-17-47-02.png' width='70%'></p>
### [Azure ベースライン OpenAI エンドツーエンド チャット リファレンス アーキテクチャ](https://learn.microsoft.com/ja-jp/azure/architecture/ai-ml/architecture/baseline-openai-e2e-chat)
- <p align='center'><img src='./img/README_2024-11-09-15-21-22.png' width='70%'></p>
### [Azure OpenAI モデルのログと監視を実装する](https://learn.microsoft.com/ja-jp/azure/architecture/ai-ml/openai/architecture/log-monitor-azure-openai)
- <p align='center'><img src='./img/README_2024-11-09-15-23-20.png' width='70%'></p>
### [Azure Databricks を使用して MLOps を調整する](https://learn.microsoft.com/ja-jp/azure/architecture/ai-ml/idea/orchestrate-machine-learning-azure-databricks)
- <p align='center'><img src='./img/README_2024-11-09-15-23-54.png' width='70%'></p>
### [マルチモーダル/AI Agent/LLMOps 3つの技術トレンドで理解するLLMの今後の展望](https://speakerdeck.com/hirosatogamo/llmops-3tunoji-shu-torendodeli-jie-surullmnojin-hou-nozhan-wang)
- <p align='center'><img src='./img/README_2024-11-17-15-42-49.png' width='70%'></p>
- <p align='center'><img src='./img/README_2024-11-17-14-59-19.png' width='70%'></p>
- <p align='center'><img src='./img/README_2024-11-17-15-02-52.png' width='70%'></p>
- <p align='center'><img src='./img/README_2024-11-17-15-20-43.png' width='70%'></p>
- <p align='center'><img src='./img/README_2024-11-17-15-39-02.png' width='70%'></p>
- <p align='center'><img src='./img/README_2024-11-17-15-41-05.png' width='70%'></p>
- <p align='center'><img src='./img/README_2024-11-17-15-43-30.png' width='70%'></p>
- <p align='center'><img src='./img/README_2024-11-17-15-43-44.png' width='70%'></p>
- <p align='center'><img src='./img/README_2024-11-17-15-44-32.png' width='70%'></p>
- <p align='center'><img src='./img/README_2024-11-17-15-45-53.png' width='70%'></p>
- <p align='center'><img src='./img/README_2024-11-17-15-48-39.png' width='70%'></p>
- <p align='center'><img src='./img/README_2024-11-17-15-48-56.png' width='70%'></p>
- <p align='center'><img src='./img/README_2024-11-17-15-51-36.png' width='70%'></p>
- <p align='center'><img src='./img/README_2024-11-17-15-52-20.png' width='70%'></p>
- <p align='center'><img src='./img/README_2024-11-17-15-52-44.png' width='70%'></p>
- <p align='center'><img src='./img/README_2024-11-17-15-55-21.png' width='70%'></p>
- <p align='center'><img src='./img/README_2024-11-17-15-55-54.png' width='70%'></p>
- <p align='center'><img src='./img/README_2024-11-17-15-56-56.png' width='70%'></p>
- <p align='center'><img src='./img/README_2024-11-17-15-57-51.png' width='70%'></p>
- <p align='center'><img src='./img/README_2024-11-17-16-01-14.png' width='70%'></p>
- [※Sentiment分析とは](https://aws.amazon.com/jp/what-is/sentiment-analysis/)
- <p align='center'><img src='./img/README_2024-11-17-16-20-11.png' width='70%'></p>
- <p align='center'><img src='./img/README_2024-11-17-16-21-29.png' width='70%'></p>
- <p align='center'><img src='./img/README_2024-11-17-16-21-42.png' width='70%'></p>
### [ChatGPT - LLMシステム開発大全](https://speakerdeck.com/hirosatogamo/chatgpt-azure-openai-da-quan)
- <u>**※絞ってキャプチャしているが全部必読レベルのものなのでリンク先をみるべき**<u/>
- <p align='center'><img src='./img/README_2024-11-17-16-24-59.png' width='70%'></p>
- <p align='center'><img src='./img/README_2024-11-17-16-25-25.png' width='70%'></p>
- <p align='center'><img src='./img/README_2024-11-17-17-19-15.png' width='70%'></p>
- <p align='center'><img src='./img/README_2024-11-17-17-20-17.png' width='70%'></p>
- <p align='center'><img src='./img/README_2024-11-17-17-21-13.png' width='70%'></p>
- <p align='center'><img src='./img/README_2024-11-17-17-23-01.png' width='70%'></p>
- <p align='center'><img src='./img/README_2024-11-17-17-23-35.png' width='70%'></p>
- <p align='center'><img src='./img/README_2024-11-17-17-24-18.png' width='70%'></p>
- <p align='center'><img src='./img/README_2024-11-17-17-25-56.png' width='70%'></p>
- <p align='center'><img src='./img/README_2024-11-17-17-26-43.png' width='70%'></p>
- <p align='center'><img src='./img/README_2024-11-17-17-27-39.png' width='70%'></p>
- <p align='center'><img src='./img/README_2024-11-17-17-28-21.png' width='70%'></p>
- <p align='center'><img src='./img/README_2024-11-17-17-28-58.png' width='70%'></p>
- <p align='center'><img src='./img/README_2024-11-17-17-29-23.png' width='70%'></p>
- <p align='center'><img src='./img/README_2024-11-17-17-34-03.png' width='70%'></p>
- <p align='center'><img src='./img/README_2024-11-17-17-39-37.png' width='70%'></p>
- <p align='center'><img src='./img/README_2024-11-17-17-40-29.png' width='70%'></p>
- <p align='center'><img src='./img/README_2024-11-17-17-41-17.png' width='70%'></p>
- <p align='center'><img src='./img/README_2024-11-17-17-41-52.png' width='70%'></p>
- <p align='center'><img src='./img/README_2024-11-17-17-42-54.png' width='70%'></p>
- <p align='center'><img src='./img/README_2024-11-17-17-45-39.png' width='70%'></p>
- <p align='center'><img src='./img/README_2024-11-17-17-46-17.png' width='70%'></p>
- <p align='center'><img src='./img/README_2024-11-17-17-46-32.png' width='70%'></p>
- <p align='center'><img src='./img/README_2024-11-17-17-47-07.png' width='70%'></p>
- [Azure OpenAI Service の クォータ管理詳細](https://zenn.dev/microsoft/articles/be24a299f46a4d)
- <p align='center'><img src='./img/README_2024-11-17-17-49-43.png' width='70%'></p>
- <p align='center'><img src='./img/README_2024-11-17-17-50-49.png' width='70%'></p>
- <p align='center'><img src='./img/README_2024-11-17-17-51-16.png' width='70%'></p>
### [AOAI Dev Day LLMシステム開発 Tips集](https://speakerdeck.com/hirosatogamo/aoai-dev-day-llmsisutemukai-fa-tipsji)
### [Introducing Azure AI Agent Service(2024/11/19)](https://techcommunity.microsoft.com/blog/azure-ai-services-blog/introducing-azure-ai-agent-service/4298357)
- 来月(2024/12)プレビュー
- 参考：[【Ignite 2024 速報】新たな AI エージェント開発機能 「Azure AI Agent Service」 を発表し、Azure AI Foundry に統合 など](https://qiita.com/nohanaga/items/d3cc240758e41ee3ec3f)
- <p align='center'><img src='./img/README_2024-11-24-13-31-02.png' width='70%'></p>
- <p align='center'><img src='./img/README_2024-11-24-13-31-23.png' width='70%'></p>
### [Azure AI Document Intelligence を使用した取得拡張生成](https://learn.microsoft.com/ja-jp/azure/ai-services/document-intelligence/concept/retrieval-augmented-generation?view=doc-intel-3.1.0)
- pdfのテキスト化改善。マークダウン形式にして取り込む。表の情報もうまく取り込める。
- <p align='center'><img src='./img/README_2024-11-24-14-06-22.png' width='70%'></p>
- <p align='center'><img src='./img/README_2024-11-24-14-07-03.png' width='70%'></p>
- <p align='center'><img src='./img/README_2024-11-24-14-10-03.png' width='70%'></p>
- あとはOCR(Optical Character Recognition)と組み合わせる方法もある。
- <p align='center'><img src='./img/README_2024-11-24-14-11-01.png' width='70%'></p>

## RAI/セキュリティ/攻撃と対策
### [OWASP Top 10 for LLM Applications 2025](https://genai.owasp.org/resource/owasp-top-10-for-llm-applications-2025/)

| # | リスク | 概要 | 誰が気をつける | 備考 |
|----------- | --------------------------- | ---------------------------------------------- | ------------ | --- |
| LLM01:2025 | Prompt Injection | プロンプトを用いてLLMの動作や出力に悪影響を与える脆弱性 | developer |  |
| LLM02:2025 | Sensitive Information Disclosure | モデルが機密情報を出力する脆弱性 | platformer | 入力情報が学習 に利用されないことを確認すればOK |
| LLM03:2025 | Supply Chain | モデルのサプライチェーンを利用した脆弱性 | platformer |  |
| LLM04:2025 | Data and Model Poisoning | 学習データが汚染されることで生じる脆弱性 | platformer |  |
| LLM05:2025 | Improper Output Handling | LLMの出力が他のシステムに入力される際に検証/サニタイズされないことによる脆弱性 | developer |  |
| LLM06:2025 | Excessive Agency | エージェントの機能、権限が過剰なことで生じる脆弱性 | developer |  |
| LLM07:2025 | System Prompt Leakage | プロンプトに含まれる機密情報が漏洩する脆弱性 | developer |  |
| LLM08:2025 | Vector and Embedding Weaknesses | RAG構築時の脆弱性全般 | developer |  |
| LLM09:2025 | Misinformation | ハルシネーション、またはユーザがLLMの出力を過信すること | developer, user |  |
| LLM10:2025 | Unbounded Consumption | LLMのトークンを消費させる脆弱性 | developer |  |

- 日本語の参考
  - [『OWASP Top 10 for LLM Applications 2025』を読む](https://zenn.dev/kimitsu/scraps/ef20f73946f521)
  - [OWASP Top 10 for LLMでLLM Applicationsのセキュリティについて学ぶ](https://zenn.dev/loglass/articles/41b1b4e809aac9)

### AzureのRAI・セキュリティ関連
- <p align='center'><img src='./img/README_2024-11-24-15-24-42.png' width='70%'></p>

### GDPR(General Data Protection Regulation, EU一般データ保護規則)
- <p align='center'><img src='./img/README_2024-11-24-15-25-28.png' width='70%'></p>