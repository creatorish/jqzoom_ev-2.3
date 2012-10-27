jQzoom Touch - Javascript Image magnifier
======================
画像の一部を拡大表示できるjQueryプラグイン「jqZoom」をタッチデバイス対応にしたもの



デモ
------
1.<a href="http://dev.creatorish.com/demo/jqzoom-touch/demos/demo_standard.html" target="_blank">基本 -Standard-</a>
2.<a href="http://dev.creatorish.com/demo/jqzoom-touch/demos/demo_drag.html" target="_blank">ドラッグ操作 -Drag-</a>
3.<a href="http://dev.creatorish.com/demo/jqzoom-touch/demos/demo_alwayson.html" target="_blank">拡大表示を常に表示 -Always on zoom-</a>
4.<a href="http://dev.creatorish.com/demo/jqzoom-touch/demos/demo_innerzoom.html" target="_blank">インライン拡大 -Inner zooom-</a>
5.<a href="http://dev.creatorish.com/demo/jqzoom-touch/demos/demo_resizeposition.html" target="_blank">サイズや位置を変更 -Reposition-</a>

使い方
------

<a href="http://www.mind-projects.it/projects/jqzoom/" target="_blank">jqZoom Evolution</a>とまったく同じです。

CSSをhead内で読み込みます。

     <link rel="stylesheet" type="text/css" href="css/jquery.jqzoom.css">

jQueryとjqZoomを読み込みます。

    <script type='text/javascript' src='js/jquery-x.x.js'></script>
    <script type='text/javascript' src='js/jquery.jqzoom-core.js'></script>

拡大したい箇所を以下のようにマークアップします。

    <a href="images/BIGIMAGE.JPG" class="MYCLASS" title="MYTITLE">
        <img src="images/SMALLIMAGE.JPG" title="IMAGE TITLE">
    </a>

aタグのhrefに拡大後の画像、imgタグに拡大前の小さい画像を指定します。  
そしてお決まりのｊQueryプラグインの記述を追加します。

    $(document).ready(function(){
        $('.MYCLASS').jqzoom();
    });

オプション等は本家のサイトを参照してください。  
<a href="http://www.mind-projects.it/projects/jqzoom/" target="_blank">jqZoom Evolution</a>

既にjqZoomを導入している場合はそのままJSを上書きするだけでOKです。

ライセンス
--------
[BSD]: http://www.freebsd.org/ja/copyright/freebsd-license.html
Copyright &copy; 2012 creatorish.com

作者
--------
creatorish yuu  
Weblog: <http://creatorish.com>  
Facebook: <http://facebook.com/creatorish>  
Twitter: <http://twitter.jp/creatorish>
