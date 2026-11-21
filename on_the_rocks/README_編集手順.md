# オン ザ ロックス アコード 10秒縦動画（9:16）— 編集キット

## 構成（全10.0秒 / 1080×1920 / 30fps / ナレーション・BGMなし、氷の音のみ）

| 秒 | 映像 | テロップ | 表示 |
|---|---|---|---|
| 0.0–2.0 | 暗いバー、琥珀色のお酒のグラスをアップ。透明な角氷が画面上から落ちてくる | オン ザ ロックス アコード | 0.0–2.0（前後0.2秒フェード） |
| 2.0–6.0 | 氷がグラスに入り「カラン」。液面に波紋、氷の角に冷たい白い光 | お酒を氷で冷やしたような、／ひんやり爽快な香り（2行） | 2.0–6.0（前後0.2秒フェード） |
| 6.0–10.0 | グラスへゆっくり寄り、琥珀色のお酒と透明な氷を同時に見せる | 温かみのある香りに、／爽やかなキレを。（2行） | 6.0–10.0 フェードなしで4.0秒固定 |

- テロップ位置：中心 Y=1420px（下端から約500px）。下端のSNS UIと重なりません。
- 書体：ゴシック、アイボリー文字＋半透明の暗い帯。

## ファイル
- `on_the_rocks_telop_overlay_9x16.mov` … 透過テロップ（ProRes 4444、10.0秒）
- `on_the_rocks_telop_overlay_9x16.webm` … 軽量版（VP9 透過）
- `telop1_0-2s.png` / `telop2_2-6s.png` / `telop3_6-10s.png` … テロップ単体の透過PNG
- `telop_preview.mp4` … 動きの確認用

## 合成手順（CapCut等）
1. 生成した映像（氷の音入り・10秒）を1段目に置く
2. 透過テロップを2段目に0秒から置く（PNGなら上の表の秒数で）
3. BGM・ナレーションは入れない。氷の「カラン」が2秒前後に来ているか確認し、ずれていれば映像ごと前後に微調整
4. 1080×1920、長さ10.0秒で書き出す

## 映像の再生成用・英語プロンプト（Seedance 2.5 / 9:16 / 10秒 / 音声あり）
```
Photorealistic luxury perfume commercial, one continuous shot, no cuts, no text, no letters, no people. A dark, intimate bar at night. Extreme close-up of a heavy cut-crystal rocks glass filled with warm amber whisky on a dark polished wood counter, soft warm golden tungsten lighting, bokeh of bar lights in the background. 0-2s: static close-up of the glass; a perfectly clear transparent ice cube falls from the top of the frame in slow motion. 2-6s: the ice cube drops into the glass, a crisp clear 'clink' sound of ice against glass; small ripples spread across the amber liquid surface, a few tiny droplets; a cool crisp white light glints on the sharp edges of the ice, contrasting with the warm amber glow. 6-10s: the camera slowly and smoothly pushes in toward the glass, showing the amber whisky and the clear ice together, ice gently settling and slowly turning, condensation forming on the glass. Elegant, refined, calm, cool-meets-warm contrast. Keep the lower part of the frame dark and uncluttered. Audio: only the realistic sound of the ice falling and clinking in the glass and soft liquid movement, no music, no voice, no narration.
```
