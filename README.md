# Terra Vista

ブラウザで動くボクセル型の探索・建築ゲームを、フォトリアル寄りのグラフィックに強化したものです。
HTML と JavaScript（three.js）だけで動き、インストールは不要です。

## 遊ぶ

- **Realistic（メイン）**: https://bigforest198402.github.io/terra-vista/realistic.html
- Ultra（写真素材・水面反射・画質切替つき）: https://bigforest198402.github.io/terra-vista/ultra.html
- Original（比較用の元の版）: https://bigforest198402.github.io/terra-vista/

## 操作

| キー | 動作 |
|---|---|
| クリック | 操作開始（マウスで視点移動） |
| W A S D | 移動 |
| Space | ジャンプ / 泳ぐ（2回押しで飛行） |
| Shift / Ctrl | しゃがむ・飛行中は下降 / ダッシュ |
| 左クリック / 右クリック | 掘る / 置く |
| 1〜9・ホイール | ブロック選択 |
| F2（Ultra） | Original と切替 |
| F4（Ultra） | 画質切替 |

## ファイル

| ファイル | 内容 |
|---|---|
| `realistic.html` | メイン版（滑らかな地形、木・草・水面の映り込み、水中の水草と魚） |
| `ultra.html` | 最高画質版（Poly Haven の PBR 素材、大気散乱の空、画質プリセット） |
| `index.html` / `original.html` | 比較用の元の版 |
| `cinematic.html` | 最初の強化版 |
| `three.min.js` | three.js r128 |
| `assets/` | Ultra 用テクスチャ（CC0）。出典は `assets/CREDITS.md` |

セーブデータはブラウザの localStorage に保存されます。
