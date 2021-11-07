# Youtube UI zen (block all 💩)

###### Table of Contents

* [Youtube UI zen (block all <g-emoji class="g-emoji" alias="hankey" fallback-src="https://github.githubassets.com/images/icons/emoji/unicode/1f4a9.png">💩</g-emoji>)](#youtube-ui-zen-block-all-)
   * [What i rip off?](#what--i-rip-off)
   * [Demo](#demo)
   * [You want block more <g-emoji class="g-emoji" alias="hankey" fallback-src="https://github.githubassets.com/images/icons/emoji/unicode/1f4a9.png">💩</g-emoji>?](#you-want-block-more-)
   * [How to use this?](#how-to-use-this)

## What 💩 i rip off?

1. Like, dislike button: this personal chose for me, i don't want to decide like/dislike
2. Trending page: i don't give a 💩 the world care, i hate news, 💩 clickbait videos
3. Video views: the video have high views is good? → i don't know, So i decide to consider to other like title, thumbnail
4. Channel subscriber: i don't want to use this data to decide good/bad
5. All stuff in the top full screen video: i don't want to accident click something useless
6. Some useless button: in the right bar, top bar, etc

## Demo

![](<./img/20211107222334.png>)
![](<./img/20211107222442.png>)

## You want block more 💩?

- Ulock have the feature block element
- Find the 💩 you want to rip off → right click → click `Block element` -> you will know what to do.

![](<./img/20211107222850.png>)

## How to use this?

1. open your ublock option setting
2. add this script below to the filter tab
3. Done

![](<./img/20211107223430.png>)

> hold you cursor in the block code, github will show you the copy button, just simple click it.

```json
www.youtube.com##ytd-topbar-menu-button-renderer.style-default.ytd-masthead.style-scope:nth-of-type(2)
www.youtube.com##ytd-toggle-button-renderer.style-text.force-icon-button.ytd-menu-renderer.style-scope > .ytd-toggle-button-renderer.style-scope.yt-simple-endpoint
www.youtube.com##ytd-guide-section-renderer.ytd-guide-renderer.style-scope:nth-of-type(4)
www.youtube.com##ytd-guide-section-renderer.ytd-guide-renderer.style-scope:nth-of-type(3)
www.youtube.com##ytd-guide-section-renderer.ytd-guide-renderer.style-scope:nth-of-type(2)
www.youtube.com##ytd-guide-entry-renderer.ytd-guide-section-renderer.style-scope:nth-of-type(2)
www.youtube.com##yt-formatted-string.ytd-channel-about-metadata-renderer.style-scope:nth-of-type(3)
www.youtube.com##span.ytd-video-meta-block.style-scope:nth-of-type(1)
www.youtube.com##span.ytd-grid-video-renderer.style-scope:nth-of-type(1)
www.youtube.com##div.ytd-topbar-logo-renderer.style-scope > .ytd-topbar-logo-renderer.style-scope
www.youtube.com##.ytp-watch-later-icon
www.youtube.com##.ytp-title-text
www.youtube.com##.ytp-share-icon
www.youtube.com###voice-search-button
www.youtube.com###thumbnail-attribution
www.youtube.com###subscriber-count
www.youtube.com###sentiment
www.youtube.com###right-column
www.youtube.com###related
www.youtube.com###owner-sub-count
www.youtube.com###guide-links-secondary
www.youtube.com###guide-links-primary
www.youtube.com###dot
www.youtube.com###country-code
www.youtube.com###count > .ytd-video-primary-info-renderer.style-scope
www.youtube.com###count
www.youtube.com###copyright
www.youtube.com###action-buttons
```
