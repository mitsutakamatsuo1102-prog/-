# Angels' Share 10秒縦動画（9:16）— 編集キット

## 構成（全10.0秒 / 1080×1920 / 30fps）

| 秒 | 映像 | テロップ | 表示秒数 |
|---|---|---|---|
| 0.0–2.0 | 暗い熟成庫、オーク樽へ寄る | ウイスキーは、樽の中で熟成する | 0.15–1.95（フェード0.25秒） |
| 2.0–6.0 | 同じ樽の真横断面・カメラ固定。液面がゆっくり下がり、元の高さに細い点線 | 熟成中に少しずつ蒸発 | 2.15–5.95（フェード0.25秒） |
| 6.0–10.0 | 断面のまま。液面と点線の間を淡い金色で示す | 蒸発した分＝天使の取り分 | 6.15–10.00 |
|  |  | ANGEL’S SHARE（上の行の下） | 6.70–10.00（0.4秒でフェードイン） |

- テロップ位置：中心 Y=1430px（下から約490px）。画面下端の約380pxは空けてあり、SNSのUIと重なりません。
- 書体：IPAゴシック（和文）／Liberation Serif（ANGEL’S SHARE・ゴールド）。読みやすいよう半透明の暗い帯つき。

## ナレーション（約8秒、0.3秒から開始）
「樽の中で、ウイスキーは少しずつ蒸発する。その分が、天使の取り分。エンジェルズシェア。」

## ファイル
- `angels_share_telop_overlay_9x16.mov` … 透過テロップ（ProRes 4444、10.0秒）。動画の上のトラックに0秒から置くだけ
- `angels_share_telop_overlay_9x16.webm` … 同じ内容の軽量版（VP9 透過）
- `telop1_0-2s.png` / `telop2_2-6s.png` / `telop3_6-10s.png` … テロップ単体の透過PNG（CapCutなどで秒数どおりに置く用）
- `telop_preview.mp4` … テロップの動きの確認用

## 合成手順（CapCut等）
1. 生成した映像（10秒）を1段目に置く
2. 透過テロップ（.mov か PNG 3枚）を2段目に、上の表の秒数で置く
3. ナレーション音声を0.3秒から置く
4. 1080×1920で書き出し、長さが10.0秒ちょうどか確認

## 映像の再生成用・英語プロンプト（Seedance 2.5 / 9:16 / 10秒 / 音声なし）
```
Photorealistic luxury perfume commercial look, calm muted palette of deep brown, amber and soft gold, no text, no letters, no people. Shot 1 (0-2s): a dark, quiet whisky aging warehouse, rows of oak casks, a thin beam of warm light; slow dolly-in toward one oak barrel with visible wood grain and iron hoops. Hard cut. Shot 2 (2-10s): the same oak barrel shown as a clean side-view cross-section cutaway, as if sliced in half vertically, centered in the frame, filling the middle of the vertical frame, LOCKED-OFF STATIC CAMERA, no camera movement. Inside the cut barrel, translucent amber whisky fills it up to a high level. A thin fine white dotted horizontal line marks the original liquid level against the inner wall. The amber liquid surface slowly and smoothly lowers by about one fifth, leaving the dotted line above it. In the final part, the empty gap between the lowered liquid surface and the dotted line glows with a soft pale gold translucent light haze, a few faint golden particles drifting upward. Dark warm background, soft rim light, shallow depth of field, elegant and minimal. Keep the top and bottom of the frame calm and uncluttered.
```
