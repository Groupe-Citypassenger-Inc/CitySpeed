# CitySpeed
Code to perform some speed test

works with this php snipset

```
        <div id="speedtest">
            <h1><?php _e('Test the speed of your internet line', 'digilan-token') ?></h1>
            <div class="testGroup">
                <div class="testArea">
                    <div class="testName"><?php _e('Download', 'digilan-token'); ?></div>
                    <div id="download" class="meterText"></div>
                    <div class="unit"><?php _e('Mbps', 'digilan-token'); ?></div>
                </div>
                <div class="testArea">
                    <div class="testName"><?php _e('Upload', 'digilan-token');?></div>
                    <div id="upload" class="meterText"></div>
                    <div class="unit"><?php _e('Mbps', 'digilan-token'); ?></div>
                </div>
            </div>
            <div class="testGroup">
                <div class="testArea">
                    <div class="testName"><?php _e('Ping', 'digilan-token'); ?></div>
                    <div id="ping" class="meterText"></div>
                    <div class="unit"><?php _e('ms', 'digilan-token'); ?></div>
                </div>
                <div class="testArea">
                    <div class="testName"><?php _e('Jitter', 'digilan-token'); ?></div>
                    <div id="jitter" class="meterText"></div>
                    <div class="unit"><?php _e('ms', 'digilan-token'); ?></div>
                </div>
            </div>
            <p><?php _e('IP Address', 'digilan-token'); ?>: <span id="ip"></span></p>
            <div id="launch_test" type="submit">
            </div>
            <div id="result">
                <h2><?php _e('Your connection is', 'digilan-token'); ?>: </h2>
                <h3 id="good_connection"><?php _e('good', 'digilan-token'); ?> !</h3>
                <h3 id="medium_connection"><?php _e('medium', 'digilan-token'); ?> !</h3>
                <h3 id="bad_connection"><?php _e('bad', 'digilan-token'); ?> !</h3>
                <p><?php _e('We suggest you an offer adapted to your needs', 'digilan-token'); ?>: <a id="offer_link"><?php _e('on this link', 'digilan-token'); ?>.</a></p>
            </div>
        </div>
````
