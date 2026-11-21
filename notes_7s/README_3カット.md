# 香りのノート 7秒縦動画（9:16）— 3カット プロンプト＆テロップ

## テロップ（中心 Y=1180px＝画面中央より少し下）

| 秒 | カット | テロップ |
|---|---|---|
| 0.0–2.3 | トップ | 氷のように冷たい柑橘 |
| 2.3–4.7 | ミドル | コニャックとキャラメルの甘さ |
| 4.7–7.0 | ベース | オークと白檀の余韻 |

透過テロップ：`notes_telop_overlay_9x16.mov` / `.webm`（7.0秒、0秒から重ねるだけ）、単体PNG 3枚。

## 3カット別・英語プロンプト（各カットを個別生成→編集でつなぐ場合）
共通設定：9:16、各3〜4秒で生成し、編集で 2.3秒 / 2.4秒 / 2.3秒 に切り出す。音声なし。

### Cut 1 — Top (0.0–2.3s)
```
Photorealistic luxury perfume commercial, extreme macro shot, vertical 9:16, near-black background. Cool pale blue light. Beside a perfectly clear transparent ice cube, fingertips slowly twist a fresh strip of bergamot peel; a fine spray of tiny citrus oil droplets bursts out and sparkles in the backlight. A halved grapefruit cross-section glows softly out of focus in the background. The bergamot peel is the single hero subject. Natural textures, shallow depth of field, slow motion. Leave an empty, uncluttered dark area slightly below the center of the frame. No text, no letters, no music.
```

### Cut 2 — Middle (2.3–4.7s)
```
Photorealistic luxury perfume commercial, extreme macro shot, vertical 9:16, near-black background. Opening on a cool reflection on ice, the scene transitions to amber cognac slowly sliding down the rim of a crystal snifter glass; the lighting warms from pale blue to rich gold during the shot. A cinnamon stick and a glossy piece of caramel rest softly out of focus in the foreground. The flowing cognac is the single hero subject. Natural textures, shallow depth of field, slow motion. Leave an empty, uncluttered dark area slightly below the center of the frame. No text, no letters, no music.
```

### Cut 3 — Base (4.7–7.0s)
```
Photorealistic luxury perfume commercial, extreme macro shot, vertical 9:16, near-black background. Continuing a warm amber tone, a soft beam of light glides slowly across dark oak wood grain, then the focus slowly racks onto a small sandalwood chip with dark tonka beans beside it. Deep brown and amber palette. The sandalwood chip is the single hero subject. The last half second is a completely still frame. Natural textures, shallow depth of field. Leave an empty, uncluttered dark area slightly below the center of the frame. No text, no letters, no music.
```

## 1本で生成した版のプロンプト（Seedance 2.5 / 9:16 / 7秒）
```
Photorealistic luxury perfume commercial, macro photography, three shots, near-black background throughout, natural material textures, one hero subject per shot, no text, no letters, no people except fingertips. Keep an empty, uncluttered area slightly below the center of the frame in every shot. Shot 1 (0.0-2.3s), cold top note: cool pale blue light, a clear transparent ice cube; fingertips twist a strip of bergamot peel beside it, a fine mist of citrus oil droplets sparkles in the backlight; a halved grapefruit cross-section softly out of focus in the background. Cut. Shot 2 (2.3-4.7s), sweet heart note: from the ice reflection to amber cognac slowly running down the rim of a crystal snifter glass; the lighting shifts from cool blue to warm gold; a cinnamon stick and a glossy piece of caramel in the foreground. Cut. Shot 3 (4.7-7.0s), deep base note: continuing the amber tone, a soft beam of light slowly glides across dark oak wood grain; focus slowly racks onto a sandalwood chip and dark tonka beans; the final half second is completely still. Color journey: pale blue to amber to deep brown. Slow, elegant, sensual. Audio: subtle natural sounds only (peel twist, liquid pour, soft room tone), no music, no voice.
```
