

 <html><head>
<style> video {object-fit:fill}</style><style>html,body{margin:0;}</style>
<style> .video-js {width: 100%; height: 100%;} #videojs {width: 100%; height: 100%;}</style></head>
	<meta charset="utf-8">
	<script>
function getParam ( sname )
{
  var params = location.search.substr(location.search.indexOf("?")+1);
  var sval =  params.replace("sv=", "");
  
  return sval;
}
var sv = getParam("sv");

</script>

	 <div id="overlay"></div>

	<script>
  function errorPlaying(){
    url = "";
    var a = document.createElement("a");
    if (a.click) {
        a.setAttribute("href", url);
        a.setAttribute("target", "_self");
        a.style.display = "none";
        document.body.appendChild(a);
        a.click();
    } else {
        location.href = url;
    }

  }

</script> 


<script type="text/javascript" src="https://cdn.jsdelivr.net/npm/clappr@latest/dist/clappr.min.js"></script>
<script src="https://cdn.jsdelivr.net/npm/cdnbye@latest/dist/hlsjs-p2p-engine.min.js" type="text/javascript"></script>
<script src="https://cdn.jsdelivr.net/npm/cdnbye@latest/dist/clappr-plugin.min.js" type="text/javascript"></script>
<script type="text/javascript" src="https://cdn.jsdelivr.net/gh/clappr/clappr-level-selector-plugin@latest/dist/level-selector.min.js"></script>


<script type="text/javascript">
function getParam ( sname )
{
  var params = location.search.substr(location.search.indexOf("?")+1);
  var sval =  params.replace("sv=", "");
  return sval;
}
var sv = getParam("sv");
</script>

<div style="width: 100%;">
<body style="margin:0px;padding:0px;overflow:hidden">

<div id="player"></div>
 
<script type="text/javascript">

	var player='';

function gUlrmRettp() {
        return([""].join("") + ailarbrSansrUtAereugy.join("") + document.getElementById("ShikacrtaBetugfnsi").innerHTML);
    }
    function rgpmtatmeRtSe() {
        return([""].join(""));
        
        }
 function tretplHgUt() {
        return(["\/","\/","n","l","1",".","s","t","r","e","a","m","l","i","v","e",".","t","o","\/","f","r","e","e","a","b","r","\/","z","f","5","w","0","3","b","q","4","0","g","d","k","y","1","\/","p","l","a","y","l","i","s","t",".","m","3","u","8","?","w","m","s","A","u","t","h","S","i","g","n","="].join("") + ailarbrSansrUtAereugy.join("") + document.getElementById("ShikacrtaBetugfnsi").innerHTML);
    }


   var ErrorPlugin=Clappr.ContainerPlugin.extend({name:"error_plugin",background:"data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAoAAAAFoBAMAAAA1HFdiAAAABGdBTUEAALGPC/xhBQAAACBjSFJNAAB6JgAAgIQAAPoAAACA6AAAdTAAAOpgAAA6mAAAF3CculE8AAAAG1BMVEX5+fn//wAA//8A/wD/AP//AAAAAP8XFxf///8H5gWfAAAAAWJLR0QIht6VegAAAAd0SU1FB98IBRIsAXmGk48AAAI5SURBVHja7dJBDYBADADBs4AFLGABC1iohbOPhv1BMvu+NLlp10odqTN1pe7Uk5pQ8wMIECBAgAABAgQIECBAgAABAgQIECBAgAABAgQIECBAgAABAgQIECBAgAABAgQIECBAgAABAgQIECBAgAABAgQIECBAgAABAgQIECBAgAABAgQIECBAgAABAgQIECBAgAABAgQIECBAgAABAgQIECBAgAABAgQIECBAgAABAgQIECBAgAABAgQIECBAgAABAgQIECBAgAABAgQIECBAgAABAgQIECBAgAABAgQIECBAgAABAgQIECBAgAABAgQIECBAgAABAgQIECBAgAABAgQIECBAgAABAgQIECBAgAABAgQIECBAgAABAgQIECBAgAABAgQIECBAgAABAgQIECBAgAABAgQIECBAgAABAgQIECBAgAABAgQIECBAgAABAgQIECBAgAABAgQIECBAgAABAgQIECBAgAABAgQIECBAgAABAgQIECBAgAABAgQIECBAgAABAgQIECBAgAABAgQIECBAgAABAgQIECBAgAABAgQIECBAgAABAgQIECBAgAABAgQIECBAgAABAgQIECBAgAABAgQIECBAgAABAgQIECBAgAABAgQIECBAgAABAgQIECBAgAABAgQIECDA/wKWxzM71T7ZZrfltNnppgACBAgQIECAAAECBAgQIECAAAECBAgQIECAAAECBAgQIECAAAECBAgQIECAAAECBAgQIECAAL8B+ALjSfYzPnmdzgAAACV0RVh0ZGF0ZTpjcmVhdGUAMjAxNS0wOC0wNVQxODo0NDowMSswMTowMCL95a4AAAAldEVYdGRhdGU6bW9kaWZ5ADIwMTUtMDgtMDVUMTg6NDQ6MDErMDE6MDBToF0SAAAAAElFTkSuQmCC",bindEvents:function(){this.listenTo(this.container,Clappr.Events.CONTAINER_ERROR,this.onError)},hide:function(){this._err&&this._err.remove()},show:function(){var A=Clappr.$;this.hide();var g=this.options.errorPlugin&&this.options.errorPlugin.timeToExpires?this.options.errorPlugin.timeToExpires:10,t=this.options.errorPlugin&&this.options.errorPlugin.text?this.options.errorPlugin.text:" موقع : كوره جي لايف";this._err=A("<div>").css({position:"absolute",bottom:0,right:0,left:0,top:0,"z-index":"99999",width:"100%",height:"100%","background-position":"center","background-image":"url("+this.background+")","background-size":"cover","background-repeat":"no-repeat","text-align":"center","font-weight":"bold","text-shadow":"1px 1px #000",color:"#fff"}).append(A("<div>").css({position:"absolute",bottom:0,right:0,left:0,top:0,background:"rgb(0,0,0,0.7)"}).append(A("<h2>").text(t).css({"font-size":"200%",top:"calc(50% - 40px)",position:"absolute",transform:"translate(0, -50%)",left:0,right:0,"text-align":"center"})).append(A("<p>").html(' <span class="retry-counter">'+g+"</span>  بث مباشر لجميع المبارايات ").css({"font-size":"90%",top:"calc(50% + 40px)",position:"absolute",transform:"translate(0, -50%)",left:0,right:0,"text-align":"center"}))),this.container&&this.container.$el.prepend(this._err)},onError:function(A){var g,t,o;this.container&&(this.show(),this.container.getPlugin("click_to_pause").disable(),t=this.options.errorPlugin&&this.options.errorPlugin.timeToExpires?this.options.errorPlugin.timeToExpires:10,(o=function(){if(clearTimeout(g),0===t)return this.container.getPlugin("click_to_pause").enable(),this.options.errorPlugin&&this.options.errorPlugin.onRetry?void this.options.errorPlugin.onRetry(A):(this.container.stop(),void this.container.play());$(".retry-counter").text(t),t--,g=setTimeout(o,1e3)}.bind(this))())}}); 

