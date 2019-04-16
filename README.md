[確認サイト](https://jpnykw.github.io/Stu-LT-Slide/)  

# 概要

3/3に開催された「[学生LT x 高専カンファレンス](https://student-lt.connpass.com/event/114723/)」でLTをした際に用いた自作のスライドエンジンです。  
シェーダーをリアルタイムに表現するためにスライド内で再生できるようになっています。  
発表に用いたフルバージョンではございません。（近いうちにフルバージョンにします）  

# 操作

左側のページをクリックしていただくか、矢印キーを押下する事でページ遷移ができます。  
「タイトル」と「オープニング」ページでシェーダー言語のアニメーションが再生されます。  
**タイトルでは比較的軽い処理を行っているので大抵のマシンで動作しますが、  
オープニングではグラフィックボードが載っていないと、とても重いです。**  

# プログラム
各種アニメーションのソースコードはこちら

| 名前 | コード |
| - | - |
| タイトル | https://github.com/JPNYKW/Stu-LT-Slide/blob/master/asset/glsl/title/fragment.glsl |
| オープニング | https://github.com/JPNYKW/Stu-LT-Slide/blob/master/asset/glsl/opening/fragment.glsl |



オープニングは、音に同期するアニメーションのため、  
環境によって見れない方は[**こちら**](https://www.youtube.com/watch?v=S9PV9rSlexA&)から確認してください。  
ちなみにLT本番のノートPCのスペックだと再生できなかったので動画で補っていました。  
