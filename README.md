# 雨量観測網の高密度化と面的雨量推定

気象レーダーと地上雨量計を用いて、雨量計の密度・配置が面的雨量推定の精度に与える影響を定量化する。最終段階では、VSAT設置地点を観測点として利用できると仮定し、地域別の改善幅を推定する。

- [研究計画](docs/research_plan.md)
- [STEP 0のタスク・成果物・保存先](docs/step0_tasks.md)
- [進捗と判断記録](docs/progress.md)

| ディレクトリ | 用途 |
| --- | --- |
| `docs/` | 研究計画、技術仕様、データ調達調査、先行研究 |
| `data/raw/`、`data/processed/` | 原データと処理済みデータのローカル格納 |
| `data/metadata/` | 公開可能なデータ辞書・出典情報 |
| `src/`、`tests/` | Python実装と検証コード |
| `notebooks/`、`experiments/` | 探索的分析と実験設定 |
| `outputs/step0/` | STEP 0の公開可能な調査結果表・図 |
| `outputs/step1/`〜`outputs/step3/` | 各段階の評価・実験結果。実施時に作成する |