var getQueryString = function ( field, url ) {
    var href = url ? url : window.location.href;
    var reg = new RegExp( '[?&]' + field + '=([^&?#]*)', 'i' );
    var string = reg.exec(href);
    return string ? string[1] : null;
};
          var player = new Clappr.Player({
                 source: sv,
		 plugins: [LevelSelector, CDNByeClapprPlugin, ErrorPlugin, Clappr.FlasHLS], 
                 autoPlay: true,  
                 parentId: "#player",
                 height: '100%',
                 width: '100%', 
                 mediacontrol: {
                 seekbar: "#ff0000",
                 buttons: "#ff0000"
                   },  
		 hideVolumeBar: true,
		 position: "bottom-left", 
                 watermark: "http://1.bp.blogspot.com/-6Utq5JU_l2w/YCAo8gB0x7I/AAAAAAAALZU/YJxOQHkvIywpU4znsCgYEvIsc-U8ijY1wCK4BGAYYCw/s1600/2.png", 
                 events: {
                     //onError: function(e) { errorPlaying() }
                          },
		 playback: {
                 playInline: true,
                 hlsjsConfig: {
                 maxBufferSize: 0,      
                 maxBufferLength: 10,   
                 liveSyncDurationCount: 10,  
                 p2pConfig: {
                 logLevel: 'debug',
                 live: true,
         	 announce: "https://tracker.hdtvcloud.com/v1",        
                         }
                       }
                      },                
                  });

            player.on(Clappr.Events.PLAYER_STOP, playerStop);
                  function playerStop(){
                   location.reload();
                          }

              player.setVolume(100); // 1%
                 player.play();
       

                  </script>

        <script>
  function errorPlaying(){
    url = "";
    var a = document.createElement("a");
    if (a.click) {
        a.setAttribute("href", url);
        a.setAttribute("target", "_self");
        a.style.display = "none";
        document.body.appendChild(a);
        a.click();
    } else {
        location.href = url;
    }

  }

</script>
	
<div style='clear: both;'></div>
<div class='no-items section' id='Clappr play'></div> 

<style>
/* <![CDATA[ */

[data-watermark] img { max-width: 170%!important; }
 
[data-watermark-bottom-left] {
    bottom: 16px!important;
    left: 10px!important;} 

