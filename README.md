<p><a href=" markdown-app.surge.sh" target="_blank">デプロイ先</a></p>

<p>📝ビルドコマンド：gatsby build</p>

<p>📝surgeへのデプロイコマンド：surge public/</p>

<h2>クエリについて</h2>
<h3>ページクエリ</h3>
<p>/src/pages/以下で使用可能。</p>
<p>import { graphql } from "gatsby"</p>

<h3>StaticQuery</h3>
<p>ページ以外のコンポーネントで使用可能。</p>
<p>import { useStaticQuery } from "gatsby"</p>

<h2>GraphQL Explorer</h2>
<p>開発サーバー実行時に、「<a href="http://localhost:8000/___graphql">http://localhost:8000/___graphql</a>」へアクセスする。</p>
