

***

<h1 align="center">
<sub>
<img src="https://github.com/gorhill/uBlock/blob/master/src/img/ublock.svg" height="38" width="38">
</sub>
uBlock Turkey (uBTR)
</h1>
<p align="center">
<sub><a href="https://github.com/gorhill/uBlock/wiki/uBlock-Origin-is-completely-unrelated-to-the-web-site-ublock.org"><b>BEWARE!</b> uBO is (and has always been) COMPLETELY UNRELATED to the website <code>ublock.org</code></a>.</sub>
<p align="center">
<sub><a href="https://github.com/gorhill/uBlock"> This project has no connection to the original developers</a>.</sub>
</p>

***

<p align="center">
<a href="https://github.com/turkeysthinktoo/uBlockTurkey/releases"><img src="https://creazilla-store.fra1.digitaloceanspaces.com/icons/3232747/github-full-icon-size_128.png" alt="Check the releases section to download the addon"></a>
<p align="center">
<sub><a https://github.com/turkeysthinktoo/uBlockTurkey/releases"> Check the releases section to download the addon</a>.</sub>
</p>

***
This fork currently only supports Chromium and Chromium-based browsers. If you compile from the source code, you can use it in Firefox and other browsers.
***

uBO(and uBTR) is **NOT** an "ad blocker"; it is a [wide-spectrum content blocker][Blocking] for Chromium and Firefox(only uBO) with CPU and memory efficiency as primary features. After a new installation, the default behavior of uBO is to block ads, trackers, and malware sites through filter lists.

***

