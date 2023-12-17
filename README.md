# 雲碼衍生方案：雲碼日文方案

該方案靈感來自[河童日文五笔方案](https://github.com/zerobikappa/rime-kappajp86)。

## 方案起源

日文輸入主流無非㒳派，一爲仮名輸入，二則羅馬字輸入，這樣的方案都要求輸入者掌握漢字至少一種讀音，且同音字仍需選重。

我作爲日語初學者，識字量小，且抗拒音碼與選重，心道能否用形碼輸入？

## 方案特點

方案設想與河童不謀而合，用羅碼字輸入仮名，用形碼輸入漢字；这裏形碼用我个人作品雲碼。

方案中三簡設純仮名詞、日文漢字，單箇仮名、拗音爲二簡，其馀一、二簡與傳統字方案簡碼完全一致，無需重記簡碼。

例: 「ください」爲「kds」，「わたし」爲「wts」；原傳統字方案中「tgb」爲「皈」，日文方案爲「仮」，原「flk」爲「銮」，日文方案爲「変」。

片仮名 = 平仮名 + 変換鍵「Z」。

例: 「たい」爲「taii」，「タイ」爲「taiiz」。

## TODO

- [x] 仮名碼表
- [x] 日文用字表
- [ ] 日文字頻表
- [ ] 上傳rime方案文件
- [ ] 詞庫

## 修改記録

2023.12.17

添加歷史仮名「ゐ(wi)」「ゑ(we)」「ヰ(wiz)」「ヱ(wez)」，放至對應碼位之次選。 

2023.12.13

匯入增廣詞彙，如「有難」等。

2023.11.21

片仮名変換鍵由「K」改爲「Z」，不會再打断仮名輸入。
