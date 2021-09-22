<?xml version="1.0" encoding="UTF-8"?>
<theme name="Mike" version="1817">
	<properties>
		<templateset><![CDATA[12]]></templateset>
		<editortheme><![CDATA[default.css]]></editortheme>
		<imgdir><![CDATA[images]]></imgdir>
		<logo><![CDATA[http://i.imgur.com/9b6TxP3.png]]></logo>
		<tablespace><![CDATA[5]]></tablespace>
		<borderwidth><![CDATA[0]]></borderwidth>
		<color><![CDATA[]]></color>
		<disporder><![CDATA[a:9:{s:10:"global.css";i:1;s:10:"Cobalt.css";i:1;s:8:"css3.css";i:2;s:10:"usercp.css";i:5;s:9:"modcp.css";i:7;s:16:"star_ratings.css";i:8;s:14:"showthread.css";i:9;s:17:"thread_status.css";i:10;s:10:"extras.css";i:11;}]]></disporder>
	</properties>
	<stylesheets>
		<stylesheet name="css3.css" version="1817"><![CDATA[tr td.trow1:first-child,
tr td.trow2:first-child,
tr td.trow_shaded:first-child {
	border-left: 0;
}

tr td.trow1:last-child,
tr td.trow2:last-child,
tr td.trow_shaded:last-child {
	border-right: 0;
}

.tborder {
	background: #444;
	width: 100%;
	margin: auto auto;
	padding: 1px;
}

.tborder tbody tr:last-child > td {
	border-bottom: 0;
}

.tborder tbody tr:last-child > td:first-child {
	-moz-border-radius-bottomleft: 6px;
	-webkit-border-bottom-left-radius: 6px;
	border-bottom-left-radius: 6px;
}

.tborder tbody tr:last-child > td:last-child {
	-moz-border-radius-bottomright: 6px;
	-webkit-border-bottom-right-radius: 6px;
	border-bottom-right-radius: 6px;
}

.thead {
	-moz-border-radius-topleft: 6px;
	-moz-border-radius-topright: 6px;
	-webkit-border-top-left-radius: 6px;
	-webkit-border-top-right-radius: 6px;
	border-top-left-radius: 6px;
	border-top-right-radius: 6px;
}

.thead_collapsed {
	-moz-border-radius-bottomleft: 6px;
	-moz-border-radius-bottomright: 6px;
	-webkit-border-bottom-left-radius: 6px;
	-webkit-border-bottom-right-radius: 6px;
	border-bottom-left-radius: 6px;
	border-bottom-right-radius: 6px;
}

.thead_left {
	-moz-border-radius-topright: 0;
	-webkit-border-top-right-radius: 0;
	border-top-right-radius: 0;
}

.thead_right {
	-moz-border-radius-topleft: 0;
	-webkit-border-top-left-radius: 0;
	border-top-left-radius: 0;
}

.tcat_menu {
	-moz-border-radius: 0 !important;
	-webkit-border-radius: 0 !important;
	border-radius: 0 !important;
}

.tborder tbody:nth-last-child(2) .tcat_collapse_collapsed {
	-moz-border-radius-bottomleft: 6px !important;
	-moz-border-radius-bottomright: 6px !important;
	-webkit-border-bottom-left-radius: 6px !important;
	-webkit-border-bottom-right-radius: 6px !important;
	border-bottom-left-radius: 6px !important;
	border-bottom-right-radius: 6px !important;
}

button,
input.button,
input.textbox,
input.invalid_field,
input.valid_field,
select,
textarea,
.editor_control_bar,
blockquote,
.codeblock,
fieldset,
.pm_alert,
.red_alert,
.popup_menu,
.postbit_buttons > a,
a.button {
	-moz-border-radius: 6px;
	-webkit-border-radius: 6px;
	border-radius: 6px;
}

.post.classic .post_author {
	-moz-border-radius: 0 6px 6px 0;
	/* -webkit-border-radius: 0 6px 6px 0; */
	/* border-radius: 0 6px 6px 0; */
}

.popup_menu .popup_item_container:first-child .popup_item {
	-moz-border-radius-topleft: 6px;
	-moz-border-radius-topright: 6px;
	-webkit-border-top-left-radius: 6px;
	-webkit-border-top-right-radius: 6px;
	border-top-left-radius: 6px;
	border-top-right-radius: 6px;
}

.popup_menu .popup_item_container:last-child .popup_item {
	-moz-border-radius-bottomleft: 6px;
	-moz-border-radius-bottomright: 6px;
	-webkit-border-bottom-left-radius: 6px;
	-webkit-border-bottom-right-radius: 6px;
	border-bottom-left-radius: 6px;
	border-bottom-right-radius: 6px;
}

.pagination a {
	-moz-border-radius: 6px;
	-webkit-border-radius: 6px;
	border-radius: 6px;
}

.pollbar {
	-moz-border-radius: 3px;
	-webkit-border-radius: 3px;
	border-radius: 3px;
}
		
		
		
		
		
		
		]]>
		</stylesheet>
		<stylesheet name="global.css" version="1817"><![CDATA[body {
	background: #272726;
	color: #272726;
	text-align: center;
	line-height: 1.4;
	margin: 0;
	overflow-y: scroll;
	
	font-family: Tahoma, Verdana, Arial, Sans-Serif;
	font-size: 13px;
}

a:link {
	color: #fff;
	text-decoration: none;
}

a:visited {
	color: #fff;
	text-decoration: none;
}

a:hover,
a:active {
	color: #fff;
	text-decoration: none;
}

#container {
	color: #333;
	text-align: left;
	line-height: 1.4;
	margin: 0;
	font-family: Tahoma, Verdana, Arial, Sans-Serif;
	font-size: 13px;
	min-width: 990px;
}

.wrapper {
	width: 85%;
	min-width: 970px;
	max-width: 1500px;
	margin: auto auto;
}

#logo {
	background: url(http://i.imgur.com/JiD9Zni.png);
	padding: 10px 0;
}

#content {
	width: auto !important;
	padding: 20px 10px;
	overflow: hidden;
}

#header ul.menu {
	margin: 0;
	padding: 0;
	list-style: none;
}

#header ul.menu li {
	margin: 0 7px;
	display: inline;
}

#header ul.menu li a {
	background-repeat: no-repeat;
	display: inline-block;
	line-height: 16px;
}

#logo ul.top_links {
	font-weight: bold;
	text-align: right;
	margin: -10px 5px 0 0;
}

#logo ul.top_links a.search {
	background-position: 0 0;
}

#logo ul.top_links a.memberlist {
	background-position: 0 -20px;
}

#logo ul.top_links a.calendar {
	background-position: 0 -40px;
}

#logo ul.top_links a.help {
	background-position: 0 -60px;
}

#logo ul.top_links a.portal {
	background-position: 0 -180px;
}

#panel .upper a.logout {
	font-weight: bold;
	background: url(images/headerlinks_sprite.png) right -80px no-repeat;
	padding-right: 20px;
	margin-left: 10px;
}

#panel .upper a.login,
#panel .upper a.lost_password {
	background: url(images/headerlinks_sprite.png) 0 -100px no-repeat;
	padding-left: 20px;
	margin-left: 10px;
	font-weight: bold;
}

#panel .upper a.register {
	background: url(images/headerlinks_sprite.png) right -80px no-repeat;
	padding-right: 20px;
	margin-left: 10px;
	font-weight: bold;
}

#panel .lower ul.panel_links {
	float: left;
}

#panel .lower ul.panel_links a.usercp {
	background-position: 0 -120px;
}

#panel .lower ul.panel_links a.modcp {
	background-position: 0 -140px;
}

#panel .lower ul.panel_links a.admincp {
	background-position: 0 -160px;
}

#panel .lower ul.user_links {
	float: right;
}

#panel .lower ul.user_links li a {
	padding: 0;
	background-image: none;
}

#panel .middle {
	background: #3a3838;
	color: #fff;
	border-top: 1px solid #737272;
	border-bottom: 1px solid #000;
	padding: 7px;
	clear: both;
}

#panel .middle a:link,
#panel .middle a:visited,
#panel .middle a:hover,
#panel .middle a:active {
	color: #fff;
}

#panel .upper {
	background: #444;
	color: #fff;
	padding: 7px;
	clear: both;
}

#panel .upper a:link,
#panel .upper a:visited,
#panel .upper a:hover,
#panel .upper a:active {
	color: #fff;
}

#panel .lower {
	background: #505050;
	color: #b7b7b7;
	padding: 5px;
}

#panel .lower a:link,
#panel .lower a:visited,
#panel .lower a:hover,
#panel .lower a:active {
	color: #fff;
}

#search {
	border: 0;
	padding: 0;
	margin: 0;
	float: right;
	vertical-align: middle;
}

#search input.button,
#search input.textbox {
	border-color: #000;
}

#search input.button {
	background: #0066a2 url(images/thead.png) top left repeat-x;
	color: #fff;
}

#search input {
	margin: -3px 0;
}

#quick_login .remember_me input {
	vertical-align: middle;
	margin: -3px 0 0 5px;
}

#footer {
	clear: both;
}

#footer ul.menu {
	margin: 0;
	padding: 0;
	list-style: none;
}

#footer ul.menu li {
	margin: 0 5px;
	display: inline;
}

#footer .upper {
	background: #efefef;
	border-top: 1px solid #bbb;
	border-bottom: 1px solid #bbb;
	padding: 6px;
	font-size: 12px;
	overflow: hidden;
}

#footer a:link,
#footer a:visited,
#footer a:hover,
#footer a:active {
	color: #777;
}

#footer .upper .language {
	float: right;
	margin: -1px;
	margin-left: 15px;
}

#footer .upper .language select {
	border-color: #ccc;
}

#footer .upper .theme {
	float: right;
	margin: -1px;
	margin-left: 15px;
}

#footer .upper .theme select {
	border-color: #ccc;
}

#footer .upper ul.bottom_links {
	float: left;
	margin: 4px 0 0 0;
}

#footer .lower {
	color: #666;
	padding: 6px 6px 12px 6px;
	overflow: hidden;
	font-size: 11px;
}

#footer .lower a:link,
#footer .lower a:visited {
	color: #444;
	font-weight: bold;
}

#footer .lower a:hover,
#footer .lower a:active {
	color: #333;
	text-decoration: none;
	font-weight: bold;
}

#footer .lower #current_time {
	float: right;
	color: #888;
}

#debug {
	float: right;
	text-align: right;
	margin-top: 20px;
	font-size: 11px;
}

.scaleimages img {
	max-width: 100%;
}

.forum_status {
height: 50px;
width: 50px;
font-size: 30px;
text-align: center;
}

.forum_status i {
display: inline-block;
line-height: 50px;
}

.forum_on {
color: #96ead7;
}

.forum_off, .forum_offlock, .forum_offlink {
color: #cacaca;
}

.forum_off i {
opacity: .4;
}

.forum_offlock i:before {
content: "\f023";
}

.forum_offlink i:before {
content: "\f0c1";
}

.subforumicon {
height: 10px;
width: 10px;
display: inline-block;
 margin: 0 5px;
}

.subforum_minion {
color: #cacaca;
}

.subforum_minioff, .subforum_miniofflock, .subforum_miniofflink {
color: #cacaca;
}

.subforum_minioff {
opacity: .4;
}

.subforum_miniofflock i:before {
content: "\f023";
}

.subforum_miniofflink i:before {
content: "\f0c1";
}

table {
	color: #fff;
	font-size: 13px;
}

.tborder {
	border: #17687c;
	padding: 1px;
}

.tfixed {
	table-layout: fixed;
	word-wrap: break-word;
}

.thead {
	background: #252525;
	color: #ffffff;
	border-bottom: 3px solid #8eaf26;
	padding: 8px;
}

.thead a:link {
	color: #ffffff;
	text-decoration: none;
}

.thead a:visited {
	color: #ffffff;
	text-decoration: none;
}

.thead a:hover,
.thead a:active {
	color: #ffffff;
	text-decoration: none;
}

.tcat {
	background: #444;
	color: #fff;
	padding: 6px;
	font-size: 12px;
}

.tcat a:link {
	color: #fff;
}

.tcat a:visited {
	color: #fff;
}

.tcat a:hover,
.tcat a:active {
	color: #fff;
}

.trow1 {
	background: #272726;
	border-bottom: 1px solid #272726;
}

.trow2 {
	background: #272726;
	border-bottom: 1px solid #272726;
}

.trow_shaded {
	background: #ffdde0;
	border: 1px solid;
	border-color: #fff #ffb8be #ffb8be #fff;
}

.no_bottom_border {
	border-bottom: 0;
}

.post.unapproved_post {
	background: #ffdde0;
}

.post.unapproved_post .post_author {
	border-bottom-color: #ffb8be;
}

.post.classic.unapproved_post .post_author {
	border-color: #ffb8be;
}

.post.unapproved_post .post_controls {
	border-top-color: #ffb8be;
}

.trow_deleted,
.post.deleted_post {
	background: #E8DEFF;
}

.trow_selected,
tr.trow_selected td {
	background: #FFFBD9;
	color: #333;
	border-right-color: #F7E86A;
	border-bottom-color: #F7E86A;
}

.trow_selected a:link,
.trow_selected a:visited,
.trow_selected a:hover,
.trow_selected a:active {
	color: #333;
}

.trow_sep {
	background: #ddd;
	color: #333;
	border-bottom: 1px solid #c5c5c5;
	padding: 6px;
	font-size: 12px;
	font-weight: bold;
}

.tfoot {
	padding: 6px;
	background: #444;
	color: #fff;
}

.tfoot a:link {
	color: #fff;
	text-decoration: none;
}

.tfoot a:visited {
	color: #fff;
	text-decoration: none;
}

.tfoot a:hover,
.tfoot a:active {
	color: #444;
	text-decoration: none;
}

.thead input.textbox,
.thead select {
	border: 1px solid #263c30;
}

.bottommenu {
	background: #efefef;
	color: #333;
	border: 1px solid #4874a3;
	padding: 10px;
}

.navigation {
	color: #333;
	font-size: 12px;
}

.navigation a:link {
	text-decoration: none;
}

.navigation a:visited {
	text-decoration: none;
}

.navigation a:hover,
.navigation a:active {
	text-decoration: none;
}

.navigation .active {
	color: #333;
	font-size: small;
	font-weight: bold;
}

.smalltext {
	font-size: 11px;
	color: #fff;
}

.largetext {
	font-size: 16px;
	font-weight: bold;
}

fieldset {
	padding: 12px;
	border: 1px solid #96ead7;
	margin: 0;
}

fieldset.trow1,
fieldset.trow2 {
	border-color: #bbb;
}

fieldset.align_right {
	text-align: right;
}

input.textbox {
	background: #ffffff;
	color: #333;
	border: 1px solid #ccc;
	padding: 3px;
	outline: 0;
	font-size: 13px;
	font-family: Tahoma, Verdana, Arial, Sans-Serif;
}

textarea {
	background: #ffffff;
	color: #333;
	border: 1px solid #ccc;
	padding: 2px;
	line-height: 1.4;
	outline: 0;
	font-family: Tahoma, Verdana, Arial, Sans-Serif;
	font-size: 13px;
}

select {
	background: #ffffff;
	padding: 3px;
	border: 1px solid #ccc;
	outline: 0;
	font-family: Tahoma, Verdana, Arial, Sans-Serif;
	font-size: 13px;
}

button,
input.button {
	padding: 3px 8px;
	cursor: pointer;
	font-family: Tahoma, Verdana, Arial, Sans-Serif;
	font-size: 13px;
	background: #eee url(images/buttons_bg.png) repeat-x;
	border: 1px solid #bbb;
	color: #333;
	outline: 0;
}

button:hover,
input.button:hover {
	border-color: #aaa;
}

form {
	margin: 0;
	padding: 0;
}

input.error, textarea.error, select.error {
	border: 1px solid #f30;
	color: #f30;
}

input.valid, textarea.valid, select.valid {
	border: 1px solid #0c0;
}

label.error {
	color: #f30;
	margin: 5px;
	padding: 0px;
	display: block;
	font-weight: bold;
	font-size: 11px;
}

form #message {
	width: 500px;
}

.editor {
	background: #f1f1f1;
	border: 1px solid #ccc;
}

.editor_control_bar {
	background: #fff;
	border: 1px solid #ccc;
}

.post .editor_control_bar {
	background: #f5f5f5;
}

.popup_menu {
	background: #fff;
	border: 1px solid #ccc;
}

.popup_menu .popup_item {
	background: #efefef;
	color: #333;
}

.popup_menu .popup_item:hover {
	background: #0072BC;
	color: #fff;
}

.trow_reputation_positive {
	background: #333;
}

.trow_reputation_negative {
	background: #ffcccc;
}

.reputation_positive {
	color: #00de00;
}

.reputation_neutral {
	color: #bfbfbf;
}

.reputation_negative {
	color: red;
}

.repbox {
	font-size:16px;
	font-weight: bold;
	padding:5px 7px 5px 7px;
}

._neutral {
	background-color:#FAFAFA;
	color: #999999;
	border:1px solid #CCCCCC;
}

