# nayraq
<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge, chrome=1">
    <meta name="description" content="A jquery plugin that adds scroll to top button">
    <meta name="author" content="Siddhartha Gudipati">
    <title>Examples</title>
    <link rel="stylesheet" href="http://fonts.googleapis.com/css?family=Bad+Script">
    <link rel="stylesheet" href="css/foundation.min.css">
    <link rel="stylesheet" href="css/styles.css">
    <link rel="stylesheet" href="css/jquery.backTotop.css">
    <link rel="stylesheet" href="css/prettify.css">
    <link rel="stylesheet" href="css/font-awesome.min.css"><!--[if IE 7]>
    <link rel="stylesheet" href="css/font-awesome-ie7.min.css"><![endif]-->
    <script src="js/jquery.min.js"></script>
    <script src="js/prettify.js"></script>
    <script src="js/jquery.easing.1.3.js"></script>
    <script src="js/jquery.backTotop.js"></script>
  </head>
  <body onload="prettyPrint()">
<style type="text/css">
  body{
   background: url("../img/noise.png") repeat scroll 0 0 #FFFBE0;
  }
  a{
    color: #D28440;
  }
  a:hover{
    color: #444;
  }
  a:focus{
    color:  #D28440;
  }
  .menu li a.current{
    border-top: solid 2px  #D28440;
  }
  .menu li a:hover{
      border-top: solid 2px  #D28440;
  }
  
</style>
<div class="row">
  <!-- Header starts-->
  <header class="row">
    <div class="six columns">
      <h2 class="logo"><a href="index.html"><i class="icon-arrow-up icon-1x"></i>backTotop!</a></h2>
      <p>A jquery plugin that adds scroll to top button</p>
    </div>
    <nav class="six columns">
      <ul class="menu">
        <li><a href="index.html" class="">Home</a></li>
        <li><a href="how-to-use.html" class="">How to use</a></li>
        <li><a href="examples.html" class="current">Examples</a></li>
      </ul>
      <div class="tools"><a target="_blank" href="https://github.com/websiddu/backTotop/archive/master.zip" class="radius button secondary"><i class="icon-download icon-2x"></i>Download</a><a target="_blank" href="https://github.com/websiddu/backTotop" class="radius button secondary"><i class="icon-github icon-2x"></i>Fork it</a><span class="seperator"></span><a href="http://twitter.com/websiddu"><i class="icon-twitter icon-1x"></i>@1kraqeeb</a></div>
    </nav>
    <hr/>
  </header>
  <!-- Header ends here-->
  <div class="row">
    <div style="padding: 0 50px; text-align: center;" class="twelve columns">
      <p><strong> Ha!</strong>An example backTotop similar to flipkart.com</p>
      <p>↓</p>
      <p>↓</p>
      <div class="content-block">
        <h3 class="subheading">Java Script</h3>
        <pre class="prettyprint">&lt;script&gt;
  (function(){
    $(&quot;body&quot;).backTotop({
      isWindow: true,
      text: &quot;TOP &lt;i class='icon-angle-up icon-1x'&gt;&lt;/i&gt;&quot;,
      cssClass:&quot;flipkart&quot;,
      buttonPos:{
        bottom: 50,
        right: 0
      }
    });
  })();
&lt;/script&gt;
</pre>
      </div>
      <p>↓</p>
      <p>↓</p>
      <div class="content-block">
        <h3 class="subheading">CSS</h3>
        <pre class="prettyprint">/* flipkart */
. nayraq{
  font-family: Ubuntu, &quot;Segoe UI&quot;, Frutiger, &quot;Frutiger Linotype&quot;, &quot;Dejavu Sans&quot;, &quot;Helvetica Neue&quot;, Arial, sans-serif;
  background:  #B9B8B9;
  border-radius: 5px 0 0 5px;
  border: solid 1px #d2d2d2;
  border-right: 0;
  color: #fff;
  padding:10px;
}
. nayraq:hover{
  color: #efefef;
  border: solid 1px #d3d3d3;
  border-right: 0;
}
</pre>
      </div>
      <p>↓</p>
      <p>↓</p>
      <p>↓</p>
      <p>↓</p>
      <p>↓</p>
      <p>↓</p>
      <p>↓</p>
      <p>↓</p>
      <p>Scroll down!!</p>
      <p>↓</p>
      <p>↓</p>
      <p>↓</p>
      <p>↓</p>
      <p>↓</p>
      <p>↓</p>
      <p>↓</p>
      <p>↓</p>
      <p>↓</p>
      <p>↓</p>
      <p>↓</p>
      <p>↓</p>
      <p><strong>Stop Scrolling buddy!!</strong></p>
      <p>Even if you scroll more!! the result will be the same!!</p>
      <p>Now go click on back to top!!</p>
    </div>
  </div>
  <!-- Footer starts here-->
  <footer class="row">
    <hr/>
    <div class="twelve columns">
      <p>Icons by <a href="http://fortawesome.github.com/Font-Awesome/" target="_blank">Font Awesome</a>  |
        Development with <a href="http://roots.cx" target="_blank">Roots </a>  |
        CSS Framework <a href="http://foundation.zurb.com/" target="_blank">Foundation</a>  |
        Built on <a href="http://www.sublimetext.com/2" target="_blank">Sublime Text 2</a>
      </p>
        Built on <a href="https://twitter.com/1kRaqeeb?s=08" target="_blank">Sublime Text 2</a>
    </div>
  </footer>
  <!-- Footer ends here-->
</div><script type="text/javascript">
(function() {

  $("body").backTotop({
    isWindow: true,
    text: "TOP <i class='icon-angle-up icon-1x'></i>",
    cssClass: "flipkart",
    buttonPos: {
      bottom: 50,
      right: 0
    }
  });

}).call(this);
</script>
  </body><script>protocol = window.location.protocol === 'http:' ? 'ws://' : 'wss://'; address = protocol + window.location.host + window.location.pathname + '/ws'; socket = new WebSocket(address);
socket.onmessage = function(msg) { msg.data == 'reload' && window.location.reload() }</script>
</html>
