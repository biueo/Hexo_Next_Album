---
title: 照片
date: 2018-2-15 22:32:22
type: "photos"
fancybox: false
comments: false
---
<link rel="stylesheet" href="../lib/album/ins.css">
<link rel="stylesheet" href="../lib/album/photoswipe.css"> 
<link rel="stylesheet" href="../lib/album/default-skin/default-skin.css"> 
<div class="photos-btn-wrap">
  <a class="photos-btn active" href="javascript:void(0)" target="_blank" rel="external">Photos</a>
</div>
<div class="instagram itemscope">
  <a href="http://www.biueo.com" target="_blank" class="open-ins">图片正在加载中…</a>
</div>
 
<script>
  (function() {
    var loadScript = function(path) {
      var $script = document.createElement('script')
      document.getElementsByTagName('body')[0].appendChild($script)
      $script.setAttribute('src', path)
    }
    setTimeout(function() {
        loadScript('../lib/album/ins.js')
    }, 0)
  })()
</script>