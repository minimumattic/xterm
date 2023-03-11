# XTerm

my custom XTerm configuration

copy .Xresources file you want to use in your home/$user directory (name should be ".Xresources" so delete any naming ".xxxx" in ".Xresources.xxxx") and run "xrdb -merge ~/.Xresources" to merge.

DOS font "Perfect DOS VGA 437" can be downloaded from > https://laemeur.sdf.org/fonts/

Ubuntu fonts can be downloaded from > https://design.ubuntu.com/font

Windows Powershell default font: Consolas

Windows Terminal default font: Cascadia Code

VSCode default font: Droid Sans Mono


<div>
<html lang="en-US">

  <style>
    html {
    font-family: Sans;
    font-size: 10pt;
    margin: 0 200px 0 200px;
}

h4 {
    font-style: italic;
    text-decoration-line: underline;
}

table {
    font-family: Dejavu Sans Mono;
    border-collapse: collapse;
    border: 1px solid rgb(0,0,0);
    font-size: 0.8rem;
    margin: 0 0 50px 30px;
}

td, th {
    border: 1px solid rgb(0,0,0);
    padding: 10px 20px;
}

td {
    text-align: center;
}

/* ################### Default (White on Black) colors ################## */

td.defaultBackground {background: #000000;color: #fff;}
td.defaultFont {background: #ffffff;color: #000;}
td.defaultColor0 {background: #000000;color: #fff;}
td.defaultColor1 {background: #800000;color: #fff;}
td.defaultColor2 {background: #008000;color: #fff;}
td.defaultColor3 {background: #808000;color: #fff;}
td.defaultColor4 {background: #000080;color: #fff;}
td.defaultColor5 {background: #800080;color: #fff;}
td.defaultColor6 {background: #008080;color: #fff;}
td.defaultColor7 {background: #c0c0c0;color: #000;}
td.defaultColor8 {background: #808080;color: #fff;}
td.defaultColor9 {background: #ff0000;color: #fff;}
td.defaultColor10 {background: #00ff00;color: #000;}
td.defaultColor11 {background: #ffff00;color: #000;}
td.defaultColor12 {background: #0000ff;color: #fff;}
td.defaultColor13 {background: #ff00ff;color: #000;}
td.defaultColor14 {background: #00ffff;color: #000;}
td.defaultColor15 {background: #ffffff;color: #000;}

/* ################### Ubuntu colors ################## */

td.ubuntuBackground {background: #380c2a;color: #fff;}
td.ubuntuFont {background: #ffffff;color: #000;}
td.ubuntuColor0 {background: #171421;color: #fff;}
td.ubuntuColor1 {background: #c01c28;color: #fff;}
td.ubuntuColor2 {background: #26a269;color: #fff;}
td.ubuntuColor3 {background: #a2734c;color: #fff;}
td.ubuntuColor4 {background: #12488b;color: #fff;}
td.ubuntuColor5 {background: #a347ba;color: #fff;}
td.ubuntuColor6 {background: #2aa1b3;color: #fff;}
td.ubuntuColor7 {background: #d0cfcc;color: #000;}
td.ubuntuColor8 {background: #5e5c64;color: #fff;}
td.ubuntuColor9 {background: #f66151;color: #fff;}
td.ubuntuColor10 {background: #33da7a;color: #000;}
td.ubuntuColor11 {background: #e9ad0c;color: #000;}
td.ubuntuColor12 {background: #2a7bde;color: #fff;}
td.ubuntuColor13 {background: #c061cb;color: #fff;}
td.ubuntuColor14 {background: #33c7de;color: #000;}
td.ubuntuColor15 {background: #ffffff;color: #000;}

/* ################### DOS colors ################## */

td.dosBackground {background: #000000;color: #fff;}
td.dosFont {background: #aaaaaa;color: #000;}
td.dosColor0 {background: #000000;color: #fff;}
td.dosColor1 {background: #cd0000;color: #fff;}
td.dosColor2 {background: #00cd00;color: #fff;}
td.dosColor3 {background: #cdcd00;color: #fff;}
td.dosColor4 {background: #0000cd;color: #fff;}
td.dosColor5 {background: #cd00cd;color: #fff;}
td.dosColor6 {background: #00cdcd;color: #fff;}
td.dosColor7 {background: #c0c0c0;color: #000;}
td.dosColor8 {background: #7f7f7f;color: #fff;}
td.dosColor9 {background: #ff0000;color: #fff;}
td.dosColor10 {background: #00ff00;color: #000;}
td.dosColor11 {background: #ffff00;color: #000;}
td.dosColor12 {background: #0000ff;color: #fff;}
td.dosColor13 {background: #ff00ff;color: #fff;}
td.dosColor14 {background: #00ffff;color: #000;}
td.dosColor15 {background: #ffffff;color: #000;}

/* ################### VS Code colors ################## */

td.vscodeBackground {background: #1e1e1e;color: #fff;}
td.vscodeFont {background: #d4d4d4;color: #000;}
td.vscodeColor0 {background: #000000;color: #fff;}
td.vscodeColor1 {background: #c50f1f;color: #fff;}
td.vscodeColor2 {background: #16825d;color: #fff;}
td.vscodeColor3 {background: #d7ba7d;color: #fff;}
td.vscodeColor4 {background: #007acc;color: #fff;}
td.vscodeColor5 {background: #68217a;color: #fff;}
td.vscodeColor6 {background: #98c7e1;color: #fff;}
td.vscodeColor7 {background: #d4d4d4;color: #000;}
td.vscodeColor8 {background: #858585;color: #fff;}
td.vscodeColor9 {background: #da6771;color: #fff;}
td.vscodeColor10 {background: #6a9953;color: #000;}
td.vscodeColor11 {background: #ffd700;color: #000;}
td.vscodeColor12 {background: #04395e;color: #fff;}
td.vscodeColor13 {background: #d470d6;color: #fff;}
td.vscodeColor14 {background: #9cdcfe;color: #000;}
td.vscodeColor15 {background: #ffffff;color: #000;}

/* ################### Powershell colors ################## */

td.powershellBackground {background: rgb(01,36,86);color: #fff;}
td.powershellFont {background: #eeedf0;color: #000;}
td.powershellColor0 {background: #000000;color: #fff;}
td.powershellColor1 {background: #800000;color: #fff;}
td.powershellColor2 {background: #008000;color: #fff;}
td.powershellColor3 {background: #808000;color: #fff;}
td.powershellColor4 {background: #000080;color: #fff;}
td.powershellColor5 {background: #800080;color: #fff;}
td.powershellColor6 {background: #008080;color: #fff;}
td.powershellColor7 {background: #c0c0c0;color: #000;}
td.powershellColor8 {background: #808080;color: #fff;}
td.powershellColor9 {background: #ff0000;color: #fff;}
td.powershellColor10 {background: #00ff00;color: #000;}
td.powershellColor11 {background: #ffff00;color: #000;}
td.powershellColor12 {background: #0000ff;color: #fff;}
td.powershellColor13 {background: #ff00ff;color: #fff;}
td.powershellColor14 {background: #00ffff;color: #000;}
td.powershellColor15 {background: #ffffff;color: #000;}

/* ################### Windows Terminal (Campbell) colors ################## */

td.winterminalBackground {background: #0c0c0c;color: #fff;}
td.winterminalFont {background: #cccccc;color: #000;}
td.winterminalColor0 {background: #0c0c0c;color: #fff;}
td.winterminalColor1 {background: #c50f1f;color: #fff;}
td.winterminalColor2 {background: #13a10e;color: #fff;}
td.winterminalColor3 {background: #c19c00;color: #fff;}
td.winterminalColor4 {background: #0037da;color: #fff;}
td.winterminalColor5 {background: #881798;color: #fff;}
td.winterminalColor6 {background: #3a96dd;color: #fff;}
td.winterminalColor7 {background: #cccccc;color: #000;}
td.winterminalColor8 {background: #767676;color: #fff;}
td.winterminalColor9 {background: #e74856;color: #fff;}
td.winterminalColor10 {background: #16c60c;color: #000;}
td.winterminalColor11 {background: #f9f1a5;color: #000;}
td.winterminalColor12 {background: #3b78ff;color: #fff;}
td.winterminalColor13 {background: #b4009e;color: #fff;}
td.winterminalColor14 {background: #61d6d6;color: #000;}
td.winterminalColor15 {background: #f2f2f2;color: #000;}

/* ################### custom colors ################## */

td.customBackground {background: #000000;color: #fff;}
td.customFont {background: #a8a8a8;color: #000;}
td.customColor0 {background: #000000;color: #fff;}
td.customColor1 {background: #a80000;color: #fff;}
td.customColor2 {background: #00a800;color: #fff;}
td.customColor3 {background: #a85400;color: #fff;}
td.customColor4 {background: #0000a8;color: #fff;}
td.customColor5 {background: #a800a8;color: #fff;}
td.customColor6 {background: #00a8a8;color: #fff;}
td.customColor7 {background: #a8a8a8;color: #000;}
td.customColor8 {background: #545454;color: #fff;}
td.customColor9 {background: #fc5454;color: #fff;}
td.customColor10 {background: #54fc54;color: #000;}
td.customColor11 {background: #fcfc54;color: #000;}
td.customColor12 {background: #5454fc;color: #fff;}
td.customColor13 {background: #fc54fc;color: #fff;}
td.customColor14 {background: #54fcfc;color: #000;}
td.customColor15 {background: #fcfcfc;color: #000;}

/* ################### Monochrome (black on white) ################## */

td.monowhiteBackground {background: #ffffff;color: #000;}
td.monowhiteFont {background: #000000;color: #fff;}
td.monowhiteColor0 {background: #000000;color: #fff;}
td.monowhiteColor1 {background: #121212;color: #fff;}
td.monowhiteColor2 {background: #303030;color: #fff;}
td.monowhiteColor3 {background: #444444;color: #fff;}
td.monowhiteColor4 {background: #080808;color: #fff;}
td.monowhiteColor5 {background: #1c1c1c;color: #fff;}
td.monowhiteColor6 {background: #3a3a3a;color: #fff;}
td.monowhiteColor7 {background: #808080;color: #fff;}
td.monowhiteColor8 {background: #4e4e4e;color: #fff;}
td.monowhiteColor9 {background: #585858;color: #fff;}
td.monowhiteColor10 {background: #8a8a8a;color: #fff;}
td.monowhiteColor11 {background: #9e9e9e;color: #fff;}
td.monowhiteColor12 {background: #262626;color: #fff;}
td.monowhiteColor13 {background: #626262;color: #fff;}
td.monowhiteColor14 {background: #949494;color: #fff;}
td.monowhiteColor15 {background: #a8a8a8;color: #fff;}

/* ################### Monochrome (white on black) ################## */

td.monoblackBackground {background: #000000;color: #fff;}
td.monoblackFont {background: #ffffff;color: #000;}
td.monoblackColor0 {background: #6c6c6c;color: #000;}
td.monoblackColor1 {background: #808080;color: #000;}
td.monoblackColor2 {background: #a8a8a8;color: #000;}
td.monoblackColor3 {background: #b2b2b2;color: #000;}
td.monoblackColor4 {background: #767676;color: #000;}
td.monoblackColor5 {background: #949494;color: #000;}
td.monoblackColor6 {background: #9e9e9e;color: #000;}
td.monoblackColor7 {background: #d0d0d0;color: #000;}
td.monoblackColor8 {background: #bcbcbc;color: #000;}
td.monoblackColor9 {background: #c6c6c6;color: #000;}
td.monoblackColor10 {background: #dadada;color: #000;}
td.monoblackColor11 {background: #eeeeee;color: #000;}
td.monoblackColor12 {background: #8a8a8a;color: #000;}
td.monoblackColor13 {background: #c0c0c0;color: #000;}
td.monoblackColor14 {background: #e4e4e4;color: #000;}
td.monoblackColor15 {background: #ffffff;color: #000;}

/* ################### Monochrome (blueprint) ################## */

td.monoblueBackground {background: #005fd7;color: #fff;}
td.monoblueFont {background: #ffffff;color: #000;}
td.monoblueColor0 {background: #6c6c6c;color: #000;}
td.monoblueColor1 {background: #808080;color: #000;}
td.monoblueColor2 {background: #a8a8a8;color: #000;}
td.monoblueColor3 {background: #b2b2b2;color: #000;}
td.monoblueColor4 {background: #767676;color: #000;}
td.monoblueColor5 {background: #949494;color: #000;}
td.monoblueColor6 {background: #9e9e9e;color: #000;}
td.monoblueColor7 {background: #d0d0d0;color: #000;}
td.monoblueColor8 {background: #bcbcbc;color: #000;}
td.monoblueColor9 {background: #c6c6c6;color: #000;}
td.monoblueColor10 {background: #dadada;color: #000;}
td.monoblueColor11 {background: #eeeeee;color: #000;}
td.monoblueColor12 {background: #8a8a8a;color: #000;}
td.monoblueColor13 {background: #c0c0c0;color: #000;}
td.monoblueColor14 {background: #e4e4e4;color: #000;}
td.monoblueColor15 {background: #ffffff;color: #000;}

/* ################### Green Phosphor ################## */

td.greenBackground {background: #282828;color: #fff;}
td.greenFont {background: #00ff66;color: #000;}
td.greenColor0 {background: #282828;color: #fff;}
td.greenColor1 {background: #007f33;color: #fff;}
td.greenColor2 {background: #00cc51;color: #000;}
td.greenColor3 {background: #00e55b;color: #000;}
td.greenColor4 {background: #006628;color: #fff;}
td.greenColor5 {background: #007f33;color: #fff;}
td.greenColor6 {background: #00b247;color: #000;}
td.greenColor7 {background: #00cc51;color: #000;}
td.greenColor8 {background: #007f33;color: #fff;}
td.greenColor9 {background: #00993d;color: #fff;}
td.greenColor10 {background: #00e55b;color: #000;}
td.greenColor11 {background: #19ff75;color: #000;}
td.greenColor12 {background: #007f33;color: #fff;}
td.greenColor13 {background: #00b247;color: #fff;}
td.greenColor14 {background: #00e55b;color: #000;}
td.greenColor15 {background: #00ff66;color: #000;}

/* ################### Amber Phosphor ################## */

td.amberBackground {background: #282828;color: #fff;}
td.amberFont {background: #ffb000;color: #000;}
td.amberColor0 {background: #282828;color: #fff;}
td.amberColor1 {background: #7f5800;color: #fff;}
td.amberColor2 {background: #cc8c00;color: #000;}
td.amberColor3 {background: #e59e00;color: #000;}
td.amberColor4 {background: #664600;color: #fff;}
td.amberColor5 {background: #7f5800;color: #fff;}
td.amberColor6 {background: #b27b00;color: #000;}
td.amberColor7 {background: #cc8c00;color: #000;}
td.amberColor8 {background: #7f5800;color: #fff;}
td.amberColor9 {background: #996900;color: #fff;}
td.amberColor10 {background: #e59e00;color: #000;}
td.amberColor11 {background: #ffb719;color: #000;}
td.amberColor12 {background: #7f5800;color: #fff;}
td.amberColor13 {background: #b27b00;color: #fff;}
td.amberColor14 {background: #e59e00;color: #000;}
td.amberColor15 {background: #ffb000;color: #000;}

div {background: #282828;padding: 20px;margin: 0 0 50px 30px;}

p {font-size: 14pt;margin: 20px;}

p.amber {color: #ffb000;}
p.amberLt {color: #ffcc00;}
p.green1 {color: #33ff00;}
p.apple2 {color: #33ff33;}
p.green2 {color: #00ff33;}
p.apple2c {color: #66ff66;}
p.green3 {color: #00ff66;}
p.phosphorBackground {color: #aaa;}

table.phosphor {
    font-family: Sans;
    font-size: 14pt;
    margin: 0 0 20px 20px;
    border-collapse: collapse;
    border: none;
}

td.title {
    border: none;
    padding: 10px 20px;
    text-align: right;
}

td.content {
    border: none;
    padding: 10px 20px;
    text-align: right;
}

td.rgb {
    border: none;
    padding: 10px 20px;
    text-align: left;
}

tr.amber {color: #ffb000;}
tr.amberLt {color: #ffcc00;}
tr.green1 {color: #33ff00;}
tr.apple2 {color: #33ff33;}
tr.green2 {color: #00ff33;}
tr.apple2c {color: #66ff66;}
tr.green3 {color: #00ff66;}
tr.phosphorBackground {color: #aaa;}
  </style>
  
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width" />
  <link href="https://fonts.googleapis.com/css?family=Open+Sans+Condensed:300|Sonsie+One" rel="stylesheet" />
  <link rel="stylesheet" href="xterm/style.css" />
</head>

<body>

  <h1>XTerm custom color schemes</h1>

  <h4>Default (White on Black) colors:</h4>

  <table>

    <tr>
      <td class="defaultFont">font: <br> #ffffff</td>
      <td class="defaultColor0">color0: <br> black <br> #000000</td>
      <td class="defaultColor1">color1: <br> maroon <br> #800000</td>
      <td class="defaultColor2">color2: <br> green <br> #008000</td>
      <td class="defaultColor3">color3: <br> olive <br> #808000</td>
      <td class="defaultColor4">color4: <br> navy <br> #000080</td>
      <td class="defaultColor5">color5: <br> purple <br> #800080</td>
      <td class="defaultColor6">color6: <br> teal <br> #008080</td>
      <td class="defaultColor7">color7: <br> silver <br> #c0c0c0</td>
    </tr>
    <tr>
      <td class="defaultBackground">background: <br> #000000</td>
      <td class="defaultColor8">color8: <br> grey <br> #808080</td>
      <td class="defaultColor9">color9: <br> red <br> #ff0000</td>
      <td class="defaultColor10">color10: <br> lime <br> #00ff00</td>
      <td class="defaultColor11">color11: <br> yellow <br> #ffff00</td>
      <td class="defaultColor12">color12: <br> blue <br> #0000ff</td>
      <td class="defaultColor13">color13: <br> fuchsia <br> #ff00ff</td>
      <td class="defaultColor14">color14: <br> aqua <br> #00ffff</td>
      <td class="defaultColor15">color15: <br> white <br> #ffffff</td>
    </tr>

  </table>

  <h4>Ubuntu (GNOME 4x) colors:</h4>

  <table>

    <tr>
      <td class="ubuntuFont">font: <br> #ffffff</td>
      <td class="ubuntuColor0">color0: <br> #171421</td>
      <td class="ubuntuColor1">color1: <br> #c01c28</td>
      <td class="ubuntuColor2">color2: <br> #26a269</td>
      <td class="ubuntuColor3">color3: <br> #a2734c</td>
      <td class="ubuntuColor4">color4: <br> #12488b</td>
      <td class="ubuntuColor5">color5: <br> #a347ba</td>
      <td class="ubuntuColor6">color6: <br> #2aa1b3</td>
      <td class="ubuntuColor7">color7: <br> #d0cfcc</td>
    </tr>
    <tr>
      <td class="ubuntuBackground">background: <br> #380c2a</td>
      <td class="ubuntuColor8">color8: <br> #5e5c64</td>
      <td class="ubuntuColor9">color9: <br> #f66151</td>
      <td class="ubuntuColor10">color10: <br> #33da7a</td>
      <td class="ubuntuColor11">color11: <br> #e9ad0c</td>
      <td class="ubuntuColor12">color12: <br> #2a7bde</td>
      <td class="ubuntuColor13">color13: <br> #c061cb</td>
      <td class="ubuntuColor14">color14: <br> #33c7de</td>
      <td class="ubuntuColor15">color15: <br> #ffffff</td>
    </tr>

  </table>

  <h4>DOS colors:</h4>

  <table>

    <tr>
      <td class="dosFont">font: <br> #aaaaaa</td>
      <td class="dosColor0">color0: <br> #000000</td>
      <td class="dosColor1">color1: <br> #cd0000</td>
      <td class="dosColor2">color2: <br> #00cd00</td>
      <td class="dosColor3">color3: <br> #cdcd00</td>
      <td class="dosColor4">color4: <br> #0000cd</td>
      <td class="dosColor5">color5: <br> #cd00cd</td>
      <td class="dosColor6">color6: <br> #00cdcd</td>
      <td class="dosColor7">color7: <br> #c0c0c0</td>
    </tr>
    <tr>
      <td class="dosBackground">background: <br> #000000</td>
      <td class="dosColor8">color8: <br> #7f7f7f</td>
      <td class="dosColor9">color9: <br> #ff0000</td>
      <td class="dosColor10">color10: <br> #00ff00</td>
      <td class="dosColor11">color11: <br> #ffff00</td>
      <td class="dosColor12">color12: <br> #0000ff</td>
      <td class="dosColor13">color13: <br> #ff00ff</td>
      <td class="dosColor14">color14: <br> #00ffff</td>
      <td class="dosColor15">color15: <br> #ffffff</td>
    </tr>

  </table>

  <h4>VS Code colors:</h4>

  <table>

    <tr>
      <td class="vscodeFont">font: <br> #d4d4d4</td>
      <td class="vscodeColor0">color0: <br> #000000</td>
      <td class="vscodeColor1">color1: <br> #c50f1f</td>
      <td class="vscodeColor2">color2: <br> #16825d;</td>
      <td class="vscodeColor3">color3: <br> #d7ba7d</td>
      <td class="vscodeColor4">color4: <br> #007acc</td>
      <td class="vscodeColor5">color5: <br> #68217a</td>
      <td class="vscodeColor6">color6: <br> #98c7e1</td>
      <td class="vscodeColor7">color7: <br> #d4d4d4</td>
    </tr>
    <tr>
      <td class="vscodeBackground">background: <br> #1e1e1e</td>
      <td class="vscodeColor8">color8: <br> #858585</td>
      <td class="vscodeColor9">color9: <br> #da6771</td>
      <td class="vscodeColor10">color10: <br> #6a9953</td>
      <td class="vscodeColor11">color11: <br> #ffd700</td>
      <td class="vscodeColor12">color12: <br> #04395e</td>
      <td class="vscodeColor13">color13: <br> #d470d6</td>
      <td class="vscodeColor14">color14: <br> #9cdcfe</td>
      <td class="vscodeColor15">color15: <br> #ffffff</td>
    </tr>

  </table>

  <h4>Powershell colors:</h4>

  <table>

    <tr>
      <td class="powershellFont">font: <br> #eeedf0</td>
      <td class="powershellColor0">color0: <br> #000000</td>
      <td class="powershellColor1">color1: <br> #800000</td>
      <td class="powershellColor2">color2: <br> #008000</td>
      <td class="powershellColor3">color3: <br> #808000</td>
      <td class="powershellColor4">color4: <br> #000080</td>
      <td class="powershellColor5">color5: <br> #800080</td>
      <td class="powershellColor6">color6: <br> #008080</td>
      <td class="powershellColor7">color7: <br> #c0c0c0</td>
    </tr>
    <tr>
      <td class="powershellBackground">background: <br> #012456 <br> rgb 01,36,86</td>
      <td class="powershellColor8">color8: <br> #808080</td>
      <td class="powershellColor9">color9: <br> #ff0000</td>
      <td class="powershellColor10">color10: <br> #00ff00</td>
      <td class="powershellColor11">color11: <br> #ffff00</td>
      <td class="powershellColor12">color12: <br> #0000ff</td>
      <td class="powershellColor13">color13: <br> #ff00ff</td>
      <td class="powershellColor14">color14: <br> #00ffff</td>
      <td class="powershellColor15">color15: <br> #ffffff</td>
    </tr>

  </table>

  <h4>Windows Terminal (Campbell) colors:</h4>

  <table>

    <tr>
      <td class="winterminalFont">font: <br> #cccccc</td>
      <td class="winterminalColor0">color0: <br> #0c0c0c</td>
      <td class="winterminalColor1">color1: <br> #c50f1f</td>
      <td class="winterminalColor2">color2: <br> #13a10e</td>
      <td class="winterminalColor3">color3: <br> #c19c00</td>
      <td class="winterminalColor4">color4: <br> #0037da</td>
      <td class="winterminalColor5">color5: <br> #881798</td>
      <td class="winterminalColor6">color6: <br> #3a96dd</td>
      <td class="winterminalColor7">color7: <br> #cccccc</td>
    </tr>
    <tr>
      <td class="winterminalBackground">background: <br> #0c0c0c</td>
      <td class="winterminalColor8">color8: <br> #767676</td>
      <td class="winterminalColor9">color9: <br> #e74856</td>
      <td class="winterminalColor10">color10: <br> #16c60c</td>
      <td class="winterminalColor11">color11: <br> #f9f1a5</td>
      <td class="winterminalColor12">color12: <br> #3b78ff</td>
      <td class="winterminalColor13">color13: <br> #b4009e</td>
      <td class="winterminalColor14">color14: <br> #61d6d6</td>
      <td class="winterminalColor15">color15: <br> #f2f2f2</td>
    </tr>

  </table>

  <h4>custom colors:</h4>

  <table>

    <tr>
      <td class="customFont">font: <br> #a8a8a8</td>
      <td class="customColor0">color0: <br> #000000</td>
      <td class="customColor1">color1: <br> #a80000</td>
      <td class="customColor2">color2: <br> #00a800</td>
      <td class="customColor3">color3: <br> #a85400</td>
      <td class="customColor4">color4: <br> #0000a8</td>
      <td class="customColor5">color5: <br> #a800a8</td>
      <td class="customColor6">color6: <br> #00a8a8</td>
      <td class="customColor7">color7: <br> #a8a8a8</td>
    </tr>
    <tr>
      <td class="customBackground">background: <br> #000000</td>
      <td class="customColor8">color8: <br> #545454</td>
      <td class="customColor9">color9: <br> #fc5454</td>
      <td class="customColor10">color10: <br> #54fc54</td>
      <td class="customColor11">color11: <br> #fcfc54</td>
      <td class="customColor12">color12: <br> #5454fc</td>
      <td class="customColor13">color13: <br> #fc54fc</td>
      <td class="customColor14">color14: <br> #54fcfc</td>
      <td class="customColor15">color15: <br> #fcfcfc</td>
    </tr>

  </table>

  <h4>Monochrome (Black on White) colors:</h4>

  <table>

    <tr>
      <td class="monowhiteFont">font: <br> #000000</td>
      <td class="monowhiteColor0">color0: <br> #000000</td>
      <td class="monowhiteColor1">color1: <br> #121212</td>
      <td class="monowhiteColor2">color2: <br> #303030</td>
      <td class="monowhiteColor3">color3: <br> #444444</td>
      <td class="monowhiteColor4">color4: <br> #080808</td>
      <td class="monowhiteColor5">color5: <br> #1c1c1c</td>
      <td class="monowhiteColor6">color6: <br> #3a3a3a</td>
      <td class="monowhiteColor7">color7: <br> #808080</td>
    </tr>
    <tr>
      <td class="monowhiteBackground">background: <br> #ffffff</td>
      <td class="monowhiteColor8">color8: <br> #4e4e4e</td>
      <td class="monowhiteColor9">color9: <br> #585858</td>
      <td class="monowhiteColor10">color10: <br> #8a8a8a</td>
      <td class="monowhiteColor11">color11: <br> #9e9e9e</td>
      <td class="monowhiteColor12">color12: <br> #262626</td>
      <td class="monowhiteColor13">color13: <br> #626262</td>
      <td class="monowhiteColor14">color14: <br> #949494</td>
      <td class="monowhiteColor15">color15: <br> #a8a8a8</td>
    </tr>

  </table>

  <h4>Monochrome (White on Black) colors:</h4>

  <table>

    <tr>
      <td class="monoblackFont">font: <br> #ffffff</td>
      <td class="monoblackColor0">color0: <br> #6c6c6c</td>
      <td class="monoblackColor1">color1: <br> #808080</td>
      <td class="monoblackColor2">color2: <br> #a8a8a8</td>
      <td class="monoblackColor3">color3: <br> #b2b2b2</td>
      <td class="monoblackColor4">color4: <br> #767676</td>
      <td class="monoblackColor5">color5: <br> #949494</td>
      <td class="monoblackColor6">color6: <br> #9e9e9e</td>
      <td class="monoblackColor7">color7: <br> #d0d0d0</td>
    </tr>
    <tr>
      <td class="monoblackBackground">background: <br> #000000</td>
      <td class="monoblackColor8">color8: <br> #bcbcbc</td>
      <td class="monoblackColor9">color9: <br> #c6c6c6</td>
      <td class="monoblackColor10">color10: <br> #dadada</td>
      <td class="monoblackColor11">color11: <br> #eeeeee</td>
      <td class="monoblackColor12">color12: <br> #8a8a8a</td>
      <td class="monoblackColor13">color13: <br> #c0c0c0</td>
      <td class="monoblackColor14">color14: <br> #e4e4e4</td>
      <td class="monoblackColor15">color15: <br> #ffffff</td>
    </tr>

  </table>

  <h4>Monochrome (Blueprint) colors:</h4>

  <table>

    <tr>
      <td class="monoblueFont">font: <br> #ffffff</td>
      <td class="monoblueColor0">color0: <br> #6c6c6c</td>
      <td class="monoblueColor1">color1: <br> #808080</td>
      <td class="monoblueColor2">color2: <br> #a8a8a8</td>
      <td class="monoblueColor3">color3: <br> #b2b2b2</td>
      <td class="monoblueColor4">color4: <br> #767676</td>
      <td class="monoblueColor5">color5: <br> #949494</td>
      <td class="monoblueColor6">color6: <br> #9e9e9e</td>
      <td class="monoblueColor7">color7: <br> #d0d0d0</td>
    </tr>
    <tr>
      <td class="monoblueBackground">background: <br> #005fd7</td>
      <td class="monoblueColor8">color8: <br> #bcbcbc</td>
      <td class="monoblueColor9">color9: <br> #c6c6c6</td>
      <td class="monoblueColor10">color10: <br> #dadada</td>
      <td class="monoblueColor11">color11: <br> #eeeeee</td>
      <td class="monoblueColor12">color12: <br> #8a8a8a</td>
      <td class="monoblueColor13">color13: <br> #c0c0c0</td>
      <td class="monoblueColor14">color14: <br> #e4e4e4</td>
      <td class="monoblueColor15">color15: <br> #ffffff</td>
    </tr>

  </table>

  <h4>Green Phosphor:</h4>

  <table>

    <tr>
      <td class="greenFont">font: <br> #00ff66</td>
      <td class="greenColor0">color0: <br> #282828</td>
      <td class="greenColor1">color1: <br> #007f33</td>
      <td class="greenColor2">color2: <br> #00cc51</td>
      <td class="greenColor3">color3: <br> #e59e00</td>
      <td class="greenColor4">color4: <br> #006628</td>
      <td class="greenColor5">color5: <br> #007f33</td>
      <td class="greenColor6">color6: <br> #00b247</td>
      <td class="greenColor7">color7: <br> #00cc51</td>
    </tr>
    <tr>
      <td class="greenBackground">background: <br> #282828</td>
      <td class="greenColor8">color8: <br> #007f33</td>
      <td class="greenColor9">color9: <br> #00993d</td>
      <td class="greenColor10">color10: <br> #00e55b</td>
      <td class="greenColor11">color11: <br> #ffb719</td>
      <td class="greenColor12">color12: <br> #007f33</td>
      <td class="greenColor13">color13: <br> #b27b00</td>
      <td class="greenColor14">color14: <br> #00e55b</td>
      <td class="greenColor15">color15: <br> #00ff66</td>
    </tr>

  </table>

  <h4>Amber Phosphor:</h4>

  <table>

    <tr>
      <td class="amberFont">font: <br> #ffb000</td>
      <td class="amberColor0">color0: <br> #282828</td>
      <td class="amberColor1">color1: <br> #7f5800</td>
      <td class="amberColor2">color2: <br> #cc8c00</td>
      <td class="amberColor3">color3: <br> #00cdcd</td>
      <td class="amberColor4">color4: <br> #664600</td>
      <td class="amberColor5">color5: <br> #7f5800</td>
      <td class="amberColor6">color6: <br> #b27b00</td>
      <td class="amberColor7">color7: <br> #cc8c00</td>
    </tr>
    <tr>
      <td class="amberBackground">background: <br> #282828</td>
      <td class="amberColor8">color8: <br> #7f5800</td>
      <td class="amberColor9">color9: <br> #996900</td>
      <td class="amberColor10">color10: <br> #e59e00</td>
      <td class="amberColor11">color11: <br> #00ffff</td>
      <td class="amberColor12">color12: <br> #7f5800</td>
      <td class="amberColor13">color13: <br> #00cdcd</td>
      <td class="amberColor14">color14: <br> #e59e00</td>
      <td class="amberColor15">color15: <br> #ffb000</td>
    </tr>

  </table>

  <h4>Phosphor Color Codes:</h4>

<div class="phosphor">

 <table class="phosphor">

    <tr class="amber">
      <td class="title">Amber:</td>
      <td class="content">The quick brown fox jumps over the lazy dog.</td>
      <td class="rgb">RGB (255,176,0) = #ffb000 = 600 nm (P3)</td>
    </tr>
    <tr class="amberLt">
      <td class="title">Amber Lite:</td>
      <td class="content">The quick brown fox jumps over the lazy dog.</td>
      <td class="rgb">RGB (255,204,0) = #ffcc00 = 593 nm</td>
    </tr>
    <tr class="blank">
      <td class="title"></td>
      <td class="content"></td>
      <td class="rgb"></td>
    </tr>
    <tr class="green1">
      <td class="title">Green 1:</td>
      <td class="content">The quick brown fox jumps over the lazy dog.</td>
      <td class="rgb">RGB (51,255,0) = #33ff00 = 524 nm</td>
    </tr>
    <tr class="apple2">
      <td class="title">Apple ][:</td>
      <td class="content">The quick brown fox jumps over the lazy dog.</td>
      <td class="rgb">RGB (51,255,51) = #33ff33 (P1)</td>
    </tr>
    <tr class="green2">
      <td class="title">Green 2:</td>
      <td class="content">The quick brown fox jumps over the lazy dog.</td>
      <td class="rgb">RGB (0,255,51) = #00ff33 = 506 nm</td>
    </tr>
    <tr class="blank">
      <td class="title"></td>
      <td class="content"></td>
      <td class="rgb"></td>
    </tr>
    <tr class="apple2c">
      <td class="title">Apple //c:</td>
      <td class="content">The quick brown fox jumps over the lazy dog.</td>
      <td class="rgb">RGB (102,255,102) = #66ff66 (P24)</td>
    </tr>
    <tr class="green3">
      <td class="title">Green 3:</td>
      <td class="content">The quick brown fox jumps over the lazy dog.</td>
      <td class="rgb">RGB (0,255,102) = #00ff66 = 502 nm</td>
    </tr>
    <tr class="blank">
      <td class="title"></td>
      <td class="content"></td>
      <td class="rgb"></td>
    </tr>
    <tr class="phosphorBackground">
      <td class="title"></td>
      <td class="content">Background:</td>
      <td class="rgb">RGB (40,40,40) = #282828</td>
    </tr>

  </table>

</div>

</body>

</html>

</div>


#Screenshots:

default (256color):

![default](https://user-images.githubusercontent.com/72235930/217951637-c75feb1b-5c29-40e4-a06e-b80644427159.png)


Ubuntu (256color):

![ubuntu](https://user-images.githubusercontent.com/72235930/217951710-9476fb05-e288-40dd-a4d5-d70e018c8181.png)


DOS (256color):

![dos](https://user-images.githubusercontent.com/72235930/217951676-ca805c77-6683-49bc-b570-df5bacfa3550.png)


VS Code (256color):

![vscode](https://user-images.githubusercontent.com/72235930/217951853-2300510c-a99b-4ff1-8dae-89d1e7cd946f.png)


Windows Terminal (256color):

![winterminal](https://user-images.githubusercontent.com/72235930/217951932-8fbd8d17-cd42-4e4b-9dd2-661a0fc7f4f0.png)


Windows Powershell (256color):

![powershell](https://user-images.githubusercontent.com/72235930/217952104-d529aef6-555f-4d72-8230-5b0e2caf3215.png)


Custom:

![custom](https://user-images.githubusercontent.com/72235930/217980458-cf9386d0-d9a3-4d72-88cb-ecaf6f153e07.png)


Monochrome White (black on white - 16color):

![mono](https://user-images.githubusercontent.com/72235930/217970133-430364a5-166e-40d3-9dc3-be28d0eee4c8.png)


Monochrome Black (white on black - 16color):

![mono-black](https://user-images.githubusercontent.com/72235930/219065119-3aaf9066-6b5e-4ea5-8e96-6051096977a3.png)


Blueprint (16color):

![Screenshot from 2023-02-11 15-01-47](https://user-images.githubusercontent.com/72235930/218257345-bacec9d7-e498-409b-9c59-0e4588669fd5.png)


Green Phosphor (16color):

![green](https://user-images.githubusercontent.com/72235930/217970185-765ef17c-f884-4437-b031-45ad3d73ad81.png)

![Screenshot from 2023-02-10 14-52-22](https://user-images.githubusercontent.com/72235930/218086180-d5cd86b6-a797-4595-8912-9ada8dadf098.png)


Amber Phosphor (16color):

![amber](https://user-images.githubusercontent.com/72235930/217970216-c4fbc949-98bc-4c7d-8604-190c4214d26c.png)


