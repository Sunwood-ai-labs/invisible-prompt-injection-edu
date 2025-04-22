# 📚 Invisible Prompt Injection 教育リポジトリ

<p align="center">
  <img src="assets/header.svg" alt="Invisible Prompt Injection" />
</p>

## 🎯 目的
このリポジトリは、LLMに対する「見えないプロンプトインジェクション」の手法を学ぶための教育用サンプルを提供します。

## 📝 内容
- Marp形式のスライド：`slides/invisible_prompt_injection_demo.md`
- デモ資料（JavaScriptやHTML）：後ほど追加予定
- 対策・防御方法のコード例

## 🚀 使い方
1. Marp CLIをインストール
   ```bash
   npm install -g @marp-team/marp-cli
   ```
2. スライドをPDFに変換
   ```bash
   marp slides/invisible_prompt_injection_demo.md --pdf
   ```

## 📚 参考資料
- Riley Goodside, "Prompt injection via Unicode tag characters", 2024
- OWASP, "LLM Security Top 10", 2024
- NTT R&D, "大規模言語モデルの利活用におけるインジェクション攻撃とその対策", 2024