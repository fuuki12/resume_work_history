# 履歴書と職務経歴書をバージョン管理 PDF に自動変換

このプロジェクトは、テキストのリント（lint）と PDF のリリースを行う GitHub Actions と、GitHub Pages で動作するドキュメンテーションサイトを含んでいます。

[履歴書](https://fuuki12.github.io/resume_work_history/resume.html)
[職務経歴書](https://fuuki12.github.io/resume_work_history/workHistory.html)

#### lint.yml

lint.yml はコードの品質を保つためのワークフローです。push イベント発生時に、すべてのテキストファイルに対して lint（静的解析）を実行します。

#### release-pdf.yml

release-pdf.yml は、pull request が main ブランチについて、または docs/\*.md ファイルが変更された時に PDF データのリリースドラフトを作成します。
