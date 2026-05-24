# マージコンフリクトを解決する

_コンフリクトがなぜ起きるのか、どのように解決するのかを学びます。_

## ようこそ

マージコンフリクトは、GitHub 上で同じファイルの同じ箇所に複数の変更が加わったときに発生します。共同作業ではよくあることです。差分の解決には相談が必要な場合もありますが、マージコンフリクトは怖いものではありません。

- **対象者**: 新しい開発者、Git と GitHub を学び始めた人
- **学ぶこと**: マージコンフリクトを確認し、解決するためのツール
- **作るもの**: Web エディタを使って、Markdown ファイル内の競合した変更を修正します
- **前提条件**:
  - Skills Exercise: [GitHub 入門](https://github.com/skills/introduction-to-github)
- **所要時間**: 30 分以内

この演習では、次のことを行います。

1. マージコンフリクトが起きる原因を学ぶ。
2. マージコンフリクトを解決するためのツールを知る。
3. いつ、どのようにマージコンフリクトを解決するかを学ぶ。

### 演習を始める

次のボタンから演習を自分のアカウントへコピーしてください。コピー後、Mona が最初のレッスンを準備するまで **20 秒ほど** 待ってから、ページを再読み込みします。

[![](https://img.shields.io/badge/%E6%BC%94%E7%BF%92%E3%82%92%E3%82%B3%E3%83%94%E3%83%BC-%E2%86%92-1f883d?style=for-the-badge&logo=github&labelColor=197935)](https://github.com/new?template_owner=tsato-cnlab&template_name=resolve-merge-conflicts&owner=%40me&name=skills-resolve-merge-conflicts&description=%E6%BC%94%E7%BF%92:+%E3%83%9E%E3%83%BC%E3%82%B8%E3%82%B3%E3%83%B3%E3%83%95%E3%83%AA%E3%82%AF%E3%83%88%E3%82%92%E8%A7%A3%E6%B1%BA%E3%81%99%E3%82%8B&visibility=public)

<details>
<summary>うまくいかない場合</summary><br/>

演習をコピーするときは、次の設定をおすすめします。

- Owner には、自分の個人アカウントまたはリポジトリを置く Organization を選びます。

- Public リポジトリとして作成することをおすすめします。Private リポジトリでは Actions の利用時間を消費します。

20 秒ほど待っても演習が準備されない場合は、[Actions](../../actions) タブを確認してください。

- ジョブが実行中か確認します。少し時間がかかっているだけの場合があります。

- ジョブが失敗している場合は Issue で報告してください。バグを見つけてくれてありがとうございます。

</details>

---

&copy; 2025 GitHub &bull; [Code of Conduct](https://www.contributor-covenant.org/version/2/1/code_of_conduct/code_of_conduct.md) &bull; [MIT License](https://gh.io/mit)
