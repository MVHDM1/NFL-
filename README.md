# NFL-
<html xmlns="http://www.w3.org/1999/xhtml"><head><meta http-equiv="Content-Type" content="text/html; charset=UTF-8"><meta content="IE=11.0000" http-equiv="X-UA-Compatible">
     <title></title>     
<link href="./nflschedulepicker_files/prettify.css" rel="stylesheet" type="text/css">     
<style type="text/css">
        #container{
            width:960px;
            margin:0 auto;
        }
        body{
            margin:0;
        }
        .button_up {
            padding: 2px;
            border: 1px outset;
        }

        .button_down {
            padding: 2px;
            border: 1px inset;
            font-weight: bold;
            background: buttonhighlight;
        }

        td.button_up {
            border: 1px;
            border-color: background;
            background: #dedede;
        }

        td.button_down {
            border: 1px;
            font-weight: bold;
            background: buttonhighlight;
        }

        .clip {
            position: absolute;
            top: 0;
            left: 0;
        }

        .m-icon {
            height: 34px;
            width: 34px;
            background-repeat: no-repeat;
        }

        .sp-mARI {
            background-position: 0 0;
        }

        .sp-mATL {
            background-position: 0 -35px;
        }

        .sp-mBAL {
            background-position: 0 -70px;
        }

        .sp-mBUF {
            background-position: 0 -105px;
        }

        .sp-mCAR {
            background-position: 0 -140px;
        }

        .sp-mCHI {
            background-position: 0 -175px;
        }

        .sp-mCIN {
            background-position: 0 -210px;
        }

        .sp-mCLE {
            background-position: 0 -245px;
        }

        .sp-mDAL {
            background-position: 0 -280px;
        }

        .sp-mDEN {
            background-position: 0 -315px;
        }

        .sp-mDET {
            background-position: 0 -350px;
        }

        .sp-mGB {
            background-position: 0 -385px;
        }

        .sp-mHOU {
            background-position: 0 -420px;
        }

        .sp-mIND {
            background-position: 0 -455px;
        }

        .sp-mJAC {
            background-position: 0 -490px;
        }

        .sp-mKC {
            background-position: 0 -525px;
        }

        .sp-mMIA {
            background-position: 0 -560px;
        }

        .sp-mMIN {
            background-position: 0 -595px;
        }

        .sp-mNE {
            background-position: 0 -630px;
        }

        .sp-mNO {
            background-position: 0 -665px;
        }

        .sp-mNYG {
            background-position: 0 -700px;
        }

        .sp-mNYJ {
            background-position: 0 -735px;
        }

        .sp-mOAK {
            background-position: 0 -770px;
        }

        .sp-mPHI {
            background-position: 0 -805px;
        }

        .sp-mPIT {
            background-position: 0 -840px;
        }

        .sp-mSD {
            background-position: 0 -875px;
        }

        .sp-mSEA {
            background-position: 0 -910px;
        }

        .sp-mSF {
            background-position: 0 -945px;
        }

        .sp-mSTL {
            background-position: 0 -980px;
        }

        .sp-mTB {
            background-position: 0 -1015px;
        }

        .sp-mTEN {
            background-position: 0 -1050px;
        }

        .sp-mWAS {
            background-position: 0 -1085px;
        }

        .DAL {
            background-color: #002244;
            color: #8c8b8a;
            border-color: #8c8b8a;
        }

        .NYG {
            background-color: #192F6B;
            color: #FFFFFF;
            border-color: #ca001a;
        }

        .PHI {
            background-color: #002f30;
            color: #c0c0c0;
            border-color: #c0c0c0;
        }

        .WAS {
            background-color: #773141;
            color: #ffb612;
            border-color: #ffb612;
        }

        .CHI {
            background-color: #03202f;
            color: #dd4814;
            border-color: #dd4814;
        }

        .DET {
            background-color: #006db0;
            color: #c5c7cf;
            border-color: #c5c7cf;
        }

        .GB {
            background-color: #213d30;
            color: #ffcc00;
            border-color: #ffcc00;
        }

        .MIN {
            background-color: #3b0160;
            color: #f0bf00;
            border-color: #f0bf00;
        }

        .ATL {
            background-color: #bd0d18;
            color: black;
            border-color: black;
        }

        .CAR {
            background-color: black;
            color: #0088ce;
            border-color: #0088ce;
        }

        .NO {
            background-color: black;
            color: #d2b887;
            border-color: #d2b887;
        }

        .TB {
            background-color: #b20032;
            color: white;
            border-color: black;
        }

        .ARI {
            background-color: #870619;
            color: white;
            border-color: black;
        }

        .STL {
            background-color: #13264b;
            color: #c9af74;
            border-color: #c9af74;
        }

        .SF {
            background-color: #af1e2c;
            color: #e6be8a;
            border-color: #e6be8a;
        }

        .SEA {
            background-color: #06192e;
            color: #4eae47;
            border-color: #4eae47;
        }

        .BUF {
            background-color: #00338d;
            color: white;
            border-color: #c60c30;
        }

        .MIA {
            background-color: #008d97;
            color: #f5811f;
            border-color: #f5811f;
        }

        .NE {
            background-color: #0d254c;
            color: #d6d6d6;
            border-color: #d6d6d6;
        }

        .NYJ {
            background-color: #0c371d;
            color: white;
            border-color: #0c371d;
        }

        .BAL {
            background-color: #280353;
            color: #d0b240;
            border-color: #d0b240;
        }

        .CIN {
            background-color: #fb4f14;
            color: white;
            border-color: black;
        }

        .CLE {
            background-color: #26201e;
            color: #e34912;
            border-color: #e34912;
        }

        .PIT {
            background-color: black;
            color: #f2c800;
            border-color: #f2c800;
        }

        .HOU {
            background-color: #02253a;
            color: white;
            border-color: #b31b34;
        }

        .IND {
            background-color: #003b7b;
            color: white;
            border-color: #003b7b;
        }

        .JAC {
            background-color: #007198;
            color: white;
            border-color: #d3a205;
        }

        .TEN {
            background-color: #648fcc;
            color: white;
            border-color: navy;
        }

        .DEN {
            background-color: #002244;
            color: #fb4f14;
            border-color: #fb4f14;
        }

        .KC {
            background-color: #b20032;
            color: #f2c800;
            border-color: #f2c800;
        }

        .OAK {
            background-color: black;
            color: #c4c8cb;
            border-color: #c4c8cb;
        }

        .SD {
            background-color: #0c2340;
            color: #ffb81c;
            border-color: #ffb81c;
        }

        .team-header {
            padding: 0px;
            text-align: center;
            font-size: 1.8em;
            font-family: sans-serif;
            font-weight: bold;
        }

        div.header_warning {
            background-color: #ccc;
        }

        table.conf_table {
            border-width: 1px;
            border-style: solid;
            font-size: 0.8125em;
            background-color: #fafafa;
        }

            table.conf_table th {
                border-width: 0px;
                text-align: center;
                padding: 1px;
                background-color: #aaa;
            }

        table.recordtable {
            font-size: 0.875em;
            color: black;
            background-color: #fafafa;
            border-collapse: collapse;
            border-width: 2px;
            border-style: solid;
            border-color: black;
        }

            table.recordtable th {
                border-right: 2px solid;
                background-color: #fafafa;
                color: black;
                padding: 0px 8px 0px 8px;
            }

            table.recordtable td {
                border-right: 2px solid;
                background-color: #fafafa;
                color: black;
                padding: 0px 8px 0px 8px;
            }

        table.gametable {
            font-family: serif;
            font-size: 0.875em;
            border-width: 2px;
            border-style: solid;
            background-color: #fafafa;
            color: black;
        }

            table.gametable th {
                text-align: center;
                padding: 4px;
                border-style: solid;
                border-width: 2px;
            }

        .transparent {
            background-color: transparent;
            border-color: transparent;
        }

        td.team-font {
            font-size: 0.75em;
            padding: 1px;
        }

        .not-selected {
            border-width: 2px;
            border-color: #d5d5d5;
            border-style: dashed;
        }

        .tied-team {
            border-width: 2px;
            border-color: red;
            border-style: solid;
            color: #6a6a6a;
            font-size: 0.75em;
            font-style: italic;
        }

        .anti-selected {
            border-width: 2px;
            border-color: transparent;
            border-style: solid;
            color: #656565;
            filter: alpha(opacity=60);
            -moz-opacity: 0.6;
            -khtml-opacity: 0.6;
            opacity: 0.6;
        }

        .selected {
            border-width: 2px;
            border-style: solid;
            font-weight: bold;
            font-style: italic;
        }

        .other-team-tab {
            background-color: #ddd;
            border-color: black;
        }

        .tied-tie {
            color: white;
            background-color: red;
            border-color: #922;
        }

        .tied-team {
            filter: alpha(opacity=80);
            -moz-opacity: 0.8;
            -khtml-opacity: 0.8;
            opacity: 0.8;
            background-color: #eee;
        }

        .byeweek {
            text-align: center;
            font-weight: bold;
            font-style: italic;
            height: 42;
        }

        .bye_header {
            padding: 3px;
            font-family: serif;
            font-size: 0.875em;
            font-style: italic;
            background-color: #eee;
            color: black;
        }

        div.save_footer {
            font-weight: bold;
            font-size: 1.2em;
        }

        span.unpicked-warning {
            color: brown;
        }
    </style>
 