._minus {
	background-color: #FDD2D1;
	color: #CB0200;
	border:1px solid #980201;
}

._plus {
	background-color:#E8FCDC;
	color: #008800;
	border:1px solid #008800;
}

img {
	border: none;
}

img.attachment {
	border: 1px solid #E9E5D7;
	padding: 2px;
}

hr {
border: 1px solid #333;

width: 103%;

margin-left: -11px;
}

.clear {
	clear: both;
}

.float_left {
	float: left;
}

.float_right {
	float: right;
}

.hidden {
	display: none;
	float: none;
	width: 1%;
}

.hiddenrow {
	display: none;
}

.selectall {
	background: #FFFBD9;
	border-bottom: 1px solid #F7E86A;
	color: #333;
	text-align: center;
}

.expcolimage {
	float: right;
	width: auto;
	vertical-align: middle;
	margin-top: 3px;
}

.tcat_menu > .expcolimage {
	margin-top: 0;
}

blockquote {
	border: 1px solid #ccc;
	margin: 0;
	background: #333;
	padding: 10px;
}

blockquote cite {
	font-weight: bold;
	border-bottom: 1px solid #ccc;
	font-style: normal;
	display: block;
	padding-bottom: 3px;
	margin: 0 0 10px 0;
}

blockquote cite span {
	float: right;
	font-weight: normal;
	font-size: 12px;
	color: #666;
}

blockquote cite span.highlight {
	float: none;
	font-weight: bold;
	padding-bottom: 0;
}

.codeblock {
	background: #fff;
	border: 1px solid #ccc;
	padding: 10px;
}

.codeblock .title {
	border-bottom: 1px solid #ccc;
	font-weight: bold;
	padding-bottom: 3px;
	margin: 0 0 10px 0;
}

.codeblock code {
	overflow: auto;
	height: auto;
	max-height: 200px;
	display: block;
	font-family: Monaco, Consolas, Courier, monospace;
	font-size: 13px;
}

.smilie {
	vertical-align: middle;
}

.smilie_pointer {
	cursor: pointer;
}

.separator {
	margin: 5px;
	padding: 0;
	height: 0px;
	font-size: 1px;
	list-style-type: none;
}

.popup_menu .popup_item_container {
	margin: 1px;
	text-align: left;
}

.popup_menu .popup_item {
	display: block;
	padding: 4px;
	white-space: nowrap;
	text-decoration: none;
}

.popup_menu a.popup_item:hover {
	text-decoration: none;
}

.subject_new {
	font-weight: bold;
}

.highlight {
	background: #FFFFCC;
	padding-top: 3px;
	padding-bottom: 3px;
}

.pm_alert {
	background: #444444;
	border: 2px solid #96ead7;
	text-align: center;
	padding: 7px;
	color: #b7b7b7;
	font-size: 11px;
}

.red_alert {
	background: #FBE3E4;
	border: 1px solid #A5161A;
	color: #A5161A;
	text-align: center;
	padding: 5px 20px;
	margin-bottom: 15px;
	font-size: 11px;
	word-wrap: break-word;
}

.red_alert a:link,
.red_alert a:visited,
.red_alert a:hover,
.red_alert a:active {
	color: #A5161A;
}

.high_warning {
	color: #CC0000;
}

.moderate_warning {
	color: #F3611B;
}

.low_warning {
	color: #AE5700;
}

.imminent_banned {
	color: #880000;
}

.high_banned {
	color: #FF0000;
}

.moderate_banned {
	color: #FF6600;
}

.low_banned {
	color: #008000;
}

.online {
	color: #15A018;
}

.offline {
	color: #C7C7C7;
}

div.error {
	padding: 5px 10px;
	border-top: 2px solid #FFD324;
	border-bottom: 2px solid #FFD324;
	background: #444444;
	font-size: 12px;
}

div.error p {
	margin: 0;
	color: #333;
	font-weight: normal;
}

div.error p em {
	font-style: normal;
	font-weight: bold;
	padding-left: 24px;
	display: block;
	color: #ef5d5d;
	background: url(images/error.png) no-repeat 0;
}

div.error ul {
	margin-left: 24px;
}

.pagination {
	font-size: 11px;
	padding-top: 10px;
	margin-bottom: 5px;
}

.tfoot .pagination,
.tcat .pagination {
	padding-top: 0;
}

.pagination .pages {
	font-weight: bold;
}

.pagination .pagination_current,
.pagination a {
	padding: 3px 6px;
	margin-bottom: 3px;
}

.pagination a {
	background: #f5f5f5;
	border: 1px solid #ccc;
}

.pagination .pagination_current {
	background: none;
	color: #333;
	border: none;
	font-weight: bold;
}

.pagination a:hover {
	background: #0072BC;
	color: #fff;
	border-color: #263c30;
	text-decoration: none;
}

.pagination .go_page img {
	margin-bottom: -4px;
}

.drop_go_page {
	background: #f5f5f5;
	padding: 4px;
}

.pagination_breadcrumb {
	background-color: #efefef;
	border: 1px solid #fff;
	outline: 1px solid #ccc;
	padding: 5px;
	margin-top: 5px;
	font-weight: normal;
}

.pagination_breadcrumb_link {
	vertical-align: middle;
	cursor: pointer;
}

.thread_legend,
.thread_legend dd {
	margin: 0;
	padding: 0;
}

.thread_legend dd {
	padding-bottom: 4px;
	margin-right: 15px;
}

.thread_legend img {
	margin-right: 4px;
	vertical-align: bottom;
}

.forum_legend,
.forum_legend dt,
.forum_legend dd {
	margin: 0;
	padding: 0;
}

.forum_legend dd {
	float: left;
	margin-right: 10px;
	margin-top: 7px;
}

.forum_legend dt {
	margin-right: 10px;
	float: left;
}

.success_message {
	color: #00b200;
	font-weight: bold;
	font-size: 10px;
	margin-bottom: 10px;
}

.error_message {
	color: #C00;
	font-weight: bold;
	font-size: 10px;
	margin-bottom: 10px;
}

#posts_container {
	padding: 0;
}

.ignored_post {
	border-top: 3px solid #333;
	padding: 15px;
}

.ignored_post .show_ignored_post {
	margin-top: -15px;
}

.ignored_post .show_ignored_post a.button span {
	background-position: 0 -400px;
}

.post {
	overflow: hidden;
}

.post.classic {
	padding-top: 15px;
}

.post .post_author {
	padding: 5px;
	overflow: hidden;
}

.post.classic .post_author {
	float: left;
	width: 10%;
	margin: -15px 0% 0px 0;
	border-left: 0;
	padding: 5px 1%;
}

.post .post_author .buddy_status {
	vertical-align: middle;
	margin-top: -4px;
}

.post .post_author div.author_avatar {
	float: left;
	margin-right: 3px;
}

.post.classic .post_author div.author_avatar {
	float: none;
	text-align: center;
	margin-bottom: 8px;
}

.post .post_author div.author_avatar img {
	padding: 5px;
	border: 1px solid #ddd;
	background: #fff;
}

.post .post_author div.author_information {
	float: left;
	padding: 6px 8px;
}

.post.classic .post_author div.author_information {
	float: none;
	padding: 0;
	text-align: center;
}

.post .post_author div.author_statistics {
	float: right;
	font-size: 11px;
	padding: 3px 10px 3px 5px;
	color: #fff;
	line-height: 1.3;
}

.post.classic .post_author div.author_statistics {
	border-top: 1px dotted #ccc;
	margin: 6px 0 0 0;
	padding: 6px 6px 3px 6px;
	float: none;
}

.post .post_head {
	font-size: 11px;
	padding-bottom: 4px;
	border-bottom: 1px dotted #ddd;
	margin-bottom: 4px;
}

.post .post_head span.post_date {
	color: #fff;
}

.post .post_head span.edited_post {
	font-size: 10px;
	color: #999;
}

.post .post_head span.edited_post a {
	color: #666;
}

.post_body {
	font-size: 14px;
	padding: 12px 0;
}

.post.classic .post_content {
	float: left;
	width: 86%;
}

.post_content {
	padding: 9px 10px 5px 10px;
	background: #444;
	border-left: 1px solid #333;
	margin-top: -16px;
}

.post_content .signature {
	margin-top: 5px;
	border-top: 1px dotted #ddd;
	padding: 10px 0 4px 0;
}

.post .post_meta {
	margin: 4px 0;
	font-size: 11px;
	color: #fff;
}

.post .post_meta a:link,
.post .post_meta a:visited {
	color: #fff;
}

.post .post_meta a:hover,
.post .post_meta a:active {
	color: #FFE;
}

.post_controls {
	clear: both;
	background: #333333;
	border-bottom: 1px solid #96ead7;
	padding: 5px;
	overflow: hidden;
}

.postbit_buttons > a:link,
.postbit_buttons > a:hover,
.postbit_buttons > a:visited,
.postbit_buttons > a:active {
	display: inline-block;
	padding: 2px 5px;
	margin: 2px;
	background: #4e4e4e;
	font-size: 11px;
	color: #fff;
	border-radius: 5px;
}

.postbit_buttons > a:hover {
	border-color: #bbb;
}

.postbit_buttons a span {
	display: inline-block;
	height: 16px;
	background-repeat: no-repeat;
	padding: 3px;
}

a.button:link,
a.button:hover,
a.button:visited,
a.button:active {
	background: #4e4e4e;
	color: #fff;
	display: inline-block;
	padding: 4px 8px;
	margin: 2px 2px 6px 2px;
	font-size: 14px;
}

a.button.small_button {
	font-size: 13px;
	margin: 0;
	padding: 3px 6px;
}

a.button span {
	display: inline-block;
	padding: 3px;
	background-repeat: no-repeat;
}

a.button.new_thread_button span {
	background-position: 0 -340px;
}

a.button.closed_button span {
	background-position: 0 -380px;
}

a.button.rate_user_button span {
	background-position: 0 -400px;
}

a.button.add_buddy_button span {
	background-position: 0 -440px;
}

a.button.remove_buddy_button span {
	background-position: 0 -480px;
}

a.button.add_ignore_button span {
	background-position: 0 -460px;
}

a.button.remove_ignore_button span {
	background-position: 0 -500px;
}

a.button.report_user_button span {
	background-position: 0 -520px;
}

.quick_jump {
	background: url(images/jump.png) no-repeat 0;
	width: 13px;
	height: 13px;
	padding-left: 13px;
	margin-top: -3px;
	border: none;
}

.pollbar {
	background: url(images/pollbar.png) top left repeat-x;
	border: 1px solid #3f3f3f;
	height: 10px;
}

.pollbar .percent {
	display: none;
}

.posticons_label {
	white-space: nowrap;
}

/** jGrowl Start **/

/** Special IE6 Style Positioning **/
.ie6 {
	position: absolute;
}

.ie6.top-right {
	right: auto;
	bottom: auto;
	left: expression( ( 0 - jGrowl.offsetWidth + ( document.documentElement.clientWidth ? document.documentElement.clientWidth : document.body.clientWidth ) + ( ignoreMe2 = document.documentElement.scrollLeft ? document.documentElement.scrollLeft : document.body.scrollLeft ) ) + 'px' );
	top: expression( ( 0 + ( ignoreMe = document.documentElement.scrollTop ? document.documentElement.scrollTop : document.body.scrollTop ) ) + 'px' );
}

.ie6.top-left {
	left: expression( ( 0 + ( ignoreMe2 = document.documentElement.scrollLeft ? document.documentElement.scrollLeft : document.body.scrollLeft ) ) + 'px' );
	top: expression( ( 0 + ( ignoreMe = document.documentElement.scrollTop ? document.documentElement.scrollTop : document.body.scrollTop ) ) + 'px' );
}

.ie6.bottom-right {
	left: expression( ( 0 - jGrowl.offsetWidth + ( document.documentElement.clientWidth ? document.documentElement.clientWidth : document.body.clientWidth ) + ( ignoreMe2 = document.documentElement.scrollLeft ? document.documentElement.scrollLeft : document.body.scrollLeft ) ) + 'px' );
	top: expression( ( 0 - jGrowl.offsetHeight + ( document.documentElement.clientHeight ? document.documentElement.clientHeight : document.body.clientHeight ) + ( ignoreMe = document.documentElement.scrollTop ? document.documentElement.scrollTop : document.body.scrollTop ) ) + 'px' );
}

.ie6.bottom-left {
	left: expression( ( 0 + ( ignoreMe2 = document.documentElement.scrollLeft ? document.documentElement.scrollLeft : document.body.scrollLeft ) ) + 'px' );
	top: expression( ( 0 - jGrowl.offsetHeight + ( document.documentElement.clientHeight ? document.documentElement.clientHeight : document.body.clientHeight ) + ( ignoreMe = document.documentElement.scrollTop ? document.documentElement.scrollTop : document.body.scrollTop ) ) + 'px' );
}

.ie6.center {
	left: expression( ( 0 + ( ignoreMe2 = document.documentElement.scrollLeft ? document.documentElement.scrollLeft : document.body.scrollLeft ) ) + 'px' );
	top: expression( ( 0 + ( ignoreMe = document.documentElement.scrollTop ? document.documentElement.scrollTop : document.body.scrollTop ) ) + 'px' );
	width: 100%;
}

/** jGrowl Styling **/
.jGrowl {
	z-index: 9999;
	color: #ffffff;
	font-size: 12px;
	font-family: "Helvetica Neue", Helvetica, Arial, sans-serif;
	position: fixed;
}

.jGrowl.top-left {
	left: 0px;
	top: 0px;
}

.jGrowl.top-right {
	right: 0px;
	top: 0px;
}

.jGrowl.bottom-left {
	left: 0px;
	bottom: 0px;
}

.jGrowl.bottom-right {
	right: 0px;
	bottom: 0px;
}

.jGrowl.center {
	top: 0px;
	width: 50%;
	left: 25%;
}

/** Cross Browser Styling **/

.jGrowl.center .jGrowl-notification,
.jGrowl.center .jGrowl-closer {
	margin-left: auto;
	margin-right: auto;
}

.jGrowl-notification {
	background-color: transparent;
	opacity: 0.9;
	filter: progid:DXImageTransform.Microsoft.Alpha(Opacity=(0.9*100));
	-ms-filter: progid:DXImageTransform.Microsoft.Alpha(Opacity=(0.9*100));
	zoom: 1;
	width: 250px;
	padding: 10px;
	margin: 10px;
	text-align: left;
	display: none;
	-moz-border-radius: 5px;
	-webkit-border-radius: 5px;
	border-radius: 5px;
	word-break: break-all;
}

.jGrowl .jGrowl-notification {
	min-height: 40px;
}

.jGrowl-notification .ui-state-highlight,
.jGrowl-notification .ui-widget-content .ui-state-highlight,
.jGrowl-notification .ui-widget-header .ui-state-highlight {
	border: 1px solid #000;
	background: #000;
	color: #fff;
}

.jGrowl-notification .jGrowl-header {
	font-weight: bold;
	font-size: .85em;
}

.jGrowl-notification .jGrowl-close {
	background-color: transparent;
	color: inherit;
	border: none;
	z-index: 99;
	float: right;
	font-weight: bold;
	font-size: 1em;
	cursor: pointer;
}

.jGrowl-closer {
	background-color: #000000;
	opacity: 0.9;
	filter: progid:DXImageTransform.Microsoft.Alpha(Opacity=(0.9*100));
	-ms-filter: progid:DXImageTransform.Microsoft.Alpha(Opacity=(0.9*100));
	zoom: 1;
	width: 250px;
	padding: 10px;
	margin: 10px;
	text-align: left;
	display: none;
	border-radius: 5px;
	word-break: break-all;
	padding-top: 4px;
	padding-bottom: 4px;
	cursor: pointer;
	font-size: .9em;
	font-weight: bold;
	text-align: center;
}

.jGrowl-closer .ui-state-highlight,
.jGrowl-closer .ui-widget-content .ui-state-highlight,
.jGrowl-closer .ui-widget-header .ui-state-highlight {
	border: 1px solid #000;
	background: #000;
	color: #fff;
}

.jGrowl .jGrowl-notification.jgrowl_success {
    background: lightgreen;
    border: 1px solid lightgreen;
    color: #333;
}

.jGrowl .jGrowl-notification.jgrowl_error {
    background: red;
    border: 1px solid red;
    color: #333;
}

.jGrowl .jGrowl-notification.jgrowl_process, .jGrowl .jGrowl-closer {
    background: yellow;
    border: 1px solid yellow;
	color: #333;
}

/** Hide jGrowl when printing **/
@media print {
	.jGrowl {
		display: none;
}


}

/** jGrowl End **/

/** Modal Start **/

.modal {
	display: none;
	width: 400px;
	text-align: left;
	background: #fff;
	-webkit-border-radius: 8px;
	-moz-border-radius: 8px;
	-o-border-radius: 8px;
	-ms-border-radius: 8px;
	border-radius: 8px;
	-webkit-box-shadow: 0 0 10px #000;
	-moz-box-shadow: 0 0 10px #000;
	-o-box-shadow: 0 0 10px #000;
	-ms-box-shadow: 0 0 10px #000;
	box-shadow: 0 0 10px #000;
}

