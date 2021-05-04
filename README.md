# aviutlスクリプト
- aviutlで動作するスクリプトです。  
- 自由に利用、改変、再配布することができますが、開発者は一切の保証をしません。
- 修正のプルリクエストも歓迎いたします。
- 不具合、改善希望などがあれば、issueまたはDiscord( https://discord.gg/NXTkNuRn )の`#aviutlスクリプト`でディスカッションをしましょう。
- 開発途中であることに留意してください。素早い対応、継続的な開発に期待しないでください。
- 開発者及び成果物はTrap Nationとは関わりがありません。
# オーディオスペクトラム
## AS_TrapNation_akkadaska.obj
TrapNation風の音声波形です。  
[![](https://img.youtube.com/vi/lXlsTNX0NhE/0.jpg)](https://www.youtube.com/watch?v=lXlsTNX0NhE)
## AS_Particles_akkadaska.obj
TrapNation風のパーティクルです。
# 音に合わせたアニメーション効果
## AS_config_akkadaska.obj(カスタムオブジェクト)
音に合わせたアニメーション効果に共通するパラメータを設定する際に補助となる情報を表示します。
## AS_Shake_akkadaska.anm
音に合わせて振動します。
## AS_Zoom_akkadaska.anm
音に合わせて拡大します。
# 使用方法
**使い方をまとめた動画を作成中です。**  
*`rikky_module`が必要です！(無料)*  
http://hazumurhythm.com/wev/amazon/?script=NRMv2q9Q から入手し、このページの使い方に従って導入してください。(AviUtl1.10の場合)  
スクリプト(`*.obj,*.anm`)をダウンロード(右上緑の[↓Code] > Download ZIP)して、aviutl.exeがあるフォルダに`script`というフォルダを作成し、その中に移動します。  
`.obj`はレイヤーで右クリック>カスタムオブジェクト で利用できます。
`.anm`はエフェクト>アニメーション効果 で利用できます。
# 注意
- 60fps付近or30fps付近でうまくタイミングが合うように作成しています。
- プレビュー時のフレームレート低下により、AS_Particles_akkadaska.objはプレビュー時とエンコードした時で速度がかわることがあります。「大きさ」の変更はエンコードして、あるいは拡張編集RAMプレビューで確認してください。