<meta name="GENERATOR" content="MSHTML 11.00.9600.17496"></head> 
<body>
<div id="container">
<div class="header_warning" id="header">
<h3 style="margin: 0px auto;">NFL Predictor, originally by Clinton Morell        
         
<input class="button_up" id="help-button" onclick="show_help()" type="button" value="Help"> 
                <input class="button_up" id="reset-button" onclick="    reset_button()" type="button" value="Reset all games"> 
            </h3>            Go to week:             <input class="button_up" id="week-1-button" onclick="    show_week_tab('week-1')" type="button" value="1"> 
            <input class="button_up" id="week-2-button" onclick="    show_week_tab('week-2')" type="button" value="2"> 
            <input class="button_up" id="week-3-button" onclick="    show_week_tab('week-3')" type="button" value="3"> 
            <input class="button_up" id="week-4-button" onclick="    show_week_tab('week-4')" type="button" value="4"> 
            <input class="button_up" id="week-5-button" onclick="    show_week_tab('week-5')" type="button" value="5"> 
            <input class="button_up" id="week-6-button" onclick="    show_week_tab('week-6')" type="button" value="6"> 
            <input class="button_up" id="week-7-button" onclick="    show_week_tab('week-7')" type="button" value="7"> 
            <input class="button_up" id="week-8-button" onclick="    show_week_tab('week-8')" type="button" value="8"> 
            <input class="button_up" id="week-9-button" onclick="    show_week_tab('week-9')" type="button" value="9"> 
            <input class="button_up" id="week-10-button" onclick="    show_week_tab('week-10')" type="button" value="10"> 
            <input class="button_up" id="week-11-button" onclick="    show_week_tab('week-11')" type="button" value="11"> 
            <input class="button_up" id="week-12-button" onclick="    show_week_tab('week-12')" type="button" value="12"> 
            <input class="button_up" id="week-13-button" onclick="    show_week_tab('week-13')" type="button" value="13"> 
            <input class="button_up" id="week-14-button" onclick="    show_week_tab('week-14')" type="button" value="14"> 
            <input class="button_up" id="week-15-button" onclick="    show_week_tab('week-15')" type="button" value="15"> 
            <input class="button_up" id="week-16-button" onclick="    show_week_tab('week-16')" type="button" value="16"> 
            <input class="button_up" id="week-17-button" onclick="    show_week_tab('week-17')" type="button" value="17"> 
            <br></div>
