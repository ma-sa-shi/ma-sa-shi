## 作ったもの

### 社内RAGチャットアプリ（Lambda版）— [serverless-rag-chat](https://github.com/ma-sa-shi/serverless-rag-chat)

ECS版をサーバーレス構成に移し替え、固定費を大幅に抑えました（[損益分岐点の比較](https://github.com/ma-sa-shi/serverless-rag-chat/blob/main/docs/cost-comparison.md)）

**技術:** Lambda / S3 Vectors / DynamoDB / Bedrock / LangGraph / CDK 

https://github.com/user-attachments/assets/281f1c77-528e-4e81-9cb9-13ff9673abb9

<details>
<summary>アーキテクチャ図</summary>

![アプリ設計図](https://raw.githubusercontent.com/ma-sa-shi/serverless-rag-chat/main/docs/diagrams/%E3%82%A2%E3%83%97%E3%83%AA%E8%A8%AD%E8%A8%88%E5%9B%B3.svg)

![RAGパイプライン](https://raw.githubusercontent.com/ma-sa-shi/serverless-rag-chat/main/docs/diagrams/RAG%E3%83%91%E3%82%A4%E3%83%97%E3%83%A9%E3%82%A4%E3%83%B3.svg)

</details>

### 社内RAGチャットアプリ（ECS版）— [fargate-rag-chat](https://github.com/ma-sa-shi/fargate-rag-chat)

ECS Fargate構成で、社内のナレッジを共有するRAGチャットアプリを作りました。

**技術:** ECS Fargate / RDS MySQL / Chroma / Next.js / FastAPI など

https://github.com/user-attachments/assets/5617046a-c229-4914-a120-0a7c6836cfe1

<details>
<summary>アーキテクチャ図</summary>

![アプリ設計図](https://raw.githubusercontent.com/ma-sa-shi/fargate-rag-chat/main/docs/diagrams/%E3%82%A2%E3%83%97%E3%83%AA%E8%A8%AD%E8%A8%88.svg)

</details>
