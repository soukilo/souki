# 家族 国内制作

■ 変更点
1.family/kokunai/配下 旧header/footer ⇒ 新simple-heder

2.viewport 
   現状：
   <meta name="viewport" content="width=device-width, user-scalable=no, initial-scale=1, maximum-scale=1">
   ↑ipad崩れ　iphone5余白が出る
   
   変更：
   https://www.his-j.com/kokunai/kanto/js_common/viewport.js      追加
   https://www.his-j.com/kokunai/special/common/js/responsive.js  追加
         
3.breadcrumb list
   itemprop="itemListElement"、itemscope、itemtype="http://schema.org/BreadcrumbList"、
   itemtype="http://schema.org/ListItem"、itemprop="item、itemprop="name"
   <meta itemprop="position" content="">
   ↑削除

4.<h1 class="mv__title">　⇒　<h2 class="mv__title">

5.地域タブ切り替え　追加
  kokunai_change.js

6.common.js　⇒　common_ver2.js　変更
　元：var headerHeight = $('#t-header').height();　⇒　var headerHeight = $('#simple-header').height();
      var headerHeight = $('#header').height();　　⇒　var headerHeight = $('#simple-header').height();
