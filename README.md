# next-with-type

## 構築方法

1. `docker-compose build`
2. `docker-compose run --rm app yarn install`
3. `docker-compose up`
4. http://localhost:3000/ にアクセス
5. Welcome to Next.js! と出れば構築完了

## 使用技術

#### 言語・フレームワーク

- Next.js
- TypeScript
- Tailwind CSS(CSS フレームワーク)

#### テスト

- Jest (Unit テスト)

#### 仮想環境

- Docker

#### CI/CD

- GitHub Actions

#### クラウドプラットフォーム

- Vercel

## 参考文献

Next.js

[✨Next.js入門✨ 思考停止・爆速開発テンプレ 【TypeScript+ESLint+Prettier】](https://zenn.dev/66ed3gs/articles/99aa613a86f21f)  
[ぼくのかんがえたNext.jsの構成](https://zenn.dev/nus3/articles/257d724e24a39b756b5a)

GitHub Actions

[GitHub Actions 入門](https://docs.github.com/ja/actions/learn-github-actions/introduction-to-github-actions)  
[Node.js のビルドとテスト](https://docs.github.com/ja/actions/guides/building-and-testing-nodejs)  
[Vercel の定期デプロイを GitHub Actions で実現する nikaeraさんによる記事 zenn.dev](https://zenn.dev/nikaera/articles/vercel-github-actions)  
[Vercel CLI 使ってみる](https://neos21.net/blog/2020/11/23-03.html)


