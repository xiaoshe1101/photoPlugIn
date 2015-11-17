# photoPlugIn
本插件类似QQ空间的相册功能及图片旋转功能；
用法：
1.在页面引入layer.min.js;
2.在页面引入插件；
;!function(){
    //加载插件
    layer.use('extend/layer.ext.js',function(){

    });
}();
3.找到这些图片并绑定click事件，
执行   callAlbum (imgs,currImg);  方法
imgs 要循环显示的所有图片；
currImg 当前的图片；
