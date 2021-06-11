

<html>
<head><meta http-equiv="Content-Type" content="text/html; charset=utf-8">
<style>*{margin:0;padding:0;outline:none;border:none;}html,body{margin:0;padding:0;background:#000;;}</style>

<script src="https://code.jquery.com/jquery-2.1.4.js"></script>
<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.2.0/jquery.min.js"></script>
<script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/js/bootstrap.min.js"></script>
<script type="text/javascript" src="https://cdn.jsdelivr.net/clappr/latest/clappr.min.js"></script>
<script type="text/javascript" src="https://cdn.jsdelivr.net/clappr.level-selector/latest/level-selector.min.js"></script>
<script src="https://cdn.jsdelivr.net/clappr.chromecast-plugin/latest/clappr-chromecast-plugin.js"></script>
<script type="text/javascript" src="https:////cdn.jsdelivr.net/clappr/latest/clappr.min.js"></script>
<script type="text/javascript" src="https:////cdn.jsdelivr.net/clappr.level-selector/latest/level-selector.min.js"></script>
<script src="https://cdn.jsdelivr.net/gh/clappr/dash-shaka-playback@latest/dist/dash-shaka-playback.js"></script>
<script type="text/javascript" src="https://cdn.jsdelivr.net/clappr.chromecast-plugin/latest/clappr-chromecast-plugin.js"></script>
<script type="text/javascript" src="https://cdn.jsdelivr.net/clappr/latest/clappr.min.js"></script>
<script type="text/javascript" src="https://cdn.jsdelivr.net/clappr.level-selector/latest/level-selector.min.js"></script>
<script src="https://cdn.jsdelivr.net/npm/cdnbye@latest/dist/hlsjs-p2p-engine.min.js"></script>
<script src="https://cdn.jsdelivr.net/npm/cdnbye@latest/dist/clappr-plugin.min.js"></script>
<script type="text/javascript" src="//cdn.jsdelivr.net/jwplayer/5.10/jwplayer.js">
<!-- <script src="https://cdn.dashjs.org/latest/dash.all.min.js"></script> -->
<script src="https://cdn.plyr.io/3.6.2/plyr.polyfilled.js"></script>   
<script type="text/javascript" src="https://cdn.jsdelivr.net/npm/@clappr/hlsjs-playback@latest/dist/hlsjs-playback.min.js"></script>
<script type="text/javascript" src="https://github.com/clappr/clappr-core/blob/master/src/base/playback/playback.js"></script>

<title>indiasports.xyz</title>

</head>
<body>
<div style="width: 100%;">
<div id="player"></div>
</div>
<script>
function getParam ( sname )
{
  var params = location.search.substr(location.search.indexOf("?")+1);
  var sval =  params.replace("sv=", "");
  
  return sval;
}
var sv = getParam("sv");

</script>
<script>
  var responseText = ''+sv+'';
  urlArry = responseText.split(',');
  start = true;
  num_of_urlArry = urlArry.length;
  index_of_urlArry = 0;
</script>
<script>
 if (navigator.userAgent.match(/Android/i) ||
             navigator.userAgent.match(/webOS/i) ||
             navigator.userAgent.match(/iPhone/i) ||
             navigator.userAgent.match(/iPod/i) ||
             navigator.userAgent.match(/iPad/i) ||
             navigator.userAgent.match(/Blackberry/i)){
    document.write("\<video style=\"z-index:2;width:100%;height:250;background-color:#000;-o-object-fit:fill;object-fit:fill\"  controls=\"controls\" autoplay=\"true\" preload=\"auto\" height=\"auto\" src=\""+urlArry[0]+"\"\>\<\/video\>");
    }else{
	player = new Clappr.Player({
								source: ""+sv+"",
					            parentId: '#player',
					            width: '100%',
                                height: "100%",
					            hideMediaControl: true,
					            seekbar: "#ffaa56",
					            buttons: "#FFFF00",gaAccount: 'UA-128386009-2',gaTrackerName: 'hackiesite',
					            autoPlay: 'true',
					            hide: 'false',
					            watermark: "https://www.pngjoy.com/pngl/361/6721124_subscribe-us-join-us-on-telegram-png-download.png", position: 'bottom-right', 
                                                   watermarkLink: "https://telegram.me/joinchat/UfaDu9ueYiR-W8Eg",position: "top-left",

      events: {
       onError : function (event) {
        if(start == true)
        {
         index_of_urlArry = index_of_urlArry + 1;
         
         if(index_of_urlArry <= num_of_urlArry){
          reLoad(urlArry[index_of_urlArry]);
         }

 } else{ reLoad(urlArry[index_of_urlArry]);}},
       onBuffer: function (event){
        playing = false;
        setTimeout(function(){
         if(playing == false){
          if(start == true){
           index_of_urlArry = index_of_urlArry + 1;
         
           if(index_of_urlArry <= num_of_urlArry){
            reLoad(urlArry[index_of_urlArry]);
           }
          }else{
           reLoad(urlArry[index_of_urlArry]);
          }
         }
        },20000);
        
       },
       onPlay: function (event){
        start = false;
        playing = true;
        
       }
      }
     });
}
	</script>
</body>
</html>