.modal a.close-modal {
	position: absolute;
	top: -12.5px;
	right: -12.5px;
	display: block;
	width: 30px;
	height: 30px;
	text-indent: -9999px;
	background: url(images/close.png) no-repeat 0 0;
}

.modal-spinner {
	display: none;
	width: 64px;
	height: 64px;
	position: fixed;
	top: 50%;
	left: 50%;
	margin-right: -32px;
	margin-top: -32px;
	background: url(images/spinner_big.gif) no-repeat center center;
	-webkit-border-radius: 8px;
	-moz-border-radius: 8px;
	-o-border-radius: 8px;
	-ms-border-radius: 8px;
	border-radius: 8px;
}

/** Modal End **/

/** Impromptu Start **/

/*! jQuery-Impromptu - v6.2.1 - 2015-05-10
* http://trentrichardson.com/Impromptu
* Copyright (c) 2015 Trent Richardson; Licensed MIT */

.jqifade{
	position: absolute;
	background-color: #777777;
}

iframe.jqifade{
	display:block;
	z-index:-1;
}

div.jqi{
	width: 400px;
	max-width:90%;
	font-family: Verdana, Geneva, Arial, Helvetica, sans-serif;
	position: absolute;
	background-color: #ffffff;
	font-size: 11px;
	text-align: left;
	border: solid 1px #eeeeee;
	border-radius: 6px;
	-moz-border-radius: 6px;
	-webkit-border-radius: 6px;
	padding: 7px;
}

div.jqi .jqicontainer{
}

div.jqi .jqiclose{
	position: absolute;
	top: 4px; right: -2px;
	width: 18px;
	cursor: default;
	color: #bbbbbb;
	font-weight: bold;
}

div.jqi .jqistate{
	background-color: #fff;
}

div.jqi .jqititle{
	padding: 5px 10px;
	font-size: 16px;
	line-height: 20px;
	border-bottom: solid 1px #eeeeee;
}

div.jqi .jqimessage{
	padding: 10px;
	line-height: 20px;
	color: #444444;
	overflow: auto;
}

div.jqi .jqibuttonshide{
	display: none;
}

div.jqi .jqibuttons{
	text-align: right;
	margin: 0 -7px -7px -7px;
	border-top: solid 1px #e4e4e4;
	background-color: #f4f4f4;
	border-radius: 0 0 6px 6px;
	-moz-border-radius: 0 0 6px 6px;
	-webkit-border-radius: 0 0 6px 6px;
}

div.jqi .jqibuttons button{
	margin: 0;
	padding: 15px 20px;
	background-color: transparent;
	font-weight: normal;
	border: none;
	border-left: solid 1px #e4e4e4;
	color: #777;
	font-weight: bold;
	font-size: 12px;
}

div.jqi .jqibuttons button.jqidefaultbutton{
	color: #489afe;
}

div.jqi .jqibuttons button:hover,
div.jqi .jqibuttons button:focus{
	color: #287ade;
	outline: none;
}

div.jqi .jqibuttons button[disabled]{
	color: #aaa;
}

.jqiwarning .jqi .jqibuttons{
	background-color: #b95656;
}

/* sub states */
div.jqi .jqiparentstate::after{
	background-color: #777;
	opacity: 0.6;
	filter: alpha(opacity=60);
	content: '';
	position: absolute;
	top:0;left:0;bottom:0;right:0;
	border-radius: 6px;
	-moz-border-radius: 6px;
	-webkit-border-radius: 6px;
}

div.jqi .jqisubstate{
	position: absolute;
	top:0;
	left: 20%;
	width: 60%;
	padding: 7px;
	border: solid 1px #eeeeee;
	border-top: none;
	border-radius: 0 0 6px 6px;
	-moz-border-radius: 0 0 6px 6px;
	-webkit-border-radius: 0 0 6px 6px;
}

div.jqi .jqisubstate .jqibuttons button{
	padding: 10px 18px;
}

/* arrows for tooltips/tours */
.jqi .jqiarrow{
 position: absolute; height: 0; width:0; line-height: 0; font-size: 0; border: solid 10px transparent;
}

.jqi .jqiarrowtl{
 left: 10px; top: -20px; border-bottom-color: #ffffff;
}

.jqi .jqiarrowtc{
 left: 50%; top: -20px; border-bottom-color: #ffffff; margin-left: -10px;
}

.jqi .jqiarrowtr{
 right: 10px; top: -20px; border-bottom-color: #ffffff;
}

.jqi .jqiarrowbl{
 left: 10px; bottom: -20px; border-top-color: #ffffff;
}

.jqi .jqiarrowbc{
 left: 50%; bottom: -20px; border-top-color: #ffffff; margin-left: -10px;
}

.jqi .jqiarrowbr{
 right: 10px; bottom: -20px; border-top-color: #ffffff;
}

.jqi .jqiarrowlt{
 left: -20px; top: 10px; border-right-color: #ffffff;
}

.jqi .jqiarrowlm{
 left: -20px; top: 50%; border-right-color: #ffffff; margin-top: -10px;
}

.jqi .jqiarrowlb{
 left: -20px; bottom: 10px; border-right-color: #ffffff;
}

.jqi .jqiarrowrt{
 right: -20px; top: 10px; border-left-color: #ffffff;
}

.jqi .jqiarrowrm{
 right: -20px; top: 50%; border-left-color: #ffffff; margin-top: -10px;
}

.jqi .jqiarrowrb{
 right: -20px; bottom: 10px; border-left-color: #ffffff;
}

/** Impromptu End */



/* postbit custom design */

.pbit {
       background: #111;
       border-radius: 3px;
       border: 1px double #111;
       font-size: 11px;
       font-weight: normal;
       margin-bottom: 3px;
       padding: 6px 5px 5px;
       text-align: left;
}

.postbit-online {
	color: #71BA51;
	height: 10px;
	width:10px;
}

.postbit-offline {
	color: #CF2D2D;
	height: 10px;
	width:10px
}

/*! New code for 1.8.9 */

.deleted_post_hidden {
	border-top: 2px solid #ccc;
	padding: 15px;
}

.deleted_post_collapsed {
	border-top: 3px solid #333;
	padding: 15px;
}

.deleted_post_collapsed .show_deleted_post {
	margin-top: -15px;
}

.deleted_post_collapsed .show_deleted_post a.button span {
	background-position: 0 -400px;
}

/** Modal Start **/

.blocker {
   position: fixed;
   top: 0;
   right: 0;
   bottom: 0;
   left: 0;
   width: 100%;
   height: 100%;
   overflow: auto;
   z-index: 9999;
   padding: 20px;
   box-sizing: border-box;
   background-color: rgb(0,0,0);
   background-color: rgba(0,0,0,0.75);
   text-align: center;
}

.blocker:before{
   content: "";
   display: inline-block;
   height: 100%;
   vertical-align: middle;
   margin-right: -0.05em;
}

.blocker.behind {
   background-color: transparent;
}

.modal {
   width: 400px;
   text-align: left;
   background: #fff;
   display: inline-block;
   vertical-align: middle;
   position: relative;
   z-index: 2;
   -webkit-box-sizing: border-box;
   -moz-box-sizing: border-box;
   box-sizing: border-box;
   -webkit-border-radius: 8px;
   -moz-border-radius: 8px;
   -o-border-radius: 8px;
   -ms-border-radius: 8px;
   border-radius: 8px;
   -webkit-box-shadow: 0 0 10px #000;
   -moz-box-shadow: 0 0 10px #000;
   -o-box-shadow: 0 0 10px #000;
   -ms-box-shadow: 0 0 10px #000;
   box-shadow: 0 0 10px #000;
}

.modal a.close-modal {
   position: absolute;
   top: -12.5px;
   right: -12.5px;
   display: block;
   width: 30px;
   height: 30px;
   text-indent: -9999px;
   background: url(images/close.png) no-repeat 0 0;
}

.modal-spinner {
   display: none;
   width: 64px;
   height: 64px;
   position: fixed;
   top: 50%;
   left: 50%;
   margin-right: -32px;
   margin-top: -32px;
   background: url(images/spinner_big.gif) no-repeat center center;
   -webkit-border-radius: 8px;
   -moz-border-radius: 8px;
   -o-border-radius: 8px;
   -ms-border-radius: 8px;
   border-radius: 8px;
}

/* DVZ Shoutbox */
#shoutbox { margin-bottom: 10px; border: solid 2px rgba(0,0,0,0.1); }
#shoutbox .head { padding: 8px; }
#shoutbox.front .head { cursor: pointer; }
#shoutbox .head .right { float: right; margin: 0; font-size: 13px; }
#shoutbox.collapsed .head { opacity: 0.6; }
#shoutbox.collapsed .body { display: none; }

#shoutbox .panel { border-top: solid 2px rgba(0,0,0,0.1); }
#shoutbox input.text { margin: 0; padding: 10px 8px; width: 100%; box-sizing: border-box; border: none; box-shadow: inset 0 2px 4px rgba(0,0,0,0.08); font-family: Arial, sans-serif; font-size: 12px; color: #000; }
#shoutbox .minposts, #shoutbox .blocked { padding: 6px; font-size: 11px; }
#shoutbox .panel.minposts { background: #FFFED8; color: #727250; }
#shoutbox .panel.blocked { background: #FCEFEF; color: #543A3A; }
#shoutbox .panel p { margin: 0; }

#shoutbox .window { border-top: solid 2px rgba(0,0,0,0.1); overflow-y: scroll; }
#shoutbox .data { display: table; width: 100%; border-top: solid 2px rgba(0,0,0,0.1); font-family: Arial, sans-serif; font-size: 12px; }
#shoutbox.front .data { border-top: none; }

#shoutbox .entry { display: table-row !important; width: 100%; transition: background-color 0.2s; }
#shoutbox .entry:nth-child(even) { background-color: rgba(0,0,0,0.01); }
#shoutbox .entry.new { background-color: rgba(255,255,100,0.1); }
#shoutbox .entry:target { background-color: rgba(50,200,255,0.1); }
#shoutbox .entry > div { border-bottom: dashed 1px rgba(0,0,0,0.05); }
#shoutbox .entry:last-child > div { border-bottom: none; }

#shoutbox .entry > div { display: table-cell; padding: 6px; }

#shoutbox .avatar img { margin: 0 auto; vertical-align: middle; max-height: 20px; max-width: 20px; border: solid 1px rgba(255,255,255,0.1); box-shadow: 0 0 2px rgba(0,0,0,0.1); cursor: pointer; }
#shoutbox .user { border-right: solid 1px rgba(0,0,0,0.05); text-align: right; white-space: nowrap; }
#shoutbox .text { width: 100%; color: #555; word-break: break-all; word-wrap: break-word; }
#shoutbox .info { font-size: 11px; color: #AAA; white-space: nowrap; text-align: right; }
#shoutbox .entry.unread .info:before { display: inline-block; position: relative; top: -2px; margin-right: 10px; height: 4px; width: 4px; content: ''; background: rgba(255,100,0,0.8); border-radius: 10px; }
#shoutbox .info a { color: inherit; }
#shoutbox .mod { padding: 6px 8px; font-size: 9px; font-weight: bold; color: #AAA; text-decoration: none; }
#shoutbox .mod:nth-of-type(2) { margin-right: 5px; border-left: solid 1px rgba(0,0,0,0.1); }
#shoutbox  .ip { margin-right: 10px; color: #CECECE; }

/** Modal End **/
		
		]]>
		</stylesheet>
		<stylesheet name="extras.css" version="1817"><![CDATA[a
		]]>
		</stylesheet>
		<stylesheet name="Cobalt.css" version="1817"><![CDATA[/*****************************************************************
1. INITIAL SETTINGS
*****************************************************************/

/* Limited Reset
----------------------------------------------------------------*/

.pun table, .pun div, .pun form, .pun p, .pun h1, .pun h2, .pun h3,
.pun h4, .pun h5, .pun pre, .pun blockquote, .pun ul, .pun ol, .pun li, .pun dl,
.pun dt, .pun dd, .pun th, .pun td, .pun fieldset, .pun img, .pun abbr, .pun cite {
	margin: 0;
	padding: 0;
	border: 0;
	}

.pun ul, .pun ol {
	list-style: none
	}


/* Structural Settings
----------------------------------------------------------------*/

.pun .clearer, .pun .nosize {
	height: 0;
	width: 0;
	line-height: 0;
	font-size: 0;
	overflow: hidden
	}

.pun .clearer, .pun .clearb {
	clear: both
	}

.pun .nosize {
	position: absolute;
	left: -9999em;
	text-indent: -9999em;
	width: 0;
	}

* html .inbox, * html .inform, * html .pun, * html .tclcon, * html .codebox {
	height: 1px
	}

.pun, .pun .inbox, .pun .inform, .pun .tclcon, .pun .codebox {
	min-height: 1px
	}

.clearl {
	clear: left;
	}

/* Hidden Elements
----------------------------------------------------------------*/

#brdfooter h2, #brdstats h2, #brdstats .conl dt, #brdstats .conr dt,
#modcontrols dt, #searchlinks dt, div.postright h3, span.closedtext,
.pun .required strong span {
	position: absolute;
	display: block;
	overflow: hidden;
	width: 0;
	left: -9999em;
	text-indent: -9999em;
	}

/*****************************************************************
2. TEXT & CONTENT
*****************************************************************/

/* Text Defaults
----------------------------------------------------------------*/

.pun {
	font: 68.75%/1.4545em Verdana, Helvetica, Arial, sans-serif;
	line-height: normal;
	}

.pun table, .pun td, .pun th, .pun input, .pun select, .pun optgroup, .pun textarea, .pun samp, .pun legend {
	font-size: 10px;
	font-family: verdana, helvetica, arial, sans-serif;
	}

.pun pre, .pun code {
	font-size: 1.182em;
	font-family: consolas, monaco, "bitstream vera sans mono", "courier new", courier, monospace
	}

.pun pre code {
	font-size: 1em;
	tab-size: 4;
	-moz-tab-size: 4;
	}

.pun strong {
	font-weight: bold;
	}

.pun em {
	font-style: italic;
	}

.pun .forumdesc {
	font-size: 10px;
	color: #888;
	}

/* Content Defaults
----------------------------------------------------------------*/

.pun p, .pun ul, .pun ol, .pun dl {
	font-size: 11px;
	padding: 3px 0;
	}

.pun h2 {
	font-size: 1em;
	font-weight: normal;
	padding: 4px 6px;
	}

.pun h3 {
	font-size: 1.091em;
	padding: 3px 0;
	}

.pun table p, .pun table h3 {
	padding: 0;
	}

.pun span.warntext, .pun p.warntext {
	font-weight: bold
	}

/* User Content (Announcements, Rules, Posts)
----------------------------------------------------------------*/

.pun .usercontent p, .pun .postmsg p {
	padding: 0.75em 0
	}

.pun .usercontent ul, .pun .postmsg ul {
	padding: 0.75em 1em 0.75em 2.5em;
	list-style: disc
	}

.pun .usercontent ol, .pun .postmsg ol {
	padding: 0.75em 1em 0.75em 2.5em;
	list-style: decimal
	}

.pun .usercontent ol.alpha, .pun .postmsg ol.alpha {
	list-style: lower-alpha
	}

.pun .usercontent li ol, .pun .usercontent li ul, .pun .postmsg li ol, .pun .postmsg li ul {
	padding: 0.25em 1em 0.75em 2.5em
	}

.pun .usercontent li p, .pun .postmsg li p {
	padding: 0
	}

.pun .usercontent h1 {
	font-size: 1.4em;
	font-weight: bold;
	padding: 0.75em 0 0 0
	}

.pun .usercontent h2 {
	font-size: 1.2em;
	font-weight: bold;
	padding: 0.75em 0 0 0
	}

.pun .usercontent h3 {
	font-size: 1.1em;
	font-weight: bold;
	padding: 0.75em 0 0 0
	}

.pun .usercontent h4, .pun .usercontent h5, .pun .usercontent h6 {
	font-size: 1em;
	font-weight: bold;
	padding: 0.75em 0 0 0
	}

.pun .quotebox cite {
	font-weight: bold;
	font-style: normal;
	padding: 0.75em 0.75em 0 0.75em
	}

.pun span.bbu {
	text-decoration: underline
	}

.pun span.bbs, .pun del {
	text-decoration: line-through;
	}

.pun .postmsg ins, #punhelp samp ins {
	text-decoration: none;
	}

.pun div.postmsg h5, #punhelp h5 {
	font-size: 1.1em;
	font-weight: bold;
	padding: 0.75em 0 0 0;
	}


/*****************************************************************
3. COMMON STYLES
*****************************************************************/

/* Page Layout
----------------------------------------------------------------*/

html, body {
	margin: 0;
	padding: 0
	}

.pun {
	max-width: 1070px;
	width: 95%;
	margin: 0 auto;
	padding: 12px 20px;
	}

#punredirect, #punmaint, #puninstall, #pundb_update {
	margin: 50px 20% 12px 20%
	}


/* Vertical Element Spacing
----------------------------------------------------------------*/

