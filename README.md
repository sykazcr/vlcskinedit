# vlcskinedit
 skin of vlc study

-----以下メモ
�@vlcskineditor環境構築時、JavaのJREが必要ですが。実は32bit版JRE利用する。windows10なら６４Bitと32bit版を両方ともインストールすれば無難
�Avlcがソースコードからのビルドが容易ではない、不可能と思っても構わない。
�B幸い今回の課題がvlcの豊富なコマンドラインオプションで進められそうです。
例：
再生時ロゴ入れ：
vlc --sub-source logo --logo-file logo73.png dan.mp4

スキン付き起動：
vlc.exe -Iskins

いろいろ組合せへ可能
