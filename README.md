# e-commerce

※ 現在開発中ですので、インストールしても動作しません。

e-commerce は、モダンなウェブ技術を使用して構築されたオンラインショッピングプラットフォームです。使いやすいインターフェースと柔軟なカスタマイズ機能により、多様な商品の販売と管理を簡単に行うことができます。

## インストール

このプロジェクトをローカルで実行するには、次の手順に従ってください：

```bash
git clone https://github.com/commte/commerce.git
cd commerce
npm install
```

### エラーが出る場合

`.env.example` ファイルには、アプリケーションが動作するために必要な環境変数の例が記載されています。
このファイルをコピーして `.env` という名前で保存し、必要な情報を記入します。

`.env` ファイルにはセキュリティ上重要な情報が含まれる可能性があるため、Gitリポジトリにはコミットしないでください。
Vercel CLIを使用するのは、Vercelにデプロイする場合のみです。ローカルでのみ動作させる場合は、Vercel CLIやvercel link、vercel env pull は必要ありません。

エラーメッセージ "https://[your-shopify-store-subdomain].myshopify.com/api/2023-01/graphql.json" にある [your-shopify-store-subdomain] は、実際のShopifyストアのサブドメインに置き換える必要があるプレースホルダーです。`.env` ファイル内の対応する環境変数が正しく設定されていない可能性があります。

`.env` ファイルを開いて、Shopifyストアのサブドメインに関する環境変数（例えば、SHOPIFY_STORE_SUBDOMAIN）が正しい値に設定されているか確認してください。その値はあなたの実際のShopifyストアのサブドメインにする必要があります。

[Vercel and Shopify Integration](https://vercel.com/docs/integrations/shopify)

### 使用方法

アプリケーションを起動するには、以下のコマンドを実行します：

```bash
npm install -g pnpm
pnpm install
pnpm dev
```

### 機能

- 製品の表示と管理
- カート機能とオンライン決済
- ユーザーアカウント管理
- レスポンシブデザイン

### コントリビューション

プロジェクトへの貢献に興味がある方は、以下の手順に従ってください：

- プロジェクトをフォークし、変更を加えます。
- プルリクエストを作成します。
- あなたの変更がレビューされた後、必要に応じて修正します。
- 変更が承認されたら、メインプロジェクトにマージされます。

### ライセンス

このプロジェクトは MIT ライセンスの下で公開されています。

### 著者

- [@commte](https://github.com/commte)
