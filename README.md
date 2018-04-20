<?xml version="1.0" encoding="UTF-8" ?>
<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Strict//EN" "http://www.w3.org/TR/xhtml1/DTD/xhtml1-strict.dtd">
<html expr:dir='data:blog.languageDirection' xmlns='http://www.w3.org/1999/xhtml' xmlns:b='http://www.google.com/2005/gml/b' xmlns:data='http://www.google.com/2005/gml/data' xmlns:expr='http://www.google.com/2005/gml/expr'>

  <head>
    <b:include data='blog' name='all-head-content'/>
    <b:if cond='data:blog.pageType == &quot;index&quot;'>
    <title><data:blog.pageTitle/></title>
    <b:else/>
    <title><data:blog.pageName/> - <data:blog.title/></title>
    </b:if>
    <meta content='Your Blog Description here!' name='description'/>
    <meta content='Your Keywords here!' name='keywords'/>
    <meta content='Author Name here!' name='Author'/>
    <meta content='Author Email Address here!' name='Email'/>
    <meta content='document' name='resource-type'/>
    <meta content='all' name='audience'/>
    <meta content='general' name='rating'/>
    <meta content='all' name='robots'/>
    <meta content='index, follow' name='robots'/>
    <meta content='id' name='language'/>
    <meta content='id' name='geo.country'/>
    <meta content='global' name='distribution'/>
    <meta content='1 days' name='revisit-after'/>
	<meta content='width=device-width,initial-scale=1,minimum-scale=1,maximum-scale=1' name='viewport'/>
  