#brdheader {
	margin: 0 0 12px 0;
	}

#brdtitle p {
	padding-top: 0px
	}

#announce, #brdstats {
	margin: 12px 0 12px 0;
	}

.pun .blocktable, .pun .block, .pun .blockform, .pun .block2col, #postreview {
	margin-bottom: 12px
	}

#punindex .blocktable, .pun .blockpost {
	margin-bottom: 6px
	}

#postreview .blockpost {
	margin-bottom: -1px;
	}

.pun .block2col .blockform, .pun .block2col .block {
	margin-bottom: 0px
	}

.pun .linkst, .pun .linksb {
	margin-top: -12px
	}

.pun .postlinksb {
	margin-top: -6px
	}


/* External Borders
----------------------------------------------------------------*/

.pun .box {
	border-style: solid;
	border-width: 1px;
	}

#brdheader .box {
	border-top-width: 4px;
	border-radius: 4px;
	}

/* Default Internal Spacing
----------------------------------------------------------------*/

.pun .block .inbox, .pun .blockmenu .inbox {
	padding: 3px 6px
	}
	

/*****************************************************************
4. COMMON BOARD ELEMENTS
*****************************************************************/

/* Board Header
----------------------------------------------------------------*/

#brdtitle h1 {
	font-size: 1.8em;
	font-weight: normal;
	padding: 3px 0 0 0;
	font-family: 'Raleway', Verdana;
	}

#brdtitle h1 a {
	color: #eaeaea;
	}

#brdtitle h1 a span {
	color: #95b806;
	}

#brdmenu li {
	display: inline;
	margin-right: 12px;
	}

#brdmenu a:link, #brdmenu a:visited {
	text-decoration: none
	}

#brdmenu a:hover, #brdmenu a:active {
	text-decoration: underline
	}

#brdwelcome .conl {
	float: left;
	}

#brdwelcome .conr {
	float: right;
	text-align: right;
	}

/* Breadcrumbs and Post Links
----------------------------------------------------------------*/

.pun .linkst {
	padding: 8px 6px 3px 6px
	}

.pun .linksb, .pun .postlinksb {
	padding: 3px 6px 8px 6px
	}

.pun .crumbs {
	clear: both;
	width: 100%;
	overflow: hidden;
	font-size: 11px;
	}

.pun .crumbs li {
	display: inline;
	white-space: nowrap;
	font-weight: bold;
	}

.pun .pagelink {
	float: left;
	white-space: nowrap;
	}

.pun .postlink {
	font-weight: bold;
	white-space: nowrap;
	}

.pun .postlink, .pun .modbuttons {
	float: right;
	text-align: right;
	}

.pun .modbuttons {
	padding: 1px 0;
	white-space: nowrap;
	}

.pun .modbuttons input {
	margin-left: 6px;
	}

.pun .postlink a:link, .pun .postlink a:visited {
	text-decoration: none
	}

.pun .postlink a:hover, .pun .postlink a:active {
	text-decoration: underline;
	}

.pun .topiclink {
	font-size: 11px;
	}

#punindex .subscribelink {
	margin-top: 6px;
	}

/* Board Footer
----------------------------------------------------------------*/

#brdfooter .conl {
	float: left;
	}

#brdfooter .conr {
	float: right;
	text-align: right;
	}

#brdfooter #modcontrols {
	border-bottom-style: solid;
	border-bottom-width: 1px;
	text-align: center;
	}

#brdfooter #modcontrols dd {
	display: inline;
	margin:0 6px;
	}


/* Board Stats
----------------------------------------------------------------*/

#brdstats .conl {
	float: left;
	}

#brdstats .conr {
	float: right;
	text-align: right;
	}

#onlinelist dd, #onlinelist dt {
	display: inline;
	}


/*****************************************************************
5. MAIN TABLES
*****************************************************************/

.pun table {
	width: 100%;
	border-collapse: collapse;
	border-spacing: 0;
	empty-cells: show;
	}

.pun .blocktable table {
	table-layout: fixed;
	}

.pun td, .pun th {
	padding: 4px 6px;
	text-align: left;
	font-weight: normal;
	}

.pun tbody td, .pun tbody th {
	border-style: solid none none solid;
	border-width: 1px;
	}

.pun .tcl {
	border-left: 0;
	width: auto;
	}

.pun .tc2, .pun .tc3, .pun .tcmod {
	width: 10%;
	text-align: center;
	padding: 4px 0;
	}

.pun .tcr {
	width: 30%;
	overflow-x: hidden;
	white-space: nowrap;
	text-overflow: ellipsis;
	}

.pun .tcl h3 {
	font-size: 11px;
	font-weight: bold;
	}

.pun .tcl h3 a {
	color: #ccc;
	}

.pun .tcl h3 a:hover {
	color: #b4e61e;
}

.pun .tcl h3 span.newtext {
	font-size: 0.917em;
	}

.pun .tcl span.newtext, .pun .tcl span.pagestext {
	white-space: nowrap;
	font-weight: normal;
	}

.pun td span.byuser {
	white-space: nowrap;
	}

.pun .tcl p {
	padding: 5px 0 0 0
	}

#punsearch #vf .tc2 {
	width: 18%;
	text-align: left;
	padding: 4px 6px;
	}

#users1 .tcr {
	width: 25%
	}

#users1 .tc2 {
	width: 25%;
	text-align: left;
	padding: 4px 6px;
	}

#debug .tcl {
	width: 10%
	}

#debug .tcr {
	width: 90%;
	white-space: normal
	}

#punindex .tcr .byuser {
	display: block
	}

.pun .blocktable .tclcon {
	padding: 0 11px 0 12px;
	overflow: hidden;
	min-height: 1px;
	position: relative;
	}

.pun .blocktable .tclcon div {
	width: 100%;
	overflow: hidden;
	}

.pun .icon {
	margin: 0.3em 0 0 0.2em;
	border-width: 0.4em;
	border-style: solid;
	border-radius: 2px;
	height: 0;
	width: 0;
	overflow: hidden;
	float: left;
	}

.pun .icon div {
	position: absolute;
	left: -9999em;
	text-indent: -9999em;
	height: 0;
	}

.pun .iposted .ipost {
	position: absolute;
	left: 0;
	font-weight: bold;
	width: 8px;
	padding-left: 4px;
	text-align: center;
	top: 0;
	}

.pun .rowlist {
	display: inline-block;
	vertical-align: middle;
	}

/*****************************************************************
6. MAIN FORMS
*****************************************************************/

.pun .blockform form, .pun .fakeform {
	PADDING: 20px 20px 15px 20px
	}

.pun .forminfo {
	margin-bottom: 12px;
	padding: 9px 10px;
	border-style: solid;
	border-width: 1px;
	}

.pun .forminfo h3 {
	font-weight: bold;
	}

.pun .inform {
	padding-bottom: 12px
	}

.pun fieldset {
	padding: 0px 12px 0px 12px;
	border-style: solid;
	border-width: 1px
	}

.pun legend {
	padding: 0px 6px
	}

.pun .infldset {
	padding: 9px 0px 12px 0
	}

.pun label {
	display: block;
	padding: 3px 0
	}

.pun label.conl {
	float: left;
	overflow: visible;
	margin-right: 10px
	}

.pun fieldset .rbox br {
	display: none;
	}

.pun fieldset .rbox label {
	padding: 3px 0 3px 25px;
	position: relative;
	vertical-align: middle;
	}

.pun fieldset .rbox input {
	margin: 0 9px 0 -25px;
	padding: 0;
	width: 16px;
	position: relative;
	vertical-align: middle;
	}

.pun .txtarea {
	width: 75%
	}

.pun .txtarea textarea, .pun input.longinput {
	width: 100%
	}

.pun .bblinks {
	padding-bottom: 10px;
	padding-left: 4px
	}

.pun .bblinks li {
	display: inline;
	padding-right: 20px
	}

.pun .blockform .buttons {
	padding-left: 12px;
	}

.pun .blockform .buttons input {
	margin-right: 8px;
	}

#posterror ul {
	list-style: square;
	padding: 3px 0 3px 24px;
	}

.pun .deletemsg {
	border-style: solid;
	border-width: 1px;
	padding: 6px 15px;
	}

.pun p.actions span {
	margin-right: 12px;
	}

.pun .multiselect {
	float: left;
	padding-bottom: 7px;
	}

.pun .checklist {
	border-width: 1px;
	border-style: solid;
	max-height: 9em;
	width: 20em;
	overflow: auto;
	padding: 0.3em 0.5em;
	margin: 0.25em 16px 0 0.15em;
	}

.pun .checklist fieldset {
	border: 0;
	padding: 0;
	}

.pun .checklist legend {
	padding: 0;
	}

.pun .checklist legend span {
	width: auto;
	max-width: 25em;
	}

/*****************************************************************
7. PROFILES AND ADMIN
*****************************************************************/

.pun .block2col {
	padding-bottom: 1px
	}

.pun .block2col .blockform, .pun .block2col .block {
	margin-left: 14em
	}

.pun .blockmenu {
	float:left;
	width: 13em
	}

.pun .blockmenu li {
	padding: 3px 0;
	font-weight: bold;
	}

.pun .blockmenu a:link, .pun .blockmenu a:visited {
	text-decoration: none
	}

.pun .blockmenu a:hover, .pun .blockmenu a:active {
	text-decoration: underline
	}

#viewprofile dl {
	float: left;
	width: 100%;
	overflow: hidden
	}

#viewprofile dd {
	margin-left: 14em;
	padding: 3px;
	}

#viewprofile dt {
	float: left;
	width: 13em;
	margin: 3px 0;
	}

#profileavatar img {
	float: right;
	margin-left: 1em
	}

#adintro ul {
	list-style-type: disc;
	margin-left: 8px;
	padding-left: 16px;
	}

/*****************************************************************
8. MAIN POSTS
*****************************************************************/

.pun .blockpost h2 a:link, .pun .blockpost h2 a:visited {
	text-decoration: none;
	}

.pun .blockpost h2 a:hover, .pun .blockpost h2 a:active {
	text-decoration: underline;
	}

.pun .blockpost h2 .conr {
	float: right;
	text-align: right;
	}

#punsearch .blockpost h2 span {
	white-space: nowrap;
	}

.pun .blockpost .box {
	overflow: hidden;
	}

.pun .postleft, .pun .postfootleft {
	float:left;
	width: 18em;
	position: relative;
	overflow: hidden;
	}

.pun .postleft dl {
	padding: 6px;
	}

.pun .postleft .usercontacts, .pun .postleft .icon {
	margin-top: 6px
	}

.pun .postleft .postavatar, .pun .postleft .usertitle {
	margin-bottom: 6px;
	display: block;
	}

.pun .blockpost dt {
	font-size: 1.091em;
	font-weight: bold;
	}

.pun .blockpost dt a:link, .pun .blockpost dt a:visited {
	text-decoration: none;
	}

.pun .blockpost dt a:hover, .pun .blockpost dt a:active {
	text-decoration: underline;
	}

.pun .postright, .pun .postfootright {
	border-left-width: 18em;
	border-left-style: solid
	}

#postpreview .postright {
	border-left: 0
	}

.pun .postright {
	padding: 0 6px;
	}

.pun .postfootright, .pun .multidelete {
	text-align: right
	}

.pun .postmsg {
	width:98%;
	overflow: hidden;
	padding-bottom: 6px;
	word-wrap: break-word;
	}

.pun .postmsg p {
	font-size: 11px;
	}

.pun .postfootright ul, .pun .postfootright div, .pun .postfootright p,
.pun .postfootleft p {
	padding: 10px 6px 5px 6px;
	}

.pun .postfootright li {
	display: inline;
	}

.pun .postfootright li:before {
	content: " | ";
	}

.pun .postfootright li:first-child:before {
	content: "";
	}

.pun .postfootright a:link, .pun .postfootright a:visited {
	text-decoration: none
	}

.pun .postfootright a:hover, .pun .postfootright a:active {
	text-decoration: underline
	}

.pun .codebox {
	border-style: solid;
	border-width: 1px;
	margin: 0.75em 1em;
	padding: 0;
	}

.pun .quotebox {
	border-style: solid;
	border-width: 1px;
	margin: 0.75em 1em;
	padding: 0 0.75em;
	}

.pun .quotebox cite {
	display: block;
	padding: 0.75em 0 0 0;
	}

.pun .quotebox blockquote {
	width: 100%;
	overflow: hidden
	}

.pun .codebox pre {
	overflow: auto;
	width: 100%;
	overflow-y:hidden
	}

* html .pun .codebox pre {
	padding-bottom: 10px;
	}

*+html .pun .codebox pre {
	padding-bottom: 10px
	}

.pun .codebox pre code {
	display: block;
	padding: 0.75em;
	}

.pun .codebox pre.vscroll {
	height: 32em;
	overflow: auto;
	overflow-y: auto
	}

.pun .postmsg img {
	vertical-align: bottom;
	}

.pun .postsignature hr {
	margin-left: 0px;
	width: 200px;
	text-align: left;
	height: 1px;
	border:none
	}

.pun .postmsg .postimg img {
	max-width: 98%;
	vertical-align: middle;
	margin: 7px 0.5em 7px 0;
	}

.pun .postmsg .postimg a:link img, .pun .postmsg .postimg a:visited img {
	border-style: solid;
	border-width: 2px;
	}

.pun .blockpost label {
	padding: 3px 6px;
	border-style: solid;
	border-width: 1px;
	vertical-align: middle;
	display: inline-block;
	}

.pun .blockpost label * {
	vertical-align: middle;
	margin: 0;
	padding: 0;
	}

.pun input.pollchoice {
	display: table-cell;
	vertical-align: middle;
	margin: 5px 5px;
	}

.pun .stickytext {
	font-size: 1.2em;
	color: #ffd200;
	}

/****************************************************************/
/* 9. HELP FILES AND MISC. */
/****************************************************************/

#punhelp h2 {
	margin-top: 12px
	}

#punhelp div.box {
	padding: 10px
	}

#debugtime {
	margin-top: -12px;
	text-align: center;
	}

#brdwelcome, #brdfooter dl a, div.blockmenu li, div.rbox input {
	line-height: 1.4em
	}

#announce div.inbox div {
	padding: 3px 0
	}

.pun .inbox thead {
	color: #777;
	font-size: 10px;
	border-style: none;
	}

.pun .inbox thead .tcl,
.pun .inbox thead .tc2,
.pun .inbox thead .tc3,
.pun .inbox thead .tcr {
	border-bottom: 1px solid #95b806;
	}

/*****************************************************************
COLOUR SCHEME
*****************************************************************/

/* Background / Text
----------------------------------------------------------------*/

body {
	background-color: #020202;
	color: #d4d4d4
	}

.punwrap {
	background-color: #131311;
	padding: 20px 20px !important;
	border-radius: 4px;
	}

.pun {
	color: #d4d4d4
	}

.pun .box {
	background-color: #272726
	}

.pun #adminconsole fieldset th {
	background-color: #383838
	}

.pun td.tc2, .pun td.tc3, .pun td.tcmod, #postpreview, #viewprofile dd, .pun .forminfo,
#brdfooter #modcontrols, #adminconsole fieldset td, .pun .blockmenu .box, #adstats dd {
	background-color: #303030
	}

.pun h2 {
	border-top-left-radius: 4px;
	border-top-right-radius: 4px;
    background-image: -webkit-linear-gradient(top, #343433 0%, #272726 100%);
    background-image: -o-linear-gradient(top, #343433 0%, #272726 100%);
    background-image: -webkit-gradient(linear, left top, left bottom, from(#343433), to(#272726));
    background-image: linear-gradient(to bottom, #343433 0%, #272726 100%);
    filter: progid: DXImageTransform.Microsoft.gradient(startColorstr='#ff343433', endColorstr='#ff272726', GradientType=0);
    filter: progid: DXImageTransform.Microsoft.gradient(enabled false);
    background-repeat: repeat-x;
    border-top: 1px solid #4f4f4d;
    border-right: 1px solid #4f4f4d;
    border-left: 1px solid #4f4f4d;
    padding: 5px;
    text-transform: none;
    font-size: 11px;
    line-height: 1.4;
    font-weight: bold;
    position: relative;
	color: #bbb;
	}

#brdmenu {
	background-color: #565656;
	color: #d4d4d4
	}

.pun th {
	background-color: #272726
	}

.pun legend {
	color: #60a0dc
	}

.pun .blockmenu li.isactive a, #posterror li strong {
	color: #d4d4d4
	}

.pun .usercontent * {
	background: transparent;
	color: #d4d4d4
	}

.pun textarea, .pun input, .pun select {
	background-color: #212122;
	color: #ccc;
	border: 1px solid #3e3e3e;
	}

.pun input:hover, .pun select:hover {
    background-color: #1b1b1b;
    border-color: #444;
    color: #aaa
	}

.pun input:disabled, .pun select:disabled,
.pun input:disabled:hover, .pun select:disabled:hover {
	opacity: 0.5;
	background-color: #1b1b1b;
	color: #ccc;
	color: #ccc;
	border: 1px solid #3e3e3e;
	}

.pun input:focus, .pun select:focus {
	outline: none;
	border-color: #666;
}

.pun .multiselect, .pun .checklist {
	color: #D4D4D4;
	}

.pun .checklist {
	border-color: #666;
	}

.pun .rowodd {
	background-color: #1c1c1b;
	}

.pun .roweven {
	background-color: #1d1d1c;
	}

.pun .rowodd:hover,
.pun .roweven:hover {
	background-color: #20201f;
	}

/* Posts
----------------------------------------------------------------*/

.pun .blockpost .box, .pun .postright, .pun .postfootright, .pun .deletemsg {
	background-color: #383838
	}

.pun .postright, .pun .postfootright {
	border-left-color: #424242
	}

.pun .postleft, .pun .postfootleft, .pun .blockpost label, .pun .codebox, .pun .quotebox {
	background-color: #424242
	}

.pun .blockpost h2 {
	background-color: #565656
	}

.pun .blockpost h2 span.conr {
	color: #a19e96
	}

.pun .postmsg ins, #punhelp samp ins {
	background-color: #ff0;
	}

.pun hr {
	background-color: #606060;
	color: #606060
	}

/* Borders
----------------------------------------------------------------*/

.pun .box {
	border-color:#4f4f4d;
	}

.pun .blocktable .box {
	border-top: none;
	}

.pun td, #brdfooter #modcontrols {
	border-color: #333
	}

.pun th {
	border-color: #292929
	}

.pun fieldset {
	border-color: #606060
	}

#adminconsole td, #adminconsole th {
	border-color: #383838
	}

