# test_milestone_as_deadline
GitHub Issues は締切が設定できないからタスク管理には向かないが Milestone 使えば実現できるかもとひらめいた

アイデア: **タイトルと締切日が YYYY-MM-DD のマイルストーンを各日分作る＆締切日としてマイルストーンを付与する**

## 使い心地
- :o: YYYY-MM-DD のマイルストーンを見れば当該日締切のタスクが全部見える
- :x: 最初にマイルストーン作るのがだるい（API使った）
- :x: Issue 上で締切を設定する時、マイルストーンを選ぶが、絶対日付でしか選べない（一週間後など相対で選べない）
- :x: [Milestone 一覧](https://github.com/stakiran/test_milestone_as_deadline/milestones) には365件のマイルストーン全部表示されるので重い...
- :x: マイルストーン選択時のフィルタが「17 11」で2017-11にヒットしない（いちいち「-」も打たないといけない）

## 結論
GitHub Issue で締切付きタスク管理、いけるかも？ｗｗ
