# test_milestone_as_deadline
GitHub Issues は締切が設定できないからタスク管理には向かないが Milestone 使えば実現できるかもとひらめいた

アイデア: **タイトルと締切日が YYYY-MM-DD のマイルストーンを各日分作る＆締切日としてマイルストーンを付与する**

## 使い心地
[1年分365件のマイルストーンを登録してみた](https://github.com/stakiran/test_milestone_as_deadline/milestones)。

- :o: YYYY-MM-DD のマイルストーンを見れば当該日締切のタスクが全部見える
- :x: 最初にマイルストーン作るのがだるい（API使った）
- Issue ページでマイルストーンを設定するとき
  - :x: Issue 上で締切を設定する時、マイルストーンを選ぶが、絶対日付でしか選べない（一週間後など相対で選べない）
  - :x: マイルストーン選択時のフィルタが「17 11」で2017-11にヒットしない（いちいち「-」も打たないといけない）
- [Milestone 一覧](https://github.com/stakiran/test_milestone_as_deadline/milestones)
  - :x: 365件のマイルストーン全部表示されるので重い...
  - :o: 締切近い順などでソートできる
  - :x: マイルストーン CRUD 時など再描画走るが（365件全部表示されてると）再読み込みが重い...
  - :x: ~~デフォのソート順が Recently Updated なのが使いづらい（Closest due dateにしてほしい）~~ [専用URLから見ればおっけー](https://github.com/stakiran/test_milestone_as_deadline/milestones?direction=asc&sort=due_date&state=open) `?direction=asc&sort=due_date`

## 結論
GitHub Issue で締切付きタスク管理、いけるかも？ｗｗ

## 発展トピック
- マイルストーン名に曜日も含めてあげると見やすい