.pun .quotebox, .pun .codebox, .pun .forminfo,
.pun .blockpost label, .pun .deletemsg {
	border-color: #606060
	}

/* Links
----------------------------------------------------------------*/

.pun a:link, .pun a:visited {
	color: #60a0dc;
	text-decoration: none;
	}

.pun a:hover, .pun a:active, .pun a:focus {
	color: #80d6ff
	}

.pun .postmsg .postimg a:link img, .pun .postmsg .postimg a:visited img {
	border-color: #60a0dc;
	}

.pun .postmsg .postimg a:hover img, .pun .postmsg .postimg a:active img, .pun .postmsg .postimg a:focus img {
	border-color: #80d6ff;
	}

.pun h2 a:link, .pun h2 a:visited,
#brdmenu a:link, #brdmenu a:visited {
	color: #d4d4d4
	}

.pun h2 a:hover, .pun h2 a:active,
#brdmenu a:hover, #brdmenu a:active {
	color: #d4d4d4
	}

.pun .postreport a:link, .pun .postreport a:visited,
.pun .iclosed td.tcl a:link, .pun .iclosed td.tcl a:visited {
	color: #888
	}

.pun .postreport a:hover, .pun .postreport a:active,
.pun .iclosed td.tcl a:hover, .pun .iclosed td.tcl a:active {
	color: #aaa
	}

.pun .maintenancelink a:link, .pun .maintenancelink a:visited {
	color: #ff4000
	}

.pun .maintenancelink a:hover, .pun .maintenancelink a:active {
	color: #ff5010
	}

/* Status Indicators
----------------------------------------------------------------*/

.pun .icon {
	border-color: #333333;
	}

.pun .iredirect .icon {
	border-color: #383838 #383838 #383838 #383838
	}

.pun .inew .icon {
	border-color: #5496d8 #4b85c0 #4377ac #4f8dcb
	}

/* Usergroup name colors
----------------------------------------------------------------*/
.pun .usergroup-1 { /* Administrator */
	color: #b4e61e !important;
	font-weight: bold;
	}

.pun a:hover.usergroup-1 { /* Administrator */
	color: #e4ff5e !important;
	}
	
.pun .usergroup-2 { /* Moderator */
	color: #ff9933 !important;
	font-weight: bold;
	}

.pun a:hover.usergroup-2 { /* Moderator */
	color: #ffcc00 !important;
	}

.pun .usergroup-5 { /* Premium */
	color: #e61515 !important;
	font-weight: bold;
	}

.pun a:hover.usergroup-5 { /* Premium */
	color: #ff4545 !important;
	}

.pun a.usergroup-6 { /* Banned */
	font-weight: normal;
	}

/* Notification bars
----------------------------------------------------------------*/
.pun .notice-bar {
	border: 1px solid #000;
	margin: 10px auto 10px auto;
	width: 100%;
	height: 20px;
	background: #9900cc linear-gradient(#9900cc, #660099);
	color: #eee;
	font-weight: bold;
	font-size: 11px;
	text-align: center;
	vertical-align: middle;
	text-shadow: 1px 1px #000;
	text-transform: uppercase;
	padding-top: 6px;
	}

.pun .notice-bar a {
	color: #fff;
	}

/* Payment form
----------------------------------------------------------------*/
#payment th {
	width: 15em;
	font-weight: bold
	}

#payment fieldset td span {
    display: block;
    font-size: 1em;
    font-weight: normal;
	}

#payment table.aligntop th, #paymenttable.aligntop td {
	vertical-align: top;
	}

#payment .payment-icons img {
	width: 30px;
	margin-left: 2px;
	margin-top: 4px;
	opacity: 0.5;
	border: 1px solid #111;
	-webkit-filter: grayscale(0.5);
	-webkit-filter: grayscale(50%);
	filter: grayscale(50%);
	filter: url(#greyscale);
	filter: gray;
	}
	