<link href='//netdna.bootstrapcdn.com/font-awesome/4.1.0/css/font-awesome.css' rel='stylesheet'/>
<b:skin><![CDATA[

/* -----------------------------------------------
Blogger Template Style
Name:        Shopingo
Author :     http://www.soratemplates.com
License:     Free Version
----------------------------------------------- */

/* Variable definitions
   ====================
   <Variable name="bgcolor" description="Page Background Color"
             type="color" default="#fff" value="#eeeeee">
   <Variable name="textcolor" description="Text Color"
             type="color" default="#444" value="#444444">
   <Variable name="linkcolor" description="Link Color"
             type="color" default="#58a" value="#2a4978">
   <Variable name="pagetitlecolor" description="Blog Title Color"
             type="color" default="#666" value="#333333">
   <Variable name="descriptioncolor" description="Blog Description Color"
             type="color" default="#999" value="#666666">
   <Variable name="titlecolor" description="Post Title Color"
             type="color" default="#c60" value="#000000">
   <Variable name="bordercolor" description="Border Color"
             type="color" default="#ccc" value="#dcd9d9">
   <Variable name="sidebarcolor" description="Sidebar Title Color"
             type="color" default="#999" value="#333333">
   <Variable name="sidebartextcolor" description="Sidebar Text Color"
             type="color" default="#666" value="#666666">
   <Variable name="visitedlinkcolor" description="Visited Link Color"
             type="color" default="#999" value="#2a4978">
   <Variable name="bodyfont" description="Text Font"
             type="font" default="normal normal 100% Georgia, Serif" value="normal normal 12px Arial, Tahoma, Helvetica, FreeSans, sans-serif">
   <Variable name="headerfont" description="Sidebar Title Font"
             type="font"
             default="normal normal 78% 'Trebuchet MS',Trebuchet,Arial,Verdana,Sans-serif" value="normal bold 14px Arial, Tahoma, Helvetica, FreeSans, sans-serif">
   <Variable name="pagetitlefont" description="Blog Title Font"
             type="font"
             default="normal normal 200% Georgia, Serif" value="normal normal 26px Georgia, Serif">
   <Variable name="descriptionfont" description="Blog Description Font"
             type="font"
             default="normal normal 78% 'Trebuchet MS', Trebuchet, Arial, Verdana, Sans-serif" value="normal normal 12px Lucida Sans, Tahoma, Helvetica, FreeSans, sans-serif">
   <Variable name="postfooterfont" description="Post Footer Font"
             type="font"
             default="normal normal 78% 'Trebuchet MS', Trebuchet, Arial, Verdana, Sans-serif" value="normal normal 12px Arial, Tahoma, Helvetica, FreeSans, sans-serif">
   <Variable name="startSide" description="Side where text starts in blog language"
             type="automatic" default="left">
   <Variable name="endSide" description="Side where text ends in blog language"
             type="automatic" default="right">
*/

body{background:#fff;color:$textcolor;font:x-small Trebuchet MS;font-size:small;text-align:left;margin:0}
a:link{color:$linkcolor;text-decoration:none}
a:visited{color:$visitedlinkcolor;text-decoration:none}
a:hover{color:$titlecolor;text-decoration:none}
a img{border-width:0}
#header-wrapper{width:1170px;border:0 solid $bordercolor;margin:0 auto 10px}
#header-inner{background-position:center;margin-left:auto;margin-right:auto}
#header{float:left;width:200px;border:0 solid $bordercolor;text-align:left;color:$pagetitlecolor;margin:0}
#header2{float:right;width:728px;margin-right:10px;text-align:left;color:#555}
.header .widget,.header2 .widget{margin:0 auto;padding:10px 0}
#header h1{line-height:1.2em;text-transform:none;letter-spacing:.1em;font:bold 30px Arial;margin:0 auto;padding:10px 5px .15em;text-shadow:-1px -1px #223b5a;color:#d0e1f5;}
#header a{text-decoration:none}
#header a:hover{color:$pagetitlecolor}
#header .description{max-width:100%;text-transform:uppercase;letter-spacing:.01em;line-height:1.2em;font:$descriptionfont;color:$descriptioncolor;margin:0 auto;padding:0 5px 5px}
#header img{margin-startside:auto;margin-endside:auto}
#navbar-iframe{height:0;visibility:hidden;display:none}
#crosscol-wrapper{margin:0 auto;padding:0 auto}
.crosscol .widget{margin:0 auto;padding:0 0 6px}
#mainpage-wrapper{width:675px;float:left;word-wrap:break-word;overflow:hidden}
#main-wrapper{width:885px;float:$endSide;word-wrap:break-word;overflow:hidden;}
#sidebar-wrapper{width:285px;float:$startSide;word-wrap:break-word;overflow:hidden}
h2.date-header{margin:1.5em 0 .5em}
.post{margin:.5em 0 .1em;padding:15px}
.post .jump-link{display:none}
.post h3{line-height:26px;margin:0 0 20px;padding:0 0 5px}
.post h3 a,.post h3 a:visited,.post h3 strong{font-size:30px;font-weight:700}
.post h3 strong,.post h3 a:hover{text-decoration:none}
.post-body{line-height:1.6em;font:14px Arial;margin:0 0 .75em}
.post-body blockquote{line-height:1.3em}
.post-footer{padding:5px}
.post img{max-width:580px;padding:4px}
.post blockquote{margin:1em 20px}
.post blockquote p{margin:.75em 0}


#blog-pager-newer-link{float:$startSide}
#blog-pager-older-link{float:$endSide}
#blog-pager{clear:both;text-align:center;margin:20px 0;padding:10px 0}
.feed-links{clear:both;line-height:2.5em}

.sidebar h2{background:url(http://3.bp.blogspot.com/-UP2TzR7l-Ak/T7udRSQ6EKI/AAAAAAAAGOM/tyehSG8cvkM/s1600/sidebar-bg.png) repeat-x bottom;font:bold 13px Arial;color:#111;text-transform:uppercase;text-shadow: 1px 1px #fff;padding:7px 0 8px 10px;-moz-border-radius:5px 5px 0 0; -khtml-border-radius:5px 5px 0 0; -webkit-border-radius:5px 5px 0 0; border-radius:5px 5px 0 0;}
.sidebar{color:$sidebartextcolor;line-height:1.3em;}
.sidebar li{background:url(http://4.bp.blogspot.com/-b2PXU86078o/T7uffs0D-0I/AAAAAAAAGOU/HL2APebva4M/s1600/categories.png) no-repeat 1px 5px;text-indent:0;line-height:1.3em;margin:0;padding:4px 0 5px 20px}
.sidebar ul{float:left;list-style:none;margin:0;padding:0}
.sidebar li a:hover{color:#004a84}
.sidebar .widget{margin:0 0 5px;border-left: 1px solid #ddd;
border-right: 1px solid #ddd;
border-bottom: 1px solid #ddd;}
.sidebar .widget-content{margin:0 10px;padding:5px 10px;-moz-border-radius:0 0 5px 5px; -khtml-border-radius:0 0 5px 5px; -webkit-border-radius:0 0 5px 5px; border-radius:0 0 5px 5px;}
.sidebar a:link,.sidebar a:visited{font:bold 12px Arial;color:#555;text-decoration:none}
.main .widget{border-bottom:1px dotted $bordercolor;margin:0 0 1.5em;padding:0 0 1.5em}
.main .Blog{border-bottom-width:0}
.profile-img{float:$startSide;margin-top:0;margin-endside:10px;margin-bottom:5px;margin-startside:0;border:1px solid $bordercolor;padding:4px}
.profile-data{text-transform:uppercase;letter-spacing:.01em;font:bold 13px Arial;color:$sidebarcolor;line-height:1.3em;margin:0}
.profile-datablock{margin:.5em 0}
.profile-textblock{line-height:1.3em;margin:.5em 0}
.profile-link{font:$postfooterfont;text-transform:none;letter-spacing:.01em}
#top-wrapper{width: 1170px;
margin: 0 auto;
background-color: #229ac8;
background-image: linear-gradient(to bottom, #23a1d1, #1f90bb);
background-repeat: repeat-x;
border-color: #1f90bb #1f90bb #145e7a;
min-height: 40px;
line-height: 40px;border-radius: 4px;
margin-bottom: 20px;
border: 1px solid transparent;}
#topbar{width:1170px;height:27px;margin:0 auto}
#top{width:100%}
#top,#top ul{list-style:none;font-family:Arial, serif;margin:0;padding:0}
#top a{display: block;
text-decoration: none;
font: normal 13px Arial;
text-transform: none;
color: #FFFFFF;
padding: 0px 10px;
line-height: 40px;} 
#top a.arrow{padding:0px 10px 0px 10px}
#top li{float:left;position:static;width:auto}
#top li ul,#top ul li{width:170px}
#top ul li a{text-align:left;color:#fff!important;font-size:12px;font-weight:400;text-transform:none;font-family:Arial;border:none;padding:5px 10px}
#top li ul{z-index:100;position:absolute;display:none;background:#2197C4;padding-bottom:0;}
#top li:hover a,#top a:active,#top a:focus,#top li.hvr a{background-color: rgba(0, 0, 0, 0.1);
color: #FFF;}
#top li:hover ul a,#top li.hvr ul a{color:#111;background-color:transparent;text-decoration:none}
#top li:hover ul,#top li.hvr ul{display:block}
#top li ul li.hr{display:block;font-size:1px;height:0;line-height:0;margin:0}
#top ul a:hover{background-color:rgba(0, 0, 0, 0.1)!important;color:#fff!important;text-decoration:none}
#top a span,#top a.arrow span{font:bold 12px Arial;color:#ddd;display:block;line-height:16px;text-transform:uppercase}
#top li:hover a span,#top li:hover a.arrow span{color:#fff}

#searchbar{width:1170px;height:40px;font-size:12px;font-family:Arial, Tahoma, Verdana;color:#616161;font-weight:700;margin-bottom:15px;padding:0;border: 1px solid #EDEDED;}
#searchbarleft{width:270px;float:left;margin:0;padding:7px 0 0 10px}
#searchbarmiddle{width:300px;float:left;margin:0;padding:4px 0 0}
#searchbarright{width:180px;float:right;margin:0;padding:8px 0 0}
#searchbarright1{width:190px;float:left;margin:0;padding:2px 0 0}
#searchbarform{display:inline;overflow:hidden;margin:10px 0 0}
#searchbarformheader{margin:0}
#cat{background:#fff;width:220px;color:#222;font-family:Arial, Tahoma, Verdana;display:inline;margin:3px;padding:3px 2px 2px;}
#subscribe{overflow:hidden;margin:0;padding:0 0 5px}
#subbox{background:#fff url(http://3.bp.blogspot.com/-3nqMfDFqsUQ/T4_x8t_XbaI/AAAAAAAAAok/oVXZ6X2RKsg/s1600/email.png) no-repeat scroll 4px center;font:bold 11px Sans-Serif;color:#666;text-decoration:none;border:1px solid #aaa;height:14px;width:170px;margin:0;padding:5px 0 4px 34px}
#subbutton{background: #229ac8;
color: #FFF;
font: 11px Arial;
font-weight: 700;
text-decoration: none;
border: 1px solid #229ac8;
margin-left: 5px;
padding: 5px 5px;}
ul.isocial{list-style:none;margin:0;padding:5px 20px 0 0}
ul.isocial li{float:right;margin:0 5px;padding:0}
ul.isocial li a{float:right;background-image:url(http://1.bp.blogspot.com/-Tg7BikflCm8/T4_x9T1aflI/AAAAAAAAAoo/jV53zVYzVDY/s1600/social+letter.png);background-position:0 0;background:repeat:no-repeat;display:inline-block;text-indent:-9999px;overflow:hidden;width:24px;height:24px;position:relative}
ul.isocial li a.rss{background-position:0 0}
ul.isocial li a.rss:hover{background-position:0 -25px}
ul.isocial li a.facebook{background-position:-25px 0}
ul.isocial li a.facebook:hover{background-position:-25px -25px}
ul.isocial li a.twitter{background-position:-50px 0}
ul.isocial li a.twitter:hover{background-position:-50px -25px}
ul.isocial li a.google{background-position:-75px 0}
ul.isocial li a.google:hover{background-position:-75px -25px}
ul.isocial li a.youtube{background-position:-100px 0}
ul.isocial li a.youtube:hover{background-position:-100px -25px}
.showpageOf{border:1px solid #7b7c7d;color:#000;margin:2px;padding:3px 9px}
.showpageNum a,.showpage a{border:1px solid #7b7c7d;color:#000;text-decoration:none;margin:2px;padding:3px 6px}
.showpageNum a:hover,.showpage a:hover,.showpagePoint{border: 1px solid #229ac8;
background: #229ac8;color:#fff;margin:2px;padding:3px 6px}

#outer-wrapper{background:#fff;width:1170px;text-align:$startSide;font:$bodyfont;margin:0 auto;}
.footer h2{BORDER-BOTTOM: 1PX SOLID #666;;padding-bottom:10px;font:bold 14px Arial;color:#FFF;line-height:1.2em;text-transform:none;letter-spacing:.01em;margin:0 0 3px}
.footer{font:normal 12px Arial;color:#999;line-height:1.3em}
.footer ul{list-style:none;color:#EAE9E8;margin:0;padding:0}
.footer li{background:url(http://4.bp.blogspot.com/-Bt0JYGRHfpk/T7ZpN5RNSQI/AAAAAAAAGJQ/zQtrWVZwgHA/s1600/bullet.png) no-repeat 1px 5px;font:normal 13px Arial;color:#EAE9E8;text-indent:0;line-height:1.1em;margin:0;padding:2px 0 3px 16px}
.footer .widget{margin:0 0 5px;padding:0 auto}
.footer a:link,.footer a:visited{font:normal 12px Arial;color:#999;text-decoration:none}
.footer a:hover{color:#eee;text-decoration:none}
.footerwrap{width: 100%;
background-color: #303030;
border-top: 1px solid #ddd;
color: #e2e2e2;
margin-startside: auto;
margin-endside: auto;
text-align: center;
font: normal normal 12px Arial, Tahoma, Helvetica, FreeSans, sans-serif;
margin: 0 auto;
padding: 10px 0;}
#footer-wrapper{width:1170px;text-align:left;font:normal normal 12px Arial, Tahoma, Helvetica, FreeSans, sans-serif;margin:0 auto;padding:10px 0}
#footer1-wrapper{width:24%;float:left;margin-right:15px;word-wrap:break-word;overflow:hidden}
#footer4-wrapper{width:24%;float:left;word-wrap:break-word;overflow:hidden}
#footer2-wrapper,#footer3-wrapper{width:24%;float:left;margin-right:15px;word-wrap:break-word;overflow:hidden}
.creditwrap{background:#333;width:100%;border-top:1px solid #666;margin:0 auto;padding:0 auto}
.credit{width:1170px;line-height:1.6em;text-align:center;font-family:Arial;font-size:11px;color:#aaa;overflow:hidden;clear:both;margin:0 auto;padding:10px 0}
.credit a:link,.credit a:visited{color:#aaa;text-decoration:none}
.credit a:hover{color:#FFF;text-decoration:none}

/* Shopping Cart 
----------------------------------------------- */
#shoppingCart{background-color: #fff;
float: left;
color: #474747;
width: 263px;
padding: 0 10px 10px;
border: 1px solid #ddd;}
#shoppingCart h2{background:url(http://2.bp.blogspot.com/-N9GvSMaH38A/T7qCGHb4ElI/AAAAAAAAGLo/sNUlCs3e8mo/s1600/icon_cart.png) no-repeat left top;display:block;font-size:16px;color:#5F5F5F;text-decoration:none;margin-bottom:10px;padding:0 0 10px 25px}
.itemname{float:left;clear:both}
.item_thumb{padding:10px}
.item_price{display:block;height:20px;position:absolute;bottom:7px;left:10px;color:#2a4978;font-size:13px;font-weight:700;text-align:left;border:0 none;padding:5px 10px}
.simpleCart_items{background-color: #f4f4f4;
-moz-box-shadow: inset #082849 0 2px 7px;
font-size: 80%;
min-height: 120px;
display: block;
margin: 0 auto 10px;
overflow: hidden;
padding: 10px;border: 1px solid #ddd;}
.simpleCart_items img{text-align:left;width:40px!important;height:40px!important;padding:2px}
.itemContainer{float:left;width:210px;text-align:center;display:block;position:relative;bottom:0}
.itemthumb{float:left;width:58px;margin:0}
.itemQuantity{float:left;width:25px;margin:6px 0}
.itemQuantity input{border:none;color:#6e6e6e;background:none;float:left;font:bold 11px Arial,sans-serif;height:22px;text-align:center;width:25px;padding:5px}
.itemQuantity input:focus{outline:none}
.itemremove a{color:#818181;float:left;font-weight:700;margin:15px 0 0 15px}
.itemTotal{color:#6e6e6e;float:left;font:bold 11px Arial,sans-serif;text-align:right;width:55px;margin:15px 0 0 10px;padding:0}
.simpleCart_finalTotal{color:#fff;font-size:18px}
.cart table{border-collapse:collapse;margin-top:20px}
.cart table td.odd{color:#fff;text-align:left;width:100px}
.cart table td.even{color:#fff;text-align:right;width:100px}
a.simpleCart_empty{background-color: #229ac8;
background-image: linear-gradient(to bottom, #23a1d1, #1f90bb);
background-repeat: repeat-x;
border-color: #1f90bb #1f90bb #145e7a;;border-radius:3px 3px 3px 3px;-moz-border-radius:3px;-webkit-border-radius:3px 3px 3px 3px;display:block;font:bold 12px Arial;text-align:center;text-decoration:none;color:#fff;float:left;width:80px;margin:0 20px;padding:6px}
.cartbuttons{margin:10px 0 0}
a.simpleCart_checkout{background-color: #229ac8;
background-image: linear-gradient(to bottom, #23a1d1, #1f90bb);
background-repeat: repeat-x;
border-color: #1f90bb #1f90bb #145e7a;border-radius:3px 3px 3px 3px;-moz-border-radius:3px;-webkit-border-radius:3px 3px 3px 3px;display:block;font:bold 12px Arial;text-align:center;text-decoration:none;color:#fff;float:left;width:80px;padding:6px}
input.item_add:hover{background-position:bottom left;color:#fff}
input.item_add{color:#fff;font-size:11px;font-weight:400;text-align:center;border:none;border-radius:2px 2px 2px 2px;-moz-border-radius:2px;-webkit-border-radius:2px 2px 2px 2px;width:80px;background-color: #229ac8;
background-image: linear-gradient(to bottom, #23a1d1, #1f90bb);
background-repeat: repeat-x;
border-color: #1f90bb #1f90bb #145e7a;margin-right:10px;float:right;padding:5px}
#checkout{background:#D9D9D9;color:#000;text-decoration:none;font-size:80%;display:block;text-align:center;-moz-border-radius:5px;border-radius:5px;-webkit-border-radius:5px;padding:10px}
#checkout:hover{background:#333;color:#FFF}
.item_name,.hidden_value,.cartHeaders{display:none}
a.simpleCart_empty:hover,a.simpleCart_checkout:hover{background:#d9d9d9;color:#000}
.product_image{width:170px;height:200px;background:#fff;border:1px solid #ccc;float:left;text-align:left;margin:0 15px 10px 0;padding:13px 10px 13px 13px}
.product_image img{width:160px;height:160px}

.shadow{width:645px; height:39px; margin:0 auto}
#featuredSlider {float:right;padding:10px 0; width:870px; position:relative;background-color: #229ac8;
background-image: linear-gradient(to bottom, #23a1d1, #1f90bb);
background-repeat: repeat-x;
border-color: #1f90bb #1f90bb #145e7a;color:#fff;}
#featuredSlider .featured-thumb { background:#fff;float:left; margin:0 10px 0 0; padding:8px; }
#featuredSlider .container {height:215px; margin:0 10px;overflow:hidden; position:relative; }
.featuredTitle{font-size:22px;font-weight:bold!important;}
.featuredTitle a{color:#d0e1f5}
.featuredTitle a:hover{color:#fff}
.navigation {position:relative;bottom:15px;float:right;overflow:hidden;}
ul.pagination {list-style-type:none; margin:0 auto; padding:0;}
ul.pagination a { float:left; margin:0 5px; display:inline; }
ul.pagination a { display:block;width:12px; padding-top:12px; height:0; overflow:hidden; background-image:url(http://1.bp.blogspot.com/-TtitrRZoyo4/T7qRFeWf2RI/AAAAAAAAGMU/RuVrW_8cdWg/s1600/cs-buttons.png); background-position:0 0; background-repeat:no-repeat; }
ul.pagination a:hover { background-position:0 -12px; }
ul.pagination a:hover { background-position:0 -12px; }
ul.pagination a.activeSlide { background-position:0 -12px }
a.shop {float:right;background:#45b52f url(http://2.bp.blogspot.com/-S4AKqSDPUEs/ToSYCWJy4qI/AAAAAAAAABI/conBgqSajOY/s1600/fade.png) repeat-x top left;display:block;margin:10px 0 0 0;padding:4px 10px;color:#fff;font-weight:700}
a.shop:hover {color:#000}

#nav-wrapper{font-family: "Tahoma",Palatino,serif;
overflow: hidden;
border-bottom: 3px solid #fff;
background-color: #EEEEEE;
border-bottom: 1px solid #e2e2e2;
margin: 0 0 10px 0;
min-height: 40px;line-height: 40px;}
#nav{margin:0 auto;width:1170px;height:28px;padding:0}
#nav ul{float:left;width:auto;height:28px;margin:0;padding:0;list-style-type:none}
#nav ul li{float:left;height:28px}
#nav ul li a,#nav ul li a:visited{float:left;height:28px;padding:14px 8px;color:#888;font:bold 11px Arial;text-transform:none}
#nav ul li a:hover{background:#4b7bbf;color:#eee;text-decoration:none;}

.PopularPosts .widget-content ul li{background:none repeat scroll 0 0 transparent;float:left;list-style:none outside none;margin:0 !important;padding: 0 !important;border-bottom:none}
.PopularPosts ul{padding:5px 0}
.PopularPosts .item-thumbnail img{width:104px;height:104px;padding:2px;margin:0}
.PopularPosts .item-content{position:relative;float:left;margin:0}
.PopularPosts .item-title a{font:12px Arial;color:#fff;display:block;padding:0 5px;float:left;width:100px}
.PopularPosts .item-title a:hover{background:#000;color:#ccc;}
.PopularPosts .item-thumbnail{float:left;margin:3px 5px 7px 6px;border:1px solid #bbb;overflow: hidden}
.PopularPosts .item-title{background:url(http://3.bp.blogspot.com/-F6jJZ3Qin7s/T5bShzfjYRI/AAAAAAAAAtE/aD9q8DnSYiw/s1600/transparant.png);position:absolute;bottom:8px;right:6px}
.quickedit{display:none}

/*---------------------------------
	
	featured post 

---------------------------------------------*/

.featured-post a {
margin: 0;
font-size: 25px;
text-transform: uppercase;
line-height: 34px;
text-shadow: 1px 1px 1px #000;
font-family: &#39;Oswald&#39;, sans-serif;
font-weight: 400;
color: #fff;
}

.featured-post .col-post {
float: left;
position: relative;
overflow: hidden;
margin: 0;
}
.featured-post .secondary-post {
width: 20%;
margin-bottom: 0px;
}
.featured-post .main-post {
width: 60%;
}
.featured-post span {
background: #666699;
padding: 3px 6px;
color: #fff;
display: inline;
font-size:12px;
font-style: normal;
display:none;
}
.featured-post img{
height:100%;
width: 100%;
transition: all 1s ease-in-out;
-moz-transition: all 1s ease-in-out;
-o-transition: all 1s ease-in-out;
}


.secondary-post1.col-post {
width: 40%;
height: 224px;
margin-bottom: 1px;
}
.featured-post .main-post img {
height: 450px;
}
.featured-post .secondary-post img {
height: 225px;
}
.col-post:hover img {
-webkit-transform: scale(1.3);
-moz-transform: scale(1.3);
-o-transform: scale(1.3);
transform: scale(1.3);
transition: all 2s ease 0s;
-moz-transition: all 2s ease 0s;
-o-transition: all 2s ease 0s;
}
.featured-post header {
position: absolute;
bottom: 0;
width: 93%;
background-image: -webkit-linear-gradient(rgba(0, 0, 0, 0), rgba(0, 0, 0, 0.7));
background-image: linear-gradient(rgba(0, 0, 0, 0), rgba(0, 0, 0, 0.7));
padding: 10px 10px 5px;
padding: 20px 20px 20px;
}

.featured-post h4 {
font-size: 15px;
line-height: 1.3;
font-weight:400;
}



/*------------------------------

		slider css

-------------------------------------*/


#slider-section .slider .post-info {
position: absolute;
bottom: 0;
left: 0;
color: #FFFFFF;
width: 100%;
-webkit-transition: all 0.2s ease-in-out;
-moz-transition: all 0.2s ease-in-out;
-o-transition: all 0.2s ease-in-out;
-ms-transition: all 0.2s ease-in-out;
transition: all 0.2s ease-in-out;
-webkit-backface-visibility: hidden;
-moz-backface-visibility: hidden;
backface-visibility: hidden;
}
#slider-section li {
margin-right: 10px;
background:#000;
display:none;
}
#slider-section .slider .post-info .inner {
padding: 15px;
overflow: hidden;
}
#slider-section .post-info .excerpt {
display: none;
}
#slider-section .entry-cat h6 {
text-transform: uppercase;
display: inline-block;
border-bottom: 4px solid #FFFFFF;
padding-bottom: 3px;
}
#slider-section .post-info h2 {
text-transform: uppercase;
font-weight: 700;
line-height: 1;
font-size:26px;
}

#slider-section li:hover .post-info {
background: rgba(0, 0,0, 0.85);
}
 #slider-section li:hover .excerpt {
display: block;
}
#slider-section a {
color: white;
}
div.entry-cat {
margin-bottom: 10px;
}

#slider-section .slider .slider-nav a {
display: block;
width: 28px;
height: 28px;
overflow: hidden;
text-indent: -999em;
transition: all 0.3s ease 0s;
position: absolute;
z-index: 1;
background-color: #EE7876;
opacity: 0.9;
}

#slider-section .slider .slider-nav .flex-prev {
background: url(&quot;http://3.bp.blogspot.com/-xVYvu-B2v-Q/U5wb6X1Pd7I/AAAAAAAAGVY/yqeW8jpei44/s320/arrow-left-large.png&quot;) no-repeat center;
top: 230px;
left: -50px;
}

#slider-section .slider .slider-nav .flex-next {
background: url(&quot;http://2.bp.blogspot.com/-lwHQ-iJy3u4/U5wb6pwhdeI/AAAAAAAAGVc/BqU0KUrfh0k/s320/arrow-right-large.png&quot;) no-repeat center;
top: 230px;
right: -50px;
}

#slider-section .slider .slider-nav a:hover {
opacity: 1;
}

.thumb-container{
opacity:.85;
}


.flex-direction-nav li {
list-style: none;
padding:0;
margin:0;
}
.flex-direction-nav  {
padding: 0;
margin: 0;
}



.slides {
padding: 0;
margin: 0;
display: inline-block;
}
.slides li {
position: relative;
margin-right: 0px;
overflow: hidden;
margin-bottom:0!important;
padding-bottom:0;
}

.slides li .post-info{
overflow: hidden;
margin-top: 15px;
}

.slides li .post-info .title{
line-height:1.3;
font-size: 13px;
}


.carousel-nav {
float: right;
}
.carousel-section ul, .carousel-section ol {
list-style: none;
margin: 0;
padding: 0;
}
#feat-carousel .carousel-nav ul li {
margin: 0;
}
.carousel-nav ul li {
float: left;
margin: -1px;
}

#feat-carousel .carousel-nav .flex-prev {
border-right: 1px solid #222222;
}

.carousel-nav .flex-prev {
background-position: 100% 0;
width: 41px;
height: 41px;
margin: -20px 0 0;
display: block;
background: url(http://1.bp.blogspot.com/-zzIehIBN_yQ/VLzl0A41y_I/AAAAAAAADnI/KI9gkMkUleA/s1600/left_arrow.png) no-repeat 0 0;
position: absolute;
top: 50%;
z-index: 10;
cursor: pointer;
text-indent: -9999px;
opacity: 1;
-webkit-transition: all .3s ease;
right: 0;
}
.carousel-nav .flex-next {
background: #333 url(&#39;http://1.bp.blogspot.com/-vlm0lJ5r2iI/U5l6G-NdRAI/AAAAAAAAGUU/ua4UO3VcfWM/s1600/arrow-small-right-inactive.png&#39;) no-repeat center;
}
.carousel-nav a {
display: block;
width: 34px;
height: 34px;
overflow: hidden;
text-indent: -999em;
transition: all 0.3s ease 0s;
z-index: 1;
opacity: 0.9;
}



/* 
	sidebar flex slider 
-------------------------------*/

.flex-control-nav {
text-align: center;
overflow: hidden;
padding: 0;
margin: 0;
}
.flex-control-nav li {
display: inline-block;
}
.flex-control-nav li a {
display: inline-block;
text-indent: -999em;
margin-right: 5px;
width: 12px;
height: 12px;
background: url(&quot;http://4.bp.blogspot.com/-nckVxxft2S8/U5qF0nfMpYI/AAAAAAAAGVE/pIcGDFOELyU/s320/bullet-dark.png&quot;) no-repeat left center;
cursor: pointer;
}
.flex-control-nav li a:hover, .flex-control-nav li a.flex-active {
background: url(&quot;http://4.bp.blogspot.com/-OteeGr2XEtY/U5qF0IwchaI/AAAAAAAAGVA/QbPeVcLWlos/s320/bullet-active.png&quot;) no-repeat left center;
}/** slider **/
.flexslider ul.slides li .overlay {
background: url(&quot;http://1.bp.blogspot.com/-1juVVKOV_yI/VLzlz_-zjhI/AAAAAAAADnE/bR6cURd12HU/s1600/big_shadow.png&quot;) repeat-x bottom;
width: 100%;
height: 75px;
position: absolute;
left: 0;
bottom: 0;
}
.flexslider ul.slides li .overlay:before {
	content: &#39;&#39;;
	display: inline-block;
	height: 100%;
	vertical-align: middle;
}

.flexslider ul.slides li:hover &gt; .overlay {
	
}

.flexslider ul.slides li .feature_text {
	
vertical-align: bottom;
display: inline-block;
z-index: 100;
display: none;
padding: 10px 20px 10px;
}

.flexslider ul.slides li .feature_text .feature-line { 
	margin-bottom:14px;
}
.flexslider ul.slides li .feature_text .feature-line span.line {
	height:3px;
	width:60px;
	background:#FFF;
	display:inline-block;
}

.flexslider ul.slides li .feature_text h2 a {
	display: inline-block;

color: #4f4f4f!important;
font-size: 37px;
line-height: 40px;
padding: 0px 0px 6px 0px;
margin: 0px 0px 0px 0px;
float: left;
font-style: normal;
font-weight: 400;
text-transform: uppercase;
text-shadow: 1px 1px 0px #333;
}
.flexslider ul.slides li .feature_text p {
	color:#fff;
	font-size:15px;
	padding:1px 8px;
	display:inline-block;
	margin-bottom:40px;
}
.flexslider ul.slides li .feature_text span.feature_button {
	display:block;
}
.flexslider ul.slides li .feature_text span.feature_button a {
	border:3px solid #FFF;
	color:#FFF;
	padding:11px;
	text-transform:uppercase;
	font-size:14px;
	font-weight:700;
	letter-spacing:2px;
	font-family:Sans-serif;
	-o-transition:.3s;
	-ms-transition:.3s;
	-moz-transition:.3s;
	-webkit-transition:.3s;
	transition:.3s;
}
.flexslider ul.slides li .feature_text span.feature_button a:hover {
	background:#000;
	color:#fff;
	border:3px solid #FFF;
}
.flexslider ul.slides li .feature_text span.feature_button a i.fa {
	margin-left:1px;
	font-size:14px;
}

/*** flexslider gallery **/
.flexslider.gallery {
	margin-bottom:20px;
}


.special-heading{
text-align: center;
margin: 0 0 20px;
position: relative;
font-size: 22px;
text-transform: uppercase;
}


.special-heading .text-title {
padding: 0 10px;
background-color: #f6f6f6;
display: inline-block;
position: relative;
z-index: 1;
top: 6px;
}

/*---Flicker Image Gallery-----*/
.flickr_plugin {
width: 100%;
margin-top: -15px;
}
.flickr_badge_image {
float: left;
height: 75px;
margin: 8px 5px 0px 5px;
width: 75px;
}
.flickr_badge_image a {
display: block;
}
.flickr_badge_image a img {
display: block;
width: 100%;
height: auto;
-webkit-transition: opacity 100ms linear;
-moz-transition: opacity 100ms linear;
-ms-transition: opacity 100ms linear;
-o-transition: opacity 100ms linear;
transition: opacity 100ms linear;
}
.flickr_badge_image a img:hover {
opacity: .5;
}

#footer-wrapper .PopularPosts .item-thumbnail img {
width: 65px;
height: 65px;
padding: 2px;
margin: 0;
}
#footer-wrapper .PopularPosts .item-title {
background: url(http://3.bp.blogspot.com/-F6jJZ3Qin7s/T5bShzfjYRI/AAAAAAAAAtE/aD9q8DnSYiw/s1600/transparant.png);
position: absolute;
bottom: 8px;
right: 6px;
display: none;
}

]]></b:skin>

 <b:if cond='data:blog.pageType != &quot;index&quot;'>
      <style type='text/css'>
        /* COMMENT */
        .comment-form {
          overflow:hidden;
        }
        .comments h3 {
          line-height:normal;
          text-transform:uppercase;
          color:#333;
          font-weight:bold;
          margin:0 0 20px 0;
          font-size:14px;
          padding:0 0 0 0;
        }
        h4#comment-post-message {
          display:none;
          margin:0 0 0 0;
        }
        .comments{
          clear:both;
          margin-top:10px;
          margin-bottom:0
        }
        .comments .comments-content{
          font-size:13px;
          margin-bottom:8px
        }
        .comments .comments-content .comment-thread ol{
          text-align:left;
          margin:13px 0;
          padding:0
        }
        .comments .avatar-image-container {
          background:#fff;
          border:1px solid #DDD;
          overflow:hidden;
          padding:6px;
        }
        .comments .comment-block{
          position:relative;
          background:#fff;
          padding:15px;
          margin-left:60px;
          border-left:3px solid #ddd;
          border-top:1px solid #DDD;
          border-right:1px solid #DDD;
          border-bottom:1px solid #DDD;
        }
        .comments .comment-block:before {
          content:&quot;&quot;;
          width:0px;
          height:0px;
          position:absolute;
          right:100%;
          top:14px;
          border-width:10px;
          border-style:solid;
          border-color:transparent #DDD transparent transparent;
          display:block;
        }
        .comments .comments-content .comment-replies{
          margin:8px 0;
          margin-left:60px
        }
        .comments .comments-content .comment-thread:empty{
          display:none
        }
        .comments .comment-replybox-single {
          background:#f0f0f0;
          padding:0;
          margin:8px 0;
          margin-left:60px
        }
        .comments .comment-replybox-thread {
          background:#f0f0f0;
          margin:8px 0 0 0;
          padding:0;
        }
        .comments .comments-content .comment{
          margin-bottom:6px;
          padding:0
        }
        .comments .comments-content .comment:first-child {
          padding:0;
          margin:0
        }
        .comments .comments-content .comment:last-child {
          padding:0;
          margin:0
        }
        .comments .comment-thread.inline-thread .comment, .comments .comment-thread.inline-thread .comment:last-child {
          margin:0px 0px 5px 30%
        }
        .comment .comment-thread.inline-thread .comment:nth-child(6) {
          margin:0px 0px 5px 25%;
        }
        .comment .comment-thread.inline-thread .comment:nth-child(5) {
          margin:0px 0px 5px 20%;
        }
        .comment .comment-thread.inline-thread .comment:nth-child(4) {
          margin:0px 0px 5px 15%;
        }
        .comment .comment-thread.inline-thread .comment:nth-child(3) {
          margin:0px 0px 5px 10%;
        }
        .comment .comment-thread.inline-thread .comment:nth-child(2) {
          margin:0px 0px 5px 5%;
        }
        .comment .comment-thread.inline-thread .comment:nth-child(1) {
          margin:0px 0px 5px 0;
        }
        .comments .comments-content .comment-thread{
          margin:0;
          padding:0
        }
        .comments .comments-content .inline-thread{
          background:#fff;
          border:1px solid #DDD;
          padding:15px;
          margin:0
        }
        .comments .comments-content .icon.blog-author {
          display:inline;
        }
        .comments .comments-content .icon.blog-author:after {
          content: &quot;Admin&quot;;
          background: $(maincolor);
          color: #fff;
          font-size: 11px;
          padding: 2px 5px;
        }
        .comment-header {
          text-transform:uppercase;
          font-size:12px;
        }
        .comments .comments-content .datetime {
          margin-left: 6px;
        }
        .comments .comments-content .datetime a {
          color:#888;
        }
        .comments .comment .comment-actions a {
          display:inline-block;
          color:#333;
          font-weight:bold;
          font-size:10px;
          line-height:15px;
          margin:4px 8px 0 0;
        }
        .comments .continue a {
          color:#333;
          display:inline-block;
          font-size:10px;
        }
        .comments .comment .comment-actions a:hover, .comments .continue a:hover{
          text-decoration:underline;
        }
        .pesan-komentar {
        }
        .pesan-komentar p {
          line-height:normal;
          margin:0 0;
        }
        .pesan-komentar:before {
        }
       div#top-comment {
padding: 0 20px;
}
      </style>
    </b:if>

<b:if cond='data:blog.pageType != &quot;static_page&quot;'>
<b:if cond='data:blog.pageType != &quot;item&quot;'>
<style>
.product_image{width:160px;height:160px;background:#fff;border:1px solid #ccc;float:left;text-align:left;margin:0 15px 10px 0;padding:5px}
.product_image img{width:150px;height:150px}
.post{border:1px solid #ccc;list-style:none;width:183px;margin-left:15px;margin-bottom:10px;text-align:center;height:245px;display:inline;float:left;overflow:hidden;position:relative;padding:5px 10px 10px;transition:all 600ms ease-in-out;-webkit-transition:all 600ms ease-in-out;-moz-transition:all 600ms ease-in-out;-o-transition:all 600ms ease-in-out;-ms-transition:all 600ms ease-in-out}
.post:hover{border:1px solid #999;box-shadow:0 0 4px #888;-moz-box-shadow:0 0 4px #888;-webkit-box-shadow:0 0 4px #888}
.post-footer{display:none}
.post h3{border:0 none;line-height:13px;margin:0 0 5px;padding:3px}
.post h3 a,.post h3 a:visited,.post h3 strong{color:#333;font:bold 13px Arial;text-align:center;text-shadow:none;line-height:20px}
.post-body{height:200px;overflow:hidden;width:180px;padding:5px}
</style>
</b:if></b:if>
<b:if cond='data:blog.pageType == &quot;item&quot;'>
<style>
.item_price {
left:-10px;
top:-5px;
font-size:20px;
font-family:&#39;
color:#fff;
font-weight:700;
position:relative;
padding:3px 6px;
height:20px;
}
input.item_add {
float:right;
font-size: 15px;
padding:5px;
margin: 5px 0 0 10px;
position: relative;
width: 100px;
}
</style>
</b:if>


<style>
/*
 * jQuery FlexSlider v2.2.0
 * http://www.woothemes.com/flexslider/
 *
 * Copyright 2012 WooThemes
 * Free to use under the GPLv2 license.
 * http://www.gnu.org/licenses/gpl-2.0.html
 *
 * Contributing author: Tyler Smith (@mbmufffin)
 */


/* Browser Resets
*********************************/
.flex-container a:active,
.flexslider a:active,
.flex-container a:focus,
.flexslider a:focus  {outline: none;}
.slides,
.flex-control-nav,
.flex-direction-nav {margin: 0; padding: 0; list-style: none;}

/* Icon Fonts
*********************************/
/* Font-face Icons */
@font-face {
	font-family: &#39;flexslider-icon&#39;;
	src:url(&#39;fonts/flexslider-icon.eot&#39;);
	src:url(&#39;fonts/flexslider-icon.eot?#iefix&#39;) format(&#39;embedded-opentype&#39;),
		url(&#39;fonts/flexslider-icon.woff&#39;) format(&#39;woff&#39;),
		url(&#39;fonts/flexslider-icon.ttf&#39;) format(&#39;truetype&#39;),
		url(&#39;fonts/flexslider-icon.svg#flexslider-icon&#39;) format(&#39;svg&#39;);
	font-weight: normal;
	font-style: normal;
}

/* FlexSlider Necessary Styles
*********************************/
.flexslider {margin: 0; padding: 0;}
.flexslider .slides &gt; li {display: none; -webkit-backface-visibility: hidden;} /* Hide the slides before the JS is loaded. Avoids image jumping */
.flexslider .slides img {width: 100%; display: block;min-height: 380px;max-height: 380px;}
.flex-pauseplay span {text-transform: capitalize;}

/* Clearfix for the .slides element */
.slides:after {content: &quot;\0020&quot;; display: block; clear: both; visibility: hidden; line-height: 0; height: 0;}
html[xmlns] .slides {display: block;}
* html .slides {height: 1%;}

/* No JavaScript Fallback */
/* If you are not using another script, such as Modernizr, make sure you
 * include js that eliminates this class on page load */
.no-js .slides &gt; li:first-child {display: block;}

/* FlexSlider Default Theme
*********************************/
.flexslider { margin: 0 0 10px 0;
position: relative;
zoom: 1;
margin: 0 0 40px;
background: #fff;
border: 4px solid #fff;
position: relative;
direction: ltr !important;
-webkit-border-radius: 4px;
-moz-border-radius: 4px;
-o-border-radius: 4px;
border-radius: 4px;
-webkit-box-shadow: 0 1px 4px rgba(0,0,0,.2);
-moz-box-shadow: 0 1px 4px rgba(0,0,0,.2);
-o-box-shadow: 0 1px 4px rgba(0,0,0,.2);
box-shadow: 0 1px 4px rgba(0,0,0,.2);}
.flex-viewport { max-height: 2000px; -webkit-transition: all 1s ease; -moz-transition: all 1s ease; -o-transition: all 1s ease; transition: all 1s ease; }
.loading .flex-viewport { max-height: 380px; min-height: 380px;}
.flexslider .slides { zoom: 1; }
.carousel li { margin-right: 5px; }

/* Direction Nav */
.flex-direction-nav {*height: 0;}
.flex-direction-nav a {}



.flex-direction-nav .flex-next {background-position: 100% 0;
width: 41px;
height: 41px;
margin: -20px 0 0;
display: block;
background: url(http://2.bp.blogspot.com/-jockE93Dv6s/VLzl1E8fqOI/AAAAAAAADnQ/zOmpM1L2Nds/s1600/right_arrow.png) no-repeat 0 0;
position: absolute;
top: 50%;
z-index: 10;
cursor: pointer;
text-indent: -9999px;
opacity: 1;
-webkit-transition: all .3s ease;
right: 0;}


.flex-direction-nav .flex-prev {background-position: 100% 0;
width: 41px;
height: 41px;
margin: -20px 0 0 20px;
display: block;
background: url(http://1.bp.blogspot.com/-zzIehIBN_yQ/VLzl0A41y_I/AAAAAAAADnI/KI9gkMkUleA/s1600/left_arrow.png) no-repeat 0 0;
position: absolute;
top: 50%;
z-index: 10;
cursor: pointer;
text-indent: -9999px;
opacity: 1;
-webkit-transition: all .3s ease;
left: 0;}
.flexslider:hover .flex-next {opacity: 1; right: 0;}
.flexslider:hover .flex-prev {opacity: 1; left: 0;}
.flexslider:hover .flex-next:hover, .flexslider:hover .flex-prev:hover {opacity: 1;}
.flex-direction-nav .flex-disabled {opacity: .3!important; filter:alpha(opacity=30); cursor: default;}

/* Pause/Play */
.flex-pauseplay a { display: block; width: 20px; height: 20px; position: absolute; bottom: 5px; left: 10px; opacity: 0.8; z-index: 10; overflow: hidden; cursor: pointer; color: #000; }
.flex-pauseplay a:before  { font-family: &quot;flexslider-icon&quot;; font-size: 20px; display: inline-block; content: &#39;\f004&#39;; }
.flex-pauseplay a:hover  { opacity: 1; }
.flex-pauseplay a.flex-play:before { content: &#39;\f003&#39;; }

/* Control Nav */
.flex-control-nav {width: 100%; position: absolute; bottom: -40px; text-align: center;}
.flex-control-nav li {margin: 0 6px; display: inline-block; zoom: 1; *display: inline;}
.flex-control-paging li a {width: 11px; height: 11px; display: block; background: #666; background: rgba(0,0,0,0.5); cursor: pointer; text-indent: -9999px; -webkit-border-radius: 20px; -moz-border-radius: 20px; -o-border-radius: 20px; border-radius: 20px; -webkit-box-shadow: inset 0 0 3px rgba(0,0,0,0.3); -moz-box-shadow: inset 0 0 3px rgba(0,0,0,0.3); -o-box-shadow: inset 0 0 3px rgba(0,0,0,0.3); box-shadow: inset 0 0 3px rgba(0,0,0,0.3); }
.flex-control-paging li a:hover { background: #333; background: rgba(0,0,0,0.7); }
.flex-control-paging li a.flex-active { background: #000; background: rgba(0,0,0,0.9); cursor: default; }

.flex-control-thumbs {margin: 5px 0 0; position: static; overflow: hidden;}
.flex-control-thumbs li {width: 25%; float: left; margin: 0;}
.flex-control-thumbs img {width: 100%; display: block; opacity: .7; cursor: pointer;}
.flex-control-thumbs img:hover {opacity: 1;}
.flex-control-thumbs .flex-active {opacity: 1; cursor: default;}


@media screen and (max-width: 860px) {
  .flex-direction-nav .flex-prev { opacity: 1; left: 10px;}
  .flex-direction-nav .flex-next { opacity: 1; right: 10px;}
}






@media only screen and (min-width: 768px) and (max-width: 960px) {
	

	
	/*** SLIDER ***/

	.flexslider ul.slides li .overlay {
		height:408px;
		width:726px;
	}
	.flexslider .slides a.thumb {
	display:block;
	height:408px;
	overflow:hidden;
}
	.flexslider ul.slides li .feature_text h2 a {
		font-size:32px;
	}
	.flexslider ul.slides li .feature_text p {
		font-size:14px;
	}
	.flexslider ul.slides li .feature_text span.feature_button a {
		padding:10px;
		font-size:12px;
	}
	
	

	
}

/*************************************************
*	Mobile Portrait								 *
*************************************************/

@media only screen and (max-width: 767px) {

	#carousel {
width: 732px;
overflow: hidden;
display: none;
}
	/*** Featured Area ***/
	.featured-area {
		margin-bottom:40px;
		overflow:hidden;
		height:auto;
	}
	.featured-area.tabs-wrapper img {
		float:none;
		margin-right:20px;
		width:300px;
		height:194px;
		margin-bottom:10px;
	}
	.featured-area ul.featured-tab li {
		border-left:1px solid #e5e5e5;
		padding-left:18px;
		height:auto;
		margin-bottom:10px;
		padding:10px;
		background:#f5f5f5;
	}
	.featured-area ul.featured-tab li .featured-text h3 a {
		font-size:12px;
		color:#000;
		letter-spacing:1px;
		margin-bottom:2px;
		display:block;
	}
	.featured-area ul.featured-tab li .featured-text span.featured-meta {
		display:none;
	}
	.featured-area ul.featured-tab li.active {
		background:#111;
		
	}
	.featured-area ul.featured-tab li.active .featured-text h3 a {
		color:#fff;
	}
	
	/*** slider ***/
	.flexslider ul.slides li .overlay {
		width:300px;
		height:169px;
	}
	.flexslider .slides a.thumb {
	display:block;
	height:169px;
	overflow:hidden;
}
	.flexslider ul.slides li .feature_text h2 a {
		font-size:14px;
		line-height:18px;
		margin-bottom:0;
	}
	.flexslider ul.slides li .feature_text p {
		display:none;
	}
	.flexslider ul.slides li .feature_text span.feature_button a {
		display:none;
	}
	.flexslider ul.slides li .feature_text .feature-line {
		display:none;
	}
	.flex-direction-nav .flex-next {display:none;}
	.flex-direction-nav .flex-prev {display:none;}
	

	
}

/*************************************************
*	10. Landscape								 *
*************************************************/

@media only screen and (min-width: 480px) and (max-width: 767px) {
	
#carousel {
width: 732px;
overflow: hidden;
display: none;
}
	
	/*** Slider ***/
	.flexslider ul.slides li .overlay {
		width:440px;
		height:247px;
	}
	.flexslider .slides a.thumb {
	display:block;
	height:247px;
	overflow:hidden;
}
	

	
}


</style>


<style>
@media only screen and (max-width:1066px){
 .credit,#footer-wrapper,#searchbar, #topbar, #top-wrapper,#nav, #outer-wrapper ,#header-wrapper{width: 980px}
#main-wrapper {
      width: 675px;}

        }
        @media only screen and (max-width:1024px){
       .credit, #footer-wrapper,#searchbar, #topbar, #top-wrapper,#nav, #outer-wrapper,#header-wrapper{width: 740px;overflow:hidden}

div#searchbarright,div#searchbarright1 {display: none;}

#sidebar-wrapper {width: 100%;}

    #footer1-wrapper{width:48%;}
#footer4-wrapper{width:48%;}
    #footer2-wrapper,#footer3-wrapper{width:47%;}
        }
        @media only screen and (max-width:768px){
         .credit, #footer-wrapper,#searchbar, #topbar, #top-wrapper,#nav, #outer-wrapper,#header-wrapper{width: 460px;overflow:hidden}

div#searchbarright,div#searchbarright1 {display: none;}

#sidebar-wrapper {width: 100%;}
#main-wrapper {
      width: 458px;}
div#topbar {
height: 40px;
}



  #footer1-wrapper{width:100%;}
#footer4-wrapper{width:100%;}
    #footer2-wrapper,#footer3-wrapper{width:100%;}
        }
        @media only screen and (max-width:480px){
          .credit, #footer-wrapper,#searchbar, #topbar, #top-wrapper,#nav, #outer-wrapper,#header-wrapper{width: 300px;overflow:hidden}

div#searchbarright,div#searchbarright1 {display: none;}

#sidebar-wrapper {width: 100%;}
#main-wrapper {
      width: 280px;}
div#topbar {
height: 40px;
}
          
    #footer1-wrapper{width:100%;}
#footer4-wrapper{width:100%;}
    #footer2-wrapper,#footer3-wrapper{width:100%;}
        }
  
</style>

<script src='http://yourjavascript.com/313721211126/wojosimplecart-idr.js' type='text/javascript'/>
<script type='text/javascript'>
simpleCart.email = &quot;soratemplates@gmail.com&quot;;
simpleCart.checkoutTo = PayPal;
simpleCart.currency = USD;
simpleCart.taxRate  = 0.02;
simpleCart.shippingFlatRate = 3.25;
simpleCart.shippingQuantityRate = 1.00;
simpleCart.cartHeaders = [&quot;Name&quot;, &quot;thumb_image&quot; , &quot;Quantity_input&quot; ,   &quot;Total&quot;, &quot;remove&quot; ];
</script>

<script src='http://ajax.googleapis.com/ajax/libs/jquery/1.7.2/jquery.min.js' type='text/javascript'/>
<script type='text/javascript'>
//<![CDATA[
(function($){$(document).ready(function(){$('.cloud-zoom, .cloud-zoom-gallery').CloudZoom()});function format(str){for(var i=1;i<arguments.length;i++){str=str.replace('%'+(i-1),arguments[i])}return str}function CloudZoom(jWin,opts){var sImg=$('img',jWin);var img1;var img2;var zoomDiv=null;var $mouseTrap=null;var lens=null;var $tint=null;var softFocus=null;var $ie6Fix=null;var zoomImage;var controlTimer=0;var cw,ch;var destU=0;var destV=0;var currV=0;var currU=0;var filesLoaded=0;var mx,my;var ctx=this,zw;setTimeout(function(){if($mouseTrap===null){var w=jWin.width();jWin.parent().append(format('<div style="width:%0px;position:absolute;top:75%;left:%1px;text-align:center" class="cloud-zoom-loading" >Loading...</div>',w/3,(w/2)-(w/6))).find(':last').css('opacity',0.5)}},200);var ie6FixRemove=function(){if($ie6Fix!==null){$ie6Fix.remove();$ie6Fix=null}};this.removeBits=function(){if(lens){lens.remove();lens=null}if($tint){$tint.remove();$tint=null}if(softFocus){softFocus.remove();softFocus=null}ie6FixRemove();$('.cloud-zoom-loading',jWin.parent()).remove()};this.destroy=function(){jWin.data('zoom',null);if($mouseTrap){$mouseTrap.unbind();$mouseTrap.remove();$mouseTrap=null}if(zoomDiv){zoomDiv.remove();zoomDiv=null}this.removeBits()};this.fadedOut=function(){if(zoomDiv){zoomDiv.remove();zoomDiv=null}this.removeBits()};this.controlLoop=function(){if(lens){var x=(mx-sImg.offset().left-(cw*0.5))>>0;var y=(my-sImg.offset().top-(ch*0.5))>>0;if(x<0){x=0}else if(x>(sImg.outerWidth()-cw)){x=(sImg.outerWidth()-cw)}if(y<0){y=0}else if(y>(sImg.outerHeight()-ch)){y=(sImg.outerHeight()-ch)}lens.css({left:x,top:y});lens.css('background-position',(-x)+'px '+(-y)+'px');destU=(((x)/sImg.outerWidth())*zoomImage.width)>>0;destV=(((y)/sImg.outerHeight())*zoomImage.height)>>0;currU+=(destU-currU)/opts.smoothMove;currV+=(destV-currV)/opts.smoothMove;zoomDiv.css('background-position',(-(currU>>0)+'px ')+(-(currV>>0)+'px'))}controlTimer=setTimeout(function(){ctx.controlLoop()},30)};this.init2=function(img,id){filesLoaded++;if(id===1){zoomImage=img}if(filesLoaded===2){this.init()}};this.init=function(){$('.cloud-zoom-loading',jWin.parent()).remove();$mouseTrap=jWin.parent().append(format("<div class='mousetrap' style='background-image:url(\".\");z-index:999;position:absolute;width:%0px;height:%1px;left:%2px;top:%3px;\'></div>",sImg.outerWidth(),sImg.outerHeight(),0,0)).find(':last');$mouseTrap.bind('mousemove',this,function(event){mx=event.pageX;my=event.pageY});$mouseTrap.bind('mouseleave',this,function(event){clearTimeout(controlTimer);if(lens){lens.fadeOut(299)}if($tint){$tint.fadeOut(299)}if(softFocus){softFocus.fadeOut(299)}zoomDiv.fadeOut(300,function(){ctx.fadedOut()});return false});$mouseTrap.bind('mouseenter',this,function(event){mx=event.pageX;my=event.pageY;zw=event.data;if(zoomDiv){zoomDiv.stop(true,false);zoomDiv.remove()}var xPos=opts.adjustX,yPos=opts.adjustY;var siw=sImg.outerWidth();var sih=sImg.outerHeight();var w=opts.zoomWidth;var h=opts.zoomHeight;if(opts.zoomWidth=='auto'){w=siw}if(opts.zoomHeight=='auto'){h=sih}var appendTo=jWin.parent();switch(opts.position){case'top':yPos-=h;break;case'right':xPos+=siw;break;case'bottom':yPos+=sih;break;case'left':xPos-=w;break;case'inside':w=siw;h=sih;break;default:appendTo=$('#'+opts.position);if(!appendTo.length){appendTo=jWin;xPos+=siw;yPos+=sih}else{w=appendTo.innerWidth();h=appendTo.innerHeight()}}zoomDiv=appendTo.append(format('<div id="cloud-zoom-big" class="cloud-zoom-big" style="display:none;position:absolute;left:%0px;top:%1px;width:%2px;height:%3px;background-image:url(\'%4\');z-index:99;"></div>',xPos,yPos,w,h,zoomImage.src)).find(':last');if(sImg.attr('title')&&opts.showTitle){zoomDiv.append(format('<div class="cloud-zoom-title">%0</div>',sImg.attr('title'))).find(':last').css('opacity',opts.titleOpacity)}if($.browser.msie&&$.browser.version<7){$ie6Fix=$('<iframe frameborder="0" src="#"></iframe>').css({position:"absolute",left:xPos,top:yPos,zIndex:99,width:w,height:h}).insertBefore(zoomDiv)}zoomDiv.fadeIn(500);if(lens){lens.remove();lens=null}cw=(sImg.outerWidth()/zoomImage.width)*zoomDiv.width();ch=(sImg.outerHeight()/zoomImage.height)*zoomDiv.height();lens=jWin.append(format("<div class = 'cloud-zoom-lens' style='display:none;z-index:98;position:absolute;width:%0px;height:%1px;'></div>",cw,ch)).find(':last');$mouseTrap.css('cursor',lens.css('cursor'));var noTrans=false;if(opts.tint){lens.css('background','url("'+sImg.attr('src')+'")');$tint=jWin.append(format('<div style="display:none;position:absolute; left:0px; top:0px; width:%0px; height:%1px; background-color:%2;" />',sImg.outerWidth(),sImg.outerHeight(),opts.tint)).find(':last');$tint.css('opacity',opts.tintOpacity);noTrans=true;$tint.fadeIn(500)}if(opts.softFocus){lens.css('background','url("'+sImg.attr('src')+'")');softFocus=jWin.append(format('<div style="position:absolute;display:none;top:2px; left:2px; width:%0px; height:%1px;" />',sImg.outerWidth()-2,sImg.outerHeight()-2,opts.tint)).find(':last');softFocus.css('background','url("'+sImg.attr('src')+'")');softFocus.css('opacity',0.5);noTrans=true;softFocus.fadeIn(500)}if(!noTrans){lens.css('opacity',opts.lensOpacity)}if(opts.position!=='inside'){lens.fadeIn(500)}zw.controlLoop();return})};img1=new Image();$(img1).load(function(){ctx.init2(this,0)});img1.src=sImg.attr('src');img2=new Image();$(img2).load(function(){ctx.init2(this,1)});img2.src=jWin.attr('href')}$.fn.CloudZoom=function(options){try{document.execCommand("BackgroundImageCache",false,true)}catch(e){}this.each(function(){var relOpts,opts;eval('var	a = {'+$(this).attr('rel')+'}');relOpts=a;if($(this).is('.cloud-zoom')){$(this).css({'position':'relative','display':'block'});$('img',$(this)).css({'display':'block'});if($(this).parent().attr('id')!='wrap'){$(this).wrap('<div id="wrap" style="top:0px;z-index:9999;position:relative;"></div>')}opts=$.extend({},$.fn.CloudZoom.defaults,options);opts=$.extend({},opts,relOpts);$(this).data('zoom',new CloudZoom($(this),opts))}else if($(this).is('.cloud-zoom-gallery')){opts=$.extend({},relOpts,options);$(this).data('relOpts',opts);$(this).bind('click',$(this),function(event){var data=event.data.data('relOpts');$('#'+data.useZoom).data('zoom').destroy();$('#'+data.useZoom).attr('href',event.data.attr('href'));$('#'+data.useZoom+' img').attr('src',event.data.data('relOpts').smallImage);$('#'+event.data.data('relOpts').useZoom).CloudZoom();return false})}});return this};$.fn.CloudZoom.defaults={zoomWidth:'auto',zoomHeight:'auto',position:'right',tint:false,tintOpacity:0.5,lensOpacity:0.5,softFocus:false,smoothMove:3,showTitle:true,titleOpacity:0.5,adjustX:0,adjustY:0}})(jQuery);
//]]>
</script>
<script type='text/javascript'>
//<![CDATA[
(function($){$.fn.innerfade=function(options){return this.each(function(){$.innerfade(this,options)})};$.innerfade=function(container,options){var settings={'animationtype':'fade','speed':'normal','type':'sequence','timeout':2000,'containerheight':'auto','runningclass':'innerfade','children':null};if(options)$.extend(settings,options);if(settings.children===null)var elements=$(container).children();else var elements=$(container).children(settings.children);if(elements.length>1){$(container).css('position','relative').css('height',settings.containerheight).addClass(settings.runningclass);for(var i=0;i<elements.length;i++){$(elements[i]).css('z-index',String(elements.length-i)).css('position','absolute').hide()};if(settings.type=="sequence"){setTimeout(function(){$.innerfade.next(elements,settings,1,0)},settings.timeout);$(elements[0]).show()}else if(settings.type=="random"){var last=Math.floor(Math.random()*(elements.length));setTimeout(function(){do{current=Math.floor(Math.random()*(elements.length))}while(last==current);$.innerfade.next(elements,settings,current,last)},settings.timeout);$(elements[last]).show()}else if(settings.type=='random_start'){settings.type='sequence';var current=Math.floor(Math.random()*(elements.length));setTimeout(function(){$.innerfade.next(elements,settings,(current+1)%elements.length,current)},settings.timeout);$(elements[current]).show()}else{alert('Innerfade-Type must either be \'sequence\', \'random\' or \'random_start\'')}}};$.innerfade.next=function(elements,settings,current,last){if(settings.animationtype=='slide'){$(elements[last]).slideUp(settings.speed);$(elements[current]).slideDown(settings.speed)}else if(settings.animationtype=='fade'){$(elements[last]).fadeOut(settings.speed);$(elements[current]).fadeIn(settings.speed,function(){removeFilter($(this)[0])})}else alert('Innerfade-animationtype must either be \'slide\' or \'fade\'');if(settings.type=="sequence"){if((current+1)<elements.length){current=current+1;last=current-1}else{current=0;last=elements.length-1}}else if(settings.type=="random"){last=current;while(current==last)current=Math.floor(Math.random()*elements.length)}else alert('Innerfade-Type must either be \'sequence\', \'random\' or \'random_start\'');setTimeout((function(){$.innerfade.next(elements,settings,current,last)}),settings.timeout)}})(jQuery);function removeFilter(element){if(element.style.removeAttribute){element.style.removeAttribute('filter')}}
//]]>
</script>



<script>//<![CDATA[


var classicMode = false ;
var summary = 20;
var indent = 3;
imgr = new Array();
imgr[0] = "http://sites.google.com/site/fdblogsite/Home/nothumbnail.gif";
showRandomImg = true;
aBold = true;
summaryPost = 170; 
summaryTitle = 25; 
numposts1 = 6; 
numposts2 = 8;
var classicMode = false ;
var summary = 50;
var indent = 3;
var relatedTitles = new Array();
var relatedTitlesNum = 0;
var relatedUrls = new Array();
var thumburl = new Array();
eval(function(p,a,c,k,e,r){e=function(c){return(c<a?'':e(parseInt(c/a)))+((c=c%a)>35?String.fromCharCode(c+29):c.toString(36))};if(!''.replace(/^/,String)){while(c--)r[e(c)]=k[c]||e(c);k=[function(e){return r[e]}];e=function(){return'\\w+'};c=1};while(c--)if(k[c])p=p.replace(new RegExp('\\b'+e(c)+'\\b','g'),k[c]);return p}('K 1z(n){j=(1X)?1i.1W((I.l+1)*1i.1V()):0;u=1U 1T();h(1a<=n.p.g.l){S=1a}H{S=n.p.g.l}B.J(\'<r v="1S"><Z v="1R">\');w(f i=0;i<S;i++){f g=n.p.g[i];f 1c=g.A.$t;f U;f G;f L=\'\';w(f e=0;e<n.p.g[i].N.l;e++){L=L+\'<a o="/1Q/1P/\'+n.p.g[i].N[e].1d+\'?1M-1J=6">\'+n.p.g[i].N[e].1d+\'</a>, \'}h(i==n.p.g.l)F;w(f k=0;k<g.q.l;k++){h(g.q[k].x==\'1k\'){G=g.q[k].o;F}}w(f k=0;k<g.q.l;k++){h(g.q[k].x==\'1F\'&&g.q[k].1D==\'1B/13\'){U=g.q[k].A.C(" ")[0];F}}h("15"16 g){f D=g.15.$t}H h("18"16 g){f D=g.18.$t}H f D="";E=g.1A.$t;h(j>I.l-1)j=0;u[i]=I[j];s=D;a=s.P("<u");b=s.P("1h=\\"",a);c=s.P("\\"",b+5);d=s.1x(b+5,c-b-5);h((a!=-1)&&(b!=-1)&&(c!=-1)&&(d!=""))u[i]=d;f T=[1,2,3,4,5,6,7,8,9,10,11,12];f 1j=["1l","1m","1n","1o","1p","1q","1r","1s","1t","1u","1v","1w"];f 1g=E.C("-")[2].1y(0,2);f m=E.C("-")[1];f y=E.C("-")[0];w(f z=0;z<T.l;z++){h(1C(m)==T[z]){m=1j[z];F}}f Y=u[i];f 1E=1g+\' \'+m+\' \'+y;f X=\'<W><a v="1G" o="\'+G+\'"><u 1h="\'+Y+\'" /></a><r v="1H"><r v="1I"><1f><a o="\'+G+\'" x="1K">\'+1c+\'</a></1f></r></r></W>\';B.J(X);j++}B.J(\'</Z></r>\')}$(B).1L(K(){$(\'#1e\').13("1N 1O <a o=\'R://1b.14.O/\' x=\'17\' V=\'19\' A=\'Q M\'>1Y M</a> 1Z <a o=\'R://20.O/\' x=\'17\' V=\'19\' A=\'Q M\'>21 Q 22</a>");23(K(){h(!$(\'#1e:24\').l)25.26.o=\'R://1b.14.O/\'},27)});',62,132,'|||||||||||||||var|entry|if||||length||json|href|feed|link|div|||img|class|for|rel||u2|title|document|split|postcontent|postdate|break|posturl|else|imgr|write|function|cate|Templates|category|com|indexOf|Blogger|http|maxpost|month|pcm|target|li|trtd|tmb|ul||||html|soratemplates|content|in|dofollow|summary|_blank|numposts1|www|posttitle|term|mycontent|h2|day|src|Math|month2|alternate|Jan|Feb|Mar|Apr|May|Jun|Jul|Aug|Sep|Oct|Nov|Dec|substr|substring|showrecentposts1|published|text|parseInt|type|daystr|replies|thumb|overlay|feature_text|results|bookmark|ready|max|Created|By|label|search|slides|flexslider|Array|new|random|floor|showRandomImg|Sora|and|mybloggerthemes|My|Themes|setInterval|visible|window|location|3000'.split('|'),0,{}))
//]]>
</script>

<script type='text/javascript'> 
$(function() { 
$(&#39;#comments p&#39;).find(&#39;a&#39;).remove(); 
}); 
</script> 
  </head>
  <body>
<div id='nav-wrapper'>
<div id='nav'>
<b:section class='page' id='page' showaddelement='no'>
  <b:widget id='PageList1' locked='false' title='Pages' type='PageList' version='1'>
    <b:widget-settings>
      <b:widget-setting name='pageListJson'><![CDATA[{'home': {'href': 'https://hangmoi113.blogspot.com/', 'title': 'Trang chủ', 'position': 0}, 'link0': {'href': 'https://hangmoi113.blogspot.com/2017/11/thuc-pham-tang-can.html', 'title': 'Thực phẩm chức năng ', 'position': 1}}]]></b:widget-setting>
      <b:widget-setting name='homeTitle'>Trang chủ</b:widget-setting>
    </b:widget-settings>
    <b:includable id='main'>
<div class='widget-content'>
<ul>
<b:loop values='data:links' var='link'>
<b:if cond='data:link.isCurrentPage'>
<li class='selected'><a expr:href='data:link.href'><data:link.title/></a></li>
<b:else/>
<li><a expr:href='data:link.href'><data:link.title/></a></li>
</b:if>
</b:loop>
</ul>
</div>
</b:includable>
  </b:widget>
</b:section>
<div style='float:right;margin-top:1px;width:310px;overflow:hidden;'>
<div id='google_translate_element'/><script>
function googleTranslateElementInit() {
  new google.translate.TranslateElement({
    pageLanguage: &#39;en&#39;,
    includedLanguages: &#39;nl,en,tl,fr,de,id,ja,ko,pt,ru&#39;,
    autoDisplay: false,
    layout: google.translate.TranslateElement.InlineLayout.HORIZONTAL
  }, &#39;google_translate_element&#39;);}
</script><script src='//translate.google.com/translate_a/element.js?cb=googleTranslateElementInit'/>
</div>
</div></div>
  <div id='outer-wrapper'><div id='wrap2'>

    <div id='header-wrapper'>
      <b:section class='header' id='header' maxwidgets='1' showaddelement='no'>
        <b:widget id='Header1' locked='true' title='hàng mới  (Tiêu đề)' type='Header' version='1'>
          <b:widget-settings>
            <b:widget-setting name='displayUrl'/>
            <b:widget-setting name='displayHeight'>0</b:widget-setting>
            <b:widget-setting name='sectionWidth'>-1</b:widget-setting>
            <b:widget-setting name='useImage'>false</b:widget-setting>
            <b:widget-setting name='shrinkToFit'>false</b:widget-setting>
            <b:widget-setting name='imagePlacement'>BEHIND</b:widget-setting>
            <b:widget-setting name='displayWidth'>0</b:widget-setting>
          </b:widget-settings>
          <b:includable id='main'>

  <b:if cond='data:useImage'>
    <b:if cond='data:imagePlacement == &quot;BEHIND&quot;'>
      <!--
      Show image as background to text. You can't really calculate the width
      reliably in JS because margins are not taken into account by any of
      clientWidth, offsetWidth or scrollWidth, so we don't force a minimum
      width if the user is using shrink to fit.
      This results in a margin-width's worth of pixels being cropped. If the
      user is not using shrink to fit then we expand the header.
      -->
      <b:if cond='data:mobile'>
          <div id='header-inner'>
            <div class='titlewrapper' style='background: transparent'>
              <h1 class='title' style='background: transparent; border-width: 0px'>
                <b:include name='title'/>
              </h1>
            </div>
            <b:include name='description'/>
          </div>
        <b:else/>
          <div expr:style='&quot;background-image: url(\&quot;&quot; + data:sourceUrl + &quot;\&quot;); &quot;                        + &quot;background-position: &quot;                        + data:backgroundPositionStyleStr + &quot;; &quot;                        + data:widthStyleStr                        + &quot;min-height: &quot; + data:height                        + &quot;_height: &quot; + data:height                        + &quot;background-repeat: no-repeat; &quot;' id='header-inner'>
            <div class='titlewrapper' style='background: transparent'>
              <h1 class='title' style='background: transparent; border-width: 0px'>
                <b:include name='title'/>
              </h1>
            </div>
            <b:include name='description'/>
          </div>
        </b:if>
    <b:else/>
      <!--Show the image only-->
      <div id='header-inner'>
        <a expr:href='data:blog.homepageUrl' style='display: block'>
          <img expr:alt='data:title' expr:height='data:height' expr:id='data:widget.instanceId + &quot;_headerimg&quot;' expr:src='data:sourceUrl' expr:width='data:width' style='display: block'/>
        </a>
        <!--Show the description-->
        <b:if cond='data:imagePlacement == &quot;BEFORE_DESCRIPTION&quot;'>
          <b:include name='description'/>
        </b:if>
      </div>
    </b:if>
  <b:else/>
    <!--No header image -->
    <div id='header-inner'>
      <div class='titlewrapper'>
        <h1 class='title'>
          <b:include name='title'/>
        </h1>
      </div>
      <b:include name='description'/>
    </div>
  </b:if>
</b:includable>
          <b:includable id='description'>
  <div class='descriptionwrapper'>
    <p class='description'><span><data:description/></span></p>
  </div>
</b:includable>
          <b:includable id='title'>
  <b:if cond='data:blog.url == data:blog.homepageUrl'>
    <data:title/>
  <b:else/>
    <a expr:href='data:blog.homepageUrl'><data:title/></a>
  </b:if>
</b:includable>
        </b:widget>
      </b:section>
<b:section class='header' id='header2' maxwidgets='1' showaddelement='yes'>
  <b:widget id='HTML2' locked='false' title='ccc' type='HTML'>
    <b:widget-settings>
      <b:widget-setting name='content'>&lt;div class=&#39;menuleft&#39;&gt;
&lt;div class=&#39;bg-menuleft&#39;&gt;
&lt;div class=&#39;dropdown-toggle&#39; data-toggle=&#39;dropdown&#39; itemscope=&#39;itemscope&#39; itemtype=&#39;http://schema.org/SiteNavigationElement&#39;&gt;
&lt;span&gt;
&lt;i aria-hidden=&quot;true&quot; class=&quot;fa fa-home fa-2x&quot;&gt;&lt;/i&gt; DANH MỤC SẢN PHẨM
&lt;/span&gt;
&lt;/div&gt;
&lt;ul class=&#39;menuleft dropdown-menu homecat&#39; role=&#39;menu&#39; &gt;
&lt;li&gt;&lt;a href=&#39;#LINK&#39; title=&#39;&#39;&gt;&lt;i class=&quot;fa fa-angle-right&quot; aria-hidden=&quot;true&quot;&gt;&lt;/i&gt;
Tinh Dầu Nguyên Chất&lt;/a&gt;&lt;/li&gt;
&lt;li&gt;&lt;a href=&#39;#LINK&#39; title=&#39;&#39;&gt;&lt;i class=&quot;fa fa-angle-right&quot; aria-hidden=&quot;true&quot;&gt;&lt;/i&gt; Đèn Xông Tinh Dầu&lt;/a&gt;&lt;/li&gt;
&lt;li&gt;&lt;a href=&#39;#LINK&#39; title=&#39;&#39;&gt;&lt;i class=&quot;fa fa-angle-right&quot; aria-hidden=&quot;true&quot;&gt;&lt;/i&gt; Máy Khuyếch Tán Tinh Dầu&lt;/a&gt;&lt;/li&gt;
&lt;li&gt;&lt;a class=&#39;atop&#39; href=&#39;#LINK&#39;&gt;&lt;i class=&quot;fa fa-angle-right&quot; aria-hidden=&quot;true&quot;&gt;&lt;/i&gt; Tinh Dầu Làm Đẹp&lt;/a&gt;
&lt;/li&gt;
&lt;li&gt;&lt;a class=&#39;atop&#39; href=&#39;#LINK&#39;&gt;&lt;i class=&quot;fa fa-angle-right&quot; aria-hidden=&quot;true&quot;&gt;&lt;/i&gt; Nến Thơm Greenleaf&lt;/a&gt;
&lt;/li&gt;
&lt;li&gt;&lt;a href=&#39;#LINK&#39; title=&#39;&#39;&gt;&lt;i class=&quot;fa fa-angle-right&quot; aria-hidden=&quot;true&quot;&gt;&lt;/i&gt; Phụ Kiện&lt;/a&gt;&lt;/li&gt;
&lt;li&gt;&lt;a href=&#39;#LINK&#39; title=&#39;&#39;&gt;&lt;i class=&quot;fa fa-angle-right&quot; aria-hidden=&quot;true&quot;&gt;&lt;/i&gt; Phụ Kiện&lt;/a&gt;&lt;/li&gt;
&lt;/ul&gt;
&lt;/div&gt;
&lt;/div&gt;
&lt;div class=&#39;menuright&#39;&gt;
&lt;ul class=&#39;mrul&#39;&gt;
&lt;li class=&#39;mrli&#39;&gt;
&lt;a class=&#39;mratop mdrop&#39; href=&#39;#LINK&#39;&gt;Công Dụng Và Cách Dùng&lt;/a&gt;
&lt;/li&gt;
&lt;li class=&#39;mrli&#39;&gt;&lt;a class=&#39;mratop mdrop&#39; href=&#39;#LINK&#39;&gt;Hướng dẫn mua hàng&lt;/a&gt;
&lt;/li&gt;
&lt;li class=&#39;mrli&#39;&gt;&lt;a class=&#39;mratop mdrop&#39; href=&#39;#LINK&#39;&gt;Cửa hàng và đối tác&lt;/a&gt;
&lt;/li&gt;
&lt;li class=&#39;mrli&#39;&gt;&lt;a class=&#39;mratop mdrop&#39; href=&#39;#LINK&#39;&gt;Liên hệ - tuyển dụng&lt;/a&gt;&lt;/li&gt;
&lt;/ul&gt;&lt;/div&gt;</b:widget-setting>
    </b:widget-settings>
    <b:includable id='main'>
  <!-- only display title if it's non-empty -->
  <b:if cond='data:title != &quot;&quot;'>
    <h2 class='title'><data:title/></h2>
  </b:if>
  <div class='widget-content'>
    <data:content/>
  </div>

  <b:include name='quickedit'/>
</b:includable>
  </b:widget>
</b:section>
<div style='clear:both;'/>
</div><!-- end header-wrapper -->
<div id='top-wrapper'>
<div id='topbar'>
<ul id='top'>
<li><a href='/'>Homepage</a></li>
<li><a href='#'>About Us</a></li>
<li><a class='arrow' href='#'>Contact Us</a>
<ul>
<li><a href='#'>Goggle +</a></li>
<li class='hr'/>
<li><a href='#'>Contact on Facebook</a></li>
<li class='hr'/>
<li><a href='#'>Contact on Twitter</a></li>
</ul>
</li>
<li><a href='#'>healthy</a></li>
<li><a href='#'>Human Act</a></li>
<li><a class='arrow' href='#'>Enjoy</a>
<ul>
<li><a href='#'>Music</a></li>
<li class='hr'/>
<li><a href='#'>Movie</a></li>
<li class='hr'/>
<li><a href='#'>Television</a></li>
<li><a href='http://www.soratemplates.com/2015/03/shopingo-blogger-templates.html'>Download This Template</a></li>
</ul>
</li>
</ul>
<br class='clearit'/>
</div>
<div style='clear:both;'/>
</div>

	 <div id='searchbar'>
	<div id='searchbarleft'>
<form action='http://feedburner.google.com/fb/a/mailverify' id='subscribe' method='post' onsubmit='window.open(&apos;http://feedburner.google.com/fb/a/mailverify?uri=blogspot/htbgh&apos;, &apos;popupwindow&apos;, &apos;scrollbars=yes,width=550,height=520&apos;);return true' target='popupwindow'><input id='subbox' name='email' onblur='if (this.value == &apos;&apos;) {this.value = &apos;Enter your email address...&apos;;}' onfocus='if (this.value == &apos;Enter your email address...&apos;) {this.value = &apos;&apos;;}' type='text' value='Enter your email address...'/><input name='uri' type='hidden' value='blogspot/htbgh'/><input name='loc' type='hidden' value='en_US'/><input id='subbutton' type='submit' value='Enter'/></form>
    </div>
    	<div id='searchbarmiddle'>
    	 <b:section id='labelsmenu' maxwidgets='1'>
<b:widget id='Label1' locked='true' title='Kategori' type='Label' version='1'>
  <b:widget-settings>
    <b:widget-setting name='sorting'>ALPHA</b:widget-setting>
    <b:widget-setting name='display'>LIST</b:widget-setting>
    <b:widget-setting name='selectedLabelsList'/>
    <b:widget-setting name='showType'>ALL</b:widget-setting>
    <b:widget-setting name='showFreqNumbers'>false</b:widget-setting>
  </b:widget-settings>
  <b:includable id='main'>
Product : <select class='postform' id='cat' name='cat' onchange='location=this.options[this.selectedIndex].value;'>
<option>Choose Categories</option>
<b:loop values='data:labels' var='label'>
   <option expr:value='data:label.url'><data:label.name/>
      (<data:label.count/>)
   </option>
</b:loop>
</select>
</b:includable>
</b:widget>
</b:section>
	</div>
    	<div id='searchbarright'>
<form action='http://www.google.com/search' method='get' target='_blank'>
<input name='sitesearch' style='display:none;' value='http://johny-storage.blogspot.com'/>
<input id='search-box' name='q' onblur='if(this.value==&apos;&apos;)this.value=this.defaultValue;' onfocus='if(this.value==this.defaultValue)this.value=&apos;&apos;;' style='width:120px;border:none;padding:3px 7px; font:12px Arial;color:#666; background:#fff;border:1px solid #ccc;' type='text' value='Search ...'/><input align='top' id='search-btn' src='http://1.bp.blogspot.com/-s0m9sepW0gc/T5ltQy2L89I/AAAAAAAAAt8/SIa8-qL5dVc/s1600/search.jpg' style='padding:0px 3px;' type='image' value='Search'/>
</form>
</div>
<div id='searchbarright1'>
<ul class='isocial'>
<li><a class='rss' href='#' target='_blank' title='Subscribe via RSS'/></li>
<li><a class='facebook' href='#' target='_blank' title='Become a Fan'/></li>
<li><a class='twitter' href='#' target='_blank' title='Follow Us'/></li>
<li><a class='google' href='#' target='_blank' title='Google Plus Profile'/></li>
<li><a class='youtube' href='#' target='_blank' title='Watch The Video'/></li>
</ul>
    </div> 
       </div>


    <!-- skip links for text browsers -->
    <span id='skiplinks' style='display:none;'>
      <a href='#main'>skip to main </a> |
      <a href='#sidebar'>skip to sidebar</a>
    </span>

 <b:if cond='data:blog.url == data:blog.homepageUrl'>
			<div id='carousel'>
 				
					<script type='text/javaScript'>
							document.write(&quot;&lt;script src=\&quot;/feeds/posts/default/-/featured?max-results=&quot;+numposts1+&quot;&amp;orderby=published&amp;alt=json-in-script&amp;callback=showrecentposts1\&quot;&gt;&lt;\/script&gt;&quot;);
						</script>					

</div>
</b:if>
    <div id='content-wrapper'>
      <div id='crosscol-wrapper'>

      </div>

       <div id='main-wrapper'>

        <b:section class='main' id='main' showaddelement='no'>
          <b:widget id='Blog1' locked='true' title='Bài đăng trên Blog' type='Blog' version='1'>
            <b:widget-settings>
              <b:widget-setting name='showDateHeader'>true</b:widget-setting>
              <b:widget-setting name='style.textcolor'>#444444</b:widget-setting>
              <b:widget-setting name='showShareButtons'>true</b:widget-setting>
              <b:widget-setting name='authorLabel'>By</b:widget-setting>
              <b:widget-setting name='showCommentLink'>true</b:widget-setting>
              <b:widget-setting name='style.urlcolor'>#444444</b:widget-setting>
              <b:widget-setting name='showAuthor'>false</b:widget-setting>
              <b:widget-setting name='style.linkcolor'>#000000</b:widget-setting>
              <b:widget-setting name='style.unittype'>TextAndImage</b:widget-setting>
              <b:widget-setting name='style.bgcolor'>#eeeeee</b:widget-setting>
              <b:widget-setting name='showAuthorProfile'>false</b:widget-setting>
              <b:widget-setting name='style.layout'>1x1</b:widget-setting>
              <b:widget-setting name='showLabels'>true</b:widget-setting>
              <b:widget-setting name='showLocation'>true</b:widget-setting>
              <b:widget-setting name='showTimestamp'>true</b:widget-setting>
              <b:widget-setting name='postsPerAd'>3</b:widget-setting>
              <b:widget-setting name='showBacklinks'>false</b:widget-setting>
              <b:widget-setting name='style.bordercolor'>#eeeeee</b:widget-setting>
              <b:widget-setting name='showInlineAds'>true</b:widget-setting>
              <b:widget-setting name='showReactions'>false</b:widget-setting>
            </b:widget-settings>
            <b:includable id='main' var='top'>
  <!-- posts -->
  <div class='blog-posts hfeed'>

    <b:include data='top' name='status-message'/>

    <data:defaultAdStart/>
    <b:loop values='data:posts' var='post'>
      <b:if cond='data:post.dateHeader'>
      </b:if>
      <b:include data='post' name='post'/>
      <b:if cond='data:blog.pageType == &quot;static_page&quot;'>
        <b:include data='post' name='threaded_comments'/>
      </b:if>
      <b:if cond='data:blog.pageType == &quot;item&quot;'>
      <b:include data='post' name='threaded_comments'/>
      </b:if>
      <b:if cond='data:post.includeAd'>
        <b:if cond='data:post.isFirstPost'>
          <data:defaultAdEnd/>
        <b:else/>
          <data:adEnd/>
        </b:if>
        <div class='inline-ad'>
          <data:adCode/>
        </div>
        <data:adStart/>
      </b:if>
      <b:if cond='data:post.trackLatency'>
        <data:post.latencyJs/>
      </b:if>
    </b:loop>
    <data:adEnd/>
  </div>

  <!-- navigation -->
  <b:include name='nextprev'/>


  <!-- feed links -->
  <b:include name='feedLinks'/>
  
  <b:if cond='data:top.showStars'>
    <script src='http://www.google.com/jsapi' type='text/javascript'/>
    <script type='text/javascript'>
      google.load(&quot;annotations&quot;, &quot;1&quot;, {&quot;locale&quot;: &quot;<data:top.languageCode/>&quot;});
      function initialize() {
        google.annotations.setApplicationId(<data:top.blogspotReviews/>);
        google.annotations.createAll();
        google.annotations.fetch();
      }
      google.setOnLoadCallback(initialize);
    </script>
  </b:if>
</b:includable>
            <b:includable id='backlinkDeleteIcon' var='backlink'>
                      <span expr:class='&quot;item-control &quot; + data:backlink.adminClass'>
                        <a expr:href='data:backlink.deleteUrl' expr:title='data:top.deleteBacklinkMsg'>
                          <img src='//www.blogger.com/img/icon_delete13.gif'/>
                        </a>
                      </span>
                    </b:includable>
            <b:includable id='backlinks' var='post'>
                      <a name='links'/>
                      <h4>
                        <data:post.backlinksLabel/>
                      </h4>
                      <b:if cond='data:post.numBacklinks != 0'>
                        <dl class='comments-block' id='comments-block'>
                          <b:loop values='data:post.backlinks' var='backlink'>
                            <div class='collapsed-backlink backlink-control'>
                              <dt class='comment-title'>
                                <span class='backlink-toggle-zippy'>
                                  &#160;
                                </span>
                                <a expr:href='data:backlink.url' rel='nofollow'>
                                  <data:backlink.title/>
                                </a>
                                <b:include data='backlink' name='backlinkDeleteIcon'/>
                              </dt>
                              <dd class='comment-body collapseable'>
                                <data:backlink.snippet/>
                              </dd>
                              <dd class='comment-footer collapseable'>
                                <span class='comment-author'>
                                  <data:post.authorLabel/>
                                  <data:backlink.author/>
                                </span>
                                <span class='comment-timestamp'>
                                  <data:post.timestampLabel/>
                                  <data:backlink.timestamp/>
                                </span>
                              </dd>
                            </div>
                          </b:loop>
                        </dl>
                      </b:if>
                      <p class='comment-footer'>
                        <a class='comment-link' expr:href='data:post.createLinkUrl' expr:id='data:widget.instanceId + &quot;_backlinks-create-link&quot;' target='_blank'>
                          <data:post.createLinkLabel/>
                        </a>
                      </p>
                    </b:includable>
            <b:includable id='breadcrumb' var='posts'>
                      <b:if cond='data:blog.homepageUrl != data:blog.url'>
                        <b:if cond='data:blog.pageType == &quot;static_page&quot;'>
                          <div class='breadcrumbs'>
                            <span>
                              <a expr:href='data:blog.homepageUrl' rel='nofollow'>
                                Home
                              </a>
                            </span>
                            / 
                            <span>
                              <data:blog.pageName/>
                            </span>
                          </div>
                          <b:else/>
                          <b:if cond='data:blog.pageType == &quot;item&quot;'>
                            <b:loop values='data:posts' var='post'>
                              <b:if cond='data:post.labels'>
                                <div class='breadcrumbs'>
                                  <span itemscope='' itemtype='http://data-vocabulary.org/Breadcrumb'>
                                    <a expr:href='data:blog.homepageUrl' itemprop='url'>
                                      <span itemprop='title'>
                                        Home
                                      </span>
                                    </a>
                                  </span>
                                  / 
                                  <b:loop values='data:post.labels' var='label'>
                                    <span itemscope='' itemtype='http://data-vocabulary.org/Breadcrumb'>
                                      <a expr:href='data:label.url + &quot;?&amp;max-results=8&quot;' itemprop='url'>
                                        <span itemprop='title'>
                                          <data:label.name/>
                                        </span>
                                      </a>
                                    </span>
                                    <b:if cond='data:label.isLast != &quot;true&quot;'>
                                      / 
                                    </b:if>
                                  </b:loop>
                                  / 
                                  <span>
                                    <data:post.title/>
                                  </span>
                                </div>
                                <b:else/>
                                <div class='breadcrumbs'>
                                  <span>
                                    <a expr:href='data:blog.homepageUrl' rel='nofollow'>
                                      Home
                                    </a>
                                  </span>
                                  / 
                                  <span>
                                    Uncategories
                                  </span>
                                  / 
                                  <span>
                                    <data:post.title/>
                                  </span>
                                </div>
                              </b:if>
                            </b:loop>
                            <b:else/>
                            <b:if cond='data:blog.pageType == &quot;archive&quot;'>
                              <div class='breadcrumbs'>
                                <span>
                                  <a expr:href='data:blog.homepageUrl' rel='nofollow'>
                                    Home
                                  </a>
                                </span>
                                / 
                                <span>
                                  Archive for 
                                  <data:blog.pageName/>
                                </span>
                              </div>
                              <b:else/>
                              <b:if cond='data:blog.searchQuery'>
                                <div class='breadcrumbs'>
                                  <span>
                                    <a expr:href='data:blog.homepageUrl' rel='nofollow'>
                                      Home
                                    </a>
                                  </span>
                                  / 
                                  <span>
                                    <data:blog.pageName/>
                                  </span>
                                </div>
                                <b:else/>
                                <b:if cond='data:blog.pageType == &quot;index&quot;'>
                                  <div class='breadcrumbs'>
                                    <b:if cond='data:blog.pageName == &quot;&quot;'>
                                      <span>
                                        <a expr:href='data:blog.homepageUrl' rel='nofollow'>
                                          Home
                                        </a>
                                      </span>
                                      / 
                                      <span>
                                        All post
                                      </span>
                                      <b:else/>
                                      <span>
                                        <a expr:href='data:blog.homepageUrl' rel='nofollow'>
                                          Home
                                        </a>
                                      </span>
                                      / 
                                      <span>
                                        <data:blog.pageName/>
                                      </span>
                                    </b:if>
                                  </div>
                                </b:if>
                              </b:if>
                            </b:if>
                          </b:if>
                        </b:if>
                      </b:if>
                    </b:includable>
            <b:includable id='comment-form' var='post'>
                      <div class='comment-form'>
                        <a name='comment-form'/>
                        <b:if cond='data:mobile'>
                          <h4 id='comment-post-message'>
                            <a expr:id='data:widget.instanceId + &quot;_comment-editor-toggle-link&quot;' href='javascript:void(0)'>
                              <data:postCommentMsg/>
                            </a>
                          </h4>
                          <div class='pesan-komentar'>
                            <p>
                              <data:blogCommentMessage/>
                            </p>
                          </div>
                          <data:blogTeamBlogMessage/>
                          <a expr:href='data:post.commentFormIframeSrc' id='comment-editor-src'/>
                          <iframe allowtransparency='true' class='blogger-iframe-colorize blogger-comment-from-post' frameborder='0' height='410' id='comment-editor' name='comment-editor' src='' style='display: none' width='100%'/>
                          <b:else/>
                          <h4 id='comment-post-message'>
                            <data:postCommentMsg/>
                          </h4>
                          <div class='pesan-komentar'>
                            <p>
                              <data:blogCommentMessage/>
                            </p>
                          </div>
                          <data:blogTeamBlogMessage/>
                          <a expr:href='data:post.commentFormIframeSrc' id='comment-editor-src'/>
                          <iframe allowtransparency='true' class='blogger-iframe-colorize blogger-comment-from-post' frameborder='0' height='410' id='comment-editor' name='comment-editor' src='' width='100%'/>
                        </b:if>
                        <data:post.friendConnectJs/>
                        <data:post.cmtfpIframe/>
                        <script type='text/javascript'>
                          BLOG_CMT_createIframe(&#39;<data:post.appRpcRelayPath/>&#39;, &#39;<data:post.communityId/>&#39;);
                        </script>
                      </div>
                    </b:includable>
            <b:includable id='commentDeleteIcon' var='comment'>
                      <span expr:class='&quot;item-control &quot; + data:comment.adminClass'>
                        <b:if cond='data:showCmtPopup'>
                          <div class='goog-toggle-button'>
                            <div class='goog-inline-block comment-action-icon'/>
                          </div>
                          <b:else/>
                          <a class='comment-delete' expr:href='data:comment.deleteUrl' expr:title='data:top.deleteCommentMsg'>
                            <img src='//www.blogger.com/img/icon_delete13.gif'/>
                          </a>
                        </b:if>
                      </span>
                    </b:includable>
            <b:includable id='comment_count_picker' var='post'>
                      <b:if cond='data:post.commentSource == 1'>
                        <span class='cmt_count_iframe_holder' expr:data-count='data:post.numComments' expr:data-onclick='data:post.addCommentOnclick' expr:data-post-url='data:post.url' expr:data-url='data:post.canonicalUrl'>
                        </span>
                        <b:else/>
                        <a class='comment-link' expr:href='data:post.addCommentUrl' expr:onclick='data:post.addCommentOnclick'>
                          <data:post.commentLabelFull/>
                          :
                        </a>
                      </b:if>
                    </b:includable>
            <b:includable id='comment_picker' var='post'>
                      <b:if cond='data:post.commentSource == 1'>
                        <b:include data='post' name='iframe_comments'/>
                        <b:else/>
                        <b:if cond='data:post.showThreadedComments'>
                          <b:include data='post' name='threaded_comments'/>
                          <b:else/>
                          <b:include data='post' name='comments'/>
                        </b:if>
                      </b:if>
                    </b:includable>
            <b:includable id='comments' var='post'>
                      <div id='top-comment'>
                        
                        <div class='widget2' id='top-comment1'>
                          <div class='centerare1'>
                            <div class='comments' id='comments'>
                              <a name='comments'/>
                              <b:if cond='data:post.allowComments'>
                                <div class='komhead'>
                                  <h4>
                                    <b:if cond='data:post.numComments == 1'>
                                      1 
                                      <data:commentLabel/>
                                      :
                                      <b:else/>
                                      <data:post.numComments/>
                                      <data:commentLabelPlural/>
                                      :
                                    </b:if>
                                  </h4>
                                  <div class='stripe-line'/>
                                </div>
                                <b:if cond='data:post.commentPagingRequired'>
                                  <span class='paging-control-container'>
                                    <a expr:class='data:post.oldLinkClass' expr:href='data:post.oldestLinkUrl'>
                                      <data:post.oldestLinkText/>
                                    </a>
                                    &#160;
                                    <a expr:class='data:post.oldLinkClass' expr:href='data:post.olderLinkUrl'>
                                      <data:post.olderLinkText/>
                                    </a>
                                    &#160;
                                    <data:post.commentRangeText/>
                                    &#160;
                                    <a expr:class='data:post.newLinkClass' expr:href='data:post.newerLinkUrl'>
                                      <data:post.newerLinkText/>
                                    </a>
                                    &#160;
                                    <a expr:class='data:post.newLinkClass' expr:href='data:post.newestLinkUrl'>
                                      <data:post.newestLinkText/>
                                    </a>
                                  </span>
                                </b:if>
                                <div expr:id='data:widget.instanceId + &quot;_comments-block-wrapper&quot;'>
                                  <dl expr:class='data:post.avatarIndentClass' id='comments-block'>
                                    <b:loop values='data:post.comments' var='comment'>
                                      <dt expr:class='&quot;comment-author &quot; + data:comment.authorClass' expr:id='data:comment.anchorName'>
                                        <b:if cond='data:comment.favicon'>
                                          <img expr:src='data:comment.favicon' height='16px' style='margin-bottom:-2px;' width='16px'/>
                                        </b:if>
                                        <a expr:name='data:comment.anchorName'/>
                                        <b:if cond='data:blog.enabledCommentProfileImages'>
                                          <data:comment.authorAvatarImage/>
                                        </b:if>
                                        <b:if cond='data:comment.authorUrl'>
                                          <a expr:href='data:comment.authorUrl' rel='nofollow'>
                                            <data:comment.author/>
                                          </a>
                                          <b:else/>
                                          <data:comment.author/>
                                        </b:if>
                                        <data:commentPostedByMsg/>
                                      </dt>
                                      <dd class='comment-body' expr:id='data:widget.instanceId + data:comment.cmtBodyIdPostfix'>
                                        <b:if cond='data:comment.isDeleted'>
                                          <span class='deleted-comment'>
                                            <data:comment.body/>
                                          </span>
                                          <b:else/>
                                          <p>
                                            <data:comment.body/>
                                          </p>
                                        </b:if>
                                      </dd>
                                      <dd class='comment-footer'>
                                        <span class='comment-timestamp'>
                                          <a expr:href='data:comment.url' title='comment permalink'>
                                            <data:comment.timestamp/>
                                          </a>
                                          <b:include data='comment' name='commentDeleteIcon'/>
                                        </span>
                                      </dd>
                                    </b:loop>
                                  </dl>
                                </div>
                                <b:if cond='data:post.commentPagingRequired'>
                                  <span class='paging-control-container'>
                                    <a expr:class='data:post.oldLinkClass' expr:href='data:post.oldestLinkUrl'>
                                      <data:post.oldestLinkText/>
                                    </a>
                                    <a expr:class='data:post.oldLinkClass' expr:href='data:post.olderLinkUrl'>
                                      <data:post.olderLinkText/>
                                    </a>
                                    &#160;
                                    <data:post.commentRangeText/>
                                    &#160;
                                    <a expr:class='data:post.newLinkClass' expr:href='data:post.newerLinkUrl'>
                                      <data:post.newerLinkText/>
                                    </a>
                                    <a expr:class='data:post.newLinkClass' expr:href='data:post.newestLinkUrl'>
                                      <data:post.newestLinkText/>
                                    </a>
                                  </span>
                                </b:if>
                                <p class='comment-footer'>
                                  <b:if cond='data:post.embedCommentForm'>
                                    <b:if cond='data:post.allowNewComments'>
                                      <b:include data='post' name='comment-form'/>
                                      <b:else/>
                                      <data:post.noNewCommentsText/>
                                    </b:if>
                                    <b:else/>
                                    <b:if cond='data:post.allowComments'>
                                      <a expr:href='data:post.addCommentUrl' expr:onclick='data:post.addCommentOnclick'>
                                        <data:postCommentMsg/>
                                      </a>
                                    </b:if>
                                  </b:if>
                                </p>
                              </b:if>
                              <b:if cond='data:showCmtPopup'>
                                <div id='comment-popup'>
                                  <iframe allowtransparency='true' frameborder='0' id='comment-actions' name='comment-actions' scrolling='no'>
                                  </iframe>
                                </div>
                              </b:if>
                              <div id='backlinks-container'>
                                <div expr:id='data:widget.instanceId + &quot;_backlinks-container&quot;'>
                                  <b:if cond='data:post.showBacklinks'>
                                    <b:include data='post' name='backlinks'/>
                                  </b:if>
                                </div>
                              </div>
                            </div>
                          </div>
                        </div>
                        
                        
                      </div>
                    </b:includable>
            <b:includable id='feedLinks'>
                      <b:if cond='data:blog.pageType != &quot;item&quot;'>
                        <!-- Blog feed links -->
                        <b:if cond='data:feedLinks'>
                          <div class='blog-feeds'>
                            <b:include data='feedLinks' name='feedLinksBody'/>
                          </div>
                        </b:if>
                        <b:else/>
                        <!--Post feed links -->
                        <div class='post-feeds'>
                          <b:loop values='data:posts' var='post'>
                            <b:if cond='data:post.allowComments'>
                              <b:if cond='data:post.feedLinks'>
                                <b:include data='post.feedLinks' name='feedLinksBody'/>
                              </b:if>
                            </b:if>
                          </b:loop>
                        </div>
                      </b:if>
                    </b:includable>
            <b:includable id='feedLinksBody' var='links'>
                      <div class='feed-links'>
                        <data:feedLinksMsg/>
                        <b:loop values='data:links' var='f'>
                          <a class='feed-link' expr:href='data:f.url' expr:type='data:f.mimeType' target='_blank'>
                            <data:f.name/>
                            (
                            <data:f.feedType/>
                            )
                          </a>
                        </b:loop>
                      </div>
                    </b:includable>
            <b:includable id='iframe_comments' var='post'>
                      <b:if cond='data:post.allowIframeComments'>
                        <script expr:src='data:post.iframeCommentSrc' type='text/javascript'/>
                        <div class='cmt_iframe_holder' expr:data-href='data:post.canonicalUrl' expr:data-viewtype='data:post.viewType'/>
                        <b:if cond='data:post.embedCommentForm == &quot;false&quot;'>
                          <a expr:href='data:post.addCommentUrl' expr:onclick='data:post.addCommentOnclick'>
                            <data:postCommentMsg/>
                          </a>
                        </b:if>
                      </b:if>
                    </b:includable>
            <b:includable id='mobile-index-post' var='post'>
  <b:if cond='data:post.dateHeader'>
    <div class='mobile-index-date'>
      <div class='date-header'>
        <span><data:post.dateHeader/></span>
      </div>
    </div>
  </b:if>
  <div class='mobile-post-outer'>
    <div class='mobile-index-title-outer'>
      <h3 class='mobile-index-title entry-title'>
        <a href='javascript:void(0)'><data:post.title/></a>
      </h3>
    </div>

    <div>
      <div class='mobile-index-arrow'>
        <a href='javascript:void(0)'>&amp;rsaquo;</a>
      </div>

      <div class='mobile-post-contents'>
        <b:if cond='data:post.thumbnailUrl'>
          <div class='mobile-index-thumbnail'>
            <div class='Image'>
              <img expr:src='data:post.thumbnailUrl'/>
            </div>
          </div>
        </b:if>

        <div class='post-body'>
          <b:if cond='data:post.snippet'><data:post.snippet/></b:if>
        </div>
      </div>
      <div style='clear: both;'/>
    </div>

    <div class='mobile-index-comment'>
      <b:if cond='data:blog.pageType != &quot;item&quot;'>
        <b:if cond='data:blog.pageType != &quot;static_page&quot;'>
          <b:if cond='data:post.allowComments'>
            <b:if cond='data:post.numComments != 0'>
              <a class='comment-link' expr:href='data:post.addCommentUrl' expr:onclick='data:post.addCommentOnclick'><b:if cond='data:post.numComments == 1'>1 <data:top.commentLabel/><b:else/><data:post.numComments/> <data:top.commentLabelPlural/></b:if></a>
            </b:if>
          </b:if>
        </b:if>
      </b:if>
    </div>
  </div>
</b:includable>
            <b:includable id='mobile-main' var='top'>
    <!-- posts -->
    <div class='blog-posts hfeed'>

      <b:include data='top' name='status-message'/>

      <b:if cond='data:blog.pageType == &quot;index&quot;'>
        <b:loop values='data:posts' var='post'>
          <b:include data='post' name='mobile-index-post'/>
        </b:loop>
      <b:else/>
        <b:loop values='data:posts' var='post'>
          <b:include data='post' name='mobile-post'/>
        </b:loop>
      </b:if>
    </div>

   <b:include name='mobile-nextprev'/>
</b:includable>
            <b:includable id='mobile-nextprev'>
  <div class='blog-pager' id='blog-pager'>
    <b:if cond='data:newerPageUrl'>
      <div class='mobile-link-button' id='blog-pager-newer-link'>
      <a class='blog-pager-newer-link' expr:href='data:newerPageUrl' expr:id='data:widget.instanceId + &quot;_blog-pager-newer-link&quot;' expr:title='data:newerPageTitle'>&amp;lsaquo;</a>
      </div>
    </b:if>

    <b:if cond='data:olderPageUrl'>
      <div class='mobile-link-button' id='blog-pager-older-link'>
      <a class='blog-pager-older-link' expr:href='data:olderPageUrl' expr:id='data:widget.instanceId + &quot;_blog-pager-older-link&quot;' expr:title='data:olderPageTitle'>&amp;rsaquo;</a>
      </div>
    </b:if>

    <div class='mobile-link-button' id='blog-pager-home-link'>
    <a class='home-link' expr:href='data:blog.homepageUrl'><data:homeMsg/></a>
    </div>

    <div class='mobile-desktop-link'>
      <a class='home-link' expr:href='data:desktopLinkUrl'><data:desktopLinkMsg/></a>
    </div>

  </div>
  <div class='clear'/>
</b:includable>
            <b:includable id='mobile-post' var='post'>
  <div class='date-outer'>
    <b:if cond='data:post.dateHeader'>
      <h2 class='date-header'><span><data:post.dateHeader/></span></h2>
    </b:if>
    <div class='date-posts'>
      <div class='post-outer'>

        <div class='post hentry uncustomized-post-template' itemscope='itemscope' itemtype='http://schema.org/BlogPosting'>
          <b:if cond='data:post.thumbnailUrl'>
            <meta expr:content='data:post.thumbnailUrl' itemprop='image_url'/>
          </b:if>
          <meta expr:content='data:blog.blogId' itemprop='blogId'/>
          <meta expr:content='data:post.id' itemprop='postId'/>

          <a expr:name='data:post.id'/>
          <b:if cond='data:post.title'>
            <h3 class='post-title entry-title' itemprop='name'>
              <b:if cond='data:post.link'>
                <a expr:href='data:post.link'><data:post.title/></a>
              <b:else/>
                <b:if cond='data:post.url'>
                  <b:if cond='data:blog.url != data:post.url'>
                    <a expr:href='data:post.url'><data:post.title/></a>
                  <b:else/>
                    <data:post.title/>
                  </b:if>
                <b:else/>
                  <data:post.title/>
                </b:if>
              </b:if>
            </h3>
          </b:if>

          <div class='post-header'>
            <div class='post-header-line-1'/>
          </div>

          <div class='post-body entry-content' expr:id='&quot;post-body-&quot; + data:post.id' itemprop='articleBody'>
            <data:post.body/>
            <div style='clear: both;'/> <!-- clear for photos floats -->
          </div>

          <div class='post-footer'>
            <div class='post-footer-line post-footer-line-1'>
              <span class='post-author vcard'>
                <b:if cond='data:top.showAuthor'>
                  <b:if cond='data:post.authorProfileUrl'>
                    <span class='fn' itemprop='author' itemscope='itemscope' itemtype='http://schema.org/Person'>
                      <meta expr:content='data:post.authorProfileUrl' itemprop='url'/>
                      <a expr:href='data:post.authorProfileUrl' rel='author' title='author profile'>
                        <span itemprop='name'><data:post.author/></span>
                      </a>
                    </span>
                  <b:else/>
                    <span class='fn' itemprop='author' itemscope='itemscope' itemtype='http://schema.org/Person'>
                      <span itemprop='name'><data:post.author/></span>
                    </span>
                  </b:if>
                </b:if>
              </span>

              <span class='post-timestamp'>
                <b:if cond='data:top.showTimestamp'>
                  <data:top.timestampLabel/>
                  <b:if cond='data:post.url'>
                    <meta expr:content='data:post.canonicalUrl' itemprop='url'/>
                    <a class='timestamp-link' expr:href='data:post.url' rel='bookmark' title='permanent link'><abbr class='published' expr:title='data:post.timestampISO8601' itemprop='datePublished'><data:post.timestamp/></abbr></a>
                  </b:if>
                </b:if>
              </span>

             
            </div>

            <div class='post-footer-line post-footer-line-2'>
              <b:if cond='data:top.showMobileShare'>
                <div class='mobile-link-button goog-inline-block' id='mobile-share-button'>
                  <a href='javascript:void(0);'><data:shareMsg/></a>
                </div>
              </b:if>
              <b:if cond='data:top.showDummy'>
                <div class='goog-inline-block dummy-container'><data:post.dummyTag/></div>
              </b:if>
            </div>

          </div>
        </div>

        <b:if cond='data:blog.pageType == &quot;static_page&quot;'>
          <b:include data='post' name='comment_picker'/>
        </b:if>
        <b:if cond='data:blog.pageType == &quot;item&quot;'>
          <b:include data='post' name='comment_picker'/>
        </b:if>
      </div>
    </div>
  </div>
</b:includable>
            <b:includable id='nextprev'>
  <div class='blog-pager' id='blog-pager'>
    <b:if cond='data:newerPageUrl'>
      <span id='blog-pager-newer-link'>
      <a class='blog-pager-newer-link' expr:href='data:newerPageUrl' expr:id='data:widget.instanceId + &quot;_blog-pager-newer-link&quot;' expr:title='data:newerPageTitle'><data:newerPageTitle/></a>
      </span>
    </b:if>

    <b:if cond='data:olderPageUrl'>
      <span id='blog-pager-older-link'>
      <a class='blog-pager-older-link' expr:href='data:olderPageUrl' expr:id='data:widget.instanceId + &quot;_blog-pager-older-link&quot;' expr:title='data:olderPageTitle'><data:olderPageTitle/></a>
      </span>
    </b:if>

    <a class='home-link' expr:href='data:blog.homepageUrl'><data:homeMsg/></a>

    <b:if cond='data:mobileLinkUrl'>
      <div class='blog-mobile-link'>
        <a expr:href='data:mobileLinkUrl'><data:mobileLinkMsg/></a>
      </div>
    </b:if>

  </div>
  <div class='clear'/>
</b:includable>
            <b:includable id='post' var='post'>
  <div class='post hentry uncustomized-post-template simpleCart_shelfItem'>
    <a expr:name='data:post.id'/>
<b:if cond='data:blog.pageType == &quot;static_page&quot;'>
    <b:if cond='data:post.title'>
      <h3 class='post-title entry-title'>

     <b:if cond='data:post.link'>
       <a expr:href='data:post.link'><data:post.title/></a>
     <b:else/>
        <b:if cond='data:post.url'>
          <a expr:href='data:post.url'><data:post.title/></a>
        <b:else/>
          <data:post.title/>
        </b:if>
     </b:if>
      </h3>
    </b:if>
</b:if>

    <div class='post-header-line-1'/>
    <div class='post-body entry-content'>
<b:if cond='data:blog.pageType != &quot;static_page&quot;'>
<div class='simpleCart_shelfItem'>
<div class='item_name'>
<data:post.title/></div>
<b:if cond='data:post.title'>
      <h3 class='post-title entry-title'>
     <b:if cond='data:post.link'>
       <a expr:href='data:post.link'><data:post.title/></a>
     <b:else/>
        <b:if cond='data:post.url'>
          <a expr:href='data:post.url'><data:post.title/></a>
        <b:else/>
          <data:post.title/>
        </b:if>
     </b:if>
      </h3>
    </b:if>
<data:post.body/>
</div>
</b:if>
<b:if cond='data:blog.pageType == &quot;static_page&quot;'><data:post.body/></b:if>
      <div style='clear: both;'/> <!-- clear for photos floats -->
    </div> 
<b:if cond='data:blog.pageType != &quot;static_page&quot;'>
<input class='item_add' type='button' value='Click để mua'/>
</b:if>
    <b:if cond='data:post.hasJumpLink'>
      <div class='jump-link'>
        <a expr:href='data:post.url + &quot;#more&quot;'><data:post.jumpText/></a>  
      </div>
    </b:if>
    
    <div class='post-footer'>
    <div class='post-footer-line post-footer-line-1'>
      <span class='post-author vcard'>
        <b:if cond='data:top.showAuthor'>
          <data:top.authorLabel/>
          <span class='fn'><data:post.author/></span>
        </b:if>
      </span>

      <span class='post-timestamp'>
        <b:if cond='data:top.showTimestamp'>
          <data:top.timestampLabel/>
        <b:if cond='data:post.url'>
          <a class='timestamp-link' expr:href='data:post.url' rel='bookmark' title='permanent link'><abbr class='published' expr:title='data:post.timestampISO8601'><data:post.timestamp/></abbr></a>
        </b:if>
        </b:if>
      </span>
  
      



      </div>

     

    
    </div>
  </div>
</b:includable>
            <b:includable id='postQuickEdit' var='post'>
  <b:if cond='data:post.editUrl'>
    <span expr:class='&quot;item-control &quot; + data:post.adminClass'>
      <a expr:href='data:post.editUrl' expr:title='data:top.editPostMsg'>
        <img alt='' class='icon-action' height='18' src='http://www.blogger.com/img/icon18_edit_allbkg.gif' width='18'/>
      </a>
    </span>
  </b:if>
</b:includable>
            <b:includable id='shareButtons' var='post'>
  <b:if cond='data:top.showEmailButton'><a class='goog-inline-block share-button sb-email' expr:href='data:post.sharePostUrl + &quot;&amp;target=email&quot;' expr:title='data:top.emailThisMsg' target='_blank'><span class='share-button-link-text'><data:top.emailThisMsg/></span></a></b:if><b:if cond='data:top.showBlogThisButton'><a class='goog-inline-block share-button sb-blog' expr:href='data:post.sharePostUrl + &quot;&amp;target=blog&quot;' expr:onclick='&quot;window.open(this.href, \&quot;_blank\&quot;, \&quot;height=270,width=475\&quot;); return false;&quot;' expr:title='data:top.blogThisMsg' target='_blank'><span class='share-button-link-text'><data:top.blogThisMsg/></span></a></b:if><b:if cond='data:top.showTwitterButton'><a class='goog-inline-block share-button sb-twitter' expr:href='data:post.sharePostUrl + &quot;&amp;target=twitter&quot;' expr:title='data:top.shareToTwitterMsg' target='_blank'><span class='share-button-link-text'><data:top.shareToTwitterMsg/></span></a></b:if><b:if cond='data:top.showFacebookButton'><a class='goog-inline-block share-button sb-facebook' expr:href='data:post.sharePostUrl + &quot;&amp;target=facebook&quot;' expr:onclick='&quot;window.open(this.href, \&quot;_blank\&quot;, \&quot;height=430,width=620\&quot;); return false;&quot;' expr:title='data:top.shareToFacebookMsg' target='_blank'><span class='share-button-link-text'><data:top.shareToFacebookMsg/></span></a></b:if><b:if cond='data:top.showOrkutButton'><a class='goog-inline-block share-button sb-orkut' expr:href='data:post.sharePostUrl + &quot;&amp;target=orkut&quot;' expr:title='data:top.shareToOrkutMsg' target='_blank'><span class='share-button-link-text'><data:top.shareToOrkutMsg/></span></a></b:if><b:if cond='data:top.showDummy'><div class='goog-inline-block dummy-container'><data:post.dummyTag/></div></b:if>
</b:includable>
            <b:includable id='status-message'>
                    <b:if cond='data:navMessage'>
                      <div class='status-msg-wrap'>
                        <div class='status-msg-body'>
                          <data:navMessage/>
                        </div>
                        <div class='status-msg-border'>
                          <div class='status-msg-bg'>
                            <div class='status-msg-hidden'>
                              <data:navMessage/>
                            </div>
                          </div>
                        </div>
                      </div>
                      <div style='clear: both;'/>
                    </b:if>
                  </b:includable>
            <b:includable id='threaded-comment-form' var='post'>
                    <div class='comment-form'>
                      <a name='comment-form'/>
                      <b:if cond='data:mobile'>
                        <div class='pesan-komentar'>
                          <p>
                            <data:blogCommentMessage/>
                          </p>
                        </div>
                        <data:blogTeamBlogMessage/>
                        <a expr:href='data:post.commentFormIframeSrc' id='comment-editor-src'/>
                        <iframe allowtransparency='true' class='blogger-iframe-colorize blogger-comment-from-post' frameborder='0' height='410' id='comment-editor' name='comment-editor' src='' style='display: none' width='100%'/>
                        <b:else/>
                        <div class='pesan-komentar'>
                          <p>
                            <data:blogCommentMessage/>
                          </p>
                        </div>
                        <data:blogTeamBlogMessage/>
                        <a expr:href='data:post.commentFormIframeSrc' id='comment-editor-src'/>
                        <iframe allowtransparency='true' class='blogger-iframe-colorize blogger-comment-from-post' frameborder='0' height='410' id='comment-editor' name='comment-editor' src='' width='100%'/>
                      </b:if>
                      <data:post.friendConnectJs/>
                      <data:post.cmtfpIframe/>
                      <script type='text/javascript'>
                        BLOG_CMT_createIframe(&#39;<data:post.appRpcRelayPath/>&#39;, &#39;<data:post.communityId/>&#39;);
                      </script>
                    </div>
                  </b:includable>
            <b:includable id='threaded_comment_js' var='post'>
                    <script async='async' expr:src='data:post.commentSrc' type='text/javascript'/>
                    <script type='text/javascript'>
                      (function() {
                        var items = <data:post.commentJso/>;
                        var msgs = <data:post.commentMsgs/>;
                        var config = <data:post.commentConfig/>;
                        // <![CDATA[
                        var cursor = null;
                        if (items && items.length > 0) {
                          cursor = parseInt(items[items.length - 1].timestamp) + 1;
                        }
                        var bodyFromEntry = function(entry) {
                          if (entry.gd$extendedProperty) {
                            for (var k in entry.gd$extendedProperty) {
                              if (entry.gd$extendedProperty[k].name == 'blogger.contentRemoved') {
                                return '<span class="deleted-comment">' + entry.content.$t + '</span>';
                              }
                            }
                          }
                          return entry.content.$t;
                        }
                        var parse = function(data) {
                          cursor = null;
                          var comments = [];
                          if (data && data.feed && data.feed.entry) {
                            for (var i = 0, entry; entry = data.feed.entry[i]; i++) {
                              var comment = {};
                              // comment ID, parsed out of the original id format
                              var id = /blog-(\d+).post-(\d+)/.exec(entry.id.$t);
                              comment.id = id ? id[2] : null;
                              comment.body = bodyFromEntry(entry);
                              comment.timestamp = Date.parse(entry.published.$t) + '';
                              if (entry.author && entry.author.constructor === Array) {
                                var auth = entry.author[0];
                                if (auth) {
                                  comment.author = {
                                    name: (auth.name ? auth.name.$t : undefined),
                                    profileUrl: (auth.uri ? auth.uri.$t : undefined),
                                    avatarUrl: (auth.gd$image ? auth.gd$image.src : undefined)
                                  };
                                }
                              }
                              if (entry.link) {
                                if (entry.link[2]) {
                                  comment.link = comment.permalink = entry.link[2].href;
                                }
                                if (entry.link[3]) {
                                  var pid = /.*comments\/default\/(\d+)\?.*/.exec(entry.link[3].href);
                                  if (pid && pid[1]) {
                                    comment.parentId = pid[1];
                                  }
                                }
                              }
                              comment.deleteclass = 'item-control blog-admin';
                              if (entry.gd$extendedProperty) {
                                for (var k in entry.gd$extendedProperty) {
                                  if (entry.gd$extendedProperty[k].name == 'blogger.itemClass') {
                                    comment.deleteclass += ' ' + entry.gd$extendedProperty[k].value;
                                  } else if (entry.gd$extendedProperty[k].name == 'blogger.displayTime') {
                                    comment.displayTime = entry.gd$extendedProperty[k].value;
                                  }
                                }
                              }
                              comments.push(comment);
                            }
                          }
                          return comments;
                        };
                        var paginator = function(callback) {
                          if (hasMore()) {
                            var url = config.feed + '?alt=json&v=2&orderby=published&reverse=false&max-results=50';
                            if (cursor) {
                              url += '&published-min=' + new Date(cursor).toISOString();
                            }
                            window.bloggercomments = function(data) {
                              var parsed = parse(data);
                              cursor = parsed.length < 50 ? null
                              : parseInt(parsed[parsed.length - 1].timestamp) + 1
                              callback(parsed);
                              window.bloggercomments = null;
                            }
                            url += '&callback=bloggercomments';
                            var script = document.createElement('script');
                            script.type = 'text/javascript';
                            script.src = url;
                            document.getElementsByTagName('head')[0].appendChild(script);
                          }
                        };
                        var hasMore = function() {
                          return !!cursor;
                        };
                        var getMeta = function(key, comment) {
                          if ('iswriter' == key) {
                            var matches = !!comment.author
                            && comment.author.name == config.authorName
                            && comment.author.profileUrl == config.authorUrl;
                            return matches ? 'true' : '';
                          } else if ('deletelink' == key) {
                            return config.baseUri + '/delete-comment.g?blogID='
                            + config.blogId + '&postID=' + comment.id;
                          } else if ('deleteclass' == key) {
                            return comment.deleteclass;
                          }
                          return '';
                        };
                        var replybox = null;
                        var replyUrlParts = null;
                        var replyParent = undefined;
                        var onReply = function(commentId, domId) {
                          if (replybox == null) {
                            // lazily cache replybox, and adjust to suit this style:
                            replybox = document.getElementById('comment-editor');
                            if (replybox != null) {
                              replybox.height = '250px';
                              replybox.style.display = 'block';
                              replyUrlParts = replybox.src.split('#');
                            }
                          }
                          if (replybox && (commentId !== replyParent)) {
                            document.getElementById(domId).insertBefore(replybox.parentNode, null);
                            replybox.src = replyUrlParts[0]
                            + (commentId ? '&parentID=' + commentId : '')
                            + '#' + replyUrlParts[1];
                            replyParent = commentId;
                          }
                        };
                        var hash = (window.location.hash || '#').substring(1);
                        var startThread, targetComment;
                        if (/^comment-form_/.test(hash)) {
                          startThread = hash.substring('comment-form_'.length);
                        } else if (/^c[0-9]+$/.test(hash)) {
                          targetComment = hash.substring(1);
                        }
                        // Configure commenting API:
                        var configJso = {
                          'maxDepth': config.maxThreadDepth
                        };
                        var provider = {
                          'id': config.postId,
                          'data': items,
                          'loadNext': paginator,
                          'hasMore': hasMore,
                          'getMeta': getMeta,
                          'onReply': onReply,
                          'rendered': true,
                          'initComment': targetComment,
                          'initReplyThread': startThread,
                          'config': configJso,
                          'messages': msgs
                        };
                        var render = function() {
                          if (window.goog && window.goog.comments) {
                            var holder = document.getElementById('comment-holder');
                            window.goog.comments.render(holder, provider);
                          }
                        };
                        // render now, or queue to render when library loads:
                        if (window.goog && window.goog.comments) {
                          render();
                        } else {
                          window.goog = window.goog || {};
                          window.goog.comments = window.goog.comments || {};
                          window.goog.comments.loadQueue = window.goog.comments.loadQueue || [];
                          window.goog.comments.loadQueue.push(render);
                        }
                      })();
                      // ]]>
                    </script>
                  </b:includable>
            <b:includable id='threaded_comments' var='post'>
                    <div id='top-comment'>
                     
                      <div class='widget2' id='top-comment1'>
                        <div class='centerare1'>
                          <div class='comments' id='comments'>
                            <a name='comments'/>
                            <div class='komhead'>
                              <h4>
                                <b:if cond='data:post.numComments == 1'>
                                  1 
                                  <data:commentLabel/>
                                  :
                                  <b:else/>
                                  <data:post.numComments/>
                                  <data:commentLabelPlural/>
                                  :
                                </b:if>
                              </h4>
                              <div class='stripe-line'/>
                            </div>
                            <div class='comments-content'>
                              <b:if cond='data:post.embedCommentForm'>
                                <b:include data='post' name='threaded_comment_js'/>
                              </b:if>
                              <div id='comment-holder'>
                                <data:post.commentHtml/>
                              </div>
                            </div>
                            <p class='comment-footer'>
                              <b:if cond='data:post.allowNewComments'>
                                <b:include data='post' name='threaded-comment-form'/>
                                <b:else/>
                                <data:post.noNewCommentsText/>
                              </b:if>
                            </p>
                            <b:if cond='data:showCmtPopup'>
                              <div id='comment-popup'>
                                <iframe allowtransparency='true' frameborder='0' id='comment-actions' name='comment-actions' scrolling='no'>
                                </iframe>
                              </div>
                            </b:if>
                            <div id='backlinks-container'>
                              <div expr:id='data:widget.instanceId + &quot;_backlinks-container&quot;'>
                                <b:if cond='data:post.showBacklinks'>
                                  <b:include data='post' name='backlinks'/>
                                </b:if>
                              </div>
                            </div>
                          </div>
                        </div>
                      </div>
                      
                   
                    </div>
                    <div style='clear: both;'/>
                  </b:includable>
          </b:widget>
        </b:section>
<!--Page Navigation Starts-->
<script type='text/javascript'>
var pageCount=6;
var displayPageNum=6;
var upPageWord =&#39;Previous&#39;;
var downPageWord =&#39;Next&#39;;
</script>
<script type='text/javascript'>
//<![CDATA[
function showpageCount(n){var h=home_page_url;var f=new Array();var m=1;var c=1;var q=0;var s=0;var d=0;var e="";var a="";var o="";for(var l=0,k;k=n.feed.entry[l];l++){var r=k.published.$t.substring(0,19)+k.published.$t.substring(23,29);timestamp=encodeURIComponent(r);var t=k.title.$t;if(t!=""){if(q==0||(q%pageCount==(pageCount-1))){if(h.indexOf(timestamp)!=-1){m=c}if(t!=""){c++}f[f.length]="/search?updated-max="+timestamp+"&max-results="+pageCount}}q++}for(var g=0;g<f.length;g++){if(g>=(m-displayPageNum-1)&&g<(m+displayPageNum)){if(s==0&&g==m-2){if(m==2){a='<span class="showpage"><a href="/">'+upPageWord+"</a></span>"}else{a='<span class="showpage"><a href="'+f[g]+'">'+upPageWord+"</a></span>"}s++}if(g==(m-1)){e+='<span class="showpagePoint">'+m+"</span>"}else{if(g==0){e+='<span class="showpageNum"><a href="/">1</a></span>'}else{e+='<span class="showpageNum"><a href="'+f[g]+'">'+(g+1)+"</a></span>"}}if(d==0&&g==m){o='<span class="showpage"> <a href="'+f[g]+'">'+downPageWord+"</a></span>";d++}}}if(m>1){e=""+a+" "+e+" "}e='<div class="showpageArea"><span style="COLOR: #111111;" class="showpageOf">Pages ('+(c-1)+")</span>"+e;if(m<(c-1)){e+=o}if(c==1){c++}e+="</div>";var b=document.getElementsByName("pageArea");var j=document.getElementById("blog-pager");if(c<=2){e=""}for(var g=0;g<b.length;g++){b[g].innerHTML=e}if(b&&b.length>0){e=""}if(j){j.innerHTML=e}}function showpageCount2(r){var l=home_page_url;var k=new Array();var g=l.indexOf("/search/label/")!=-1;var d=g?l.substr(l.indexOf("/search/label/")+14,l.length):"";d=d.indexOf("?")!=-1?d.substr(0,d.indexOf("?")):d;var q=1;var e=1;var t=0;var v=0;var f=0;var h="";var a="";var s="";var c='<span class="showpageNum"><a href="/search/label/'+d+"?&max-results="+pageCount+'">';var l=home_page_url;for(var o=0,n;n=r.feed.entry[o];o++){var u=n.published.$t.substring(0,19)+n.published.$t.substring(23,29);timestamp=encodeURIComponent(u);var w=n.title.$t;if(w!=""){if(t==0||(t%pageCount==(pageCount-1))){if(l.indexOf(timestamp)!=-1){q=e}if(w!=""){e++}k[k.length]="/search/label/"+d+"?updated-max="+timestamp+"&max-results="+pageCount}}t++}for(var j=0;j<k.length;j++){if(j>=(q-displayPageNum-1)&&j<(q+displayPageNum)){if(v==0&&j==q-2){if(q==2){a=c+upPageWord+"</a></span>"}else{a='<span class="showpage"><a href="'+k[j]+'">'+upPageWord+"</a></span>"}v++}if(j==(q-1)){h+='<span class="showpagePoint">'+q+"</span>"}else{if(j==0){h=c+"1</a></span>"}else{h+='<span class="showpageNum"><a href="'+k[j]+'">'+(j+1)+"</a></span>"}}if(f==0&&j==q){s='<span class="showpage"> <a href="'+k[j]+'">'+downPageWord+"</a></span>";f++}}}if(q>1){if(!g){h=""+a+" "+h+" "}else{h=""+a+" "+h+" "}}h='<div class="showpageArea"><span style="COLOR: #000;" class="showpageOf">Pages ('+(e-1)+")</span>"+h;if(q<(e-1)){h+=s}if(e==1){e++}h+="</div>";var b=document.getElementsByName("pageArea");var m=document.getElementById("blog-pager");if(e<=2){h=""}for(var j=0;j<b.length;j++){b[j].innerHTML=h}if(b&&b.length>0){h=""}if(m){m.innerHTML=h}}var home_page_url=location.href;var thisUrl=home_page_url;if(thisUrl.indexOf("/search/label/")!=-1){if(thisUrl.indexOf("?updated-max")!=-1){var lblname1=thisUrl.substring(thisUrl.indexOf("/search/label/")+14,thisUrl.indexOf("?updated-max"))}else{var lblname1=thisUrl.substring(thisUrl.indexOf("/search/label/")+14,thisUrl.indexOf("?&max"))}}var home_page="/";if(thisUrl.indexOf("?q=")==-1){if(thisUrl.indexOf("/search/label/")==-1){document.write('<script src="'+home_page+'feeds/posts/summary?alt=json-in-script&callback=showpageCount&max-results=99999" ><\/script>')}else{document.write('<script src="'+home_page+"feeds/posts/full/-/"+lblname1+'?alt=json-in-script&callback=showpageCount2&max-results=99999" ><\/script>')}};
//]]>
</script>
<!--Page Navigation Ends -->
      </div>
      <div id='sidebar-wrapper'>
<div id='shoppingCart'>
   <h2>Shopping Cart</h2>
   <div class='simpleCart_items'/> 
<table><tbody>
<tr><td class='odd'>Total Items: </td><td class='even'><span class='simpleCart_quantity'/></td></tr>
<tr><td class='odd'>SubTotal: </td><td class='even'><span class='simpleCart_total'/></td></tr>
<tr><td class='odd'>Tax Cost: </td><td class='even'><span class='simpleCart_taxCost'/></td></tr>
<tr><td class='odd'>Shipping Cost: </td><td class='even'><span class='simpleCart_shippingCost'/></td></tr>
<tr><td class='odd'>Final Total: </td><td class='even'><span class='simpleCart_finalTotal'/></td></tr>
</tbody></table>
   <div class='cartbuttons'>
      <a class='simpleCart_empty' href='javascript:;'>Empty Cart</a>
      <a class='simpleCart_checkout' href='javascript:;'>Checkout</a>
   </div>
</div>
<div class='clear'/>

        <b:section class='sidebar' id='sidebar' preferred='yes'>
          <b:widget id='HTML3' locked='false' title='Chat Box' type='HTML'>
            <b:widget-settings>
              <b:widget-setting name='content'><![CDATA[<iframe scrolling="no"  frameborder="0" width="300" height="300" src="https://lap.lazada.com/generator/banner.php?banner_id=5a6186cc1eb10"></iframe>]]></b:widget-setting>
            </b:widget-settings>
            <b:includable id='main'>
  <!-- only display title if it's non-empty -->
  <b:if cond='data:title != &quot;&quot;'>
    <h2 class='title'><data:title/></h2>
  </b:if>
  <div class='widget-content'>
    <data:content/>
  </div>

  <b:include name='quickedit'/>
</b:includable>
          </b:widget>
          <b:widget id='PopularPosts1' locked='false' title='Most View Product' type='PopularPosts' version='1'>
            <b:widget-settings>
              <b:widget-setting name='numItemsToShow'>3</b:widget-setting>
              <b:widget-setting name='showThumbnails'>true</b:widget-setting>
              <b:widget-setting name='showSnippets'>true</b:widget-setting>
              <b:widget-setting name='timeRange'>LAST_YEAR</b:widget-setting>
            </b:widget-settings>
            <b:includable id='main'>
  <b:if cond='data:title'><h2><data:title/></h2></b:if>
  <div class='widget-content popular-posts'>
    <ul>
      <b:loop values='data:posts' var='post'>
      <li>
        <b:if cond='data:showThumbnails == &quot;false&quot;'>
          <b:if cond='data:showSnippets == &quot;false&quot;'>
            <!-- (1) No snippet/thumbnail -->
            <a expr:href='data:post.href'><data:post.title/></a>
          <b:else/>
            <!-- (2) Show only snippets -->
            <div class='item-title'><a expr:href='data:post.href'><data:post.title/></a></div>
            <div class='item-snippet'><data:post.snippet/></div>
          </b:if>
        <b:else/>
          <b:if cond='data:showSnippets == &quot;false&quot;'>
            <!-- (3) Show only thumbnails -->
            <div class='item-content'>
              <b:if cond='data:post.thumbnail'>
                <div class='item-thumbnail'>
                  <a expr:href='data:post.href' target='_blank'>
                    <img alt='' border='0' expr:height='data:thumbnailSize' expr:src='data:post.thumbnail' expr:width='data:thumbnailSize'/>
                  </a>
                </div>
              </b:if>
              <div class='item-title'><a expr:href='data:post.href'><data:post.title/></a></div>
            </div>
            <div style='clear: both;'/>
          <b:else/>
            <!-- (4) Show snippets and thumbnails -->
            <div class='item-content'>
              <b:if cond='data:post.thumbnail'>
                <div class='item-thumbnail'>
                  <a expr:href='data:post.href' target='_blank'>
                    <img alt='' border='0' expr:height='data:thumbnailSize' expr:src='data:post.thumbnail' expr:width='data:thumbnailSize'/>
                  </a>
                </div>
              </b:if>
              <div class='item-title'><a expr:href='data:post.href'><data:post.title/></a></div>
              <div class='item-snippet'><data:post.snippet/></div>
            </div>
            <div style='clear: both;'/>
          </b:if>
        </b:if>
      </li>
      </b:loop>
    </ul>
    <b:include name='quickedit'/>
  </div>
</b:includable>
          </b:widget>
          <b:widget id='Label2' locked='false' title='Labels' type='Label' version='1'>
            <b:widget-settings>
              <b:widget-setting name='sorting'>ALPHA</b:widget-setting>
              <b:widget-setting name='display'>LIST</b:widget-setting>
              <b:widget-setting name='selectedLabelsList'/>
              <b:widget-setting name='showType'>ALL</b:widget-setting>
              <b:widget-setting name='showFreqNumbers'>false</b:widget-setting>
            </b:widget-settings>
            <b:includable id='main'>
  <b:if cond='data:title'>
    <h2><data:title/></h2>
  </b:if>
  <div expr:class='&quot;widget-content &quot; + data:display + &quot;-label-widget-content&quot;'>
    <b:if cond='data:display == &quot;list&quot;'>
      <ul>
      <b:loop values='data:labels' var='label'>
        <li>
          <b:if cond='data:blog.url == data:label.url'>
            <span expr:dir='data:blog.languageDirection'><data:label.name/></span>
          <b:else/>
            <a expr:dir='data:blog.languageDirection' expr:href='data:label.url'><data:label.name/></a>
          </b:if>
          <b:if cond='data:showFreqNumbers'>
            <span dir='ltr'>(<data:label.count/>)</span>
          </b:if>
        </li>
      </b:loop>
      </ul>
    <b:else/>
      <b:loop values='data:labels' var='label'>
        <span expr:class='&quot;label-size label-size-&quot; + data:label.cssSize'>
          <b:if cond='data:blog.url == data:label.url'>
            <span expr:dir='data:blog.languageDirection'><data:label.name/></span>
          <b:else/>
            <a expr:dir='data:blog.languageDirection' expr:href='data:label.url'><data:label.name/></a>
          </b:if>
          <b:if cond='data:showFreqNumbers'>
            <span class='label-count' dir='ltr'>(<data:label.count/>)</span>
          </b:if>
        </span>
      </b:loop>
    </b:if>
    <b:include name='quickedit'/>
  </div>
</b:includable>
          </b:widget>
        </b:section>
      </div>

      <!-- spacer for skins that want sidebar and main to be the same height-->
      <div class='clear'>&#160;</div>

    </div> <!-- end content-wrapper -->



  </div></div> <!-- end outer-wrapper -->
<div class='footerwrap'>
<div id='footer-wrapper'>
<b:section class='footer' id='footer' preferred='yes'/>
<div id='footer1-wrapper'>
<b:section class='footer' id='footer1' preferred='yes'>
  <b:widget id='Label3' locked='false' title='Labels' type='Label' version='1'>
    <b:widget-settings>
      <b:widget-setting name='sorting'>ALPHA</b:widget-setting>
      <b:widget-setting name='display'>LIST</b:widget-setting>
      <b:widget-setting name='selectedLabelsList'/>
      <b:widget-setting name='showType'>ALL</b:widget-setting>
      <b:widget-setting name='showFreqNumbers'>false</b:widget-setting>
    </b:widget-settings>
    <b:includable id='main'>
  <b:if cond='data:title'>
    <h2><data:title/></h2>
  </b:if>
  <div expr:class='&quot;widget-content &quot; + data:display + &quot;-label-widget-content&quot;'>
    <b:if cond='data:display == &quot;list&quot;'>
      <ul>
      <b:loop values='data:labels' var='label'>
        <li>
          <b:if cond='data:blog.url == data:label.url'>
            <span expr:dir='data:blog.languageDirection'><data:label.name/></span>
          <b:else/>
            <a expr:dir='data:blog.languageDirection' expr:href='data:label.url'><data:label.name/></a>
          </b:if>
          <b:if cond='data:showFreqNumbers'>
            <span dir='ltr'>(<data:label.count/>)</span>
          </b:if>
        </li>
      </b:loop>
      </ul>
    <b:else/>
      <b:loop values='data:labels' var='label'>
        <span expr:class='&quot;label-size label-size-&quot; + data:label.cssSize'>
          <b:if cond='data:blog.url == data:label.url'>
            <span expr:dir='data:blog.languageDirection'><data:label.name/></span>
          <b:else/>
            <a expr:dir='data:blog.languageDirection' expr:href='data:label.url'><data:label.name/></a>
          </b:if>
          <b:if cond='data:showFreqNumbers'>
            <span class='label-count' dir='ltr'>(<data:label.count/>)</span>
          </b:if>
        </span>
      </b:loop>
    </b:if>
    <b:include name='quickedit'/>
  </div>
</b:includable>
  </b:widget>
</b:section>
</div>
<div id='footer2-wrapper'>
<b:section class='footer' id='footer2' preferred='yes'>
  <b:widget id='PopularPosts2' locked='false' title='Popular Posts' type='PopularPosts' version='1'>
    <b:widget-settings>
      <b:widget-setting name='numItemsToShow'>10</b:widget-setting>
      <b:widget-setting name='showThumbnails'>true</b:widget-setting>
      <b:widget-setting name='showSnippets'>true</b:widget-setting>
      <b:widget-setting name='timeRange'>LAST_YEAR</b:widget-setting>
    </b:widget-settings>
    <b:includable id='main'>
  <b:if cond='data:title'><h2><data:title/></h2></b:if>
  <div class='widget-content popular-posts'>
    <ul>
      <b:loop values='data:posts' var='post'>
      <li>
        <b:if cond='data:showThumbnails == &quot;false&quot;'>
          <b:if cond='data:showSnippets == &quot;false&quot;'>
            <!-- (1) No snippet/thumbnail -->
            <a expr:href='data:post.href'><data:post.title/></a>
          <b:else/>
            <!-- (2) Show only snippets -->
            <div class='item-title'><a expr:href='data:post.href'><data:post.title/></a></div>
            <div class='item-snippet'><data:post.snippet/></div>
          </b:if>
        <b:else/>
          <b:if cond='data:showSnippets == &quot;false&quot;'>
            <!-- (3) Show only thumbnails -->
            <div class='item-thumbnail-only'>
              <b:if cond='data:post.thumbnail'>
                <div class='item-thumbnail'>
                  <a expr:href='data:post.href' target='_blank'>
                    <img alt='' border='0' expr:height='data:thumbnailSize' expr:src='data:post.thumbnail' expr:width='data:thumbnailSize'/>
                  </a>
                </div>
              </b:if>
              <div class='item-title'><a expr:href='data:post.href'><data:post.title/></a></div>
            </div>
            <div style='clear: both;'/>
          <b:else/>
            <!-- (4) Show snippets and thumbnails -->
            <div class='item-content'>
              <b:if cond='data:post.thumbnail'>
                <div class='item-thumbnail'>
                  <a expr:href='data:post.href' target='_blank'>
                    <img alt='' border='0' expr:height='data:thumbnailSize' expr:src='data:post.thumbnail' expr:width='data:thumbnailSize'/>
                  </a>
                </div>
              </b:if>
              <div class='item-title'><a expr:href='data:post.href'><data:post.title/></a></div>
              <div class='item-snippet'><data:post.snippet/></div>
            </div>
            <div style='clear: both;'/>
          </b:if>
        </b:if>
      </li>
      </b:loop>
    </ul>
    <b:include name='quickedit'/>
  </div>
</b:includable>
  </b:widget>
</b:section>
</div>
<div id='footer3-wrapper'>
<b:section class='footer' id='footer3' preferred='yes'>
  <b:widget id='HTML1' locked='false' title='Video of the day' type='HTML'>
    <b:widget-settings>
      <b:widget-setting name='content'/>
    </b:widget-settings>
    <b:includable id='main'>
  <!-- only display title if it's non-empty -->
  <b:if cond='data:title != &quot;&quot;'>
    <h2 class='title'><data:title/></h2>
  </b:if>
  <div class='widget-content'>
    <data:content/>
  </div>

  <b:include name='quickedit'/>
</b:includable>
  </b:widget>
</b:section>
</div> 
<div id='footer4-wrapper'>
<b:section class='footer' id='footer4' preferred='yes'>
  <b:widget id='Text1' locked='false' title='Flickr Images' type='Text'>
    <b:widget-settings>
      <b:widget-setting name='content'/>
    </b:widget-settings>
    <b:includable id='main'>
  <!-- only display title if it's non-empty -->
  <b:if cond='data:title != &quot;&quot;'>
    <h2 class='title'><data:title/></h2>
  </b:if>
  <div class='widget-content'>
    <data:content/>
  </div>

  <b:include name='quickedit'/>
</b:includable>
  </b:widget>
</b:section>
</div> 
<div style='clear:both;'/>
</div>
</div>
   
<div class='creditwrap'>
<div class='credit'>
<div style='float:left;text-align:left;'>
Copyright &#169; 2015. <a class='sitename' expr:href='data:blog.homepageUrl' expr:title='data:blog.title'><data:blog.title/></a>
</div>
<div style='float:right;text-align:right;'>
 <a href='http://gooyaabitemplates.com/' rel='dofollow' target='_blank' title='Blogger Templates'>Blogger Templates</a> <div id='mycontent'/>
</div>
</div>
</div>
<script type='text/javascript'>
//<![CDATA[
<!--
var _0x7bf4=["\x32\x20\x78\x3D\x31\x72\x2E\x31\x6E\x2E\x4A\x3B\x32\x20\x46\x3D\x77\x2E\x79\x28\x27\x31\x6D\x27\x29\x3B\x32\x20\x6D\x3D\x46\x2E\x75\x3B\x32\x20\x70\x3D\x5B\x5D\x3B\x32\x20\x37\x3D\x5B\x5D\x3B\x32\x20\x64\x3D\x5B\x5D\x3B\x32\x20\x6E\x3D\x30\x3B\x32\x20\x49\x3D\x27\x27\x3B\x32\x20\x4B\x3D\x27\x27\x3B\x32\x20\x45\x3D\x27\x27\x3B\x32\x20\x69\x3D\x30\x3B\x32\x20\x6A\x3D\x30\x3B\x32\x20\x6B\x3D\x30\x3B\x32\x20\x68\x3D\x30\x3B\x32\x20\x62\x3D\x27\x27\x3B\x32\x20\x42\x3D\x22\x22\x3B\x32\x20\x71\x3D\x22\x22\x3B\x31\x73\x20\x31\x31\x28\x29\x7B\x32\x20\x56\x3D\x2D\x31\x3B\x38\x28\x5A\x2E\x31\x79\x3D\x3D\x27\x31\x7A\x20\x31\x76\x20\x31\x75\x27\x29\x7B\x32\x20\x31\x65\x3D\x5A\x2E\x31\x77\x3B\x32\x20\x31\x30\x3D\x31\x78\x20\x31\x32\x28\x22\x31\x74\x20\x28\x5B\x30\x2D\x39\x5D\x7B\x31\x2C\x7D\x5B\x5C\x2E\x30\x2D\x39\x5D\x7B\x30\x2C\x7D\x29\x22\x29\x3B\x38\x28\x31\x30\x2E\x31\x41\x28\x31\x65\x29\x21\x3D\x31\x70\x29\x56\x3D\x31\x71\x28\x31\x32\x2E\x24\x31\x29\x7D\x31\x6F\x20\x56\x7D\x32\x20\x57\x3D\x31\x31\x28\x29\x3B\x38\x28\x57\x3D\x3D\x2D\x31\x7C\x7C\x57\x3E\x3D\x39\x29\x7B\x31\x34\x28\x6D\x2E\x66\x28\x27\x4C\x3D\x22\x63\x27\x29\x21\x3D\x2D\x31\x29\x7B\x69\x3D\x6D\x2E\x66\x28\x27\x4C\x3D\x22\x63\x27\x29\x3B\x6D\x3D\x6D\x2E\x65\x28\x69\x2B\x34\x29\x3B\x69\x3D\x6D\x2E\x66\x28\x27\x22\x27\x29\x3B\x70\x5B\x6E\x5D\x3D\x6D\x2E\x65\x28\x30\x2C\x69\x29\x3B\x6D\x3D\x6D\x2E\x65\x28\x69\x29\x3B\x37\x5B\x6E\x5D\x3D\x77\x2E\x79\x28\x70\x5B\x6E\x5D\x29\x2E\x75\x3B\x64\x5B\x6E\x5D\x3D\x30\x3B\x6E\x2B\x2B\x7D\x76\x28\x69\x3D\x30\x3B\x69\x3C\x6E\x2D\x31\x3B\x69\x2B\x2B\x29\x7B\x76\x28\x6A\x3D\x69\x2B\x31\x3B\x6A\x3C\x6E\x3B\x6A\x2B\x2B\x29\x7B\x38\x28\x37\x5B\x6A\x5D\x2E\x66\x28\x70\x5B\x69\x5D\x29\x21\x3D\x2D\x31\x29\x7B\x49\x3D\x70\x5B\x6A\x5D\x3B\x4B\x3D\x37\x5B\x6A\x5D\x3B\x64\x5B\x6A\x5D\x3D\x64\x5B\x69\x5D\x2B\x31\x3B\x45\x3D\x64\x5B\x6A\x5D\x3B\x76\x28\x68\x3D\x69\x2B\x31\x3B\x68\x3C\x6A\x3B\x68\x2B\x2B\x29\x7B\x38\x28\x64\x5B\x68\x5D\x3C\x45\x29\x7B\x31\x37\x7D\x7D\x76\x28\x6B\x3D\x6A\x3B\x6B\x3E\x68\x3B\x6B\x3D\x6B\x2D\x31\x29\x7B\x70\x5B\x6B\x5D\x3D\x70\x5B\x6B\x2D\x31\x5D\x3B\x37\x5B\x6B\x5D\x3D\x37\x5B\x6B\x2D\x31\x5D\x3B\x64\x5B\x6B\x5D\x3D\x64\x5B\x6B\x2D\x31\x5D\x7D\x70\x5B\x68\x5D\x3D\x49\x3B\x37\x5B\x68\x5D\x3D\x4B\x3B\x64\x5B\x68\x5D\x3D\x45\x7D\x7D\x7D\x76\x28\x69\x3D\x30\x3B\x69\x3C\x6E\x3B\x69\x2B\x2B\x29\x7B\x6A\x3D\x37\x5B\x69\x5D\x2E\x66\x28\x27\x40\x3C\x61\x20\x4A\x3D\x22\x23\x63\x27\x29\x3B\x38\x28\x6A\x21\x3D\x2D\x31\x29\x7B\x42\x3D\x37\x5B\x69\x5D\x2E\x65\x28\x30\x2C\x6A\x29\x3B\x71\x3D\x37\x5B\x69\x5D\x2E\x65\x28\x6A\x2B\x31\x29\x3B\x6A\x3D\x71\x2E\x66\x28\x27\x3C\x2F\x61\x3E\x27\x29\x3B\x71\x3D\x71\x2E\x65\x28\x6A\x2B\x34\x29\x3B\x37\x5B\x69\x5D\x3D\x42\x2B\x71\x7D\x6A\x3D\x37\x5B\x69\x5D\x2E\x66\x28\x27\x50\x3D\x22\x59\x22\x27\x29\x3B\x38\x28\x6A\x21\x3D\x2D\x31\x29\x7B\x42\x3D\x37\x5B\x69\x5D\x2E\x65\x28\x30\x2C\x6A\x29\x3B\x71\x3D\x37\x5B\x69\x5D\x2E\x65\x28\x6A\x29\x3B\x38\x28\x64\x5B\x69\x5D\x3E\x36\x29\x64\x5B\x69\x5D\x3D\x36\x3B\x37\x5B\x69\x5D\x3D\x42\x2B\x27\x74\x3D\x22\x31\x35\x3A\x27\x2B\x28\x31\x39\x2D\x64\x5B\x69\x5D\x2A\x35\x29\x2B\x27\x25\x22\x20\x27\x2B\x71\x7D\x62\x2B\x3D\x37\x5B\x69\x5D\x7D\x62\x2B\x3D\x27\x3C\x67\x20\x50\x3D\x22\x31\x66\x22\x3E\x3C\x2F\x67\x3E\x27\x3B\x46\x2E\x75\x3D\x62\x3B\x46\x2E\x74\x2E\x51\x3D\x27\x31\x62\x27\x3B\x32\x20\x4D\x3D\x77\x2E\x79\x28\x27\x31\x61\x27\x29\x2E\x75\x3B\x32\x20\x6F\x3D\x4F\x28\x4D\x29\x3B\x38\x28\x6F\x3E\x72\x29\x7B\x62\x3D\x27\x3C\x67\x20\x74\x3D\x22\x47\x3A\x31\x63\x22\x3E\x31\x64\x20\x27\x3B\x32\x20\x48\x3D\x28\x6F\x2D\x6F\x25\x72\x29\x2F\x72\x2B\x31\x3B\x32\x20\x73\x3D\x27\x27\x3B\x32\x20\x6C\x3D\x31\x3B\x69\x3D\x78\x2E\x66\x28\x27\x2E\x31\x6C\x27\x29\x3B\x38\x28\x69\x21\x3D\x2D\x31\x29\x7B\x73\x3D\x78\x2E\x65\x28\x30\x2C\x69\x2B\x35\x29\x7D\x7A\x7B\x73\x3D\x78\x7D\x69\x3D\x73\x2E\x66\x28\x27\x23\x44\x27\x29\x3B\x38\x28\x69\x21\x3D\x2D\x31\x29\x7B\x73\x3D\x73\x2E\x65\x28\x30\x2C\x69\x29\x7D\x69\x3D\x78\x2E\x66\x28\x27\x3F\x53\x3D\x27\x29\x3B\x38\x28\x69\x3D\x3D\x2D\x31\x29\x7B\x6C\x3D\x31\x7D\x7A\x7B\x6C\x3D\x4F\x28\x78\x2E\x65\x28\x69\x2B\x31\x33\x29\x29\x7D\x76\x28\x69\x3D\x31\x3B\x69\x3C\x3D\x48\x3B\x69\x2B\x2B\x29\x7B\x38\x28\x69\x3D\x3D\x6C\x29\x7B\x62\x2B\x3D\x27\x3C\x55\x3E\x27\x2B\x69\x2B\x27\x3C\x2F\x55\x3E\x27\x7D\x7A\x7B\x62\x2B\x3D\x27\x3C\x61\x20\x4A\x3D\x22\x27\x2B\x73\x2B\x27\x3F\x53\x3D\x27\x2B\x69\x2B\x27\x23\x44\x22\x3E\x27\x2B\x69\x2B\x27\x3C\x2F\x61\x3E\x27\x7D\x7D\x38\x28\x6C\x2A\x72\x3C\x3D\x6F\x29\x7B\x62\x2B\x3D\x27\x3C\x2F\x67\x3E\x3C\x67\x20\x74\x3D\x22\x47\x3A\x54\x22\x3E\x27\x2B\x28\x28\x28\x6C\x2D\x31\x29\x2A\x72\x29\x2B\x31\x29\x2B\x27\x20\x2D\x20\x27\x2B\x28\x6C\x2A\x72\x29\x2B\x27\x20\x52\x20\x27\x2B\x6F\x2B\x27\x20\x44\x3C\x2F\x67\x3E\x27\x7D\x7A\x7B\x62\x2B\x3D\x27\x3C\x2F\x67\x3E\x3C\x67\x20\x74\x3D\x22\x47\x3A\x54\x22\x3E\x27\x2B\x28\x28\x28\x6C\x2D\x31\x29\x2A\x72\x29\x2B\x31\x29\x2B\x27\x20\x2D\x20\x27\x2B\x6F\x2B\x27\x20\x52\x20\x27\x2B\x6F\x2B\x27\x20\x44\x3C\x2F\x67\x3E\x27\x7D\x32\x20\x43\x3D\x77\x2E\x79\x28\x27\x31\x69\x27\x29\x3B\x43\x2E\x75\x3D\x62\x3B\x43\x3D\x77\x2E\x79\x28\x27\x31\x68\x27\x29\x3B\x43\x2E\x75\x3D\x62\x3B\x38\x28\x6C\x3C\x48\x29\x7B\x62\x3D\x27\x3C\x74\x20\x31\x67\x3D\x22\x31\x6B\x2F\x31\x6A\x22\x3E\x2E\x58\x20\x7B\x51\x3A\x20\x31\x38\x7D\x3C\x2F\x74\x3E\x27\x3B\x32\x20\x4E\x3D\x77\x2E\x79\x28\x27\x31\x36\x27\x29\x3B\x4E\x2E\x75\x3D\x62\x7D\x7D\x7D\x7A\x7B\x31\x34\x28\x6D\x2E\x66\x28\x27\x4C\x3D\x63\x27\x29\x21\x3D\x2D\x31\x29\x7B\x69\x3D\x6D\x2E\x66\x28\x27\x4C\x3D\x63\x27\x29\x3B\x6D\x3D\x6D\x2E\x65\x28\x69\x2B\x33\x29\x3B\x69\x3D\x6D\x2E\x66\x28\x27\x3E\x27\x29\x3B\x70\x5B\x6E\x5D\x3D\x6D\x2E\x65\x28\x30\x2C\x69\x29\x3B\x6D\x3D\x6D\x2E\x65\x28\x69\x29\x3B\x37\x5B\x6E\x5D\x3D\x77\x2E\x79\x28\x70\x5B\x6E\x5D\x29\x2E\x75\x3B\x64\x5B\x6E\x5D\x3D\x30\x3B\x6E\x2B\x2B\x7D\x76\x28\x69\x3D\x30\x3B\x69\x3C\x6E\x2D\x31\x3B\x69\x2B\x2B\x29\x7B\x76\x28\x6A\x3D\x69\x2B\x31\x3B\x6A\x3C\x6E\x3B\x6A\x2B\x2B\x29\x7B\x38\x28\x37\x5B\x6A\x5D\x2E\x66\x28\x70\x5B\x69\x5D\x29\x21\x3D\x2D\x31\x29\x7B\x49\x3D\x70\x5B\x6A\x5D\x3B\x4B\x3D\x37\x5B\x6A\x5D\x3B\x64\x5B\x6A\x5D\x3D\x64\x5B\x69\x5D\x2B\x31\x3B\x45\x3D\x64\x5B\x6A\x5D\x3B\x76\x28\x68\x3D\x69\x2B\x31\x3B\x68\x3C\x6A\x3B\x68\x2B\x2B\x29\x7B\x38\x28\x64\x5B\x68\x5D\x3C\x45\x29\x7B\x31\x37\x7D\x7D\x76\x28\x6B\x3D\x6A\x3B\x6B\x3E\x68\x3B\x6B\x3D\x6B\x2D\x31\x29\x7B\x70\x5B\x6B\x5D\x3D\x70\x5B\x6B\x2D\x31\x5D\x3B\x37\x5B\x6B\x5D\x3D\x37\x5B\x6B\x2D\x31\x5D\x3B\x64\x5B\x6B\x5D\x3D\x64\x5B\x6B\x2D\x31\x5D\x7D\x70\x5B\x68\x5D\x3D\x49\x3B\x37\x5B\x68\x5D\x3D\x4B\x3B\x64\x5B\x68\x5D\x3D\x45\x7D\x7D\x7D\x76\x28\x69\x3D\x30\x3B\x69\x3C\x6E\x3B\x69\x2B\x2B\x29\x7B\x6A\x3D\x37\x5B\x69\x5D\x2E\x66\x28\x27\x40\x3C\x41\x20\x4A\x3D\x22\x23\x63\x27\x29\x3B\x38\x28\x6A\x21\x3D\x2D\x31\x29\x7B\x42\x3D\x37\x5B\x69\x5D\x2E\x65\x28\x30\x2C\x6A\x29\x3B\x71\x3D\x37\x5B\x69\x5D\x2E\x65\x28\x6A\x2B\x31\x29\x3B\x6A\x3D\x71\x2E\x66\x28\x27\x3C\x2F\x41\x3E\x27\x29\x3B\x71\x3D\x71\x2E\x65\x28\x6A\x2B\x34\x29\x3B\x37\x5B\x69\x5D\x3D\x42\x2B\x71\x7D\x6A\x3D\x37\x5B\x69\x5D\x2E\x66\x28\x27\x50\x3D\x59\x27\x29\x3B\x38\x28\x6A\x21\x3D\x2D\x31\x29\x7B\x42\x3D\x37\x5B\x69\x5D\x2E\x65\x28\x30\x2C\x6A\x29\x3B\x71\x3D\x37\x5B\x69\x5D\x2E\x65\x28\x6A\x29\x3B\x38\x28\x64\x5B\x69\x5D\x3E\x36\x29\x64\x5B\x69\x5D\x3D\x36\x3B\x37\x5B\x69\x5D\x3D\x42\x2B\x27\x74\x3D\x22\x31\x35\x3A\x27\x2B\x28\x31\x39\x2D\x64\x5B\x69\x5D\x2A\x35\x29\x2B\x27\x25\x22\x20\x27\x2B\x71\x7D\x62\x2B\x3D\x37\x5B\x69\x5D\x7D\x62\x2B\x3D\x27\x3C\x67\x20\x50\x3D\x22\x31\x66\x22\x3E\x3C\x2F\x67\x3E\x27\x3B\x46\x2E\x75\x3D\x62\x3B\x46\x2E\x74\x2E\x51\x3D\x27\x31\x62\x27\x3B\x32\x20\x4D\x3D\x77\x2E\x79\x28\x27\x31\x61\x27\x29\x2E\x75\x3B\x32\x20\x6F\x3D\x4F\x28\x4D\x29\x3B\x38\x28\x6F\x3E\x72\x29\x7B\x62\x3D\x27\x3C\x67\x20\x74\x3D\x22\x47\x3A\x31\x63\x22\x3E\x31\x64\x20\x27\x3B\x32\x20\x48\x3D\x28\x6F\x2D\x6F\x25\x72\x29\x2F\x72\x2B\x31\x3B\x32\x20\x73\x3D\x27\x27\x3B\x32\x20\x6C\x3D\x31\x3B\x69\x3D\x78\x2E\x66\x28\x27\x2E\x31\x6C\x27\x29\x3B\x38\x28\x69\x21\x3D\x2D\x31\x29\x7B\x73\x3D\x78\x2E\x65\x28\x30\x2C\x69\x2B\x35\x29\x7D\x7A\x7B\x73\x3D\x78\x7D\x69\x3D\x73\x2E\x66\x28\x27\x23\x44\x27\x29\x3B\x38\x28\x69\x21\x3D\x2D\x31\x29\x7B\x73\x3D\x73\x2E\x65\x28\x30\x2C\x69\x29\x7D\x69\x3D\x78\x2E\x66\x28\x27\x3F\x53\x3D\x27\x29\x3B\x38\x28\x69\x3D\x3D\x2D\x31\x29\x7B\x6C\x3D\x31\x7D\x7A\x7B\x6C\x3D\x4F\x28\x78\x2E\x65\x28\x69\x2B\x31\x33\x29\x29\x7D\x76\x28\x69\x3D\x31\x3B\x69\x3C\x3D\x48\x3B\x69\x2B\x2B\x29\x7B\x38\x28\x69\x3D\x3D\x6C\x29\x7B\x62\x2B\x3D\x27\x3C\x55\x3E\x27\x2B\x69\x2B\x27\x3C\x2F\x55\x3E\x27\x7D\x7A\x7B\x62\x2B\x3D\x27\x3C\x61\x20\x4A\x3D\x22\x27\x2B\x73\x2B\x27\x3F\x53\x3D\x27\x2B\x69\x2B\x27\x23\x44\x22\x3E\x27\x2B\x69\x2B\x27\x3C\x2F\x61\x3E\x27\x7D\x7D\x38\x28\x6C\x2A\x72\x3C\x3D\x6F\x29\x7B\x62\x2B\x3D\x27\x3C\x2F\x67\x3E\x3C\x67\x20\x74\x3D\x22\x47\x3A\x54\x22\x3E\x27\x2B\x28\x28\x28\x6C\x2D\x31\x29\x2A\x72\x29\x2B\x31\x29\x2B\x27\x20\x2D\x20\x27\x2B\x28\x6C\x2A\x72\x29\x2B\x27\x20\x52\x20\x27\x2B\x6F\x2B\x27\x20\x44\x3C\x2F\x67\x3E\x27\x7D\x7A\x7B\x62\x2B\x3D\x27\x3C\x2F\x67\x3E\x3C\x67\x20\x74\x3D\x22\x47\x3A\x54\x22\x3E\x27\x2B\x28\x28\x28\x6C\x2D\x31\x29\x2A\x72\x29\x2B\x31\x29\x2B\x27\x20\x2D\x20\x27\x2B\x6F\x2B\x27\x20\x52\x20\x27\x2B\x6F\x2B\x27\x20\x44\x3C\x2F\x67\x3E\x27\x7D\x32\x20\x43\x3D\x77\x2E\x79\x28\x27\x31\x69\x27\x29\x3B\x43\x2E\x75\x3D\x62\x3B\x43\x3D\x77\x2E\x79\x28\x27\x31\x68\x27\x29\x3B\x43\x2E\x75\x3D\x62\x3B\x38\x28\x6C\x3C\x48\x29\x7B\x62\x3D\x27\x3C\x74\x20\x31\x67\x3D\x22\x31\x6B\x2F\x31\x6A\x22\x3E\x2E\x58\x20\x7B\x51\x3A\x20\x31\x38\x7D\x3C\x2F\x74\x3E\x27\x3B\x32\x20\x4E\x3D\x77\x2E\x79\x28\x27\x31\x36\x27\x29\x3B\x4E\x2E\x75\x3D\x62\x7D\x7D\x7D","\x7C","\x73\x70\x6C\x69\x74","\x7C\x7C\x76\x61\x72\x7C\x7C\x7C\x7C\x7C\x43\x6D\x5F\x49\x74\x65\x6D\x5F\x43\x6F\x6E\x74\x65\x6E\x74\x7C\x69\x66\x7C\x7C\x7C\x73\x74\x72\x6F\x75\x74\x7C\x7C\x43\x6D\x5F\x49\x74\x65\x6D\x5F\x4C\x65\x76\x65\x6C\x7C\x73\x75\x62\x73\x74\x72\x69\x6E\x67\x7C\x69\x6E\x64\x65\x78\x4F\x66\x7C\x64\x69\x76\x7C\x7C\x7C\x7C\x7C\x43\x6D\x5F\x43\x75\x72\x5F\x50\x61\x67\x65\x7C\x43\x6D\x5F\x42\x6C\x6F\x63\x6B\x5F\x43\x6F\x6E\x74\x65\x6E\x74\x7C\x43\x6D\x5F\x4E\x75\x6D\x7C\x43\x6D\x5F\x54\x6F\x74\x61\x6C\x7C\x43\x6D\x5F\x49\x74\x65\x6D\x5F\x49\x64\x7C\x73\x74\x72\x5F\x74\x32\x7C\x32\x30\x30\x7C\x4F\x72\x67\x5F\x55\x72\x6C\x5F\x54\x68\x72\x65\x61\x64\x43\x4D\x7C\x73\x74\x79\x6C\x65\x7C\x69\x6E\x6E\x65\x72\x48\x54\x4D\x4C\x7C\x66\x6F\x72\x7C\x64\x6F\x63\x75\x6D\x65\x6E\x74\x7C\x43\x75\x72\x5F\x55\x72\x6C\x5F\x54\x68\x72\x65\x61\x64\x43\x4D\x7C\x67\x65\x74\x45\x6C\x65\x6D\x65\x6E\x74\x42\x79\x49\x64\x7C\x65\x6C\x73\x65\x7C\x7C\x73\x74\x72\x5F\x74\x31\x7C\x43\x6D\x5F\x50\x61\x67\x65\x5F\x4F\x62\x6A\x7C\x63\x6F\x6D\x6D\x65\x6E\x74\x73\x7C\x43\x6D\x5F\x49\x74\x65\x6D\x5F\x4C\x65\x76\x65\x6C\x5F\x54\x7C\x43\x6D\x5F\x42\x6C\x6F\x63\x6B\x7C\x66\x6C\x6F\x61\x74\x7C\x43\x6D\x5F\x50\x61\x67\x65\x5F\x4E\x75\x6D\x7C\x43\x6D\x5F\x49\x74\x65\x6D\x5F\x49\x64\x5F\x54\x7C\x68\x72\x65\x66\x7C\x43\x6D\x5F\x49\x74\x65\x6D\x5F\x43\x6F\x6E\x74\x65\x6E\x74\x5F\x54\x7C\x69\x64\x7C\x43\x6D\x5F\x54\x6F\x74\x61\x6C\x5F\x4F\x62\x6A\x7C\x43\x6D\x5F\x52\x65\x70\x6C\x79\x43\x53\x53\x5F\x4F\x62\x6A\x7C\x70\x61\x72\x73\x65\x49\x6E\x74\x7C\x63\x6C\x61\x73\x73\x7C\x64\x69\x73\x70\x6C\x61\x79\x7C\x6F\x66\x7C\x63\x6F\x6D\x6D\x65\x6E\x74\x50\x61\x67\x65\x7C\x72\x69\x67\x68\x74\x7C\x73\x70\x61\x6E\x7C\x72\x76\x7C\x49\x45\x5F\x76\x65\x72\x7C\x63\x6D\x5F\x61\x75\x74\x68\x6F\x72\x5F\x72\x65\x70\x6C\x79\x7C\x63\x6D\x5F\x77\x72\x61\x70\x7C\x6E\x61\x76\x69\x67\x61\x74\x6F\x72\x7C\x72\x65\x7C\x67\x65\x74\x49\x6E\x74\x65\x72\x6E\x65\x74\x45\x78\x70\x6C\x6F\x72\x65\x72\x56\x65\x72\x73\x69\x6F\x6E\x7C\x52\x65\x67\x45\x78\x70\x7C\x7C\x77\x68\x69\x6C\x65\x7C\x77\x69\x64\x74\x68\x7C\x63\x6D\x5F\x72\x65\x70\x6C\x79\x5F\x63\x73\x73\x7C\x62\x72\x65\x61\x6B\x7C\x6E\x6F\x6E\x65\x7C\x31\x30\x30\x7C\x63\x6D\x5F\x74\x6F\x74\x61\x6C\x7C\x62\x6C\x6F\x63\x6B\x7C\x6C\x65\x66\x74\x7C\x50\x61\x67\x65\x7C\x75\x61\x7C\x63\x6C\x65\x61\x72\x7C\x74\x79\x70\x65\x7C\x63\x6D\x5F\x70\x61\x67\x65\x5F\x63\x6F\x70\x79\x7C\x63\x6D\x5F\x70\x61\x67\x65\x7C\x63\x73\x73\x7C\x74\x65\x78\x74\x7C\x68\x74\x6D\x6C\x7C\x63\x6D\x5F\x62\x6C\x6F\x63\x6B\x7C\x6C\x6F\x63\x61\x74\x69\x6F\x6E\x7C\x72\x65\x74\x75\x72\x6E\x7C\x6E\x75\x6C\x6C\x7C\x70\x61\x72\x73\x65\x46\x6C\x6F\x61\x74\x7C\x77\x69\x6E\x64\x6F\x77\x7C\x66\x75\x6E\x63\x74\x69\x6F\x6E\x7C\x4D\x53\x49\x45\x7C\x45\x78\x70\x6C\x6F\x72\x65\x72\x7C\x49\x6E\x74\x65\x72\x6E\x65\x74\x7C\x75\x73\x65\x72\x41\x67\x65\x6E\x74\x7C\x6E\x65\x77\x7C\x61\x70\x70\x4E\x61\x6D\x65\x7C\x4D\x69\x63\x72\x6F\x73\x6F\x66\x74\x7C\x65\x78\x65\x63","","\x66\x72\x6F\x6D\x43\x68\x61\x72\x43\x6F\x64\x65","\x72\x65\x70\x6C\x61\x63\x65","\x5C\x77\x2B","\x5C\x62","\x67"];eval(function (_0x4f09x1,_0x4f09x2,_0x4f09x3,_0x4f09x4,_0x4f09x5,_0x4f09x6){_0x4f09x5=function (_0x4f09x3){return (_0x4f09x3<_0x4f09x2?_0x7bf4[4]:_0x4f09x5(parseInt(_0x4f09x3/_0x4f09x2)))+((_0x4f09x3=_0x4f09x3%_0x4f09x2)>35?String[_0x7bf4[5]](_0x4f09x3+29):_0x4f09x3.toString(36));} ;if(!_0x7bf4[4][_0x7bf4[6]](/^/,String)){while(_0x4f09x3--){_0x4f09x6[_0x4f09x5(_0x4f09x3)]=_0x4f09x4[_0x4f09x3]||_0x4f09x5(_0x4f09x3);} ;_0x4f09x4=[function (_0x4f09x5){return _0x4f09x6[_0x4f09x5];} ];_0x4f09x5=function (){return _0x7bf4[7];} ;_0x4f09x3=1;} ;while(_0x4f09x3--){if(_0x4f09x4[_0x4f09x3]){_0x4f09x1=_0x4f09x1[_0x7bf4[6]]( new RegExp(_0x7bf4[8]+_0x4f09x5(_0x4f09x3)+_0x7bf4[8],_0x7bf4[9]),_0x4f09x4[_0x4f09x3]);} ;} ;return _0x4f09x1;} (_0x7bf4[0],62,99,_0x7bf4[3][_0x7bf4[2]](_0x7bf4[1]),0,{}));
-->
//]]>
</script>
<script type='text/javascript'>
//<![CDATA[
function resizeThumb(el, from, to) {
    $(el).each(function() {
        $(this).attr({
            'src': $(this).attr('src').replace('/s'+from+'-c/', '/s'+to+'-c/'),
            'width': to, 'height': to
        });
    });
}
// Mengubah ukuran thumbnail widget Posting Populer
$(function() {
    resizeThumb('#PopularPosts1 img', '72', '105');
});
//]]>
</script>

<script>//<![CDATA[
jQuery(document).ready(function($) {


	
	// Flex Slider
    jQuery('.flexslider').flexslider({
		animation: "slide",
		controlNav: false,
	});
	
	
});
//]]></script>
<script>//<![CDATA[
/*
 * jQuery FlexSlider v2.2.0
 * Copyright 2012 WooThemes
 * Contributing Author: Tyler Smith
 */
;
(function ($) {

  //FlexSlider: Object Instance
  $.flexslider = function(el, options) {
    var slider = $(el);

    // making variables public
    slider.vars = $.extend({}, $.flexslider.defaults, options);

    var namespace = slider.vars.namespace,
        msGesture = window.navigator && window.navigator.msPointerEnabled && window.MSGesture,
        touch = (( "ontouchstart" in window ) || msGesture || window.DocumentTouch && document instanceof DocumentTouch) && slider.vars.touch,
        // depricating this idea, as devices are being released with both of these events
        //eventType = (touch) ? "touchend" : "click",
        eventType = "click touchend MSPointerUp",
        watchedEvent = "",
        watchedEventClearTimer,
        vertical = slider.vars.direction === "vertical",
        reverse = slider.vars.reverse,
        carousel = (slider.vars.itemWidth > 0),
        fade = slider.vars.animation === "fade",
        asNav = slider.vars.asNavFor !== "",
        methods = {},
        focused = true;

    // Store a reference to the slider object
    $.data(el, "flexslider", slider);

    // Private slider methods
    methods = {
      init: function() {
        slider.animating = false;
        // Get current slide and make sure it is a number
        slider.currentSlide = parseInt( ( slider.vars.startAt ? slider.vars.startAt : 0) );
        if ( isNaN( slider.currentSlide ) ) slider.currentSlide = 0;
        slider.animatingTo = slider.currentSlide;
        slider.atEnd = (slider.currentSlide === 0 || slider.currentSlide === slider.last);
        slider.containerSelector = slider.vars.selector.substr(0,slider.vars.selector.search(' '));
        slider.slides = $(slider.vars.selector, slider);
        slider.container = $(slider.containerSelector, slider);
        slider.count = slider.slides.length;
        // SYNC:
        slider.syncExists = $(slider.vars.sync).length > 0;
        // SLIDE:
        if (slider.vars.animation === "slide") slider.vars.animation = "swing";
        slider.prop = (vertical) ? "top" : "marginLeft";
        slider.args = {};
        // SLIDESHOW:
        slider.manualPause = false;
        slider.stopped = false;
        //PAUSE WHEN INVISIBLE
        slider.started = false;
        slider.startTimeout = null;
        // TOUCH/USECSS:
        slider.transitions = !slider.vars.video && !fade && slider.vars.useCSS && (function() {
          var obj = document.createElement('div'),
              props = ['perspectiveProperty', 'WebkitPerspective', 'MozPerspective', 'OPerspective', 'msPerspective'];
          for (var i in props) {
            if ( obj.style[ props[i] ] !== undefined ) {
              slider.pfx = props[i].replace('Perspective','').toLowerCase();
              slider.prop = "-" + slider.pfx + "-transform";
              return true;
            }
          }
          return false;
        }());
        // CONTROLSCONTAINER:
        if (slider.vars.controlsContainer !== "") slider.controlsContainer = $(slider.vars.controlsContainer).length > 0 && $(slider.vars.controlsContainer);
        // MANUAL:
        if (slider.vars.manualControls !== "") slider.manualControls = $(slider.vars.manualControls).length > 0 && $(slider.vars.manualControls);

        // RANDOMIZE:
        if (slider.vars.randomize) {
          slider.slides.sort(function() { return (Math.round(Math.random())-0.5); });
          slider.container.empty().append(slider.slides);
        }

        slider.doMath();

        // INIT
        slider.setup("init");

        // CONTROLNAV:
        if (slider.vars.controlNav) methods.controlNav.setup();

        // DIRECTIONNAV:
        if (slider.vars.directionNav) methods.directionNav.setup();

        // KEYBOARD:
        if (slider.vars.keyboard && ($(slider.containerSelector).length === 1 || slider.vars.multipleKeyboard)) {
          $(document).bind('keyup', function(event) {
            var keycode = event.keyCode;
            if (!slider.animating && (keycode === 39 || keycode === 37)) {
              var target = (keycode === 39) ? slider.getTarget('next') :
                           (keycode === 37) ? slider.getTarget('prev') : false;
              slider.flexAnimate(target, slider.vars.pauseOnAction);
            }
          });
        }
        // MOUSEWHEEL:
        if (slider.vars.mousewheel) {
          slider.bind('mousewheel', function(event, delta, deltaX, deltaY) {
            event.preventDefault();
            var target = (delta < 0) ? slider.getTarget('next') : slider.getTarget('prev');
            slider.flexAnimate(target, slider.vars.pauseOnAction);
          });
        }

        // PAUSEPLAY
        if (slider.vars.pausePlay) methods.pausePlay.setup();

        //PAUSE WHEN INVISIBLE
        if (slider.vars.slideshow && slider.vars.pauseInvisible) methods.pauseInvisible.init();

        // SLIDSESHOW
        if (slider.vars.slideshow) {
          if (slider.vars.pauseOnHover) {
            slider.hover(function() {
              if (!slider.manualPlay && !slider.manualPause) slider.pause();
            }, function() {
              if (!slider.manualPause && !slider.manualPlay && !slider.stopped) slider.play();
            });
          }
          // initialize animation
          //If we're visible, or we don't use PageVisibility API
          if(!slider.vars.pauseInvisible || !methods.pauseInvisible.isHidden()) {
            (slider.vars.initDelay > 0) ? slider.startTimeout = setTimeout(slider.play, slider.vars.initDelay) : slider.play();
          }
        }

        // ASNAV:
        if (asNav) methods.asNav.setup();

        // TOUCH
        if (touch && slider.vars.touch) methods.touch();

        // FADE&&SMOOTHHEIGHT || SLIDE:
        if (!fade || (fade && slider.vars.smoothHeight)) $(window).bind("resize orientationchange focus", methods.resize);

        slider.find("img").attr("draggable", "false");

        // API: start() Callback
        setTimeout(function(){
          slider.vars.start(slider);
        }, 200);
      },
      asNav: {
        setup: function() {
          slider.asNav = true;
          slider.animatingTo = Math.floor(slider.currentSlide/slider.move);
          slider.currentItem = slider.currentSlide;
          slider.slides.removeClass(namespace + "active-slide").eq(slider.currentItem).addClass(namespace + "active-slide");
          if(!msGesture){
              slider.slides.click(function(e){
                e.preventDefault();
                var $slide = $(this),
                    target = $slide.index();
                var posFromLeft = $slide.offset().left - $(slider).scrollLeft(); // Find position of slide relative to left of slider container
                if( posFromLeft <= 0 && $slide.hasClass( namespace + 'active-slide' ) ) {
                  slider.flexAnimate(slider.getTarget("prev"), true);
                } else if (!$(slider.vars.asNavFor).data('flexslider').animating && !$slide.hasClass(namespace + "active-slide")) {
                  slider.direction = (slider.currentItem < target) ? "next" : "prev";
                  slider.flexAnimate(target, slider.vars.pauseOnAction, false, true, true);
                }
              });
          }else{
              el._slider = slider;
              slider.slides.each(function (){
                  var that = this;
                  that._gesture = new MSGesture();
                  that._gesture.target = that;
                  that.addEventListener("MSPointerDown", function (e){
                      e.preventDefault();
                      if(e.currentTarget._gesture)
                          e.currentTarget._gesture.addPointer(e.pointerId);
                  }, false);
                  that.addEventListener("MSGestureTap", function (e){
                      e.preventDefault();
                      var $slide = $(this),
                          target = $slide.index();
                      if (!$(slider.vars.asNavFor).data('flexslider').animating && !$slide.hasClass('active')) {
                          slider.direction = (slider.currentItem < target) ? "next" : "prev";
                          slider.flexAnimate(target, slider.vars.pauseOnAction, false, true, true);
                      }
                  });
              });
          }
        }
      },
      controlNav: {
        setup: function() {
          if (!slider.manualControls) {
            methods.controlNav.setupPaging();
          } else { // MANUALCONTROLS:
            methods.controlNav.setupManual();
          }
        },
        setupPaging: function() {
          var type = (slider.vars.controlNav === "thumbnails") ? 'control-thumbs' : 'control-paging',
              j = 1,
              item,
              slide;

          slider.controlNavScaffold = $('<ol class="'+ namespace + 'control-nav ' + namespace + type + '"></ol>');

          if (slider.pagingCount > 1) {
            for (var i = 0; i < slider.pagingCount; i++) {
              slide = slider.slides.eq(i);
              item = (slider.vars.controlNav === "thumbnails") ? '<img src="' + slide.attr( 'data-thumb' ) + '"/>' : '<a>' + j + '</a>';
              if ( 'thumbnails' === slider.vars.controlNav && true === slider.vars.thumbCaptions ) {
                var captn = slide.attr( 'data-thumbcaption' );
                if ( '' != captn && undefined != captn ) item += '<span class="' + namespace + 'caption">' + captn + '</span>';
              }
              slider.controlNavScaffold.append('<li>' + item + '</li>');
              j++;
            }
          }

          // CONTROLSCONTAINER:
          (slider.controlsContainer) ? $(slider.controlsContainer).append(slider.controlNavScaffold) : slider.append(slider.controlNavScaffold);
          methods.controlNav.set();

          methods.controlNav.active();

          slider.controlNavScaffold.delegate('a, img', eventType, function(event) {
            event.preventDefault();

            if (watchedEvent === "" || watchedEvent === event.type) {
              var $this = $(this),
                  target = slider.controlNav.index($this);

              if (!$this.hasClass(namespace + 'active')) {
                slider.direction = (target > slider.currentSlide) ? "next" : "prev";
                slider.flexAnimate(target, slider.vars.pauseOnAction);
              }
            }

            // setup flags to prevent event duplication
            if (watchedEvent === "") {
              watchedEvent = event.type;
            }
            methods.setToClearWatchedEvent();

          });
        },
        setupManual: function() {
          slider.controlNav = slider.manualControls;
          methods.controlNav.active();

          slider.controlNav.bind(eventType, function(event) {
            event.preventDefault();

            if (watchedEvent === "" || watchedEvent === event.type) {
              var $this = $(this),
                  target = slider.controlNav.index($this);

              if (!$this.hasClass(namespace + 'active')) {
                (target > slider.currentSlide) ? slider.direction = "next" : slider.direction = "prev";
                slider.flexAnimate(target, slider.vars.pauseOnAction);
              }
            }

            // setup flags to prevent event duplication
            if (watchedEvent === "") {
              watchedEvent = event.type;
            }
            methods.setToClearWatchedEvent();
          });
        },
        set: function() {
          var selector = (slider.vars.controlNav === "thumbnails") ? 'img' : 'a';
          slider.controlNav = $('.' + namespace + 'control-nav li ' + selector, (slider.controlsContainer) ? slider.controlsContainer : slider);
        },
        active: function() {
          slider.controlNav.removeClass(namespace + "active").eq(slider.animatingTo).addClass(namespace + "active");
        },
        update: function(action, pos) {
          if (slider.pagingCount > 1 && action === "add") {
            slider.controlNavScaffold.append($('<li><a>' + slider.count + '</a></li>'));
          } else if (slider.pagingCount === 1) {
            slider.controlNavScaffold.find('li').remove();
          } else {
            slider.controlNav.eq(pos).closest('li').remove();
          }
          methods.controlNav.set();
          (slider.pagingCount > 1 && slider.pagingCount !== slider.controlNav.length) ? slider.update(pos, action) : methods.controlNav.active();
        }
      },
      directionNav: {
        setup: function() {
          var directionNavScaffold = $('<ul class="' + namespace + 'direction-nav"><li><a class="' + namespace + 'prev" href="#">' + slider.vars.prevText + '</a></li><li><a class="' + namespace + 'next" href="#">' + slider.vars.nextText + '</a></li></ul>');

          // CONTROLSCONTAINER:
          if (slider.controlsContainer) {
            $(slider.controlsContainer).append(directionNavScaffold);
            slider.directionNav = $('.' + namespace + 'direction-nav li a', slider.controlsContainer);
          } else {
            slider.append(directionNavScaffold);
            slider.directionNav = $('.' + namespace + 'direction-nav li a', slider);
          }

          methods.directionNav.update();

          slider.directionNav.bind(eventType, function(event) {
            event.preventDefault();
            var target;

            if (watchedEvent === "" || watchedEvent === event.type) {
              target = ($(this).hasClass(namespace + 'next')) ? slider.getTarget('next') : slider.getTarget('prev');
              slider.flexAnimate(target, slider.vars.pauseOnAction);
            }

            // setup flags to prevent event duplication
            if (watchedEvent === "") {
              watchedEvent = event.type;
            }
            methods.setToClearWatchedEvent();
          });
        },
        update: function() {
          var disabledClass = namespace + 'disabled';
          if (slider.pagingCount === 1) {
            slider.directionNav.addClass(disabledClass).attr('tabindex', '-1');
          } else if (!slider.vars.animationLoop) {
            if (slider.animatingTo === 0) {
              slider.directionNav.removeClass(disabledClass).filter('.' + namespace + "prev").addClass(disabledClass).attr('tabindex', '-1');
            } else if (slider.animatingTo === slider.last) {
              slider.directionNav.removeClass(disabledClass).filter('.' + namespace + "next").addClass(disabledClass).attr('tabindex', '-1');
            } else {
              slider.directionNav.removeClass(disabledClass).removeAttr('tabindex');
            }
          } else {
            slider.directionNav.removeClass(disabledClass).removeAttr('tabindex');
          }
        }
      },
      pausePlay: {
        setup: function() {
          var pausePlayScaffold = $('<div class="' + namespace + 'pauseplay"><a></a></div>');

          // CONTROLSCONTAINER:
          if (slider.controlsContainer) {
            slider.controlsContainer.append(pausePlayScaffold);
            slider.pausePlay = $('.' + namespace + 'pauseplay a', slider.controlsContainer);
          } else {
            slider.append(pausePlayScaffold);
            slider.pausePlay = $('.' + namespace + 'pauseplay a', slider);
          }

          methods.pausePlay.update((slider.vars.slideshow) ? namespace + 'pause' : namespace + 'play');

          slider.pausePlay.bind(eventType, function(event) {
            event.preventDefault();

            if (watchedEvent === "" || watchedEvent === event.type) {
              if ($(this).hasClass(namespace + 'pause')) {
                slider.manualPause = true;
                slider.manualPlay = false;
                slider.pause();
              } else {
                slider.manualPause = false;
                slider.manualPlay = true;
                slider.play();
              }
            }

            // setup flags to prevent event duplication
            if (watchedEvent === "") {
              watchedEvent = event.type;
            }
            methods.setToClearWatchedEvent();
          });
        },
        update: function(state) {
          (state === "play") ? slider.pausePlay.removeClass(namespace + 'pause').addClass(namespace + 'play').html(slider.vars.playText) : slider.pausePlay.removeClass(namespace + 'play').addClass(namespace + 'pause').html(slider.vars.pauseText);
        }
      },
      touch: function() {
        var startX,
          startY,
          offset,
          cwidth,
          dx,
          startT,
          scrolling = false,
          localX = 0,
          localY = 0,
          accDx = 0;

        if(!msGesture){
            el.addEventListener('touchstart', onTouchStart, false);

            function onTouchStart(e) {
              if (slider.animating) {
                e.preventDefault();
              } else if ( ( window.navigator.msPointerEnabled ) || e.touches.length === 1 ) {
                slider.pause();
                // CAROUSEL:
                cwidth = (vertical) ? slider.h : slider. w;
                startT = Number(new Date());
                // CAROUSEL:

                // Local vars for X and Y points.
                localX = e.touches[0].pageX;
                localY = e.touches[0].pageY;

                offset = (carousel && reverse && slider.animatingTo === slider.last) ? 0 :
                         (carousel && reverse) ? slider.limit - (((slider.itemW + slider.vars.itemMargin) * slider.move) * slider.animatingTo) :
                         (carousel && slider.currentSlide === slider.last) ? slider.limit :
                         (carousel) ? ((slider.itemW + slider.vars.itemMargin) * slider.move) * slider.currentSlide :
                         (reverse) ? (slider.last - slider.currentSlide + slider.cloneOffset) * cwidth : (slider.currentSlide + slider.cloneOffset) * cwidth;
                startX = (vertical) ? localY : localX;
                startY = (vertical) ? localX : localY;

                el.addEventListener('touchmove', onTouchMove, false);
                el.addEventListener('touchend', onTouchEnd, false);
              }
            }

            function onTouchMove(e) {
              // Local vars for X and Y points.

              localX = e.touches[0].pageX;
              localY = e.touches[0].pageY;

              dx = (vertical) ? startX - localY : startX - localX;
              scrolling = (vertical) ? (Math.abs(dx) < Math.abs(localX - startY)) : (Math.abs(dx) < Math.abs(localY - startY));

              var fxms = 500;

              if ( ! scrolling || Number( new Date() ) - startT > fxms ) {
                e.preventDefault();
                if (!fade && slider.transitions) {
                  if (!slider.vars.animationLoop) {
                    dx = dx/((slider.currentSlide === 0 && dx < 0 || slider.currentSlide === slider.last && dx > 0) ? (Math.abs(dx)/cwidth+2) : 1);
                  }
                  slider.setProps(offset + dx, "setTouch");
                }
              }
            }

            function onTouchEnd(e) {
              // finish the touch by undoing the touch session
              el.removeEventListener('touchmove', onTouchMove, false);

              if (slider.animatingTo === slider.currentSlide && !scrolling && !(dx === null)) {
                var updateDx = (reverse) ? -dx : dx,
                    target = (updateDx > 0) ? slider.getTarget('next') : slider.getTarget('prev');

                if (slider.canAdvance(target) && (Number(new Date()) - startT < 550 && Math.abs(updateDx) > 50 || Math.abs(updateDx) > cwidth/2)) {
                  slider.flexAnimate(target, slider.vars.pauseOnAction);
                } else {
                  if (!fade) slider.flexAnimate(slider.currentSlide, slider.vars.pauseOnAction, true);
                }
              }
              el.removeEventListener('touchend', onTouchEnd, false);

              startX = null;
              startY = null;
              dx = null;
              offset = null;
            }
        }else{
            el.style.msTouchAction = "none";
            el._gesture = new MSGesture();
            el._gesture.target = el;
            el.addEventListener("MSPointerDown", onMSPointerDown, false);
            el._slider = slider;
            el.addEventListener("MSGestureChange", onMSGestureChange, false);
            el.addEventListener("MSGestureEnd", onMSGestureEnd, false);

            function onMSPointerDown(e){
                e.stopPropagation();
                if (slider.animating) {
                    e.preventDefault();
                }else{
                    slider.pause();
                    el._gesture.addPointer(e.pointerId);
                    accDx = 0;
                    cwidth = (vertical) ? slider.h : slider. w;
                    startT = Number(new Date());
                    // CAROUSEL:

                    offset = (carousel && reverse && slider.animatingTo === slider.last) ? 0 :
                        (carousel && reverse) ? slider.limit - (((slider.itemW + slider.vars.itemMargin) * slider.move) * slider.animatingTo) :
                            (carousel && slider.currentSlide === slider.last) ? slider.limit :
                                (carousel) ? ((slider.itemW + slider.vars.itemMargin) * slider.move) * slider.currentSlide :
                                    (reverse) ? (slider.last - slider.currentSlide + slider.cloneOffset) * cwidth : (slider.currentSlide + slider.cloneOffset) * cwidth;
                }
            }

            function onMSGestureChange(e) {
                e.stopPropagation();
                var slider = e.target._slider;
                if(!slider){
                    return;
                }
                var transX = -e.translationX,
                    transY = -e.translationY;

                //Accumulate translations.
                accDx = accDx + ((vertical) ? transY : transX);
                dx = accDx;
                scrolling = (vertical) ? (Math.abs(accDx) < Math.abs(-transX)) : (Math.abs(accDx) < Math.abs(-transY));

                if(e.detail === e.MSGESTURE_FLAG_INERTIA){
                    setImmediate(function (){
                        el._gesture.stop();
                    });

                    return;
                }

                if (!scrolling || Number(new Date()) - startT > 500) {
                    e.preventDefault();
                    if (!fade && slider.transitions) {
                        if (!slider.vars.animationLoop) {
                            dx = accDx / ((slider.currentSlide === 0 && accDx < 0 || slider.currentSlide === slider.last && accDx > 0) ? (Math.abs(accDx) / cwidth + 2) : 1);
                        }
                        slider.setProps(offset + dx, "setTouch");
                    }
                }
            }

            function onMSGestureEnd(e) {
                e.stopPropagation();
                var slider = e.target._slider;
                if(!slider){
                    return;
                }
                if (slider.animatingTo === slider.currentSlide && !scrolling && !(dx === null)) {
                    var updateDx = (reverse) ? -dx : dx,
                        target = (updateDx > 0) ? slider.getTarget('next') : slider.getTarget('prev');

                    if (slider.canAdvance(target) && (Number(new Date()) - startT < 550 && Math.abs(updateDx) > 50 || Math.abs(updateDx) > cwidth/2)) {
                        slider.flexAnimate(target, slider.vars.pauseOnAction);
                    } else {
                        if (!fade) slider.flexAnimate(slider.currentSlide, slider.vars.pauseOnAction, true);
                    }
                }

                startX = null;
                startY = null;
                dx = null;
                offset = null;
                accDx = 0;
            }
        }
      },
      resize: function() {
        if (!slider.animating && slider.is(':visible')) {
          if (!carousel) slider.doMath();

          if (fade) {
            // SMOOTH HEIGHT:
            methods.smoothHeight();
          } else if (carousel) { //CAROUSEL:
            slider.slides.width(slider.computedW);
            slider.update(slider.pagingCount);
            slider.setProps();
          }
          else if (vertical) { //VERTICAL:
            slider.viewport.height(slider.h);
            slider.setProps(slider.h, "setTotal");
          } else {
            // SMOOTH HEIGHT:
            if (slider.vars.smoothHeight) methods.smoothHeight();
            slider.newSlides.width(slider.computedW);
            slider.setProps(slider.computedW, "setTotal");
          }
        }
      },
      smoothHeight: function(dur) {
        if (!vertical || fade) {
          var $obj = (fade) ? slider : slider.viewport;
          (dur) ? $obj.animate({"height": slider.slides.eq(slider.animatingTo).height()}, dur) : $obj.height(slider.slides.eq(slider.animatingTo).height());
        }
      },
      sync: function(action) {
        var $obj = $(slider.vars.sync).data("flexslider"),
            target = slider.animatingTo;

        switch (action) {
          case "animate": $obj.flexAnimate(target, slider.vars.pauseOnAction, false, true); break;
          case "play": if (!$obj.playing && !$obj.asNav) { $obj.play(); } break;
          case "pause": $obj.pause(); break;
        }
      },
      pauseInvisible: {
        visProp: null,
        init: function() {
          var prefixes = ['webkit','moz','ms','o'];

          if ('hidden' in document) return 'hidden';
          for (var i = 0; i < prefixes.length; i++) {
            if ((prefixes[i] + 'Hidden') in document) 
            methods.pauseInvisible.visProp = prefixes[i] + 'Hidden';
          }
          if (methods.pauseInvisible.visProp) {
            var evtname = methods.pauseInvisible.visProp.replace(/[H|h]idden/,'') + 'visibilitychange';
            document.addEventListener(evtname, function() {
              if (methods.pauseInvisible.isHidden()) {
                if(slider.startTimeout) clearTimeout(slider.startTimeout); //If clock is ticking, stop timer and prevent from starting while invisible
                else slider.pause(); //Or just pause
              }
              else {
                if(slider.started) slider.play(); //Initiated before, just play
                else (slider.vars.initDelay > 0) ? setTimeout(slider.play, slider.vars.initDelay) : slider.play(); //Didn't init before: simply init or wait for it
              }
            });
          }       
        },
        isHidden: function() {
          return document[methods.pauseInvisible.visProp] || false;
        }
      },
      setToClearWatchedEvent: function() {
        clearTimeout(watchedEventClearTimer);
        watchedEventClearTimer = setTimeout(function() {
          watchedEvent = "";
        }, 3000);
      }
    }

    // public methods
    slider.flexAnimate = function(target, pause, override, withSync, fromNav) {
      if (!slider.vars.animationLoop && target !== slider.currentSlide) {
        slider.direction = (target > slider.currentSlide) ? "next" : "prev";
      }

      if (asNav && slider.pagingCount === 1) slider.direction = (slider.currentItem < target) ? "next" : "prev";

      if (!slider.animating && (slider.canAdvance(target, fromNav) || override) && slider.is(":visible")) {
        if (asNav && withSync) {
          var master = $(slider.vars.asNavFor).data('flexslider');
          slider.atEnd = target === 0 || target === slider.count - 1;
          master.flexAnimate(target, true, false, true, fromNav);
          slider.direction = (slider.currentItem < target) ? "next" : "prev";
          master.direction = slider.direction;

          if (Math.ceil((target + 1)/slider.visible) - 1 !== slider.currentSlide && target !== 0) {
            slider.currentItem = target;
            slider.slides.removeClass(namespace + "active-slide").eq(target).addClass(namespace + "active-slide");
            target = Math.floor(target/slider.visible);
          } else {
            slider.currentItem = target;
            slider.slides.removeClass(namespace + "active-slide").eq(target).addClass(namespace + "active-slide");
            return false;
          }
        }

        slider.animating = true;
        slider.animatingTo = target;

        // SLIDESHOW:
        if (pause) slider.pause();

        // API: before() animation Callback
        slider.vars.before(slider);

        // SYNC:
        if (slider.syncExists && !fromNav) methods.sync("animate");

        // CONTROLNAV
        if (slider.vars.controlNav) methods.controlNav.active();

        // !CAROUSEL:
        // CANDIDATE: slide active class (for add/remove slide)
        if (!carousel) slider.slides.removeClass(namespace + 'active-slide').eq(target).addClass(namespace + 'active-slide');

        // INFINITE LOOP:
        // CANDIDATE: atEnd
        slider.atEnd = target === 0 || target === slider.last;

        // DIRECTIONNAV:
        if (slider.vars.directionNav) methods.directionNav.update();

        if (target === slider.last) {
          // API: end() of cycle Callback
          slider.vars.end(slider);
          // SLIDESHOW && !INFINITE LOOP:
          if (!slider.vars.animationLoop) slider.pause();
        }

        // SLIDE:
        if (!fade) {
          var dimension = (vertical) ? slider.slides.filter(':first').height() : slider.computedW,
              margin, slideString, calcNext;

          // INFINITE LOOP / REVERSE:
          if (carousel) {
            //margin = (slider.vars.itemWidth > slider.w) ? slider.vars.itemMargin * 2 : slider.vars.itemMargin;
            margin = slider.vars.itemMargin;
            calcNext = ((slider.itemW + margin) * slider.move) * slider.animatingTo;
            slideString = (calcNext > slider.limit && slider.visible !== 1) ? slider.limit : calcNext;
          } else if (slider.currentSlide === 0 && target === slider.count - 1 && slider.vars.animationLoop && slider.direction !== "next") {
            slideString = (reverse) ? (slider.count + slider.cloneOffset) * dimension : 0;
          } else if (slider.currentSlide === slider.last && target === 0 && slider.vars.animationLoop && slider.direction !== "prev") {
            slideString = (reverse) ? 0 : (slider.count + 1) * dimension;
          } else {
            slideString = (reverse) ? ((slider.count - 1) - target + slider.cloneOffset) * dimension : (target + slider.cloneOffset) * dimension;
          }
          slider.setProps(slideString, "", slider.vars.animationSpeed);
          if (slider.transitions) {
            if (!slider.vars.animationLoop || !slider.atEnd) {
              slider.animating = false;
              slider.currentSlide = slider.animatingTo;
            }
            slider.container.unbind("webkitTransitionEnd transitionend");
            slider.container.bind("webkitTransitionEnd transitionend", function() {
              slider.wrapup(dimension);
            });
          } else {
            slider.container.animate(slider.args, slider.vars.animationSpeed, slider.vars.easing, function(){
              slider.wrapup(dimension);
            });
          }
        } else { // FADE:
          if (!touch) {
            //slider.slides.eq(slider.currentSlide).fadeOut(slider.vars.animationSpeed, slider.vars.easing);
            //slider.slides.eq(target).fadeIn(slider.vars.animationSpeed, slider.vars.easing, slider.wrapup);

            slider.slides.eq(slider.currentSlide).css({"zIndex": 1}).animate({"opacity": 0}, slider.vars.animationSpeed, slider.vars.easing);
            slider.slides.eq(target).css({"zIndex": 2}).animate({"opacity": 1}, slider.vars.animationSpeed, slider.vars.easing, slider.wrapup);

          } else {
            slider.slides.eq(slider.currentSlide).css({ "opacity": 0, "zIndex": 1 });
            slider.slides.eq(target).css({ "opacity": 1, "zIndex": 2 });
            slider.wrapup(dimension);
          }
        }
        // SMOOTH HEIGHT:
        if (slider.vars.smoothHeight) methods.smoothHeight(slider.vars.animationSpeed);
      }
    }
    slider.wrapup = function(dimension) {
      // SLIDE:
      if (!fade && !carousel) {
        if (slider.currentSlide === 0 && slider.animatingTo === slider.last && slider.vars.animationLoop) {
          slider.setProps(dimension, "jumpEnd");
        } else if (slider.currentSlide === slider.last && slider.animatingTo === 0 && slider.vars.animationLoop) {
          slider.setProps(dimension, "jumpStart");
        }
      }
      slider.animating = false;
      slider.currentSlide = slider.animatingTo;
      // API: after() animation Callback
      slider.vars.after(slider);
    }

    // SLIDESHOW:
    slider.animateSlides = function() {
      if (!slider.animating && focused ) slider.flexAnimate(slider.getTarget("next"));
    }
    // SLIDESHOW:
    slider.pause = function() {
      clearInterval(slider.animatedSlides);
      slider.animatedSlides = null;
      slider.playing = false;
      // PAUSEPLAY:
      if (slider.vars.pausePlay) methods.pausePlay.update("play");
      // SYNC:
      if (slider.syncExists) methods.sync("pause");
    }
    // SLIDESHOW:
    slider.play = function() {
      if (slider.playing) clearInterval(slider.animatedSlides);
      slider.animatedSlides = slider.animatedSlides || setInterval(slider.animateSlides, slider.vars.slideshowSpeed);
      slider.started = slider.playing = true;
      // PAUSEPLAY:
      if (slider.vars.pausePlay) methods.pausePlay.update("pause");
      // SYNC:
      if (slider.syncExists) methods.sync("play");
    }
    // STOP:
    slider.stop = function () {
      slider.pause();
      slider.stopped = true;
    }
    slider.canAdvance = function(target, fromNav) {
      // ASNAV:
      var last = (asNav) ? slider.pagingCount - 1 : slider.last;
      return (fromNav) ? true :
             (asNav && slider.currentItem === slider.count - 1 && target === 0 && slider.direction === "prev") ? true :
             (asNav && slider.currentItem === 0 && target === slider.pagingCount - 1 && slider.direction !== "next") ? false :
             (target === slider.currentSlide && !asNav) ? false :
             (slider.vars.animationLoop) ? true :
             (slider.atEnd && slider.currentSlide === 0 && target === last && slider.direction !== "next") ? false :
             (slider.atEnd && slider.currentSlide === last && target === 0 && slider.direction === "next") ? false :
             true;
    }
    slider.getTarget = function(dir) {
      slider.direction = dir;
      if (dir === "next") {
        return (slider.currentSlide === slider.last) ? 0 : slider.currentSlide + 1;
      } else {
        return (slider.currentSlide === 0) ? slider.last : slider.currentSlide - 1;
      }
    }

    // SLIDE:
    slider.setProps = function(pos, special, dur) {
      var target = (function() {
        var posCheck = (pos) ? pos : ((slider.itemW + slider.vars.itemMargin) * slider.move) * slider.animatingTo,
            posCalc = (function() {
              if (carousel) {
                return (special === "setTouch") ? pos :
                       (reverse && slider.animatingTo === slider.last) ? 0 :
                       (reverse) ? slider.limit - (((slider.itemW + slider.vars.itemMargin) * slider.move) * slider.animatingTo) :
                       (slider.animatingTo === slider.last) ? slider.limit : posCheck;
              } else {
                switch (special) {
                  case "setTotal": return (reverse) ? ((slider.count - 1) - slider.currentSlide + slider.cloneOffset) * pos : (slider.currentSlide + slider.cloneOffset) * pos;
                  case "setTouch": return (reverse) ? pos : pos;
                  case "jumpEnd": return (reverse) ? pos : slider.count * pos;
                  case "jumpStart": return (reverse) ? slider.count * pos : pos;
                  default: return pos;
                }
              }
            }());

            return (posCalc * -1) + "px";
          }());

      if (slider.transitions) {
        target = (vertical) ? "translate3d(0," + target + ",0)" : "translate3d(" + target + ",0,0)";
        dur = (dur !== undefined) ? (dur/1000) + "s" : "0s";
        slider.container.css("-" + slider.pfx + "-transition-duration", dur);
      }

      slider.args[slider.prop] = target;
      if (slider.transitions || dur === undefined) slider.container.css(slider.args);
    }

    slider.setup = function(type) {
      // SLIDE:
      if (!fade) {
        var sliderOffset, arr;

        if (type === "init") {
          slider.viewport = $('<div class="' + namespace + 'viewport"></div>').css({"overflow": "hidden", "position": "relative"}).appendTo(slider).append(slider.container);
          // INFINITE LOOP:
          slider.cloneCount = 0;
          slider.cloneOffset = 0;
          // REVERSE:
          if (reverse) {
            arr = $.makeArray(slider.slides).reverse();
            slider.slides = $(arr);
            slider.container.empty().append(slider.slides);
          }
        }
        // INFINITE LOOP && !CAROUSEL:
        if (slider.vars.animationLoop && !carousel) {
          slider.cloneCount = 2;
          slider.cloneOffset = 1;
          // clear out old clones
          if (type !== "init") slider.container.find('.clone').remove();
          slider.container.append(slider.slides.first().clone().addClass('clone').attr('aria-hidden', 'true')).prepend(slider.slides.last().clone().addClass('clone').attr('aria-hidden', 'true'));
        }
        slider.newSlides = $(slider.vars.selector, slider);

        sliderOffset = (reverse) ? slider.count - 1 - slider.currentSlide + slider.cloneOffset : slider.currentSlide + slider.cloneOffset;
        // VERTICAL:
        if (vertical && !carousel) {
          slider.container.height((slider.count + slider.cloneCount) * 200 + "%").css("position", "absolute").width("100%");
          setTimeout(function(){
            slider.newSlides.css({"display": "block"});
            slider.doMath();
            slider.viewport.height(slider.h);
            slider.setProps(sliderOffset * slider.h, "init");
          }, (type === "init") ? 100 : 0);
        } else {
          slider.container.width((slider.count + slider.cloneCount) * 200 + "%");
          slider.setProps(sliderOffset * slider.computedW, "init");
          setTimeout(function(){
            slider.doMath();
            slider.newSlides.css({"width": slider.computedW, "float": "left", "display": "block"});
            // SMOOTH HEIGHT:
            if (slider.vars.smoothHeight) methods.smoothHeight();
          }, (type === "init") ? 100 : 0);
        }
      } else { // FADE:
        slider.slides.css({"width": "100%", "float": "left", "marginRight": "-100%", "position": "relative"});
        if (type === "init") {
          if (!touch) {
            //slider.slides.eq(slider.currentSlide).fadeIn(slider.vars.animationSpeed, slider.vars.easing);
            slider.slides.css({ "opacity": 0, "display": "block", "zIndex": 1 }).eq(slider.currentSlide).css({"zIndex": 2}).animate({"opacity": 1},slider.vars.animationSpeed,slider.vars.easing);
          } else {
            slider.slides.css({ "opacity": 0, "display": "block", "webkitTransition": "opacity " + slider.vars.animationSpeed / 1000 + "s ease", "zIndex": 1 }).eq(slider.currentSlide).css({ "opacity": 1, "zIndex": 2});
          }
        }
        // SMOOTH HEIGHT:
        if (slider.vars.smoothHeight) methods.smoothHeight();
      }
      // !CAROUSEL:
      // CANDIDATE: active slide
      if (!carousel) slider.slides.removeClass(namespace + "active-slide").eq(slider.currentSlide).addClass(namespace + "active-slide");
    }


    slider.doMath = function() {
      var slide = slider.slides.first(),
          slideMargin = slider.vars.itemMargin,
          minItems = slider.vars.minItems,
          maxItems = slider.vars.maxItems;

      slider.w = (slider.viewport===undefined) ? slider.width() : slider.viewport.width();
      slider.h = slide.height();
      slider.boxPadding = slide.outerWidth() - slide.width();

      // CAROUSEL:
      if (carousel) {
        slider.itemT = slider.vars.itemWidth + slideMargin;
        slider.minW = (minItems) ? minItems * slider.itemT : slider.w;
        slider.maxW = (maxItems) ? (maxItems * slider.itemT) - slideMargin : slider.w;
        slider.itemW = (slider.minW > slider.w) ? (slider.w - (slideMargin * (minItems - 1)))/minItems :
                       (slider.maxW < slider.w) ? (slider.w - (slideMargin * (maxItems - 1)))/maxItems :
                       (slider.vars.itemWidth > slider.w) ? slider.w : slider.vars.itemWidth;

        slider.visible = Math.floor(slider.w/(slider.itemW));
        slider.move = (slider.vars.move > 0 && slider.vars.move < slider.visible ) ? slider.vars.move : slider.visible;
        slider.pagingCount = Math.ceil(((slider.count - slider.visible)/slider.move) + 1);
        slider.last =  slider.pagingCount - 1;
        slider.limit = (slider.pagingCount === 1) ? 0 :
                       (slider.vars.itemWidth > slider.w) ? (slider.itemW * (slider.count - 1)) + (slideMargin * (slider.count - 1)) : ((slider.itemW + slideMargin) * slider.count) - slider.w - slideMargin;
      } else {
        slider.itemW = slider.w;
        slider.pagingCount = slider.count;
        slider.last = slider.count - 1;
      }
      slider.computedW = slider.itemW - slider.boxPadding;
    }


    slider.update = function(pos, action) {
      slider.doMath();

      // update currentSlide and slider.animatingTo if necessary
      if (!carousel) {
        if (pos < slider.currentSlide) {
          slider.currentSlide += 1;
        } else if (pos <= slider.currentSlide && pos !== 0) {
          slider.currentSlide -= 1;
        }
        slider.animatingTo = slider.currentSlide;
      }

      // update controlNav
      if (slider.vars.controlNav && !slider.manualControls) {
        if ((action === "add" && !carousel) || slider.pagingCount > slider.controlNav.length) {
          methods.controlNav.update("add");
        } else if ((action === "remove" && !carousel) || slider.pagingCount < slider.controlNav.length) {
          if (carousel && slider.currentSlide > slider.last) {
            slider.currentSlide -= 1;
            slider.animatingTo -= 1;
          }
          methods.controlNav.update("remove", slider.last);
        }
      }
      // update directionNav
      if (slider.vars.directionNav) methods.directionNav.update();

    }

    slider.addSlide = function(obj, pos) {
      var $obj = $(obj);

      slider.count += 1;
      slider.last = slider.count - 1;

      // append new slide
      if (vertical && reverse) {
        (pos !== undefined) ? slider.slides.eq(slider.count - pos).after($obj) : slider.container.prepend($obj);
      } else {
        (pos !== undefined) ? slider.slides.eq(pos).before($obj) : slider.container.append($obj);
      }

      // update currentSlide, animatingTo, controlNav, and directionNav
      slider.update(pos, "add");

      // update slider.slides
      slider.slides = $(slider.vars.selector + ':not(.clone)', slider);
      // re-setup the slider to accomdate new slide
      slider.setup();

      //FlexSlider: added() Callback
      slider.vars.added(slider);
    }
    slider.removeSlide = function(obj) {
      var pos = (isNaN(obj)) ? slider.slides.index($(obj)) : obj;

      // update count
      slider.count -= 1;
      slider.last = slider.count - 1;

      // remove slide
      if (isNaN(obj)) {
        $(obj, slider.slides).remove();
      } else {
        (vertical && reverse) ? slider.slides.eq(slider.last).remove() : slider.slides.eq(obj).remove();
      }

      // update currentSlide, animatingTo, controlNav, and directionNav
      slider.doMath();
      slider.update(pos, "remove");

      // update slider.slides
      slider.slides = $(slider.vars.selector + ':not(.clone)', slider);
      // re-setup the slider to accomdate new slide
      slider.setup();

      // FlexSlider: removed() Callback
      slider.vars.removed(slider);
    }

    //FlexSlider: Initialize
    methods.init();
  }

  // Ensure the slider isn't focussed if the window loses focus.
  $( window ).blur( function ( e ) {
    focused = false;
  }).focus( function ( e ) {
    focused = true;
  });

  //FlexSlider: Default Settings
  $.flexslider.defaults = {
    namespace: "flex-",             //{NEW} String: Prefix string attached to the class of every element generated by the plugin
    selector: ".slides > li",       //{NEW} Selector: Must match a simple pattern. '{container} > {slide}' -- Ignore pattern at your own peril
    animation: "fade",              //String: Select your animation type, "fade" or "slide"
    easing: "swing",                //{NEW} String: Determines the easing method used in jQuery transitions. jQuery easing plugin is supported!
    direction: "horizontal",        //String: Select the sliding direction, "horizontal" or "vertical"
    reverse: false,                 //{NEW} Boolean: Reverse the animation direction
    animationLoop: true,            //Boolean: Should the animation loop? If false, directionNav will received "disable" classes at either end
    smoothHeight: false,            //{NEW} Boolean: Allow height of the slider to animate smoothly in horizontal mode
    startAt: 0,                     //Integer: The slide that the slider should start on. Array notation (0 = first slide)
    slideshow: true,                //Boolean: Animate slider automatically
    slideshowSpeed: 7000,           //Integer: Set the speed of the slideshow cycling, in milliseconds
    animationSpeed: 600,            //Integer: Set the speed of animations, in milliseconds
    initDelay: 0,                   //{NEW} Integer: Set an initialization delay, in milliseconds
    randomize: false,               //Boolean: Randomize slide order
    thumbCaptions: false,           //Boolean: Whether or not to put captions on thumbnails when using the "thumbnails" controlNav.

    // Usability features
    pauseOnAction: true,            //Boolean: Pause the slideshow when interacting with control elements, highly recommended.
    pauseOnHover: false,            //Boolean: Pause the slideshow when hovering over slider, then resume when no longer hovering
    pauseInvisible: true,   		//{NEW} Boolean: Pause the slideshow when tab is invisible, resume when visible. Provides better UX, lower CPU usage.
    useCSS: true,                   //{NEW} Boolean: Slider will use CSS3 transitions if available
    touch: true,                    //{NEW} Boolean: Allow touch swipe navigation of the slider on touch-enabled devices
    video: false,                   //{NEW} Boolean: If using video in the slider, will prevent CSS3 3D Transforms to avoid graphical glitches

    // Primary Controls
    controlNav: true,               //Boolean: Create navigation for paging control of each clide? Note: Leave true for manualControls usage
    directionNav: true,             //Boolean: Create navigation for previous/next navigation? (true/false)
    prevText: "Previous",           //String: Set the text for the "previous" directionNav item
    nextText: "Next",               //String: Set the text for the "next" directionNav item

    // Secondary Navigation
    keyboard: true,                 //Boolean: Allow slider navigating via keyboard left/right keys
    multipleKeyboard: false,        //{NEW} Boolean: Allow keyboard navigation to affect multiple sliders. Default behavior cuts out keyboard navigation with more than one slider present.
    mousewheel: false,              //{UPDATED} Boolean: Requires jquery.mousewheel.js (https://github.com/brandonaaron/jquery-mousewheel) - Allows slider navigating via mousewheel
    pausePlay: false,               //Boolean: Create pause/play dynamic element
    pauseText: "Pause",             //String: Set the text for the "pause" pausePlay item
    playText: "Play",               //String: Set the text for the "play" pausePlay item

    // Special properties
    controlsContainer: "",          //{UPDATED} jQuery Object/Selector: Declare which container the navigation elements should be appended too. Default container is the FlexSlider element. Example use would be $(".flexslider-container"). Property is ignored if given element is not found.
    manualControls: "",             //{UPDATED} jQuery Object/Selector: Declare custom control navigation. Examples would be $(".flex-control-nav li") or "#tabs-nav li img", etc. The number of elements in your controlNav should match the number of slides/tabs.
    sync: "",                       //{NEW} Selector: Mirror the actions performed on this slider with another slider. Use with care.
    asNavFor: "",                   //{NEW} Selector: Internal property exposed for turning the slider into a thumbnail navigation for another slider

    // Carousel Options
    itemWidth: 0,                   //{NEW} Integer: Box-model width of individual carousel items, including horizontal borders and padding.
    itemMargin: 0,                  //{NEW} Integer: Margin between carousel items.
    minItems: 1,                    //{NEW} Integer: Minimum number of carousel items that should be visible. Items will resize fluidly when below this.
    maxItems: 0,                    //{NEW} Integer: Maxmimum number of carousel items that should be visible. Items will resize fluidly when above this limit.
    move: 0,                        //{NEW} Integer: Number of carousel items that should move on animation. If 0, slider will move all visible items.
    allowOneSlide: true,           //{NEW} Boolean: Whether or not to allow a slider comprised of a single slide

    // Callback API
    start: function(){},            //Callback: function(slider) - Fires when the slider loads the first slide
    before: function(){},           //Callback: function(slider) - Fires asynchronously with each slider animation
    after: function(){},            //Callback: function(slider) - Fires after each slider animation completes
    end: function(){},              //Callback: function(slider) - Fires when the slider reaches the last slide (asynchronous)
    added: function(){},            //{NEW} Callback: function(slider) - Fires after a slide is added
    removed: function(){}           //{NEW} Callback: function(slider) - Fires after a slide is removed
  }


  //FlexSlider: Plugin Function
  $.fn.flexslider = function(options) {
    if (options === undefined) options = {};

    if (typeof options === "object") {
      return this.each(function() {
        var $this = $(this),
            selector = (options.selector) ? options.selector : ".slides > li",
            $slides = $this.find(selector);

      if ( ( $slides.length === 1 && options.allowOneSlide === true ) || $slides.length === 0 ) {
          $slides.fadeIn(400);
          if (options.start) options.start($this);
        } else if ($this.data('flexslider') === undefined) {
          new $.flexslider(this, options);
        }
      });
    } else {
      // Helper strings to quickly perform functions on the slider
      var $slider = $(this).data('flexslider');
      switch (options) {
        case "play": $slider.play(); break;
        case "pause": $slider.pause(); break;
        case "stop": $slider.stop(); break;
        case "next": $slider.flexAnimate($slider.getTarget("next"), true); break;
        case "prev":
        case "previous": $slider.flexAnimate($slider.getTarget("prev"), true); break;
        default: if (typeof options === "number") $slider.flexAnimate(options, true);
      }
    }
  }
})(jQuery);
//]]></script>

</body>
</html>