<div style="float: left;">
<table class="conf_table" id="AFC-table">
  <tbody>
  <tr>
    <th>#</th>
    <th>AFC East</th>
    <th>WLT</th>
    <th>Div</th>
    <th style="display: none;"></th></tr>
  
  
  <tr onclick="show_team_tab('BUF')">
    <td id="BUF-conf-rank">3</td>
    <td id="BUF-button" class="button_up">Buffalo</td>
    <td id="BUF-WLT">0-0</td>
    <td id="BUF-div">0-0</td>
    <td id="BUF-div-rank" style="display: none;">1</td></tr><tr onclick="show_team_tab('MIA')">
    <td id="MIA-conf-rank"></td>
    <td id="MIA-button" class="button_up">Miami</td>
    <td id="MIA-WLT">0-0</td>
    <td id="MIA-div">0-0</td>
    <td id="MIA-div-rank" style="display: none;">2</td></tr><tr onclick="show_team_tab('NE')">
    <td id="NE-conf-rank"></td>
    <td id="NE-button" class="button_down">New England</td>
    <td id="NE-WLT">0-0</td>
    <td id="NE-div">0-0</td>
    <td id="NE-div-rank" style="display: none;">3</td></tr><tr onclick="show_team_tab('NYJ')">
    <td id="NYJ-conf-rank"></td>
    <td id="NYJ-button" class="button_up">NY Jets</td>
    <td id="NYJ-WLT">0-0</td>
    <td id="NYJ-div">0-0</td>
    <td id="NYJ-div-rank" style="display: none;">4</td></tr>
  
  <tr>
    <th>#</th>
    <th>AFC North</th>
    <th>WLT</th>
    <th>Div</th>
    <th style="display: none;"></th></tr>
  
  <tr onclick="show_team_tab('BAL')">
    <td id="BAL-conf-rank">2</td>
    <td id="BAL-button" class="button_up">Baltimore</td>
    <td id="BAL-WLT">0-0</td>
    <td id="BAL-div">0-0</td>
    <td id="BAL-div-rank" style="display: none;">1</td></tr><tr onclick="show_team_tab('CIN')">
    <td id="CIN-conf-rank">5</td>
    <td id="CIN-button" class="button_up">Cincinnati</td>
    <td id="CIN-WLT">0-0</td>
    <td id="CIN-div">0-0</td>
    <td id="CIN-div-rank" style="display: none;">2</td></tr><tr onclick="show_team_tab('CLE')">
    <td id="CLE-conf-rank">6</td>
    <td id="CLE-button" class="button_up">Cleveland</td>
    <td id="CLE-WLT">0-0</td>
    <td id="CLE-div">0-0</td>
    <td id="CLE-div-rank" style="display: none;">3</td></tr><tr onclick="show_team_tab('PIT')">
    <td id="PIT-conf-rank"></td>
    <td id="PIT-button" class="button_up">Pittsburgh</td>
    <td id="PIT-WLT">0-0</td>
    <td id="PIT-div">0-0</td>
    <td id="PIT-div-rank" style="display: none;">4</td></tr>
  
  
  <tr>
    <th>#</th>
    <th>AFC South</th>
    <th>WLT</th>
    <th>Div</th>
    <th style="display: none;"></th></tr>
  
  <tr onclick="show_team_tab('HOU')">
    <td id="HOU-conf-rank">1</td>
    <td id="HOU-button" class="button_up">Houston</td>
    <td id="HOU-WLT">0-0</td>
    <td id="HOU-div">0-0</td>
    <td id="HOU-div-rank" style="display: none;">1</td></tr><tr onclick="show_team_tab('IND')">
    <td id="IND-conf-rank"></td>
    <td id="IND-button" class="button_up">Indianapolis</td>
    <td id="IND-WLT">0-0</td>
    <td id="IND-div">0-0</td>
    <td id="IND-div-rank" style="display: none;">2</td></tr><tr onclick="show_team_tab('JAC')">
    <td id="JAC-conf-rank"></td>
    <td id="JAC-button" class="button_up">Jacksonville</td>
    <td id="JAC-WLT">0-0</td>
    <td id="JAC-div">0-0</td>
    <td id="JAC-div-rank" style="display: none;">3</td></tr><tr onclick="show_team_tab('TEN')">
    <td id="TEN-conf-rank"></td>
    <td id="TEN-button" class="button_up">Tennessee</td>
    <td id="TEN-WLT">0-0</td>
    <td id="TEN-div">0-0</td>
    <td id="TEN-div-rank" style="display: none;">4</td></tr>
  
  
  <tr>
    <th>#</th>
    <th>AFC West</th>
    <th>WLT</th>
    <th>Div</th>
    <th style="display: none;"></th></tr>
  
  <tr onclick="show_team_tab('DEN')">
    <td id="DEN-conf-rank">4</td>
    <td id="DEN-button" class="button_up">Denver</td>
    <td id="DEN-WLT">0-0</td>
    <td id="DEN-div">0-0</td>
    <td id="DEN-div-rank" style="display: none;">1</td></tr><tr onclick="show_team_tab('KC')">
    <td id="KC-conf-rank"></td>
    <td id="KC-button" class="button_up">Kansas City</td>
    <td id="KC-WLT">0-0</td>
    <td id="KC-div">0-0</td>
    <td id="KC-div-rank" style="display: none;">2</td></tr><tr onclick="show_team_tab('OAK')">
    <td id="OAK-conf-rank"></td>
    <td id="OAK-button" class="button_up">Oakland</td>
    <td id="OAK-WLT">0-0</td>
    <td id="OAK-div">0-0</td>
    <td id="OAK-div-rank" style="display: none;">3</td></tr>
  
  <tr onclick="show_team_tab('SD')">
    <td id="SD-conf-rank"></td>
    <td id="SD-button" class="button_up">San Diego</td>
    <td id="SD-WLT">0-0</td>
    <td id="SD-div">0-0</td>
    <td id="SD-div-rank" style="display: none;">4</td></tr></tbody></table></div>
