# CitySpeed
Code to perform some speed test

works with this html snipset

```
<h1 style="font-weight: bold;"> Test the speed of your internet line </h1>
<div id="test">
<div class="testGroup">
    <div class="testArea">
        <div class="testName"> Download </div>
        <div id="download" class="meterText"></div>
        <div class="unit">Mbps</div>
    </div>
    <div class="testArea">
        <div class="testName"> Upload </div>
        <div id="upload" class="meterText"></div>
        <div class="unit">Mbps</div>
    </div>
</div>
<div class="testGroup">
    <div class="testArea">
        <div class="testName"> Ping </div>
        <div id="ping" class="meterText"></div>
        <div class="unit">ms</div>
    </div>
    <div class="testArea">
        <div class="testName"> Jitter </div>
        <div id="jitter" class="meterText"></div>
        <div class="unit">ms</div>
    </div>
</div>
<div id="ipArea">
IP Address: <span id="ip"></span>
    <div id="result" style="display:none;">
        <h1> You have a connection <span id="connection_quality"></span></h1>
    </div>
</div>
<div id="launch_test" type="submit">
</div>
</div>
````
