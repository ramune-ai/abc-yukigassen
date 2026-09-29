ABC雪合戦 サウンド素材フォルダ

sound/bgm/ … BGM（ループ曲）       推奨：mp3（128〜192kbps）
sound/se/  … 効果音・ジングル        推奨：mp3（短い音なので容量は小さい）

■ 使っているファイル（名前をこの通りにして置けば自動で使われる）
  sound/bgm/ABC Snow Battle.mp3   … タイトル
  sound/bgm/Snow Battle Loop.mp3  … 対戦中
  sound/bgm/result.mp3            … リザルト画面（まだ無い。無い間はタイトル曲が流れる）
  sound/se/win.mp3                … 勝った時のジングル（まだ無い。無い間はコードの仮の音）
  sound/se/lose.mp3               … 負けた時のジングル（まだ無い。無い間はコードの仮の音）

ファイル名や割り当てを変えたい時は、test.html の BGM_FILES / SE_FILES を直す。
ジングルは2〜4秒くらいがおすすめ（鳴り終わる頃にリザルト画面とリザルト曲が出る：約2.6秒後）。

公開時は index.html / test.html と一緒に、この sound フォルダごとGitHubへ上げる（Claudeがpushする）。