<div id="autogen_tab" style="padding: 4px; float: left; display: block;" class="NE"><div><div class="m-icon sp-mNE" style="float: left"></div><div class="team-header" style="float: left">&nbsp;NEW ENGLAND&nbsp;<br>PATRIOTS&nbsp;</div><div class="m-icon sp-mNE" style="float: left"></div><table class="recordtable" style="float: right"><tbody><tr><th>WLT</th><th>Div</th><th>Conf</th></tr><tr><td id="team-WLT">0-0</td><td id="team-div">0-0</td><td id="team-conf">0-0</td></tr><tr><th>SOV</th><th>SOS</th><th></th></tr><tr><td id="team-SOV">0.000</td><td id="team-SOS">0.000</td><td></td></tr></tbody></table></div><div style="clear:both"><br></div><div style="float:left"><table class="gametable NE"><tbody><tr><th class="transparent"></th><th class="NE">Away</th><th class="transparent"></th><th class="NE">Home</th><th class="transparent"></th></tr><tr><td>1 </td><td id="NE-NYG-away-td" onclick="wgc( 'NE-NYG', 1)" class="team-font not-selected"><div class="m-icon sp-mNE" style="float: left"></div><div style="float:right;padding:3px">NE<br>&nbsp;</div></td><td title="Click = to predict a tie." id="NE-NYG-tie-td" onclick="wgc( 'NE-NYG', 3)" class="not-selected">&nbsp;=&nbsp;</td><td id="NE-NYG-home-td" onclick="wgc( 'NE-NYG', 2)" class="team-font not-selected"><div style="float:left;padding:3px">NYG<br>&nbsp;</div><div class="m-icon sp-mNYG" style="float: right"></div></td></tr><tr><td>2 </td><td id="MIA-NE-away-td" onclick="wgc( 'MIA-NE', 1)" class="team-font not-selected"><div class="m-icon sp-mMIA" style="float: left"></div><div style="float:right;padding:3px">MIA<br>&nbsp;</div></td><td title="Click = to predict a tie." id="MIA-NE-tie-td" onclick="wgc( 'MIA-NE', 3)" class="not-selected">&nbsp;=&nbsp;</td><td id="MIA-NE-home-td" onclick="wgc( 'MIA-NE', 2)" class="team-font not-selected"><div style="float:left;padding:3px">NE<br>&nbsp;</div><div class="m-icon sp-mNE" style="float: right"></div></td></tr><tr><td>3 </td><td id="NE-NYJ-away-td" onclick="wgc( 'NE-NYJ', 1)" class="team-font not-selected"><div class="m-icon sp-mNE" style="float: left"></div><div style="float:right;padding:3px">NE<br>&nbsp;</div></td><td title="Click = to predict a tie." id="NE-NYJ-tie-td" onclick="wgc( 'NE-NYJ', 3)" class="not-selected">&nbsp;=&nbsp;</td><td id="NE-NYJ-home-td" onclick="wgc( 'NE-NYJ', 2)" class="team-font not-selected"><div style="float:left;padding:3px">NYJ<br>&nbsp;</div><div class="m-icon sp-mNYJ" style="float: right"></div></td></tr><tr><td>4 </td><td id="WAS-NE-away-td" onclick="wgc( 'WAS-NE', 1)" class="team-font not-selected"><div class="m-icon sp-mWAS" style="float: left"></div><div style="float:right;padding:3px">WAS<br>&nbsp;</div></td><td title="Click = to predict a tie." id="WAS-NE-tie-td" onclick="wgc( 'WAS-NE', 3)" class="not-selected">&nbsp;=&nbsp;</td><td id="WAS-NE-home-td" onclick="wgc( 'WAS-NE', 2)" class="team-font not-selected"><div style="float:left;padding:3px">NE<br>&nbsp;</div><div class="m-icon sp-mNE" style="float: right"></div></td></tr><tr><td>5 </td></tr><tr><td></td><td class="byeweek" colspan="3">Bye week</td></tr><tr><td>6 </td><td id="NE-BUF-away-td" onclick="wgc( 'NE-BUF', 1)" class="team-font not-selected"><div class="m-icon sp-mNE" style="float: left"></div><div style="float:right;padding:3px">NE<br>&nbsp;</div></td><td title="Click = to predict a tie." id="NE-BUF-tie-td" onclick="wgc( 'NE-BUF', 3)" class="not-selected">&nbsp;=&nbsp;</td><td id="NE-BUF-home-td" onclick="wgc( 'NE-BUF', 2)" class="team-font not-selected"><div style="float:left;padding:3px">BUF<br>&nbsp;</div><div class="m-icon sp-mBUF" style="float: right"></div></td><td title="Sunday game"> </td></tr></tbody></table></div><div style="float:left">&nbsp;&nbsp;&nbsp;&nbsp;</div><div style="float:left"><table class="gametable NE"><tbody><tr><th class="transparent"></th><th class="NE">Away</th><th class="transparent"></th><th class="NE">Home</th><th class="transparent"></th></tr><tr><td>7 </td><td id="NE-HOU-away-td" onclick="wgc( 'NE-HOU', 1)" class="team-font not-selected"><div class="m-icon sp-mNE" style="float: left"></div><div style="float:right;padding:3px">NE<br>&nbsp;</div></td><td title="Click = to predict a tie." id="NE-HOU-tie-td" onclick="wgc( 'NE-HOU', 3)" class="not-selected">&nbsp;=&nbsp;</td><td id="NE-HOU-home-td" onclick="wgc( 'NE-HOU', 2)" class="team-font not-selected"><div style="float:left;padding:3px">HOU<br>&nbsp;</div><div class="m-icon sp-mHOU" style="float: right"></div></td></tr><tr><td>8 </td><td id="NE-PHI-away-td" onclick="wgc( 'NE-PHI', 1)" class="team-font not-selected"><div class="m-icon sp-mNE" style="float: left"></div><div style="float:right;padding:3px">NE<br>&nbsp;</div></td><td title="Click = to predict a tie." id="NE-PHI-tie-td" onclick="wgc( 'NE-PHI', 3)" class="not-selected">&nbsp;=&nbsp;</td><td id="NE-PHI-home-td" onclick="wgc( 'NE-PHI', 2)" class="team-font not-selected"><div style="float:left;padding:3px">PHI<br>&nbsp;</div><div class="m-icon sp-mPHI" style="float: right"></div></td></tr><tr><td>9 </td><td id="DAL-NE-away-td" onclick="wgc( 'DAL-NE', 1)" class="team-font not-selected"><div class="m-icon sp-mDAL" style="float: left"></div><div style="float:right;padding:3px">DAL<br>&nbsp;</div></td><td title="Click = to predict a tie." id="DAL-NE-tie-td" onclick="wgc( 'DAL-NE', 3)" class="not-selected">&nbsp;=&nbsp;</td><td id="DAL-NE-home-td" onclick="wgc( 'DAL-NE', 2)" class="team-font not-selected"><div style="float:left;padding:3px">NE<br>&nbsp;</div><div class="m-icon sp-mNE" style="float: right"></div></td></tr><tr><td>10 </td><td id="NE-DEN-away-td" onclick="wgc( 'NE-DEN', 1)" class="team-font not-selected"><div class="m-icon sp-mNE" style="float: left"></div><div style="float:right;padding:3px">NE<br>&nbsp;</div></td><td title="Click = to predict a tie." id="NE-DEN-tie-td" onclick="wgc( 'NE-DEN', 3)" class="not-selected">&nbsp;=&nbsp;</td><td id="NE-DEN-home-td" onclick="wgc( 'NE-DEN', 2)" class="team-font not-selected"><div style="float:left;padding:3px">DEN<br>&nbsp;</div><div class="m-icon sp-mDEN" style="float: right"></div></td></tr><tr><td>11 </td><td id="NE-TEN-away-td" onclick="wgc( 'NE-TEN', 1)" class="team-font not-selected"><div class="m-icon sp-mNE" style="float: left"></div><div style="float:right;padding:3px">NE<br>&nbsp;</div></td><td title="Click = to predict a tie." id="NE-TEN-tie-td" onclick="wgc( 'NE-TEN', 3)" class="not-selected">&nbsp;=&nbsp;</td><td id="NE-TEN-home-td" onclick="wgc( 'NE-TEN', 2)" class="team-font not-selected"><div style="float:left;padding:3px">TEN<br>&nbsp;</div><div class="m-icon sp-mTEN" style="float: right"></div></td></tr><tr><td>12 </td><td id="JAC-NE-away-td" onclick="wgc( 'JAC-NE', 1)" class="team-font not-selected"><div class="m-icon sp-mJAC" style="float: left"></div><div style="float:right;padding:3px">JAC<br>&nbsp;</div></td><td title="Click = to predict a tie." id="JAC-NE-tie-td" onclick="wgc( 'JAC-NE', 3)" class="not-selected">&nbsp;=&nbsp;</td><td id="JAC-NE-home-td" onclick="wgc( 'JAC-NE', 2)" class="team-font not-selected"><div style="float:left;padding:3px">NE<br>&nbsp;</div><div class="m-icon sp-mNE" style="float: right"></div></td></tr></tbody></table></div><div style="float:left">&nbsp;&nbsp;&nbsp;&nbsp;</div><div style="float:left"><table class="gametable NE"><tbody><tr><th class="transparent"></th><th class="NE">Away</th><th class="transparent"></th><th class="NE">Home</th><th class="transparent"></th></tr><tr><td>13 </td><td id="IND-NE-away-td" onclick="wgc( 'IND-NE', 1)" class="team-font not-selected"><div class="m-icon sp-mIND" style="float: left"></div><div style="float:right;padding:3px">IND<br>&nbsp;</div></td><td title="Click = to predict a tie." id="IND-NE-tie-td" onclick="wgc( 'IND-NE', 3)" class="not-selected">&nbsp;=&nbsp;</td><td id="IND-NE-home-td" onclick="wgc( 'IND-NE', 2)" class="team-font not-selected"><div style="float:left;padding:3px">NE<br>&nbsp;</div><div class="m-icon sp-mNE" style="float: right"></div></td></tr><tr><td>14 </td><td id="NE-BUF-away-td" onclick="wgc( 'NE-BUF', 1)" class="team-font not-selected"><div class="m-icon sp-mNE" style="float: left"></div><div style="float:right;padding:3px">NE<br>&nbsp;</div></td><td title="Click = to predict a tie." id="NE-BUF-tie-td" onclick="wgc( 'NE-BUF', 3)" class="not-selected">&nbsp;=&nbsp;</td><td id="NE-BUF-home-td" onclick="wgc( 'NE-BUF', 2)" class="team-font not-selected"><div style="float:left;padding:3px">BUF<br>&nbsp;</div><div class="m-icon sp-mBUF" style="float: right"></div></td></tr><tr><td>15 </td><td id="CIN-NE-away-td" onclick="wgc( 'CIN-NE', 1)" class="team-font not-selected"><div class="m-icon sp-mCIN" style="float: left"></div><div style="float:right;padding:3px">CIN<br>&nbsp;</div></td><td title="Click = to predict a tie." id="CIN-NE-tie-td" onclick="wgc( 'CIN-NE', 3)" class="not-selected">&nbsp;=&nbsp;</td><td id="CIN-NE-home-td" onclick="wgc( 'CIN-NE', 2)" class="team-font not-selected"><div style="float:left;padding:3px">NE<br>&nbsp;</div><div class="m-icon sp-mNE" style="float: right"></div></td></tr><tr><td>16 </td><td id="NYJ-NE-away-td" onclick="wgc( 'NYJ-NE', 1)" class="team-font not-selected"><div class="m-icon sp-mNYJ" style="float: left"></div><div style="float:right;padding:3px">NYJ<br>&nbsp;</div></td><td title="Click = to predict a tie." id="NYJ-NE-tie-td" onclick="wgc( 'NYJ-NE', 3)" class="not-selected">&nbsp;=&nbsp;</td><td id="NYJ-NE-home-td" onclick="wgc( 'NYJ-NE', 2)" class="team-font not-selected"><div style="float:left;padding:3px">NE<br>&nbsp;</div><div class="m-icon sp-mNE" style="float: right"></div></td></tr><tr><td>17 </td><td id="NE-MIA-away-td" onclick="wgc( 'NE-MIA', 1)" class="team-font not-selected"><div class="m-icon sp-mNE" style="float: left"></div><div style="float:right;padding:3px">NE<br>&nbsp;</div></td><td title="Click = to predict a tie." id="NE-MIA-tie-td" onclick="wgc( 'NE-MIA', 3)" class="not-selected">&nbsp;=&nbsp;</td><td id="NE-MIA-home-td" onclick="wgc( 'NE-MIA', 2)" class="team-font not-selected"><div style="float:left;padding:3px">MIA<br>&nbsp;</div><div class="m-icon sp-mMIA" style="float: right"></div></td></tr></tbody></table></div></div>
<div id="help-tab" style="float: left; display: none;">
<h3>How to use: <em>mostly just click stuff...</em></h3>
<ul>
  <li>Click on numbered buttons at the top to change weeks.</li>
  <li>Click on the name of a team in the standings to display that team's<br>    
                  schedule.</li>
  <li>Click on the team you think will win.                     
  <ul>
    <li>Click the = on the middle for a tie.</li>
    <li>Click again to undo your prediction.</li></ul>
  </li><li><strong>Copy the URL at near the bottom.</strong>                         
  <ul>
    <li>It has all 256 of your predictions.</li>
    <li>Post it on Reddit.</li>
    <li>Tweet it.</li></ul></li>
  <li>Standings updated automatically.</li>
  <li>NFL tie-breakers implemented all the way to <em>Strength of Schedule</em>. 
                          <br>                        This should cover 99%+ of 
  realistic scenarioes.</li>
  </ul>
