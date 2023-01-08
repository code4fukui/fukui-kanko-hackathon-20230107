# fukui-kanko-hackathon-20230107
 
- [シビックテック入門、アイデアソンの記録](https://code4fukui.github.io/fukui-kanko-hackathon-20230107/)
- [告知ページ、高校生、高専生対象！シビックテック入門＜データ分析編> | Peatix](https://fukuidx1.peatix.com/)

## 動画変換

解像度960x540のmp4へエンコード
```sh
ffmpeg -i X.MOV -vf scale=-1:540 X.mp4
```
2分で10MB程度になる
