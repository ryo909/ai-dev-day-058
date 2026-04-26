# Day058 Story — Fridge Rescue Menu Palette

## Why
毎日使う小さな課題を、1ページで即解決できる形にしたかったため。

## Requirements
- Webブラウザだけで完結すること
- 1画面で主要操作が終わること
- GitHub Pagesで公開できること

## Design highlights
- Day058専用にテーマをseed固定して再生成時の見た目を安定化
- productivity用途に寄せた単機能UIで迷いを減らす
- 出力をそのまま再利用できるテキスト構造
- Family: fridge_rescue_menu
- Mechanic: combo_filter
- Input/Output: ingredient_cards -> meal_combo_cards
- Audience Promise: 今夜何を先に使うかをすぐ決められる。
- Publish Hook: 食材と残り日数を自分で追加・編集すると、優先食材と成立する組み合わせが同時に見える。
- Complexity Tier: small
- Selected components: none
- Complexity hint: Implement the locked brief with one clear hero interaction and keep the main screenshot readable.

## Trade-offs / Known issues
- ローカル保存機能は未実装
- 複雑な入力バリデーションは最小限

## Next ideas
- 履歴保存
- プリセット追加
- エクスポート形式拡張

## Social copy
Day058｜先食べ献立パレット
期限の近い食材から使う順を決めやすくするためのツールです。
