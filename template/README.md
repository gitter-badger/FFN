###Just copy and paste, Be funny and enjoy !!
```js
// ==UserScript==
// @id             FFN_template
// @name           FFN_template
// @version        2013/2/27
// @author         rwu.tw
// @description    Improvement template system

// @include        *friendfinderinc.com*/cgi-bin/admin/dictionary/*
// @include        *friendfinderinc.com*/cgi-bin/admin/release/cr.cgi*

// @run-at         document-end
// ==/UserScript==

;(function(init){
  var el_script = document.createElement('script') ;
  el_script.src = 'http://rwu823.github.io/lib/js/sea.js' ;
  document.head.appendChild( el_script ) ;

  el_script.onload = init ;
})(function(){  
  unsafeWindow.seajs.use('http://dl.dropboxusercontent.com/u/3430677/github/FFN/template/main.js')
})
```