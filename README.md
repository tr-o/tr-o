# Projects / Visual Catalog

研究・開発プロジェクトを、成果図とともに紹介します。

**公開版 · 2026-11-27** / 更新日時は GitHub API `updated_at`（JSTの日付）。指定された基準日時より新しい公開プロジェクトのみ掲載。非公開リポジトリの名称・成果図・研究内容はこの公開ページに含めません。

| Project | Updated (JST) | Focus |
|---|---|---|
| [dlvo](#dlvo) | 2026-11-15 | コロイド粒子間のファンデルワールス引力・電気二重層反発を計算 |
| [tem-nanoparticle-analyzer](#tem-nanoparticle-analyzer) | 2026-10-30 | TEM・HRTEMの粒径計測、粒子分離、スケール校正、監査と教師ありモデルの検証 |
| [alexa-shopping-memo-skill-example](#alexa-shopping-memo-skill-example) | 2026-10-27 | 音声で入力した買い物項目をASK SDKからLINE Notifyへ渡すPython学習例 |

## dlvo

コロイド粒子間のファンデルワールス引力・電気二重層反発を計算。非線形PB、球曲率、電荷調節、吸着層の条件探索。

[Repository ↗](https://github.com/tr-o/dlvo) · Updated: 2026-11-15 JST

<table><tr>
<td width="33%" align="center"><a href="https://github.com/tr-o/dlvo/blob/d6f2a4075ebfa0f9f7093a3de4d4ca7abd667a25/examples/dlvo.png"><img src="https://raw.githubusercontent.com/tr-o/dlvo/d6f2a4075ebfa0f9f7093a3de4d4ca7abd667a25/examples/dlvo.png" width="230" alt="DLVO相互作用"></a><br>DLVO相互作用</td>
<td width="33%" align="center"><a href="https://github.com/tr-o/dlvo/blob/d6f2a4075ebfa0f9f7093a3de4d4ca7abd667a25/studies/batio3_10nm/potential_field.png"><img src="https://raw.githubusercontent.com/tr-o/dlvo/d6f2a4075ebfa0f9f7093a3de4d4ca7abd667a25/studies/batio3_10nm/potential_field.png" width="230" alt="10 nm粒子の電位分布"></a><br>10 nm粒子の電位分布</td>
<td width="33%" align="center"><a href="https://github.com/tr-o/dlvo/blob/d6f2a4075ebfa0f9f7093a3de4d4ca7abd667a25/studies/batio3_extended/required_corona_penalty.png"><img src="https://raw.githubusercontent.com/tr-o/dlvo/d6f2a4075ebfa0f9f7093a3de4d4ca7abd667a25/studies/batio3_extended/required_corona_penalty.png" width="230" alt="安定化に必要な吸着層反発"></a><br>安定化に必要な吸着層反発</td>
</tr></table>

図：元リポジトリの保存済み成果（コミット固定リンク）。

## tem-nanoparticle-analyzer

TEM・HRTEMの粒径計測、粒子分離、スケール校正、監査と教師ありモデルの検証。研究プロトタイプ。

[Repository ↗](https://github.com/tr-o/tem-nanoparticle-analyzer) · Updated: 2026-10-30 JST

<table><tr>
<td width="33%" align="center"><a href="https://github.com/tr-o/tem-nanoparticle-analyzer/blob/649c6165b3c8f821586b0e14c8b0285b46720221/experiments/v4/docs/v4_all_six_audit.jpg"><img src="https://raw.githubusercontent.com/tr-o/tem-nanoparticle-analyzer/649c6165b3c8f821586b0e14c8b0285b46720221/experiments/v4/docs/v4_all_six_audit.jpg" width="230" alt="Pt/Ag 6視野の検出監査"></a><br>Pt/Ag 6視野の検出監査</td>
<td width="33%" align="center"><a href="https://github.com/tr-o/tem-nanoparticle-analyzer/blob/649c6165b3c8f821586b0e14c8b0285b46720221/experiments/v8/results_hrtem/NP-TEM-Image1/overview.jpg"><img src="https://raw.githubusercontent.com/tr-o/tem-nanoparticle-analyzer/649c6165b3c8f821586b0e14c8b0285b46720221/experiments/v8/results_hrtem/NP-TEM-Image1/overview.jpg" width="230" alt="DM3/HRTEM解析と粒径分布"></a><br>DM3/HRTEM解析と粒径分布</td>
<td width="33%" align="center"><a href="https://github.com/tr-o/tem-nanoparticle-analyzer/blob/649c6165b3c8f821586b0e14c8b0285b46720221/experiments/v15/results/bootstrap_ci.jpg"><img src="https://raw.githubusercontent.com/tr-o/tem-nanoparticle-analyzer/649c6165b3c8f821586b0e14c8b0285b46720221/experiments/v15/results/bootstrap_ci.jpg" width="230" alt="学習データ増量とF1の不確実性"></a><br>学習データ増量とF1の不確実性</td>
</tr></table>

図：元リポジトリの保存済み成果（コミット固定リンク）。

## alexa-shopping-memo-skill-example

音声で入力した買い物項目をASK SDKからLINE Notifyへ渡すPython学習例。既存READMEに基づく概念図であり、現行サービスの動作を保証しない（LINE Notifyは終了済み）。

[Repository ↗](https://github.com/tr-o/alexa-shopping-memo-skill-example) · Updated: 2026-10-27 JST

<table><tr>
<td width="33%" align="center"><a href="assets/catalog/alexa-flow.svg"><img src="assets/catalog/alexa-flow.svg" width="230" alt="音声入力から通知まで"></a><br>音声入力から通知まで</td>
<td width="33%" align="center"><a href="assets/catalog/alexa-intents.svg"><img src="assets/catalog/alexa-intents.svg" width="230" alt="スキルの分岐"></a><br>スキルの分岐</td>
<td width="33%" align="center"><a href="assets/catalog/alexa-architecture.svg"><img src="assets/catalog/alexa-architecture.svg" width="230" alt="システム構成"></a><br>システム構成</td>
</tr></table>

図：カタログ用に新規作成した概念図（実測・実行結果ではありません）。

