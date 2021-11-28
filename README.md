# ダウンロードの仕方
このWebページの右側にReleasesという項目があるので、そこから行ける先で最新のZipをダウンロードしてください。

# 対応aviutlバージョン
aviutl1.10 + 拡張編集0.92 でのみデバッグしております。  
他の環境での動作は保証しません。

# 規約
このツール、またはこのツールに含まれるファイルを使用して作った動画を公開する場合
* ニコニコ動画で公開するなら  
コンテンツツリーの親作品に、下記動画を登録してください。  
* 他のサイトで公開するなら  
動画説明欄などに、下記動画へのリンクを掲載してください。

動画URL：https://www.nicovideo.jp/watch/sm39679253

手間なのは承知しておりますが、このツールを多くの動画製作者に周知し、楽をしていただくためとなります。よろしくお願いいたします。

# このツールが解決する「重いこと」
* タイムラインにオブジェクトを大量に配置すると、劇的に重くなること
* ポーリングレートの高いマウス（ゲーミングマウスなど）だと、ダイアログを移動させるのが劇的に重くなること
* 編集対象のオブジェクトを切り替える際、重いこと

# どう解消するのか
bakusoku.aufを、aviutl.exeと同じフォルダに入れる。  
または、他のプラグインと同じフォルダ（aviutl/pluginsフォルダ）に入れる。  
特に設定などはありません。

# 参考動画
ツール解説動画  
https://www.nicovideo.jp/watch/sm39679253

# バグ報告
https://twitter.com/suzune25254649

こちらまで、DMやリプで報告をくださると凄く喜びます。（バグはなるべく直したい）

# 断り書き
このツールは規約を守る範囲で自由にお使いください。  
ただし、このツールを利用した際に発生した いかなる損失や損害が発生についても、作者は一切の責任を負いかねます。

## v1.02
- 環境によって、速度が「あまり上がらない」というバグを修正しました。
- 修正予定の既知のバグ
    - オブジェクトを生成した時に、水平スクロールバーに黒い線が一本出現する
    - 「上のオブジェクトでクリッピング」を設定した際に、オブジェクトに赤い下線が表示されない（1.01出直したものの再発）

## v1.01
- 「上のオブジェクトでクリッピング」を設定した際に、オブジェクトに赤い下線が表示されなくなってしまっていたバグを修正。

# ライセンス
* AviUtlPluginSDK License

The MIT License

Copyright (c) 1999-2012 Kenkun

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.

* Lua License
-----------

Lua is licensed under the terms of the MIT license reproduced below.
This means that Lua is free software and can be used for both academic
and commercial purposes at absolutely no cost.

For details and rationale, see http://www.lua.org/license.html .

===============================================================================

Copyright (C) 1994-2012 Lua.org, PUC-Rio.

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT.  IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.

===============================================================================