* [Documentation](#documentation)
* [General Information](#general-information)
* [Release History](#release-history)
* [About](#about)
* [License](#license)
* [Privacy Policy]
* [Wiki](https://github.com/gorhill/uBlock/wiki)

## Documentation

 Basic mode | Advanced-user mode
:----------:|:------------------:
[Popup user interface]|[A point-and-click firewall that is configurable on a per-site basis][Dynamic Filters]
<a href="https://github.com/gorhill/uBlock/wiki/Quick-guide:-popup-user-interface"><img src="https://user-images.githubusercontent.com/585534/84045360-b10ee580-a976-11ea-9e91-29c2107b47c2.png"/></a><br><sup>.<br>.</sup>|<a href="https://github.com/gorhill/uBlock/wiki/Dynamic-filtering:-quick-guide"><img src="https://user-images.githubusercontent.com/585534/84045366-b1a77c00-a976-11ea-9121-e8c8f35c66c8.png"/></a><br><sup>Configure as you wish.<br>The image shows 3rd-party scripts and frames blocked by default everywhere.</sup>

Visit the [wiki][Wiki] for documentation.

For support, questions, or help, visit [/r/uBlockOrigin][Reddit].

## General Information

uBO(and uBTR) is **NOT** an "ad blocker"; it is a wide-spectrum content blocker. uBO(and uBTR) blocks ads through the EasyList filter syntax and [extends][Extended Syntax] the syntax to work with custom rules and filters. Furthermore, the advanced mode allows uBO to work in [default-deny mode][Default Deny], which will cause [all 3rd-party network requests][3rd Party Requests] to be blocked by default unless allowed by the user.

It is important to note that using a blocker is **NOT** [theft]. Do not fall for this creepy idea. The _ultimate_ logical consequence of `blocking = theft` is the criminalization of the inalienable right to privacy.

Ads, "unintrusive" or not, are just the visible portion of the privacy-invading means entering your browser when you visit most sites. **uBO's primary goal is to help users neutralize these privacy-invading methods** in a way that welcomes those users who do not wish to use more technical, involved means (such as [uMatrix]).

Once you install uBO(uBTR), you may easily unselect any preselected filter lists if you think uBO blocks too much. For reference, Adblock Plus installs with only EasyList, ABP filters, and Acceptable Ads enabled by default.

## Installation

[Required Permissions][Permissions]

#### All Browsers

Do **NOT** use any other content blocker concurrently with uBO to benefit from its higher efficiency. uBO will [perform][Performance] as well as or better than most of the other popular ad blockers. Other blockers can prevent uBO's privacy or anti-blocker-defusing features from working correctly.

Do **NOT** use uBO along with other [similarly-purposed blockers][Similarly-Purposed].

#### Enterprise Deployment

[Deploying uBO][Deployment]

## About

[Manifesto][Manifesto]

Free. Open-source. For users by users. No donations sought.

Note from the original developer: Without the preset filter lists, this extension is nothing. If you ever want to contribute something, think about the people working hard to maintain the filter lists you are using, which were made available to use by all for free.

My note: I am not the original developer of this extension and all the work belongs to the original developer.

You can help contribute by translating uBO on [Crowdin].

## License

[GPLv3][License]


<!----------------------------------------------------------------------------->

[Peter Lowe's Blocklist]: https://pgl.yoyo.org/adservers/
[Malicious Blocklist]: https://gitlab.com/malware-filter/urlhaus-filter#malicious-url-blocklist
[3rd Party Requests]: https://requestpolicycontinued.github.io/#what-are-cross-site-requests
[Similarly-Purposed]: https://twitter.com/gorhill/status/1033706103782170625
[Performance]: https://www.debugbear.com/blog/chrome-extension-performance-2021#how-do-ad-blockers-and-privacy-tools-affect-browser-performance
[EasyPrivacy]: https://easylist.to/#easyprivacy
[Chrome Dev]: https://chrome.google.com/webstore/detail/ublock-origin-development/cgbcahbpdhpcegmbfconppldiemgcoii
[EasyList]: https://easylist.to/#easylist
[Mozilla]: https://addons.mozilla.org/addon/ublock-origin/
[Crowdin]: https://crowdin.com/project/ublock
[Chrome]: https://chrome.google.com/webstore/detail/ublock-origin/cjpalhdlnbpafiamejdnhcphjbkeiagm
[Reddit]: https://www.reddit.com/r/uBlockOrigin/
[Theft]: https://twitter.com/LeaVerou/status/518154828166725632
[Opera]: https://addons.opera.com/extensions/details/ublock/
[Edge]: https://microsoftedge.microsoft.com/addons/detail/ublock-origin/odfafepnkmbhccpbejgmiehpchacaeak
[NPM]: https://www.npmjs.com/package/@gorhill/ubo-core

[Manifesto]: MANIFESTO.md
[License]: LICENSE.txt

[Nicole Rolls]: https://github.com/nicole-ashley


<!---------------------------------[ Internal ]-------------------------------->

[Popup User Interface]: https://github.com/gorhill/uBlock/wiki/Quick-guide:-popup-user-interface
[Manual Installation]: https://github.com/gorhill/uBlock/tree/master/dist#install
[Extended Syntax]: https://github.com/gorhill/uBlock/wiki/Static-filter-syntax#extended-syntax
[Dynamic Filters]: https://github.com/gorhill/uBlock/wiki/Dynamic-filtering:-quick-guide
[Privacy Policy]: https://github.com/gorhill/uBlock/wiki/Privacy-policy
[Default Deny]: https://github.com/gorhill/uBlock/wiki/Dynamic-filtering:-default-deny
[uBO Filters]: https://github.com/uBlockOrigin/uAssets/tree/master/filters
[Permissions]: https://github.com/gorhill/uBlock/wiki/Permissions
[Commit Rate]: https://github.com/gorhill/uBlock/commits/master
[Deployment]: https://github.com/gorhill/uBlock/wiki/Deploying-uBlock-Origin
[Blocking]: https://github.com/gorhill/uBlock/wiki/Blocking-mode
[Releases]: https://github.com/gorhill/uBlock/releases
[UMatrix]: https://github.com/gorhill/uMatrix
[Issues]: https://github.com/uBlockOrigin/uBlock-issues/issues
[Beta]: https://github.com/gorhill/uBlock/blob/master/dist/README.md#for-beta-version
[Wiki]: https://github.com/gorhill/uBlock/wiki


<!----------------------------------[ Badges ]--------------------------------->

[Badge Localization]: https://d322cqt584bo4o.cloudfront.net/ublock/localized.svg
[Badge Commits]: https://img.shields.io/github/commit-activity/m/gorhill/ublock?label=Commits
[Badge Mozilla]: https://img.shields.io/amo/rating/ublock-origin?label=Firefox
[Badge License]: https://img.shields.io/badge/License-GPLv3-blue.svg
[Badge Chrome]: https://img.shields.io/chrome-web-store/rating/cjpalhdlnbpafiamejdnhcphjbkeiagm?label=Chrome
[Badge Issues]: https://img.shields.io/github/issues/uBlockOrigin/uBlock-issues
[Badge NPM]: https://img.shields.io/npm/v/@gorhill/ubo-core

