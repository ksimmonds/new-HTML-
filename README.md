# new-HTML-
body {
	background: #fafafa url(http://jackrugile.com/images/misc/noise-diagonal.png);
	color: #444;
	font: 100%/30px 'Helvetica Neue', helvetica, arial, sans-serif;
	text-shadow: 0 1px 0 #fff;
}

strong {
	font-weight: bold; 
}

#top{
  margin-left: 30px;
  margin-top: 30px;
  font: helvetica, arial, sans-serif;
  font-size: 30px;
  color: #0040ff;
}

.sidebar-area{
   position: Relative;
   width: 21%;
   float: left;
}

.sidebar-areab{
   position: Absolute;
   margin-top: 130px;
   width: 21%;
   float: left;
}

.sidebar-areac{
   position: Absolute;
   margin-top: 260px;
   width: 21%;
   float: left;
}

.sidebar-aread{
   position: Absolute;
   margin-top: 390px;
   width: 21%;
   float: left;
}

.sidebar-areae{
   position: Absolute;
   margin-top: 520px;
   width: 21%;
   float: left;
}

.inner-area{
  font: arial, sans-serif;
  color: #404040;
  font-size: 18px;
  padding: 25px;
  margin: 30px;
  border: #ffff00 3px solid;
  min-height: 50px;
}

.clear-area{
  display: Inline;
  position: Absolute;
  clear: both;
  height: 1px;
  font-size: 1px;
  line-height: 1px;
  padding: 0;
  margin: 0;
}

p{
   margin-left:350px;
   font: helvetica, arial, sans-serif;
   color: #0040ff;
}

table {
	background: #f5f5f5;
	border-collapse: separate;
  box-shadow: inset 0 1px 0 #fff;
	font-size: 12px;
	line-height: 24px;
	margin-left: 350px;
	text-align: left;
	width: 1000px;
}	

.caption {
	 	display: Inline;
	 	width: 100%; 
	 	height: 50px;
	 	padding-left: 350px;
	 	color: #0040ff;
	 	font-size: 20px;
	 	line-height: 55px;
	 	text-shadow: 1px 1px 1px rgba(0,0,0,.3);
	 	box-sizing: border-box;
}

th {
	background: url(http://jackrugile.com/images/misc/noise-diagonal.png), linear-gradient(#0040ff, #00134d);
  border-left: 1px solid #555;
	border-right: 1px solid #777;
	border-top: 1px solid #555;
	border-bottom: 1px solid #333;
  box-shadow: inset 0 1px 0 #999;
	color: #fff;
  font-weight: bold;
	padding: 10px 15px;
	position: relative;
	text-shadow: 0 1px 0 #000;	
}

th:after {
	background: linear-gradient(rgba(255,255,255,0), rgba(255,255,255,.08));
  content: '';
	display: block;
	height: 25%;
	left: 0;
	margin: 1px 0 0 0;
	position: absolute;
	top: 25%;
	width: 100%;
}

th:first-child {
	border-left: 1px solid #777;	
	box-shadow: inset 1px 1px 0 #999;
}

th:last-child {
	box-shadow: inset -1px 1px 0 #999;
}

td {
	border-right: 1px solid #9494b8;
	border-left: 1px solid #9494b8;
	border-top: 1px solid #9494b8;
	border-bottom: 1px solid #9494b8;
	padding: 10px 15px;
	position: relative;
	transition: all 300ms;
}

td:first-child {
	box-shadow: inset 1px 0 0 #fff;
}	

td:last-child {
	border-right: 1px solid #9494b8;
	box-shadow: inset -1px 0 0 #fff;
}	

tr {
	background: url(http://jackrugile.com/images/misc/noise-diagonal.png);	
}

tr:nth-child(odd) td {
	background: #ffd9b3 url(http://jackrugile.com/images/misc/noise-diagonal.png);	
}

tbody:hover td {
	color: transparent;
	text-shadow: 0 0 3px #aaa;
}

tbody:hover tr:hover td {
	color: #444;
	text-shadow: 0 1px 0 #fff;
}

