JW Player (Mirror)
==================

Unofficial JW Player repository accessible via Bower.

Current version is **6.12.4956**



===

# Documentation from the JW Player official website

## README: JW Player

Thank you for downloading JW Player 6, the world's most popular HTML5/Flash video player! See [About JW Player](http://www.longtailvideo.com/support/jw-player/28832/about-jw-player) for an overview of supported browsers/devices, as well as a more detailed feature list. See the [Release Notes](http://www.longtailvideo.com/support/jw-player/28835/release-notes) if you want to learn what changed with this latest release.

---

### Quick Start

Copy the **jwplayer** folder that contains this README to the www root of your website. Next, include the *jwplayer.js* script in the \<head\> of your HTML page.

If you have purchased the [Pro, Premium or Ads edition](http://www.longtailvideo.com/jw-player/pricing/) of JW Player, its features can be activated by inserting your server-less JW Player license key in the second line:

    <script type="text/javascript" src="/jwplayer/jwplayer.js"></script>
    <script type="text/javascript">jwplayer.key="ABCDEFGHIJKLMOPQ";</script>

Note: A key is not required to use the Free edition, but will still be available from your [JW Player Account](https://account.longtailvideo.com/). Including your key will enable the free [JW Player Analytics](http://www.longtailvideo.com/support/jw-player/28852/using-jw-player-analytics) for your account.

#### Embed Code

When the script and key are set, scroll down to the \<body\> of your HTML page and insert the JW Player embed code at the place you want your video to appear:

    <div id="myElement">Loading the player...</div>

    <script type="text/javascript">
        jwplayer("myElement").setup({
            file: "/uploads/myVideo.mp4",
            image: "/uploads/myPoster.jpg"
        });
    </script>

See [Embedding JW Player](http://www.longtailvideo.com/support/jw-player/28839/embedding-the-player) for a more elaborate description of options and some example embeds.

*Note two very common issues prevent smooth video playback in Internet Explorer 9/10. First, you need to set **\<!DOCTYPE html\>** to prevent triggering IE's compatibility mode. Second, your videos must be served with the **video/mp4** mimetype. Not doing so will cause IE not to play them. See our [troubleshooting guide](http://www.longtailvideo.com/support/jw-player/28840/troubleshooting-your-setup) for more common issues.*

#### Premium Skins

If you have purchased the Premium or Ads edition of the player, your player includes a set of Premium skins. These skins can be downloaded from your [JW Player Account](https://account.longtailvideo.com/), but you can also load them off our CDN by simply inserting the skin name:

        skin: "bekle"

See [Using JW Player Skins](http://www.longtailvideo.com/support/jw-player/28846/using-jw-player-skins) for more info.

---

### Documentation

If you need help, the LongTail Support Community contains a wealth of information, including guides on:

-   Supported [Media Formats](http://www.longtailvideo.com/support/jw-player/28836/media-format-support) and [Browsers & Devices](http://www.longtailvideo.com/support/jw-player/28837/browser-device-support).
-   How to [Customize](http://www.longtailvideo.com/support/jw-player/28839/embedding-the-player) and [Troubleshoot](http://www.longtailvideo.com/support/jw-player/28840/troubleshooting-your-setup) your embeds.
-   Configuring [Inline Playlists](http://www.longtailvideo.com/support/jw-player/28842/working-with-playlists) or [RSS Feeds](http://www.longtailvideo.com/support/jw-player/28843/loading-rss-feeds) (with multiple formats/qualities).
-   The [PNG Skinning Model](http://www.longtailvideo.com/support/jw-player/28846/using-jw-player-skins) and [JavaScript API](http://www.longtailvideo.com/support/jw-player/28850/using-the-javascript-api).
-   Using [RTMP Streaming](http://www.longtailvideo.com/support/jw-player/28854/using-rtmp-streaming) and [Apple HLS](http://www.longtailvideo.com/support/jw-player/28856/using-apple-hls-streaming/) (Premium/Ads edition only).
-   How to [Configure Video Ads](http://www.longtailvideo.com/support/jw-player/28862/configuring-video-ads) (Ads edition only).

Visit our [Support Forums](http://www.longtailvideo.com/support/forums/jw-player/) for setup problems, bug reports or suggestions for new features or enhancements. The forums are very active and frequently visited by members of the JW Player development team. Please see your [JW Player Account](http://account.longtailvideo.com) for more information on obtaining technical support.

Follow the [LongTail Video Blog](http://www.longtailvideo.com/blog/) for news on the JW Player and online video in general. We frequently publish posts on topics such as HTML5, video SEO, H.264, VAST advertising, etc. You can also [follow us on Twitter](http://twitter.com/longtailvideo) or [like us on Facebook](http://www.facebook.com/longtailvideo) to stay connected.

---

### Licensing


Please be aware that each player edition has its own license:

JW Player Free
Under the terms of our [Creative Commons license](http://creativecommons.org/licenses/by-nc-sa/3.0/), you can use, modify and redistribute the player for non-commercial purposes only. Commercial sites must [purchase a license](%20http://www.longtailvideo.com/jw-player/pricing/) for the **Pro**, **Premium** or **Ads** editions. See the [JW Player 6 License](http://www.longtailvideo.com/jw-player/license/jw-player-license-text) for further details.

JW Player Pro
Under the terms of our [Commercial License](http://www.longtailvideo.com/jw-player/license/jw-player-license-text), you can deploy your copy of JW Player **Pro** for commercial use on 1 domain. See our [pricing page](http://www.longtailvideo.com/jw-player/pricing/) for more information on edition features and pricing.

JW Player Premium
Under the terms of our [Commercial License](http://www.longtailvideo.com/jw-player/license/jw-player-license-text), you can deploy your copy of JW Player **Premium** for commercial use on up to 10 domains. See our [pricing page](http://www.longtailvideo.com/jw-player/pricing/) for more information on edition features and pricing.

JW Player Ads
Under the terms of our [Commercial License](http://www.longtailvideo.com/jw-player/license/jw-player-license-text), you can deploy your copy of JW Player **Ads** for commercial use on up to 10 domains, with an additional restriction of up to 250.000 filled ad impressions per month. See our [pricing page](http://www.longtailvideo.com/jw-player/pricing/) for more information on edition features and price.

Examples of **commercial use** includes websites with any advertisements, websites owned or operated by businesses, websites designed to promote products or services, and tools (e.g. a CMS) that bundle JW Player in their offering.

Note all editions of JW Player incorporate the [Block TEA library](http://www.movable-type.co.uk/scripts/tea-block.html) from Movable Type (CC-BY license).

The player also makes use of the [Underscore.js](http://underscorejs.org/) library, which is distributed under the following terms:

    Copyright (c) 2009-2014 Jeremy Ashkenas, DocumentCloud and Investigative
    Reporters & Editors

    Permission is hereby granted, free of charge, to any person
    obtaining a copy of this software and associated documentation
    files (the "Software"), to deal in the Software without
    restriction, including without limitation the rights to use,
    copy, modify, merge, publish, distribute, sublicense, and/or sell
    copies of the Software, and to permit persons to whom the
    Software is furnished to do so, subject to the following
    conditions:

    The above copyright notice and this permission notice shall be
    included in all copies or substantial portions of the Software.

    THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND,
    EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES
    OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND
    NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT
    HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY,
    WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING
    FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR
    OTHER DEALINGS IN THE SOFTWARE.