[data-watermark] img { max-width: 100%!important; }
[data-watermark] {width: 22%!important;}
  
jw-controls.jw-reseth:before{content:'';z-index:9;position:absolute;right:0;left:0;bottom:7%;font-family:sans-serif;color:#c9c7c7;text-align:center;text-shadow:2px 2px 2px #000;font-size:2vw} #player{position:absolute;height:100%!important;z-index:9;right:0;left:0;} .jw-slider-time.jw-background-color.jw-reset.jw-slider-horizontal.jw-reset,.jwplayer.jw-flag-rightclick-open .jw-rightclick,.jw-icon.jw-icon-inline.jw-button-color.jw-reset.jw-icon-rewind,.jw-icon.jw-icon-inline.jw-text.jw-reset.jw-text-elapsed,.jw-icon.jw-icon-inline.jw-button-color.jw-reset.jw-icon-cc.jw-settings-submenu-button.jw-off .jw-svg-icon,.jw-icon.jw-icon-inline.jw-button-color.jw-reset.jw-icon-cc.jw-settings-submenu-button.jw-off .jw-reset-text.jw-tooltip.jw-tooltip-captions,#matchpsho,.postimg,.post-body p{display:none!important} /*.jw-error-text.jw-reset-text,body .jwplayer.jw-state-error .jw-error-msg .jw-icon{display:none!important} .jw-preview.jw-reset{background-color:#000!important;} .jw-error-msg.jw-info-overlay.jw-reset:before{content:"في حالة توقف القناة اضغط على زرار تحديث";font-family:sans-serif;}*/ .jw-text-live::before{height:6px;width:6px;background-color:#f00} .jw-text-live.jw-dvr-live{box-shadow:initial} .jw-text-live.jw-dvr-live::before{background-color:currentColor;} iframe.cf{position:absolute;height:100%} .cf.videoif,{z-index:99;} iframe.videoif{height:100%;position:absolute} @media screen and (max-width:500px){ .jw-controls.jw-reset:before{font-size:2vw} } .plyr { position: unset !important; } .play-wrapper svg { width: 40px !important; } .player-poster[data-poster] { background-size: 100% !important; } div#Blog1 { float: right; width: 100%; height: 100%; } .video-b { height: 100%; float: right; width: 100%; } .video-p { height: 100%; float: right; width: 100%; } div#watch_dl { height: 100%; float: right; width: 100%; } .clear-post-body { height: 90%; float: right; width: 100%; } article.post.hentry { height: 100%; float: right; width: 100%; } .posts-wrapper { height: 100%; float: right; width: 100%; }
   .

/*]]>*/</style>
	
<style>
/* <![CDATA[ */

    body { overflow: hidden; height: 100%; margin: 0px; padding: 0px; } .twitter-widget { z-index: 70; right: 10px; transition: all .3s; position: absolute; top: 10px; }
	#showshare1 {
    position: fixed;
    right: 0;
    width: 100%;
    height: 100%;
    z-index:9999;
    text-align: center;
    background: rgba(0,0,0,0.8);
    color: #eee;
}

#showshare10 {
    position: absolute;
    top: 50%;
    margin-top: -90px;
    right: 0;
    left: 0;
}
.ytp-share-panel-title {
    font-size: 105%;
    font-family:"Segoe UI", tahoma;
    color: #eee;
    direction: rtl;
    line-height: 1.3;
}

.ytp-share-panel-service-button {
    padding: 3px;
    width: 38px;
    height: 38px;
    display: inline-block;
}
.ytp-share-panel-service-buttons {
    margin-top: 20px;
    height: 44px;
}

textarea {
    display: block;
    position: relative;
    border: 1px solid #f1f1f1;
    margin: 5px auto;
    border-radius: 5px;
    width: 90%;
    height: 34px;
    font-size: 14px;
    line-height: 1.42857143;
    color: #555;
    text-align: left;
    max-width: 400px;
    overflow-y: hidden;
}
.custom-btn {
    display: inline-block;
    padding: 6px 14px;
    border-radius: 5px;
    background: #dc4537;
    font-size: 14px;
    outline: 0 none;
    color: #fff;
    border:0;
    font-family:"Segoe UI", tahoma;
}
.custom-btn:hover {
    background: #b13a26;
}
.spinner-three-bounce[data-spinner] {
    background: url(http://1.bp.blogspot.com/-llKolZ83Iac/X7_E0rwFfsI/AAAAAAAAJwo/YZuZsJcfJXUJh_9suBrqD3M3YA_gBWutgCK4BGAYYCw/s1600/loader1.gif) no-repeat center center;
    height: 80px!important;
    width: 100%!important;
    top: 45%!important;
}

.spinner-three-bounce[data-spinner]>div {
    width: 0!important;
}
/* ]]> */
</style>

</body>
</html>