<h3>Known issues and quirks:</h3>
<ul>
  
  <li>Tiebreakers behave oddly when very few games picked.<br>
  <ul>
    <li>This is due to ties being broken by Strength of Schedule.</li>
    <li>Pick more games and the tiebreakers will settle down.</li></ul></li>
  <li>Point based tiebreakers NOT implemented.<br><em style="font-size: 0.8em;">Don't panic--tying division records AND conference 
  records AND Strength of Schedule<br>                        AND Strength of 
  Victory is nearly impossible.</em></li>
  <li>Coin-flip tiebreaker actually "which abbreviation comes first<br>          
            alphabetically".</li>
  <li>Data automatically saved in cookie--sometimes too automatically.<br>       
               Could use UI improvement.</li></ul></div>
<div style="float: left;">
<table class="conf_table" id="NFC-table">
  <tbody>
  <tr>
    <th>#</th>
    <th>NFC East</th>
    <th>WLT</th>
    <th>Div</th>
    <th style="display: none;"></th></tr>
  <tr onclick="show_team_tab('DAL')">
    <td id="DAL-conf-rank">5</td>
    <td id="DAL-button" class="button_up">Dallas</td>
    <td id="DAL-WLT">0-0</td>
    <td id="DAL-div">0-0</td>
    <td id="DAL-div-rank" style="display: none;">1</td></tr><tr onclick="show_team_tab('NYG')">
    <td id="NYG-conf-rank"></td>
    <td id="NYG-button" class="button_up">NY Giants</td>
    <td id="NYG-WLT">0-0</td>
    <td id="NYG-div">0-0</td>
    <td id="NYG-div-rank" style="display: none;">2</td></tr><tr onclick="show_team_tab('PHI')">
    <td id="PHI-conf-rank"></td>
    <td id="PHI-button" class="button_up">Philadelphia</td>
    <td id="PHI-WLT">0-0</td>
    <td id="PHI-div">0-0</td>
    <td id="PHI-div-rank" style="display: none;">3</td></tr><tr onclick="show_team_tab('WAS')">
    <td id="WAS-conf-rank"></td>
    <td id="WAS-button" class="button_up">Washington</td>
    <td id="WAS-WLT">0-0</td>
    <td id="WAS-div">0-0</td>
    <td id="WAS-div-rank" style="display: none;">4</td></tr>
  
  
  
  <tr>
    <th>#</th>
    <th>NFC North</th>
    <th>WLT</th>
    <th>Div</th>
    <th style="display: none;"></th></tr>
  <tr onclick="show_team_tab('CHI')">
    <td id="CHI-conf-rank"></td>
    <td id="CHI-button" class="button_up">Chicago</td>
    <td id="CHI-WLT">0-0</td>
    <td id="CHI-div">0-0</td>
    <td id="CHI-div-rank" style="display: none;">1</td></tr><tr onclick="show_team_tab('DET')">
    <td id="DET-conf-rank">6</td>
    <td id="DET-button" class="button_up">Detroit</td>
    <td id="DET-WLT">0-0</td>
    <td id="DET-div">0-0</td>
    <td id="DET-div-rank" style="display: none;">2</td></tr><tr onclick="show_team_tab('GB')">
    <td id="GB-conf-rank"></td>
    <td id="GB-button" class="button_up">Green Bay</td>
    <td id="GB-WLT">0-0</td>
    <td id="GB-div">0-0</td>
    <td id="GB-div-rank" style="display: none;">3</td></tr><tr onclick="show_team_tab('MIN')">
    <td id="MIN-conf-rank"></td>
    <td id="MIN-button" class="button_up">Minnesota</td>
    <td id="MIN-WLT">0-0</td>
    <td id="MIN-div">0-0</td>
    <td id="MIN-div-rank" style="display: none;">4</td></tr>
  
  
  
  <tr>
    <th>#</th>
    <th>NFC South</th>
    <th>WLT</th>
    <th>Div</th>
    <th style="display: none;"></th></tr>
  <tr onclick="show_team_tab('ATL')">
    <td id="ATL-conf-rank">3</td>
    <td id="ATL-button" class="button_up">Atlanta</td>
    <td id="ATL-WLT">0-0</td>
    <td id="ATL-div">0-0</td>
    <td id="ATL-div-rank" style="display: none;">1</td></tr>
  <tr onclick="show_team_tab('CAR')">
    <td id="CAR-conf-rank">5</td>
    <td id="CAR-button" class="button_up">Carolina</td>
    <td id="CAR-WLT">0-0</td>
    <td id="CAR-div">0-0</td>
    <td id="CAR-div-rank" style="display: none;">2</td></tr>
  <tr onclick="show_team_tab('NO')">
    <td id="NO-conf-rank"></td>
    <td id="NO-button" class="button_up">New Orleans</td>
    <td id="NO-WLT">0-0</td>
    <td id="NO-div">0-0</td>
    <td id="NO-div-rank" style="display: none;">3</td></tr>
  <tr onclick="show_team_tab('TB')">
    <td id="TB-conf-rank"></td>
    <td id="TB-button" class="button_up">Tampa Bay</td>
    <td id="TB-WLT">0-0</td>
    <td id="TB-div">0-0</td>
    <td id="TB-div-rank" style="display: none;">4</td></tr>
  <tr>
    <th>#</th>
    <th>NFC West</th>
    <th>WLT</th>
    <th>Div</th>
    <th style="display: none;"></th></tr>
  <tr onclick="show_team_tab('ARI')">
    <td id="ARI-conf-rank">2</td>
    <td id="ARI-button" class="button_up">Arizona</td>
    <td id="ARI-WLT">0-0</td>
    <td id="ARI-div">0-0</td>
    <td id="ARI-div-rank" style="display: none;">1</td></tr><tr onclick="show_team_tab('SEA')">
    <td id="SEA-conf-rank"></td>
    <td id="SEA-button" class="button_up">Seattle</td>
    <td id="SEA-WLT">0-0</td>
    <td id="SEA-div">0-0</td>
    <td id="SEA-div-rank" style="display: none;">2</td></tr>
  
  <tr onclick="show_team_tab('SF')">
    <td id="SF-conf-rank"></td>
    <td id="SF-button" class="button_up">San Francisco</td>
    <td id="SF-WLT">0-0</td>
    <td id="SF-div">0-0</td>
    <td id="SF-div-rank" style="display: none;">3</td></tr><tr onclick="show_team_tab('STL')">
    <td id="STL-conf-rank"></td>
    <td id="STL-button" class="button_up">St. Louis</td>
    <td id="STL-WLT">0-0</td>
    <td id="STL-div">0-0</td>
    <td id="STL-div-rank" style="display: none;">4</td></tr>
  </tbody></table></div>
