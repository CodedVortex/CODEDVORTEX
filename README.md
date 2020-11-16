<!DOCTYPE html>
<html>

<!-- Mirrored from javasnake.neocities.org/cookie/ by HTTrack Website Copier/3.x [XR&CO'2014], Wed, 28 Nov 2018 06:13:43 GMT -->
<head>
<title>Cookie Clicker</title>
<!--
Code and graphics copyright Orteil, 2013
Feel free to alter this code to your liking, but please do not re-host it, do not profit from it and do not present it as your own.

-TODO :
	-milk toys
	-temple building
	-dungeons
	-gambling
	-better tooltips
	-better prestige
	-add canvas support
	-timer bars for golden cookie effects
	-set event listeners instead of onclick
	-more zebras
-->

<link rel="shortcut icon" href="img/favicon.ico" />
<link href="../../fonts.googleapis.com/css9959.css?family=Kavoon&amp;subset=latin,latin-ext" rel="stylesheet" type="text/css">
<link href="style7682.css?v=1.5028" rel="stylesheet" type="text/css">

<script src="base64.js"></script>
<script src="ajax.js"></script>
<script src="dungeons8831.js?v=1.5026"></script>
<script src="main70b5.js?v=1.5031"></script>


<script type="text/javascript">
  var _gaq = _gaq || [];
  _gaq.push(['_setAccount', 'UA-29324474-2']);
  _gaq.push(['_setDomainName', 'dashnet.org']);
  _gaq.push(['_trackPageview']);

  (function() {
    var ga = document.createElement('script'); ga.type = 'text/javascript'; ga.async = true;
    ga.src = ('https:' == document.location.protocol ? 'https://ssl' : 'http://www') + '.google-analytics.com/ga.js';
    var s = document.getElementsByTagName('script')[0]; s.parentNode.insertBefore(ga, s);
  })();
</script>

</head>
<body>

<div id="topBar">
	<div>
		<b>Cookie Clicker</b> &copy; <a href="../../orteil.dashnet.org/index.html" target="_blank">Orteil</a>, 2013 - hosted by <a href="../../dashnet.org/index.html" target="_blank">DashNet</a> | <a href="../../twitter.com/orteil42.html" target="_blank">twitter</a> | <a href="../../orteil42.tumblr.com/index.html" target="_blank">tumblr</a> | Help? Bugs? Ideas? Check out the <a href="../../forum.dashnet.org/index.html" target="_blank">forum</a>! | Chat with us on <a href="../../forum.dashnet.org/discussion/277/irc-chat-channel/p1.html" target="_blank">IRC</a> | Getting a black screen? Try pressing ctrl-F5!
		<div id="links" style="display:block;position:absolute;right:8px;top:4px;"></div>
	</div>
</div>

<div id="game">
	<div id="javascriptError">
		<div style="padding:64px 128px;">
			<div class="title">Oops, looks like the game isn't loading right!</div>
			<div>Please make sure your javascript is enabled, then refresh.<br>
			This could also be caused by a problem on our side, in which case - wait a moment, then refresh!</div>
		</div>
	</div>

	<div id="backgroundLayers">
		<div id="backgroundLayer1"></div>
		<div id="backgroundLayer2"></div>
	</div>
	
	<div id="goldenCookie" class="goldenCookie"></div>
	<div id="alert"></div>
	<div id="particles"></div>
	<div id="versionNumber" class="title"></div>
	
	<div id="sectionLeft" class="inset">
		<div id="cookieShower"></div>
		<div class="blackGradient"></div>
		<div class="blackFiller"></div>
		<div id="sectionLeftInfo"></div>
		<div id="cookies" class="title"></div>
		<div id="cookieAnchor">
			<div id="cookieShine"></div>
			<div id="cookieCursors"></div>
			<div id="bigCookie"></div>
			<div id="cookieNumbers"></div>
		</div>
		<div id="milk">
			<div id="milkLayer1" class="milkLayer"></div>
			<div id="milkLayer2" class="milkLayer"></div>
		</div>
	</div>

	<div class="separatorLeft"></div>
	<div class="separatorRight"></div>
		
	<div id="sectionMiddle" class="inset">
		<div id="comments" class="inset title">
			<div id="prefsButton" class="button">Menu</div>
			<div id="statsButton" class="button">Stats</div>
			<div id="logButton" class="button" style="font-size:80%;">Updates</div>
			<div id="commentsText"></div>
			<div class="separatorBottom"></div>
		</div>
		<div id="rows"></div>
		<div id="menu"></div>
	</div>

	<div id="sectionRight" class="inset">
		<div id="store">
			<div id="storeTitle" class="inset title">Store</div>
			<div id="upgrades">
			</div>
			<div id="products">
			</div>
		</div>
		
		<div id="support">
			<form action="https://www.paypal.com/cgi-bin/webscr" method="post" id="donate" style="margin:0px 16px;">
			<div id="supportComment">Help us make more games!</div>
			<input type="hidden" name="cmd" value="_s-xclick">
			<input type="hidden" name="hosted_button_id" value="BBN2WL3TC6QH4">
			<input type="image" src="../../www.paypalobjects.com/en_GB/i/btn/btn_donate_LG.gif" border="0" name="submit" alt="PayPal — The safer, easier way to pay online.">
			<img alt="" border="0" src="../../www.paypalobjects.com/nl_NL/i/scr/pixelaf83.gif" width="1" height="1">
			</form>			
		</div>
	</div>
	
	<div id="tooltipAnchor"><div id="tooltip" onMouseOut="Game.tooltip.hide();"></div></div>

</div>

</body>

<!-- Mirrored from javasnake.neocities.org/cookie/ by HTTrack Website Copier/3.x [XR&CO'2014], Wed, 28 Nov 2018 06:14:05 GMT -->
</html>
