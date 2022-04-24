# ScoreSaberRankedExcludedMaps
[CSV](RankedExcludedMaps.csv) data of maps excluded from ScoreSaber’s ranked maps.  
[ScoreSaber](https://scoresaber.com/leaderboards)のランク譜面から除外されたマップのCSVデータです。  

Gameplay of [ScoreSaber Ranking Criteria](https://docs.google.com/document/d/1_EBmvCTHyJ5-0ox5IZgmnItVqAjaBWltWslxqSc5_-4/edit#heading=h.11dlgmbqgxsa) (see below), only "Standard" Mode is assumed.
[ScoreSaber Ranking Criteria](https://docs.google.com/document/d/1_EBmvCTHyJ5-0ox5IZgmnItVqAjaBWltWslxqSc5_-4/edit#heading=h.11dlgmbqgxsa)のRules 1.Gameplay の記述(以下)に基づき"Standard" Modeのみを想定しています。
> Maps must be 'Standard' game mode maps.

This repository and CSV are provisional with manual maintenance.  
このリポジトリとCSVは手動メンテナンスで暫定的です。

It is created for use in the MyBeatSaberAnalytics.  
[MyBeatSaberAnalytics](https://github.com/hatopopvr/MyBeatSaberAnalytics)で使用するために作成しています。

It may be deleted if it is no longer needed.  
不要になれば削除する可能性があります。  

__CSV Item Description__  

| item | description | Example |
| :--- | :--- | :--- |
| Hash | [key] hash of the map | B77A35FEC3F53AD11E154B67DDD9CD933D37057A | 
| Difficulty | [key] difficulty of the map (Easy to ExpertPlus) | Easy |
| RankedExcluded | [Not Null] the map was excluded from ranked map or not (bool)	| TRUE |
| SongName | song name | DANGEROOOOUS JUNGLE |
| SongSub | song sub name | NaN |
| SongAuthor | song author name | Laur | 
| LevelAuthor | map author name | Jabob | 
| Uploader | uploader name | jabob |
| ExcludedUpdateDateJa | Datetime when updated in RankedExcludedMaps.csv | 2022-04-24 02:00:00+09:00 | 
| RankDateJa | Datetime when the map was ranked | 2022-04-16 03:29:00+09:00 | 
| CreatedDateJa | Datetime when the map was created | 2022-01-08 00:59:28.886757+09:00 |

__CSV項目名の説明__  

| 項目名 | 説明 | 例 |
| :--- | :--- | :--- |
| Hash | [key] 譜面のハッシュ | B77A35FEC3F53AD11E154B67DDD9CD933D37057A | 
| Difficulty | [key] 譜面の難易度(EasyからExpertPlus) | Easy |
| RankedExcluded | [Not Null] 譜面がRank譜面から除外されたか (bool値)	| TRUE |
| SongName | 曲名 | DANGEROOOOUS JUNGLE |
| SongSub | 曲のサブタイトル | NaN |
| SongAuthor | 曲の作者 | Laur | 
| LevelAuthor | 譜面の作者 | Jabob | 
| Uploader | 譜面のアップロード者 | jabob |
| ExcludedUpdateDateJa | RankedExcludedMaps.csv で更新した日時 | 2022-04-24 02:00:00+09:00 | 
| RankDateJa | Rank化された日時 | 2022-04-16 03:29:00+09:00 | 
| CreatedDateJa | 譜面が作られた日時 | 2022-01-08 00:59:28.886757+09:00 |
