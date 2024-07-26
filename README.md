# プロジェクトの詳細

#### ＜共通＞
- MS1ページ：[テーマ1の説明](https://app.ms1.com/academy/1BYJipoSWFWcxfxUIoruQ6/4NBJkylZbtUd6Wxtpw4nbE/5VDANh8J5d2NltgkZUPyTk/2f4kqS0Gcl75ANeD8HK9bv/1XS6qWijKAPuZWKx9kY0K8) ， [修了プロジェクトのガイドライン](https://app.ms1.com/academy/1BYJipoSWFWcxfxUIoruQ6/4NBJkylZbtUd6Wxtpw4nbE/5VDANh8J5d2NltgkZUPyTk/5pbSGNRYpiaKlCctj9PaET/jBpJOZ9FVVT7qyahWPMEk)
- [7/22(月)のキックオフスライド](https://toyotaglobal.enterprise.slack.com/files/U04M3KX6CP2/F07DGHBRMDJ/____________________________________________________________.pdf)

#### ＜グループ1内の計画＞
- **[★修了プロジェクト計画（7/29提出）](./doc/修了プロジェクト計画.md)**
-  [MS1上の元々のテーマ1との要件比較](./doc/MS1上の元々のテーマ1との要件比較.md)

# 開発情報

#### ＜作業用インフラ＞
- **JIRA**：[チームのJIRAボード](https://rhdojo.atlassian.net/jira/software/projects/PCPG/boards/2)
- **GitHub Wiki**：[議事録ページ](https://github.com/rhashimoto777/python-capstone-project/wiki/%E8%AD%B0%E4%BA%8B%E9%8C%B2) ， [TIPS(ノウハウ共有)](https://github.com/rhashimoto777/python-capstone-project/wiki/TIPS%EF%BC%88%E3%83%8E%E3%82%A6%E3%83%8F%E3%82%A6%E5%85%B1%E6%9C%89%EF%BC%89)

#### ＜各種ポリシー＞
- **文書管理**
    - 設計情報は[「designフォルダ」](./design/)内に配置する．
    - ユーザーストーリーは[「designフォルダ」](./design/)内の[「ユーザーストーリー.md」](./design/ユーザーストーリー.md)に記載する．
    - その他の雑多情報（計画やプレゼンテーションなど）は[「docフォルダ」](./doc/)内に配置する．

- **GitHub Repository管理**
    - mainへの直接pushを禁止する設定にしている．mainに変更を加えるには別branchを作ってPullRequestを発行する．
    - PullRequestのマージには1人以上のレビュワー承認を必要とする．
        - デフォルトレビュワーとして下記メンバが自動追加されるが，その他メンバの承認でもマージ可能な設定にしている．
            ```
            ・全てのファイル変更：橋本
            ・ユーザーストーリー.mdの変更：尾崎
            ```

- **進捗・残件管理**
    - 水曜・金曜のスタンドアップミーティングで状況を確認する．
        - [参考：MS1上のスタンドアップミーティングのガイドライン](https://app.ms1.com/academy/1BYJipoSWFWcxfxUIoruQ6/4NBJkylZbtUd6Wxtpw4nbE/5VDANh8J5d2NltgkZUPyTk/5pbSGNRYpiaKlCctj9PaET/jBpJOZ9FVVT7qyahWPMEk)
    - スタンドアップミーティング以外でも，可能な限り「着手状況」「困りごと」などをslackで共有し，状況の透明化を目指す．
        - [参考：プロジェクトの潜在的な課題とリスク](https://github.com/rhashimoto777/python-capstone-project/blob/main/doc/%E4%BF%AE%E4%BA%86%E3%83%97%E3%83%AD%E3%82%B8%E3%82%A7%E3%82%AF%E3%83%88%E8%A8%88%E7%94%BB.md#%E8%AA%B2%E9%A1%8C%E3%81%A8%E3%83%AA%E3%82%B9%E3%82%AF)