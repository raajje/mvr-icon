# mvr-icon

This repository contains the necessary files to integrate the `mvr` icon font into your website.

## Demo

You can preview the `mvr` icon font using the demo HTML provided in this repository. The demo showcases how to use the icons and provides a font test drive.

### Demo HTML

Here’s a snippet of the demo HTML file:

<!doctype html>
<html>
<head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <link rel="stylesheet" href="demo-files/demo.css">
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <div class="bgc1 clearfix">
        <h1 class="mhmm mvm"><span class="fgc1">Font Name:</span> mvr <small class="fgc1">(Glyphs:&nbsp;1)</small></h1>
    </div>
    <div class="clearfix mhl ptl">
        <h1 class="mvm mtn fgc1">Grid Size: Unknown</h1>
        <div class="glyph fs1">
            <div class="clearfix bshadow0 pbs">
                <span class="icon-ruffiya"></span>
                <span class="mls"> icon-ruffiya</span>
            </div>
            <fieldset class="fs0 size1of1 clearfix hidden-false">
                <input type="text" readonly value="e900" class="unit size1of2" />
                <input type="text" maxlength="1" readonly value="&#xe900;" class="unitRight size1of2 talign-right" />
            </fieldset>
            <div class="fs0 bshadow0 clearfix hidden-false">
                <span class="unit pvs fgc1">liga: </span>
                <input type="text" readonly value="mvr" class="liga unitRight" />
            </div>
        </div>
    </div>

    <!--[if gt IE 8]><!-->
    <div class="mhl clearfix mbl">
        <h1>Font Test Drive</h1>
        <label>
            Font Size: <input id="fontSize" type="number" class="textbox0 mbm" min="8" value="48" />
            px
        </label>
        <input id="testText" type="text" class="phl size1of1 mvl" placeholder="Type some text to test..." value="mvr"/>
        <div id="testDrive" class="icon-" style="font-family: mvr">mvr&nbsp;</div>
    </div>
</body>
</html>