<div class="save_footer" id="save_footer" style="clear: both;"><span class="unpicked-warning" id="unpicked-warning">You have many unpicked games. </span>URL save link is:<br><span id="save_string" style="font-size: 0.6em; font-weight: normal;">http://raylehnhoff.github.io/nflschedulepicker/?a=-AAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAA_</span> 
            
<h2>Reddit Markdown Export</h2>
<pre class="prettyprint prettyprinted" style="font-size: 8px;"><code id="markdownField">[Generated by the NFL Playoff Predictor](http://raylehnhoff.github.io/nflschedulepicker/?a=-AAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAA_)</code></pre></div>
<div class="header_warning" id="footer" style="text-align: center; clear: both;">            All team logos are belong 
to their respective teams. See <a href="http://nfl.com/">nfl.com</a> for details 
on that.<br>            Javascript code copyright © 2014 Clinton Morell, Raymond 
Lehnhoff         </div></div>
<script async="" src="//www.google-analytics.com/analytics.js"></script><script async="" src="file://www.google-analytics.com/analytics.js"></script><script async="" src="file://www.google-analytics.com/analytics.js"></script><script async="" src="file://www.google-analytics.com/analytics.js"></script><script async="" src="file://www.google-analytics.com/analytics.js"></script><script async="" src="file://www.google-analytics.com/analytics.js"></script><script src="./nflschedulepicker_files/jquery.js" type="text/javascript"></script>
     
<script src="./nflschedulepicker_files/prettify.js" type="text/javascript"></script>
     
<script src="./nflschedulepicker_files/n.js" type="text/javascript"></script>
     
<script>
        (function (i, s, o, g, r, a, m) {
            i['GoogleAnalyticsObject'] = r; i[r] = i[r] || function () {
                (i[r].q = i[r].q || []).push(arguments)
            }, i[r].l = 1 * new Date(); a = s.createElement(o),
            m = s.getElementsByTagName(o)[0]; a.async = 1; a.src = g; m.parentNode.insertBefore(a, m)
        })(window, document, 'script', '//www.google-analytics.com/analytics.js', 'ga');

        ga('create', 'UA-50019712-2', 'raylehnhoff.github.io');
        ga('send', 'pageview');

        $(document).ready(function () {
            markdownExport();
            prettyPrint();
            if (window.location.hash) {
                var team = window.location.hash.substring(1);
                if (NFL_teams.indexOf(team) != -1) {
                    show_team_tab(team);
                }
            }
        });

</script>
 
</body></html>