.contains-error {
	border: 1px solid #BA2323 !important;
	}
		]]>
		</stylesheet>
	</stylesheets>
	<templates>
		<template name="footer" version="1817"><![CDATA[	<br />
<footer>
	<div class="wrapper" align="center">
		<div id="mainwidth2">	
		<span class="smalltext">
<div id="brdfooter" class="block">
	
</div>

		</span>
	</div>
  </div>	
</footer>
</div>
</div>


                <!-- MyBB is free software developed and maintained by a volunteer community.
					It would be much appreciated by the MyBB Group if you left the full copyright and "powered by" notice intact,
					to show your support for MyBB.  If you choose to remove or modify the copyright below,
					you may be refused support on the MyBB Community Forums.

					This is free software, support us and we'll support you. -->
				<!-- End powered by --> 
		
<!-- The following piece of code allows MyBB to run scheduled tasks. DO NOT REMOVE -->{$task_image}<!-- End task image code -->
{$auto_dst_detection}
</div>

        <br />


	</div>]]></template>
		<template name="forumbit_depth1_cat" version="1812"><![CDATA[<table border="0" cellspacing="{$theme['borderwidth']}" cellpadding="{$theme['tablespace']}" class="tborder">
<thead>
<tr>
<td class="thead{$expthead}" colspan="5">
<div><strong><a href="{$forum_url}">{$forum['name']}</a></strong><br /><div class="smalltext">{$forum['description']}</div></div>
</td>
</tr>
</thead>
<tbody style="{$expdisplay}" id="cat_{$forum['fid']}_e">
<tr>
<td class="tcat" colspan="2"><span class="smalltext"></span></td>
<td class="tcat" width="85" align="center" style="white-space: nowrap"><span class="smalltext"></span></td>
<td class="tcat" width="85" align="center" style="white-space: nowrap"><span class="smalltext"></span></td>
<td class="tcat" width="200" align="center"><span class="smalltext"></span></td>
</tr>
{$sub_forums}
</tbody>
</table>
<br />]]></template>
		<template name="forumbit_depth2_cat" version="1808"><![CDATA[<tr>
<td class="{$bgcolor}">
<strong><a href="{$forum_url}">{$forum['name']}</a></strong>{$forum_viewers_text}<div class="smalltext">{$forum['description']}{$subforums}</div>
</td>
<td class="{$bgcolor}" align="center" style="white-space: nowrap">{$threads}{$unapproved['unapproved_threads']}</td>
<td class="{$bgcolor}" align="center" style="white-space: nowrap">{$posts}{$unapproved['unapproved_posts']}</td>
<td class="{$bgcolor}" align="right" style="white-space: nowrap">{$lastpost}</td>
</tr>]]></template>
		<template name="forumbit_depth2_forum" version="1812"><![CDATA[<tr>
<td class="{$bgcolor}" align="center" width="1"><div class="forum_status forum_{$lightbulb['folder']} ajax_mark_read ficons_{$forum['fid']}" title="{$lightbulb['altonoff']}" id="mark_read_{$forum['fid']}"><i class="fa fa-comments"></i></div></td>
<td class="{$bgcolor}">
<strong><a href="{$forum_url}">{$forum['name']}</a></strong>{$forum_viewers_text}<div class="smalltext">{$forum['description']}{$modlist}{$subforums}</div>
</td>
<td class="{$bgcolor}" align="center" style="white-space: nowrap"><span style="float: left;">Discussions:</span> <span style="float: right;">{$threads}{$unapproved['unapproved_threads']}</span><br/><span style="float: left;">Comments:</span> <span style="float: right;">{$posts}{$unapproved['unapproved_posts']}</span></td>
	<td class="{$bgcolor}" align="center" style="white-space: nowrap"></div>
<td class="{$bgcolor}" style="white-space: nowrap">{$lastpost}</td>
</tr>]]></template>
		<template name="forumbit_depth2_forum_lastpost" version="1808"><![CDATA[<span class="smalltext">
<a href="{$lastpost_link}" title="{$full_lastpost_subject}"><strong>{$lastpost_subject}</strong></a>
<br />{$lastpost_date}<br />{$lang->by} {$lastpost_profilelink}</span>]]></template>
		<template name="forumbit_depth3_statusicon" version="1808"><![CDATA[<div title="{$lightbulb['altonoff']}" class="subforumicon subforum_{$lightbulb['folder']} ajax_mark_read" id="mark_read_{$forum['fid']}"><i class="fa fa-comment"></i></div>]]></template>
		<template name="forumbit_subforums" version="1812"><![CDATA[{$sub_forums}]]></template>
		<template name="forumdisplay_subforums" version="1808"><![CDATA[<table border="0" cellspacing="{$theme['borderwidth']}" cellpadding="{$theme['tablespace']}" class="tborder">
<tr>
<td class="thead" colspan="5" align="center"><strong>{$lang->sub_forums_in}</strong></td>
</tr>
<tr>
<td class="tcat" width="2%">&nbsp;</td>
<td class="tcat" width="59%"><span class="smalltext"><strong>Forum Name</strong></span></td>
<td class="tcat" width="7%" align="center" style="white-space: nowrap"><span class="smalltext"><strong>Total Threads</strong></span></td>
<td class="tcat" width="7%" align="center" style="white-space: nowrap"><span class="smalltext"><strong>Total Replies</strong></span></td>
<td class="tcat" width="15%" align="center"><span class="smalltext"><strong>Most Recent Post</strong></span></td>
</tr>
{$forums}
</table>
<br />]]></template>
		<template name="forumdisplay_threadlist" version="1808"><![CDATA[<div class="float_left">
	{$multipage}
</div>
<div class="float_right">
	{$newthread}
</div>
<table border="0" cellspacing="{$theme['borderwidth']}" cellpadding="{$theme['tablespace']}" class="tborder clear">
	<tr>
		<td class="thead" colspan="{$colspan}">
			<div class="float_right">
				<span class="smalltext"><strong><a href="misc.php?action=markread&amp;fid={$fid}{$post_code_string}">{$lang->markforum_read}</a> | <a href="usercp2.php?action={$add_remove_subscription}subscription&amp;type=forum&amp;fid={$fid}&amp;my_post_key={$mybb->post_code}">{$add_remove_subscription_text}</a>{$clearstoredpass}</strong></span>
			</div>
			<div>
				<strong>{$foruminfo['name']}</strong>
			</div>
		</td>
	</tr>
	<tr>
		<td class="tcat" colspan="3" width="66%"><span class="smalltext"><strong><a href="{$sorturl}&amp;sortby=subject&amp;order=asc">{$lang->thread}</a> {$orderarrow['subject']} / <a href="{$sorturl}&amp;sortby=starter&amp;order=asc">{$lang->author}</a> {$orderarrow['starter']}</strong></span></td>
		<td class="tcat" align="center" width="7%"><span class="smalltext"><strong><a href="{$sorturl}&amp;sortby=replies&amp;order=desc">{$lang->replies}</a> {$orderarrow['replies']}</strong></span></td>
		<td class="tcat" align="center" width="7%"><span class="smalltext"><strong><a href="{$sorturl}&amp;sortby=views&amp;order=desc">{$lang->views}</a> {$orderarrow['views']}</strong></span></td>
		{$ratingcol}
		<td class="tcat" align="right" width="20%"><span class="smalltext"><strong><a href="{$sorturl}&amp;sortby=lastpost&amp;order=desc">{$lang->lastpost}</a> {$orderarrow['lastpost']}</strong></span></td>
		{$inlinemodcol}
	</tr>
	{$selectall}
	{$announcementlist}
	{$threads}
	<tr>
		<td class="tfoot" align="right" colspan="{$colspan}">
			<form action="forumdisplay.php" method="get">
				<input type="hidden" name="fid" value="{$fid}" />
				<select name="sortby">
					<option value="subject"{$sortsel['subject']}>{$lang->sort_by_subject}</option>
					<option value="lastpost"{$sortsel['lastpost']}>{$lang->sort_by_lastpost}</option>
					<option value="starter"{$sortsel['starter']}>{$lang->sort_by_starter}</option>
					<option value="started"{$sortsel['started']}>{$lang->sort_by_started}</option>
					{$ratingsort}
					<option value="replies"{$sortsel['replies']}>{$lang->sort_by_replies}</option>
					<option value="views"{$sortsel['views']}>{$lang->sort_by_views}</option>
				</select>
				<select name="order">
					<option value="asc"{$ordersel['asc']}>{$lang->sort_order_asc}</option>
					<option value="desc"{$ordersel['desc']}>{$lang->sort_order_desc}</option>
				</select>
				<select name="datecut">
					<option value="1"{$datecutsel['1']}>{$lang->datelimit_1day}</option>
					<option value="5"{$datecutsel['5']}>{$lang->datelimit_5days}</option>
					<option value="10"{$datecutsel['10']}>{$lang->datelimit_10days}</option>
					<option value="20"{$datecutsel['20']}>{$lang->datelimit_20days}</option>
					<option value="50"{$datecutsel['50']}>{$lang->datelimit_50days}</option>
					<option value="75"{$datecutsel['75']}>{$lang->datelimit_75days}</option>
					<option value="100"{$datecutsel['100']}>{$lang->datelimit_100days}</option>
					<option value="365"{$datecutsel['365']}>{$lang->datelimit_lastyear}</option>
					<option value="9999"{$datecutsel['9999']}>{$lang->datelimit_beginning}</option>
				</select>
				{$prefixselect}
				{$gobutton}
			</form>
		</td>
	</tr>
</table>
<div class="float_left">
{$multipage}
</div>
<div class="float_right" style="margin-top: 4px;">
<a href="#" id="sldtoggle"><div id="sldtog"><i class="fa fa-wrench" aria-hidden="true"></i> Topic Options</div></a>
{$newthread}
</div>
<br class="clear" /><br />
<div class="sldtoggle">
<div class="float_left">
<div class="float_left">
<dl class="thread_legend smalltext">
<dd><span class="thread_status newfolder" title="{$lang->new_thread}">&nbsp;</span> {$lang->new_thread}</dd>
<dd><span class="thread_status newhotfolder" title="{$lang->new_hot_thread}">&nbsp;</span> {$lang->new_hot_thread}</dd>
<dd><span class="thread_status hotfolder" title="{$lang->hot_thread}">&nbsp;</span> {$lang->hot_thread}</dd>
</dl>
</div>
<div class="float_left">
<dl class="thread_legend smalltext">
<dd><span class="thread_status folder" title="{$lang->no_new_thread}">&nbsp;</span> {$lang->no_new_thread}</dd>
<dd><span class="thread_status dot_folder" title="{$lang->posts_by_you}">&nbsp;</span> {$lang->posts_by_you}</dd>
<dd><span class="thread_status lockfolder" title="{$lang->locked_thread}">&nbsp;</span> {$lang->locked_thread}</dd>
</dl>
</div>
<br class="clear" />
</div>
<div class="float_right" style="text-align: right;">
{$inlinemod}
{$searchforum}
{$forumjump}</div>
</div>
<br class="clear" />
{$inline_edit_js}

<script>
$('#sldtoggle').click(function() {
$('.sldtoggle').slideToggle('fast').addClass( "sldshow" ); return false;
});
</script>

<style>
#sldtog{padding: 5.4px 15px; background: #222;color:#f5f5f5;cursor:pointer;display:inline-block;border-radius:5px;    }    
.sldtoggle {display:none;}
.sldshow {display:visible;}
</style>]]></template>
		<template name="header" version="1817"><![CDATA[<head>
<meta http-equiv="Content-Type" content="text/html; charset=utf-8" />
<title>Privacy policy / Opium</title>
	<link rel="stylesheet" type="text/css" href="style/Cobalt.css" />
	<link rel="stylesheet" type="text/css" href="/static/css/shoutbox.css" />
	<link rel="stylesheet" type="text/css" href="/static/css/font-awesome.min.css" />
	<link href="https://fonts.googleapis.com/css?family=Raleway:900,400" rel="stylesheet" type="text/css" />
	<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.1.0/jquery.min.js"></script>
</head>

<body>

<nav class="gs-navbar">
	<div class="gs-nav-container">
		<ul>
			<li><a href="/"><i class="fa fa-home"></i></a></li>
			<li class="active"><a href="/forums">SITE</a></li>
		</ul>
	</div>
</nav>

<div class="gs-divider"></div>

<div id="puntos" class="pun">
<div class="top-box"></div>
<div class="punwrap">

<div id="brdheader" class="block">
	<div class="box">
		<div id="brdtitle" class="inbox">
			<h1><a href="home.php">zMotan<span> Cheats</span></a></h1>
			<div id="brddesc"><p><span>Aleluia... Ai luat muia</span></p></div>
		</div>
		<div id="brdmenu" class="inbox">
			<ul>
				<li id="navindex"><a href="home.php">Home</a></li>
				<li id="navsearch"><a href="search.php">Search</a></li>
				<li id="navprofile"><a href="member.php?action=profile">Profile</a></li>
				<li id="navprofile"><a href="usercp.php">UserCP</a></li>
				<li id="navpmsnew"><a href="private.php?action=send">PM</a></li>
			</ul>
		</div>
		<div id="brdwelcome" class="inbox">
			<ul class="conl">
			</ul>
			<ul class="conr">
				<li><span>Topics: <a href="search.php?action=show_replies" title="Find topics you have posted to.">Posted</a> | <a href="search.php?action=show_new" title="Find topics with new posts since your last visit.">New</a> | <a href="search.php?action=show_recent" title="Find topics with recent posts.">Active</a> | <a href="search.php?action=show_unanswered" title="Find topics with no replies.">Unanswered</a></span></li>
			</ul>
			<div class="clearer"></div>
		</div>
	</div>
</div>


	

		</div>
		<div id="content">
			<div class="wrapper">
				{$pm_notice}
				{$bannedwarning}
				{$bbclosedwarning}
				{$unreadreports}
				{$pending_joinrequests}
				<br />]]></template>
		<template name="headerinclude" version="1809"><![CDATA[<link rel="alternate" type="application/rss+xml" title="{$lang->latest_threads} (RSS 2.0)" href="{$mybb->settings['bburl']}/syndication.php" />
<link rel="alternate" type="application/atom+xml" title="{$lang->latest_threads} (Atom 1.0)" href="{$mybb->settings['bburl']}/syndication.php?type=atom1.0" />
<meta http-equiv="Content-Type" content="text/html; charset={$charset}" />
<meta http-equiv="Content-Script-Type" content="text/javascript" />
<script type="text/javascript" src="{$mybb->asset_url}/jscripts/jquery.js?ver=1806"></script>
<script type="text/javascript" src="{$mybb->asset_url}/jscripts/jquery.plugins.min.js?ver=1806"></script>
<script type="text/javascript" src="{$mybb->asset_url}/jscripts/general.js?ver=1809"></script>

{$stylesheets}
<link href="//maxcdn.bootstrapcdn.com/font-awesome/4.3.0/css/font-awesome.min.css" rel="stylesheet">
<link href='//maxcdn.bootstrapcdn.com/font-awesome/4.1.0/css/font-awesome.min.css' rel='stylesheet' type='text/css'>

<script type="text/javascript">

var quoteMsg = "View More";
var quotePop = "Too Many Quotes";

jQuery(function() {
   jQuery('blockquote:not(blockquote > blockquote)').each(function(a, b) {
       jQuery(this).children('blockquote').each(function() {
         jQuery(this).html("<div><div class=\"spoilerheader\">" + quoteMsg + " <a href=\"javascript:void(0);\" class=\"spoilerclick\">(" + quotePop + ")</a></div><div class=\"spoilerbody\" style=\"display: none;\">" + jQuery(this).html() + "</div></div>");
       });
     
   });
jQuery(".spoilerclick").click(function() {

   var spoiler = jQuery(this).parent().parent();
   jQuery(spoiler).children(".spoilerbody").show();
   jQuery(spoiler).children(".spoilerheader").hide();
})
});

</script>

<script type="text/javascript">
<!--
	lang.unknown_error = "{$lang->unknown_error}";

	lang.select2_match = "{$lang->select2_match}";
	lang.select2_matches = "{$lang->select2_matches}";
	lang.select2_nomatches = "{$lang->select2_nomatches}";
	lang.select2_inputtooshort_single = "{$lang->select2_inputtooshort_single}";
	lang.select2_inputtooshort_plural = "{$lang->select2_inputtooshort_plural}";
	lang.select2_inputtoolong_single = "{$lang->select2_inputtoolong_single}";
	lang.select2_inputtoolong_plural = "{$lang->select2_inputtoolong_plural}";
	lang.select2_selectiontoobig_single = "{$lang->select2_selectiontoobig_single}";
	lang.select2_selectiontoobig_plural = "{$lang->select2_selectiontoobig_plural}";
	lang.select2_loadmore = "{$lang->select2_loadmore}";
	lang.select2_searching = "{$lang->select2_searching}";

	var cookieDomain = "{$mybb->settings['cookiedomain']}";
	var cookiePath = "{$mybb->settings['cookiepath']}";
	var cookiePrefix = "{$mybb->settings['cookieprefix']}";
	var cookieSecureFlag = "{$mybb->settings['cookiesecureflag']}";
	var deleteevent_confirm = "{$lang->deleteevent_confirm}";
	var removeattach_confirm = "{$lang->removeattach_confirm}";
	var loading_text = '{$lang->ajax_loading}';
	var saving_changes = '{$lang->saving_changes}';
	var use_xmlhttprequest = "{$mybb->settings['use_xmlhttprequest']}";
	var my_post_key = "{$mybb->post_code}";
	var rootpath = "{$mybb->settings['bburl']}";
	var imagepath = "{$theme['imgdir']}";
  	var yes_confirm = "{$lang->yes}";
	var no_confirm = "{$lang->no}";
	var MyBBEditor = null;
	var spinner_image = "{$theme['imgdir']}/spinner.gif";
	var spinner = "<img src='" + spinner_image +"' alt='' />";
	var modal_zindex = 9999;
// -->
</script>]]></template>
		<template name="header_welcomeblock_guest" version="1814"><![CDATA[						<!-- Continuation of div(class="upper") as opened in the header template -->

<li style="float: right;margin-right: 8%;"><a href="{$mybb->settings['bburl']}/member.php?action=register"><i class="fa fa-user" aria-hidden="true"></i> Register</a></li>
<li style="float: right"><a href="{$mybb->settings['bburl']}/member.php?action=login"><span><i class="fa fa-user" aria-hidden="true"></i> Login</span></a></li>]]></template>
		<template name="header_welcomeblock_member" version="1814"><![CDATA[<li style="float: right;margin-right: 8%;"><a href="{$mybb->settings['bburl']}/member.php?action=logout&amp;logoutkey={$mybb->user['logoutkey']}"><i class="fa fa-warning" aria-hidden="true"></i> Log Me Out</a></li>
<li style="float: right"><a href="{$mybb->settings['bburl']}/private.php"><span><i class="fa fa-folder" aria-hidden="true"></i> Messages</span></a></li>
<li style="float: right"><label for="drop-1" class="toggle">Dropdown <i class="fa fa-sort-desc" aria-hidden="true"></i></label>
                   <a href="#"><i class="fa fa-user" aria-hidden="true"></i> {$mybb->user['username']}</a>
                   <input type="checkbox" id="drop-1"/>
                   <ul>
                       <li><a href="{$mybb->settings['bburl']}/member.php?action=profile&uid={$mybb->user['uid']}"><i class="fa fa-user" aria-hidden="true"></i> Profile</a></li>
                       <li><a href="{$mybb->settings['bburl']}/usercp.php"><i class="fa fa-bed" aria-hidden="true"></i> User CP</a></li>
                       <li>{$modcplink}</li>
					   <li>{$admincplink}</li>
                   </ul></li>]]></template>
		<template name="header_welcomeblock_member_admin" version="1814"><![CDATA[<li><a href="{$mybb->settings['bburl']}/{$admin_dir}/index.php" class="admincp"><i class="fa fa-heartbeat"></i> Admin CP</a></li>]]></template>
		<template name="header_welcomeblock_member_moderator" version="1814"><![CDATA[<li><a href="{$mybb->settings['bburl']}/modcp.php" class="modcp"><i class="fa fa-gavel"></i> Moderator CP</a></li>]]></template>
		<template name="header_welcomeblock_member_pms" version="1814"><![CDATA[<!-- <li><a href="{$mybb->settings['bburl']}/private.php">{$lang->welcome_pms}</a> {$lang->welcome_pms_usage}</li> -->]]></template>
		<template name="header_welcomeblock_member_search" version="1814"><![CDATA[<!-- <li><a href="{$mybb->settings['bburl']}/search.php?action=getnew">{$lang->welcome_newposts}</a></li>
<li><a href="{$mybb->settings['bburl']}/search.php?action=getdaily">{$lang->welcome_todaysposts}</a></li> -->]]></template>
		<template name="header_welcomeblock_member_user" version="1814"><![CDATA[<!-- <li><a href="{$mybb->settings['bburl']}/usercp.php" class="usercp">{$lang->welcome_usercp}</a></li> -->]]></template>
		<template name="index" version="1817"><![CDATA[<html>
<head>
<title>{$mybb->settings['bbname']}</title>
{$headerinclude}
<script type="text/javascript">
<!--
	lang.no_new_posts = "{$lang->no_new_posts}";
	lang.click_mark_read = "{$lang->click_mark_read}";
// -->

</script>
</head>
<body>
{$header}
{$dvz_shoutbox}
<div class="side" style="float: right; width: 20%;border: 1px solid #4c4c4c;">
	<table border="0" cellspacing="{$theme['borderwidth']}" cellpadding="{$theme['tablespace']}" class="tborder">
		<tr>
			<td class="thead">
				Forum Statistics
   			</td>
		</tr>

		<tr>
   			<td class="trow1">
				<span style="float:left;">Total Posts:</span><span style="float:right;">{$stats['numposts']}</span>
   			</td>
		</tr>
		<tr>
   			<td class="trow1">
				<span style="float:left;">Total Threads:</span><span style="float:right;">{$stats['numthreads']}</span>
   			</td>
		</tr>
		<tr>
   			<td class="trow1">
				<span style="float:left;">Total Members:</span><span style="float:right;">{$stats['numusers']}</span>
   			</td>
		</tr>
		<tr>
   			<td class="trow1">
				<span style="float:left;">Newest Member:</span><span style="float:right;">{$stats['lastusername']}</span>
   			</td>
		</tr>
	</table>
</div>

<div class="forum" style="float: left; width: 79%;">
{$forums}</div>
{$boardstats}
{$footer}
</body>
</html>]]></template>
		<template name="index_boardstats" version="1812"><![CDATA[<table border="0" cellspacing="{$theme['borderwidth']}" cellpadding="{$theme['tablespace']}" class="tborder">
<thead>
<tr>
<td class="thead{$collapsedthead['boardstats']}">
<div><strong>{$lang->online_note}</strong></div>
</td>
</tr>
</thead>
<tbody style="{$collapsed['boardstats_e']}" id="boardstats_e">
{$whosonline}
</tbody>
</table>]]></template>
		<template name="index_whosonline" version="1812"><![CDATA[<tr>
<td class="trow1">
{$onlinemembers}
</td>
</tr>]]></template>
		<template name="member_profile" version="1812"><![CDATA[<html>
<head>
<title>{$mybb->settings['bbname']} - {$lang->profile}</title>
{$headerinclude}
<script type="text/javascript" src="{$mybb->asset_url}/jscripts/report.js?ver=1804"></script>
</head>
<body>
{$header}
<fieldset style="background: #444">
	<table width="100%" cellspacing="0" cellpadding="0" border="0">
		<tr>
			<td width="75%">
				<span class="largetext"><strong>{$formattedname}</strong></span><br />
				<span class="smalltext">
					({$usertitle})<br />
					{$groupimage}
					{$userstars}<br />
					<br />
					<strong>{$lang->registration_date}</strong> {$memregdate}<br />
					<strong>{$lang->date_of_birth}</strong> {$membday} {$membdayage}<br />
					<strong>{$lang->local_time}</strong> {$localtime}<br />
					<strong>{$lang->postbit_status}</strong> {$online_status}
				</span>
			</td>
			<td width="25%" align="right" valign="middle">{$avatar}</td>
		</tr>
	</table>
</fieldset>
<br />
{$awaybit}{$bannedbit}
<table width="100%" cellspacing="0" cellpadding="0" border="0" align="center">
	<tr>
		<td width="50%" valign="top">
			<table border="0" cellspacing="{$theme['borderwidth']}" cellpadding="{$theme['tablespace']}" class="tborder">
				<tr>
					<td colspan="2" class="thead"><strong>{$lang->users_forum_info}</strong></td>
				</tr>
				<tr>
					<td class="trow1" style="width: 30%;"><strong>{$lang->joined}</strong></td>
					<td class="trow1">{$memregdate}</td>
				</tr>
				<tr>
					<td class="trow2"><strong>{$lang->lastvisit}</strong></td>
					<td class="trow2">{$memlastvisitdate}</td>
				</tr>
				<tr>
					<td class="trow1"><strong>{$lang->total_posts}</strong></td>
					<td class="trow1">{$memprofile['postnum']} {$findposts}</td>
				</tr>
				<tr>
					<td class="trow2"><strong>{$lang->total_threads}</strong></td>
					<td class="trow2">{$memprofile['threadnum']} {$findthreads}</td>
				</tr>
				<tr>
					<td class="trow1"><strong>{$lang->timeonline}</strong></td>
					<td class="trow1">{$timeonline}</td>
				</tr>
				{$referrals}
{$referrer}
				{$reputation}
				{$warning_level}
			</table>
			{$contact_details}
		</td>
		<td>&nbsp;&nbsp;</td>
		<td width="50%" valign="top">
			{$profilefields}
			{$signature}
			{$modoptions}
			{$adminoptions}
			<div style="text-align: center">{$buddy_options}{$ignore_options}{$report_options}</div>
		</td>
	</tr>
</table>
{$footer}
</body>
</html>]]></template>
		<template name="member_profile_customfields" version="1817"><![CDATA[<table border="0" cellspacing="{$theme['borderwidth']}" cellpadding="{$theme['tablespace']}" class="tborder tfixed">
<colgroup>
<col style="width: 30%;" />
</colgroup>
<tr>
<td colspan="2" class="thead"><strong>{$lang->users_additional_info}</strong></td>
</tr>
{$customfields}
<!--Invitation-->
</table>
<br />]]></template>
		<template name="member_profile_findposts" version="1809"><![CDATA[<span class="smalltext">[<a href="search.php?action=finduser&amp;uid={$uid}">{$lang->find_posts}</a>]</span>]]></template>
		<template name="member_profile_findthreads" version="1809"><![CDATA[<span class="smalltext">[<a href="search.php?action=finduserthreads&amp;uid={$uid}">{$lang->find_threads}</a>]</span>]]></template>
		<template name="member_profile_referrals" version="1817"><![CDATA[<tr>
<td class="{$bg_color}"><strong>{$lang->members_referred}</strong></td>
<td class="{$bg_color}">{$memprofile['referrals']} {$referredList}</td>
</tr>]]></template>
		<template name="member_profile_reputation" version="1814"><![CDATA[<tr>
	<td class="{$bg_color}"><strong>{$lang->reputation}</strong></td>
	<td class="{$bg_color}">{$reputation} [<a href="reputation.php?uid={$memprofile['uid']}">{$lang->reputation_details}</a>] {$vote_link}</td>
</tr>]]></template>
		<template name="member_profile_signature" version="1814"><![CDATA[<table border="0" cellspacing="{$theme['borderwidth']}" cellpadding="{$theme['tablespace']}" class="tborder tfixed">
<tr>
<td class="thead"><strong>{$lang->users_signature}</strong></td>
</tr>
<tr>
<td style="overflow: auto; height: auto; max-height: 150px; display: block;">{$memprofile['signature']}</td>
</tr>
</table>
<br />]]></template>
		<template name="member_register" version="1817"><![CDATA[
<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Strict//EN" "http://www.w3.org/TR/xhtml1/DTD/xhtml1-strict.dtd">
<html xmlns="http://www.w3.org/1999/xhtml" xml:lang="en" lang="en" dir="ltr">
<head>
<meta http-equiv="Content-Type" content="text/html; charset=utf-8" />
<meta name="ROBOTS" content="NOINDEX, FOLLOW" />
	<title>Register / opiumcheats</title>
	<link rel="stylesheet" type="text/css" href="style/Cobalt.css" />
	<link rel="stylesheet" type="text/css" href="/static/css/shoutbox.css" />
	<link rel="stylesheet" type="text/css" href="/static/css/font-awesome.min.css" />
	<link href="https://fonts.googleapis.com/css?family=Raleway:900,400" rel="stylesheet" type="text/css" />
	<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.1.0/jquery.min.js"></script>
<script type="text/javascript">
</head>
<body>
{$header}
<form action="member.php" method="post" id="registration_form"><input type="text" style="visibility: hidden;" value="" name="regcheck1" /><input type="text" style="visibility: hidden;" value="true" name="regcheck2" />
{$regerrors}
<table border="0" cellspacing="{$theme['borderwidth']}" cellpadding="{$theme['tablespace']}" class="tborder">
<tr>
<td class="thead" colspan="2"><strong>{$lang->registration}</strong></td>
</tr>
<tr>
<td width="50%" class="trow1" valign="top">
<fieldset class="trow2">
<legend><strong>{$lang->account_details}</strong></legend>
<table cellspacing="0" cellpadding="{$theme['tablespace']}" width="100%">
<tr>
<td colspan="2"><span class="smalltext"><label for="username">{$lang->username}</label></span></td>
</tr>
<tr>
<td colspan="2"><input type="text" class="textbox" name="username" id="username" style="width: 100%" value="{$username}" /></td>
</tr>
{$passboxes}
<tr>
<td width="50%" valign="top"><span class="smalltext"><label for="email">{$lang->email}</label></span></td>
<td width="50%" valign="top"><span class="smalltext"><label for="email2">{$lang->confirm_email}</label></span></td>
</tr>
<tr>
<td width="50%" valign="top"><input type="text" class="textbox" name="email" id="email" style="width: 100%" maxlength="50" value="{$email}" /></td>
<td width="50%" valign="top"><input type="text" class="textbox" name="email2" id="email2" style="width: 100%" maxlength="50" value="{$email2}" /></td>
</tr>
<tr>
	<td colspan="2" style="display: none;" id="email_status">&nbsp;</td>
</tr>
{$hiddencaptcha}
</table>
</fieldset>
{$requiredfields}
{$customfields}
{$referrer}
<!--Invitation-->
{$regimage}
{$questionbox}
</td>
<td width="50%" class="trow1" valign="top">
<fieldset class="trow2">
<legend><strong>{$lang->account_prefs}</strong></legend>
<table cellspacing="0" cellpadding="{$theme['tablespace']}" width="100%">
<tr>
<td valign="top" width="1"><input type="checkbox" class="checkbox" name="allownotices" id="allownotices" value="1" {$allownoticescheck} /></td>
<td valign="top"><span class="smalltext"><label for="allownotices">{$lang->allow_notices}</label></span></td>
</tr>
<tr>
<td valign="top" width="1"><input type="checkbox" class="checkbox" name="hideemail" id="hideemail" value="1" {$hideemailcheck} /></td>
<td valign="top"><span class="smalltext"><label for="hideemail">{$lang->hide_email}</label></span></td>
</tr>
<tr>
<td valign="top" width="1"><input type="checkbox" class="checkbox" name="receivepms" id="receivepms" value="1" {$receivepmscheck} /></td>
<td valign="top"><span class="smalltext"><label for="receivepms">{$lang->receive_pms}</label></span></td>
</tr>
<tr>
<td valign="top" width="1"><input type="checkbox" class="checkbox" name="pmnotice" id="pmnotice" value="1"{$pmnoticecheck} /></td>
<td valign="top"><span class="smalltext"><label for="pmnotice">{$lang->pm_notice}</label></span></td>
</tr>
<tr>
<td valign="top" width="1"><input type="checkbox" class="checkbox" name="pmnotify" id="pmnotify" value="1" {$pmnotifycheck} /></td>
<td valign="top"><span class="smalltext"><label for="pmnotify">{$lang->email_notify_newpm}</label></span></td>
</tr>
<tr>
<td valign="top" width="1"><input type="checkbox" class="checkbox" name="invisible" id="invisible" value="1" {$invisiblecheck} /></td>
<td valign="top"><span class="smalltext"><label for="invisible">{$lang->invisible_mode}</label></span></td>
</tr>
<tr>
<td colspan="2"><span class="smalltext"><label for="subscriptionmethod">{$lang->subscription_method}</label></span></td>
</tr>
<tr>
<td colspan="2">
	<select name="subscriptionmethod" id="subscriptionmethod">
		<option value="0" {$no_auto_subscribe_selected}>{$lang->no_auto_subscribe}</option>
		<option value="1" {$no_subscribe_selected}>{$lang->no_subscribe}</option>
		<option value="2" {$instant_email_subscribe_selected}>{$lang->instant_email_subscribe}</option>
		<option value="3" {$instant_pm_subscribe_selected}>{$lang->instant_pm_subscribe}</option>
	</select>
</td>
</tr>
</table>
</fieldset>
<br />
<fieldset class="trow2">
<legend><strong><label for="timezone">{$lang->time_offset}</label></strong></legend>
<table cellspacing="0" cellpadding="{$theme['tablespace']}" width="100%">
<tr>
<td><span class="smalltext">{$lang->time_offset_desc}</span></td>
</tr>
<tr>
<td>{$tzselect}</td>
</tr>
<tr>
<td><span class="smalltext">{$lang->dst_correction}</span></td>
</tr>
<tr>
<td>
	<select name="dstcorrection">
		<option value="2" {$dst_auto_selected}>{$lang->dst_correction_auto}</option>
		<option value="1" {$dst_enabled_selected}>{$lang->dst_correction_enabled}</option>
		<option value="0" {$dst_disabled_selected}>{$lang->dst_correction_disabled}</option>
	</select>
</td>
</tr>
</table>
</fieldset>
{$boardlanguage}
</td>
</tr>
</table>
<br />
<div align="center">
<input type="hidden" name="regtime" value="{$time}" />
<input type="hidden" name="step" value="registration" />
<input type="hidden" name="action" value="do_register" />
<input type="submit" class="button" name="regsubmit" value="{$lang->submit_registration}" />
</div>
</form>
{$validator_javascript}
{$footer}
</body>
</html>]]></template>
		<template name="nav" version="1808"><![CDATA[<fieldset class="breadcrumb"><span class="crumbs">    
<img src="http://i.imgur.com/rUZQkRT.png" alt="Home" class="home"/>        
    <span class="arrow">
        <span></span>
       </span>{$nav}{$activesep}<span class="crust" itemscope="itemscope" itemtype="http://data-vocabulary.org/Breadcrumb">
{$activebit}</span></span></fieldset>]]></template>
		<template name="nav_bit" version="1808"><![CDATA[<span class="crust" itemscope="itemscope" itemtype="http://data-vocabulary.org/Breadcrumb">
<a href="{$navbit['url']}" class="crumb" rel="up" itemprop="url">
          {$navbit['name']} </a>
       <span class="arrow">
           <span></span>
    </span></span>]]></template>
		<template name="nav_bit_active" version="1808"><![CDATA[<a href="{$navbit['url']}" class="crumb" rel="up" itemprop="url">
{$navbit['name']} </a>
       <span class="arrow">
           <span></span>
       </span>]]></template>
		<template name="nav_dropdown" version="1808"><![CDATA[]]></template>
		<template name="nav_sep" version="1808"><![CDATA[]]></template>
		<template name="nav_sep_active" version="1808"><![CDATA[]]></template>
		<template name="newthread" version="1808"><![CDATA[<html>
<head>
<title>{$lang->newthread_in}</title>
{$headerinclude}
<script type="text/javascript" src="{$mybb->asset_url}/jscripts/post.js?ver=1808"></script>
</head>
<body>
{$header}
{$preview}
{$thread_errors}
{$attacherror}
{$moderation_notice}
<form action="newthread.php?fid={$fid}&amp;processed=1" method="post" enctype="multipart/form-data" name="input">
<input type="hidden" name="my_post_key" value="{$mybb->post_code}" />
<table border="0" cellspacing="{$theme['borderwidth']}" cellpadding="{$theme['tablespace']}" class="tborder">
<tr>
<td class="thead" colspan="2"><strong>{$lang->post_new_thread}</strong></td>
</tr>
{$loginbox}
<tr>
<td class="trow2" width="20%"><strong>{$lang->thread_subject}</strong></td>
<td class="trow2">{$prefixselect}<input type="text" class="textbox" name="subject" size="40" maxlength="85" value="{$subject}" tabindex="1" /><input type="checkbox" class="input_control"  value="subject" />I believe <strong>{$forum['name']}</strong> is the best section for this thread.</td>
</tr>
{$posticons}
<tr>
<td class="trow2" valign="top"><strong>{$lang->your_message}</strong>{$smilieinserter}</td>
<td class="trow2">
<textarea name="message" id="message" rows="20" cols="70" tabindex="2">{$message}</textarea>
{$codebuttons}
{$multiquote_external}
</td>
</tr>
<tr>
<td class="trow1" valign="top"><strong>{$lang->post_options}</strong></td>
<td class="trow1"><span class="smalltext">
<label><input type="checkbox" class="checkbox" name="postoptions[signature]" value="1" tabindex="7"{$postoptionschecked['signature']} /> {$lang->options_sig}</label>
{$disablesmilies}</span></td>
</tr>
{$modoptions}
{$subscriptionmethod}
{$pollbox}
{$captcha}
</table>
{$attachbox}
<br />
<div style="text-align:center"><input type="submit" class="button" name="submit" value="{$lang->post_thread}" tabindex="4" accesskey="s" />  <input type="submit" class="button" name="previewpost" value="{$lang->preview_post}" tabindex="5" />{$savedraftbutton}</div>
<input type="hidden" name="action" value="do_newthread" />
<input type="hidden" name="posthash" value="{$posthash}" />
<input type="hidden" name="attachmentaid" value="" />
<input type="hidden" name="attachmentact" value="" />
<input type="hidden" name="quoted_ids" value="{$quoted_ids}" />
<input type="hidden" name="tid" value="{$tid}" />
{$editdraftpid}
</form>
{$forumrules}
{$footer}
<script type="text/javascript">
	$(".author_avatar img").error(function () {
		$(this).unbind("error").closest('.author_avatar').remove();
	});
</script>
	
	<script type="text/javascript">
$(document).ready(function () {
       $('.input_control').change(function () {
           $('input[name=' + this.value + ']')[0].disabled = !this.checked;
       }).change();
    });
</script>
<style type="text/css">
    input.textbox:disabled {
        background: #DDD;
       }
</style>
	
</body>
</html>]]></template>
		<template name="portal" version="1808"><![CDATA[<html>
<head>
<title>{$mybb->settings['bbname']}</title>
<link rel="alternate" type="application/rss+xml" title="{$lang->latest_announcements} (RSS 2.0)" href="{$mybb->settings['bburl']}/syndication.php?portal=1" />
<link rel="alternate" type="application/atom+xml" title="{$lang->latest_announcements} (Atom 1.0)" href="{$mybb->settings['bburl']}/syndication.php?portal=1&type=atom1.0" />
{$headerinclude}
</head>
<body>
{$header}
<table width="100%" cellspacing="0" cellpadding="{$theme['tablespace']}" border="0" align="center">
<tr><td valign="top" width="200">
{$welcome}{$teamonline}
{$pms}


{$search}
{$stats}
{$whosonline}
{$latestthreads}
</td>
<td>&nbsp;</td>
<td valign="top">
{$announcements}
{$multipage}
</td>
</tr>
</table>
{$footer}
</body>
</html>]]></template>
		<template name="postbit" version="1814"><![CDATA[{$ignore_bit}
<a name="pid{$post['pid']}" id="pid{$post['pid']}"></a>
<div class="post classic {$unapproved_shade}" style="{$post_visibility}" id="post_{$post['pid']}">
<div class="post_author scaleimages">
	{$post['useravatar']}
	<div class="author_information">
			<strong><span class="largetext">{$post['profilelink']}</span></strong>
		{$post['onlinestatus']}
			<span class="smalltext">
				{$post['usertitle']}
				{$post['userstars']}
				{$post['groupimage']}
			</span>
	</div>
	<div class="author_statistics">
		{$post['user_details']}
	</div>
</div>
<div class="post_content">
	<div class="post_head">
		{$post['posturl']}
		{$post['icon']}
		<span class="post_date">{$post['postdate']} <span class="post_edit" id="edited_by_{$post['pid']}">{$post['editedmsg']}</span></span>
	{$post['subject_extra']}
	</div>
	<div class="post_body scaleimages" id="pid_{$post['pid']}">
		{$post['message']}
	</div>
	{$post['attachments']}
	{$post['signature']}
	<div class="post_meta" id="post_meta_{$post['pid']}">
		{$post['iplogged']}
	</div>
</div>
<div class="post_controls">
	<div class="postbit_buttons author_buttons float_left">
		{$post['button_pm']}{$post['button_rep']}
	</div>
	<div class="postbit_buttons post_management_buttons float_right">
		{$post['button_edit']}{$post['button_quickdelete']}{$post['button_quickrestore']}{$post['button_quote']}{$post['button_multiquote']}{$post['button_report']}{$post['button_warn']}{$post['button_purgespammer']}{$post['button_reply_pm']}{$post['button_replyall_pm']}{$post['button_forward_pm']}{$post['button_delete_pm']}
	</div>
</div>
</div>]]></template>
		<template name="postbit_author_user" version="1808"><![CDATA[<span style="float:left;">{$lang->postbit_posts}</span> <span style="float:right;"> {$post['postnum']}</span><br /><span style="float:left;">{$lang->postbit_threads}</span> <span style="float:right;">{$post['threadnum']}</span><br /><span style="float:left;">{$lang->postbit_joined}</span> <span style="float:right;">{$post['userregdate']}</span>{$post['replink']}{$post['profilefield']}{$post['warninglevel']}]]></template>
		<template name="postbit_classic" version="1814"><![CDATA[{$ignore_bit}
<a name="pid{$post['pid']}" id="pid{$post['pid']}"></a>
<div class="post classic {$unapproved_shade}" style="{$post_visibility}" id="post_{$post['pid']}">
<div class="post_author scaleimages">
	{$post['onlinestatus']}{$post['useravatar']}
	<div class="author_information">
			<strong><span class="largetext">{$post['profilelink']}</span></strong><br/>
		<span class="derusertitle">{$post['usertitle']}</span><br/>
				<span class="smalltext">{$post['userstars']}<br/>
				{$post['groupimage']}
			</span>
	</div>
	<div class="author_statistics">
		{$post['user_details']}
	</div>
</div>
<div class="post_content">
	<div class="post_head">
		{$post['posturl']}
		{$post['icon']}
		<span class="post_date">{$post['postdate']} <span class="post_edit" id="edited_by_{$post['pid']}">{$post['editedmsg']}</span></span>
	{$post['subject_extra']}
	</div>
	<div class="post_body scaleimages" id="pid_{$post['pid']}">
		{$post['message']}
	</div>
	{$post['attachments']}
	{$post['signature']}
	<div class="post_meta" id="post_meta_{$post['pid']}">
		{$post['iplogged']}
	</div>
</div>
<div class="post_controls">
	<div class="postbit_buttons author_buttons float_left">
		{$post['button_pm']}
	</div>
	<div class="postbit_buttons post_management_buttons float_right">
		{$post['button_edit']}{$post['button_quickdelete']}{$post['button_quickrestore']}{$post['button_quote']}{$post['button_multiquote']}{$post['button_report']}{$post['button_warn']}{$post['button_reply_pm']}{$post['button_replyall_pm']}{$post['button_forward_pm']}{$post['button_delete_pm']}
	</div>
</div>
</div>]]></template>
		<template name="postbit_offline" version="1814"><![CDATA[<span class="postbit-offline" title="Currently offline"><i class="fa fa-user" aria-hidden="true"></i></span>]]></template>
		<template name="postbit_online" version="1814"><![CDATA[<span class="postbit-online" title="Currently online"><i class="fa fa-user" aria-hidden="true"></i></span>]]></template>
		<template name="postbit_pm" version="1814"><![CDATA[<a href="private.php?action=send&amp;uid={$post['uid']}" title="{$lang->postbit_pm}" style="margin-left:63px;"><span>Message</span></a>]]></template>
		<template name="postbit_profilefield" version="1808"><![CDATA[<br />{$post['fieldname']}:<div style="float:right"> {$post['fieldvalue']}</div>]]></template>
		<template name="postbit_purgespammer" version="1814"><![CDATA[]]></template>
		<template name="postbit_reputation" version="1814"><![CDATA[<br /><center>{$post['userreputation']}</center>]]></template>
		<template name="postbit_signature" version="1814"><![CDATA[<hr size="1" width="100%" align="center" />
<br />
<div style="overflow: auto; height: auto; max-height: 150px; display: block;">{$post['signature']}</div>]]></template>
		<template name="postbit_warninglevel" version="1814"><![CDATA[{$lang->postbit_warning_level} <div class="float_right"><a href="{$warning_link}">{$warning_level}</a></div>]]></template>
		<template name="private_read" version="1814"><![CDATA[<html>
<head>
<title>{$lang->viewing_pm} {$pm['subject']}</title>
{$headerinclude}
</head>
<body>
{$header}
<table width="100%" border="0" align="center">
<tr>
{$usercpnav}
<td style="vertical-align: top;">
<table border="0" cellspacing="{$theme['borderwidth']}" cellpadding="{$theme['tablespace']}" class="tborder tfixed clear no_bottom_border" style="background: #444">
<tr>
<td class="thead">
<strong>{$pm['subject']}</strong>
</td>
</tr>
{$action_time}
<tr><td id="posts_container">
<div id="posts">
{$message}
</div>
</td></tr>
</table>
{$quickreply}
</td>
</tr>
</table>
{$footer}
<script type="text/javascript">
	$(".author_avatar img").error(function () {
		$(this).unbind("error").closest('.author_avatar').remove();
	});
</script>
</body>
</html>]]></template>
		<template name="reputation" version="1814"><![CDATA[<html>
<head>
<title>{$mybb->settings['bbname']} - {$lang->reputation_report}</title>
{$headerinclude}
<script type="text/javascript">
<!--
	var delete_reputation_confirm = "{$lang->delete_reputation_confirm}";
// -->
</script>
<script type="text/javascript" src="{$mybb->asset_url}/jscripts/report.js?ver=1804"></script>
</head>
<body>
{$header}
{$add_reputation}
<table border="0" cellspacing="{$theme['borderwidth']}" cellpadding="{$theme['tablespace']}" class="tborder clear">
<tr>
	<td class="thead"><strong>{$lang->reputation_report}</strong></td>
</tr>
<tr>
	<td class="tcat"><strong>{$lang->summary}</strong></td>
</tr>
<tr>
	<td class="trow1">
	<table width="100%" cellspacing="0" cellpadding="0" border="0">
		<tr>
			<td>
				<span class="largetext"><strong>{$username}</strong></span><br />
				<span class="smalltext">
					({$usertitle})<br />
					<br />
					<strong>{$lang->total_reputation}:</strong> <span class="repbox {$total_class}">{$rep_total}</span><br /><br />
					<strong>{$lang->reputation_members} {$rep_members}</strong><br />
					<strong>{$lang->reputation_posts} {$rep_posts}</strong>
				</span>
			</td>
			<td align="right" style="width: 300px;">
					<table border="0" cellspacing="{$theme['borderwidth']}" cellpadding="{$theme['tablespace']}" class="tborder trow2" style="background: #333">
						<tr>
							<td>&nbsp;</td>
							<td><span class="smalltext reputation_positive">{$lang->positive_count}</span></td>
							<td><span class="smalltext reputation_neutral">{$lang->neutral_count}</span></td>
							<td><span class="smalltext reputation_negative">{$lang->negative_count}</span></td>
						</tr>
						<tr>
							<td style="text-align: right;"><span class="smalltext">{$lang->last_week}</span></td>
							<td style="text-align: center;"><span class="smalltext">{$f_positive_week}</span></td>
							<td style="text-align: center;"><span class="smalltext">{$f_neutral_week}</span></td>
							<td style="text-align: center;"><span class="smalltext">{$f_negative_week}</span></td>
						</tr>
						<tr>
							<td style="text-align: right;"><span class="smalltext">{$lang->last_month}</span></td>
							<td style="text-align: center;"><span class="smalltext">{$f_positive_month}</span></td>
							<td style="text-align: center;"><span class="smalltext">{$f_neutral_month}</span></td>
							<td style="text-align: center;"><span class="smalltext">{$f_negative_month}</span></td>
						</tr>
						<tr>
							<td style="text-align: right;"><span class="smalltext">{$lang->last_6months}</span></td>
							<td style="text-align: center;"><span class="smalltext">{$f_positive_6months}</span></td>
							<td style="text-align: center;"><span class="smalltext">{$f_neutral_6months}</span></td>
							<td style="text-align: center;"><span class="smalltext">{$f_negative_6months}</span></td>
						</tr>
						<tr>
							<td style="text-align: right;"><span class="smalltext">{$lang->all_time}</span></td>
							<td style="text-align: center;"><span class="smalltext">{$f_positive_count}</span></td>
							<td style="text-align: center;"><span class="smalltext">{$f_neutral_count}</span></td>
							<td style="text-align: center;"><span class="smalltext">{$f_negative_count}</span></td>
						</tr>
					</table>
			</td>
		</tr>
	</table>
	</td>
</tr>
<tr>
	<td class="tcat"><strong>{$lang->comments}</strong></td>
</tr>
{$reputation_votes}
<tr>
	<td class="tfoot" align="right">
	<form action="reputation.php" method="get">
		<input type="hidden" name="uid" value="{$user['uid']}" />
		<select name="show">
			<option value="all" {$show_selected['all']}>{$lang->show_all}</option>
			<option value="positive" {$show_selected['positive']}>{$lang->show_positive}</option>
			<option value="neutral" {$show_selected['neutral']}>{$lang->show_neutral}</option>
			<option value="negative" {$show_selected['negative']}>{$lang->show_negative}</option>
		</select>
		<select name="sort">
			<option value="dateline" {$sort_selected['last_updated']}>{$lang->sort_updated}</option>
			<option value="username" {$sort_selected['username']}>{$lang->sort_username}</option>
		</select>
		{$gobutton}
	</form>
	</td>
</tr>
</table>
{$multipage}
{$footer}
</body>
</html>]]></template>
		<template name="showthread" version="1812"><![CDATA[<html>
<head>
<title>{$thread['subject']}</title>
{$headerinclude}
<script type="text/javascript">
<!--
	var quickdelete_confirm = "{$lang->quickdelete_confirm}";
	var quickrestore_confirm = "{$lang->quickrestore_confirm}";
	var allowEditReason = "{$mybb->settings['alloweditreason']}";
	lang.save_changes = "{$lang->save_changes}";
	lang.cancel_edit = "{$lang->cancel_edit}";
	lang.quick_edit_update_error = "{$lang->quick_edit_update_error}";
	lang.quick_reply_post_error = "{$lang->quick_reply_post_error}";
	lang.quick_delete_error = "{$lang->quick_delete_error}";
	lang.quick_delete_success = "{$lang->quick_delete_success}";
	lang.quick_delete_thread_success = "{$lang->quick_delete_thread_success}";
	lang.quick_restore_error = "{$lang->quick_restore_error}";
	lang.quick_restore_success = "{$lang->quick_restore_success}";
	lang.editreason = "{$lang->postbit_editreason}";
// -->
</script>
<!-- jeditable (jquery) -->
<script type="text/javascript" src="{$mybb->asset_url}/jscripts/report.js?ver=1804"></script>
<script src="{$mybb->asset_url}/jscripts/jeditable/jeditable.min.js"></script>
<script type="text/javascript" src="{$mybb->asset_url}/jscripts/thread.js?ver=1808"></script>
</head>
<body>
	{$header}
	{$threadnotesbox}
	{$pollbox}
	<div class="float_left">
		{$multipage}
	</div>
	<div class="float_right">
		{$newreply}
	</div>
	{$ratethread}
	<table border="0" cellspacing="{$theme['borderwidth']}" cellpadding="{$theme['tablespace']}" class="tborder tfixed clear" style="background:#444;">
		<tr>
			<td class="thead">
				<div class="float_right">
					<span class="smalltext"><strong><a href="javascript:;" id="thread_modes">{$lang->thread_modes}</a>{$threadnoteslink}</strong></span>
				</div>
				<div>
					<strong>{$thread['threadprefix']}{$thread['subject']}</strong>
				</div>
			</td>
		</tr>
<tr><td id="posts_container">
	<div id="posts">
		{$posts}
	</div>
</td></tr>
		<tr>
			<td class="tfoot">
				{$search_thread}
				<div>
					<strong>&laquo; <a href="{$next_oldest_link}">{$lang->next_oldest}</a> | <a href="{$next_newest_link}">{$lang->next_newest}</a> &raquo;</strong>
				</div>
			</td>
		</tr>
	</table>
	<div class="float_left">
{$multipage}
</div>
<div style="padding-top: 4px;" class="float_right">
<div id="slidetoggle"><i class="fa fa-wrench" aria-hidden="true"></i> Topic Options</div>{$newreply}
</div>    
<div id="slidepanel">    <div class="float_left">
<ul class="thread_tools">
<li class="printable"><a href="printthread.php?tid={$tid}">{$lang->view_printable}</a></li>
{$sendthread}
<li class="subscription_{$add_remove_subscription}"><a href="usercp2.php?action={$add_remove_subscription}subscription&amp;tid={$tid}&amp;my_post_key={$mybb->post_code}">{$add_remove_subscription_text}</a></li>
{$addpoll}
</ul>
</div>
<div class="float_right" style="text-align: right;">
{$moderationoptions}
{$forumjump}</div>
</div>
<br class="clear" />
{$quickreply}
{$threadexbox}
{$similarthreads}
<br />    
<br class="clear" />
{$usersbrowsing}
</div>{$footer}</div>
<div id="thread_modes_popup" class="popup_menu" style="display: none;"><div class="popup_item_container"><a href="showthread.php?mode=linear&amp;tid={$tid}&amp;pid={$pid}#pid{$pid}" class="popup_item">{$lang->linear}</a></div><div class="popup_item_container"><a href="showthread.php?mode=threaded&amp;tid={$tid}&amp;pid={$pid}#pid{$pid}" class="popup_item">{$lang->threaded}</a></div></div>
<script type="text/javascript">
// <!--
if(use_xmlhttprequest == "1")
{
$("#thread_modes").popupMenu();
}
// -->
</script>
<script type="text/javascript">
$(".author_avatar img").error(function () {
$(this).unbind("error").closest('.author_avatar').remove();
});
</script>
</body>
</html>
<script>
$(document).ready(function(){
 $("#slidetoggle").click(function(){
   $("#slidepanel").fadeToggle(700);
 });
});</script>
<style>
#slidetoggle{padding: 5.4px 15px; background: #222;color:#f5f5f5;cursor:pointer;display:inline-block;border-radius:5px;    }
#slidetoggle:hover {color:#f5f4f9;background-color:#000;border-color:#222;opacity: 0.6;-webkit-transition: all 250ms ease-in-out;-moz-transition: all 250ms ease-in-out;-o-transition: all 250ms ease-in-out;transition: all 250ms ease-in-out;    }
#slidepanel{display:none;text-align:left;    padding:65px 20px}
</style>
</body>
</html>]]></template>
		<template name="showthread_quickreply" version="1809"><![CDATA[
<div id="quickreply_spinner" class="showthread_spinner" style="display: none"><img src="{$theme['imgdir']}/spinner.gif" /></div>
<br />
{$moderation_notice}
<form method="post" action="newreply.php?tid={$tid}&amp;processed=1" name="quick_reply_form" id="quick_reply_form">
	<input type="hidden" name="my_post_key" value="{$mybb->post_code}" />
	<input type="hidden" name="subject" value="RE: {$reply_subject}" />
	<input type="hidden" name="action" value="do_newreply" />
	<input type="hidden" name="posthash" value="{$posthash}" id="posthash" />
	<input type="hidden" name="quoted_ids" value="" id="quoted_ids" />
	<input type="hidden" name="lastpid" id="lastpid" value="{$last_pid}" />
	<input type="hidden" name="from_page" value="{$page}" />
	<input type="hidden" name="tid" value="{$tid}" />
	<input type="hidden" name="method" value="quickreply" />

	<table border="0" cellspacing="{$theme['borderwidth']}" cellpadding="{$theme['tablespace']}" class="tborder">
		<thead>
			<tr>
				<td class="thead{$collapsedthead['quickreply']}" colspan="2">
					<div class="expcolimage"><img src="{$theme['imgdir']}/collapse{$collapsedimg['quickreply']}.png" id="quickreply_img" class="expander" alt="[-]" title="[-]" /></div>
					<div><strong>{$lang->quick_reply}</strong></div>
				</td>
			</tr>
		</thead>
		<tbody style="{$collapsed['quickreply_e']}" id="quickreply_e">
			<tr>
				<td class="{$trow}" valign="top" width="22%">
					<strong>{$lang->message}</strong><br />
					<span class="smalltext">{$lang->message_note}<br /><br />
					{$option_signature}
					<label><input type="checkbox" class="checkbox" name="postoptions[disablesmilies]" value="1" />&nbsp;<strong>{$lang->disable_smilies}</strong></label>{$closeoption}</span>
				</td>
				<td class="{$trow}">
					<div style="width: 95%">
						<textarea style="width: 100%; padding: 4px; margin: 0;" rows="8" cols="80" name="message" id="message" tabindex="1"></textarea>
					</div>
					<div class="editor_control_bar" style="width: 95%; padding: 4px; margin-top: 3px; display: none;" id="quickreply_multiquote">
						<span class="smalltext">
							{$lang->quickreply_multiquote_selected} <a href="./newreply.php?tid={$tid}&amp;load_all_quotes=1" onclick="return Thread.loadMultiQuoted();">{$lang->quickreply_multiquote_now}</a> {$lang->or} <a href="javascript:void(0)" onclick="Thread.clearMultiQuoted(); return false;">{$lang->quickreply_multiquote_deselect}</a>.
						</span>
					</div>
				</td>
			</tr>
			{$captcha}
			<tr>
				<td colspan="2" align="center" class="tfoot"><input type="submit" class="button" value="{$lang->post_reply}" tabindex="2" accesskey="s" id="quick_reply_submit" /> <input type="submit" class="button" name="previewpost" value="{$lang->preview_post}" tabindex="3" /></td>
			</tr>
		</tbody>
	</table>
</form>]]></template>
		<template name="stats" version="1808"><![CDATA[<html>
<head>
<title>{$mybb->settings['bbname']} - {$lang->board_stats}</title>
{$headerinclude}
</head>
<body>
{$header}
<table border="0" cellspacing="{$theme['borderwidth']}" cellpadding="{$theme['tablespace']}" class="tborder">
<tr>
<td class="thead" colspan="2"><strong>{$lang->board_stats}</strong></td>
</tr>
<tr>
<td class="tcat" width="50%"><strong>{$lang->totals}</strong></td>
<td class="tcat" width="50%"><strong>{$lang->averages}</strong></td>
</tr>
<tr>
<td class="trow1" valign="top">
{$lang->posts} <strong>{$stats['numposts']}</strong><br />
{$lang->threads} <strong>{$stats['numthreads']}</strong><br />
{$lang->members} <strong>{$stats['numusers']}</strong>
</td>
<td class="trow1" rowspan="3" valign="top">
{$lang->ppd} <strong>{$postsperday}</strong><br />
{$lang->tpd} <strong>{$threadsperday}</strong><br />
{$lang->mpd} <strong>{$membersperday}</strong><br />
{$lang->ppm} <strong>{$postspermember}</strong><br />
{$lang->tpm} <strong>{$threadspermember}</strong><br />
{$lang->rpt} <strong>{$repliesperthread}</strong>
</td>
</tr>
<tr>
<td class="tcat" valign="top"><strong>{$lang->general}</strong></td>
</tr>
<tr>
<td class="trow1">
{$lang->newest_member} {$stats['newest_user']}<br />
{$lang->members_posted} <strong>{$havepostedpercent}</strong><br />
{$lang->todays_top_poster}<br />
{$lang->popular_forum}<br />
{$top_referrer}
</td>
</tr>
</table>
{$footer}
</body>
</html>]]></template>
		<template name="usercp_nav_misc" version="1814"><![CDATA[<tbody>
<tr>
	<td class="tcat tcat_menu tcat_collapse{$collapsedimg['usercpmisc']}">
		<div class="expcolimage"><img src="{$theme['imgdir']}/collapse{$collapsedimg['usercpmisc']}.png" id="usercpmisc_img" class="expander" alt="[-]" title="[-]" /></div>
		<div><span class="smalltext"><strong>{$lang->ucp_nav_misc}</strong></span></div>
	</td>
</tr>
</tbody>
<tbody style="{$collapsed['usercpmisc_e']}" id="usercpmisc_e">{mysubscriptions_nav}
	<!--Invitation-->
	<tr><td class="trow1 smalltext"><a href="usercp.php?action=usergroups" class="usercp_nav_item usercp_nav_usergroups">{$lang->ucp_nav_usergroups}</a></td></tr>
	<tr><td class="trow1 smalltext"><a href="usercp.php?action=editlists" class="usercp_nav_item usercp_nav_editlists">{$lang->ucp_nav_editlists}</a></td></tr>
	{$attachmentop}
	<tr><td class="trow1 smalltext"><a href="usercp.php?action=drafts" class="usercp_nav_item usercp_nav_drafts">{$draftcount}</a></td></tr>
	<tr><td class="trow1 smalltext"><a href="usercp.php?action=subscriptions" class="usercp_nav_item usercp_nav_subscriptions">{$lang->ucp_nav_subscribed_threads}</a></td></tr>
	<tr><td class="trow1 smalltext"><a href="usercp.php?action=forumsubscriptions" class="usercp_nav_item usercp_nav_fsubscriptions">{$lang->ucp_nav_forum_subscriptions}</a></td></tr>
	<tr><td class="trow1 smalltext"><a href="{$profile_link}" class="usercp_nav_item usercp_nav_viewprofile">{$lang->ucp_nav_view_profile}</a></td></tr>
</tbody>]]></template>
	</templates>
</theme>
