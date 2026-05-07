# 🔗 参考リソース

## 公式・試験情報

- [LPI Japan 公式 - LPIC-1 試験概要](https://www.lpi.org/ja/our-certifications/lpic-1-overview/)
- [LPI LPIC-1 試験目標（101-500 / 102-500）](https://www.lpi.org/ja/our-certifications/exam-101-objectives/)

## 教材

| 教材 | 用途 |
|------|------|
| LPICレベル1 Linux教科書（あずき本）| メインテキスト |
| [ping-t](https://ping-t.com/) | 問題演習・弱点分析 |

## Ubuntu 実機環境

```bash
# OrbStack で Ubuntu 起動
orb start ubuntu

# Ubuntu に入る
orb shell ubuntu

# または ssh で
ssh ubuntu@orb
```

## よく使う確認コマンド（学習中に手を動かす用）

```bash
# カーネル・OS確認
uname -a
cat /etc/os-release

# プロセス確認
ps aux
top

# ディスク・ファイルシステム
df -h
mount | column -t
```

## 関連ノート

- [Java Silver 学習ノート](https://wedsiamang.github.io/Java_Study_Notes/#/) ← 同じ形式の先輩ノート
