<p align="center"><img src="https://github.com/K3V1991/Disable-Firefox-Telemetry-and-Data-Collection/blob/main/Data-Collection.png" width="200"></a>
<h1 align="center"><b>How to disable Firefox Telemetry and Data Collection</b></h1>
<br />

<p align="center">
  <p>
    Please support the original author, as they came up with a LOT of good stuff.
  </p>
<a href="https://liberapay.com/K3V1991" alt="LiberaPay"><img src="https://img.shields.io/badge/Liberapay-F6C915?style=for-the-badge&logo=liberapay&logoColor=black" /></a>
<a href="https://www.buymeacoffee.com/k3v1991" alt="BuyMeACoffee"><img src="https://img.shields.io/badge/Buy%20Me%20a%20Coffee-ffdd00?style=for-the-badge&logo=buy-me-a-coffee&logoColor=black" /></a>
<a href="https://ko-fi.com/k3v1991" alt="Ko-fi"><img src="https://img.shields.io/badge/Ko--fi-F16061?style=for-the-badge&logo=ko-fi&logoColor=white" /></a>
<a href="https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=HW8B98TVDLKWA" alt="PayPal"><img src="https://img.shields.io/badge/PayPal-00457C?style=for-the-badge&logo=paypal&logoColor=white" /></a>
<a href="https://github.com/K3V1991/Donate-Crypto/blob/main/README.md" alt="Crypto"><img src="https://img.shields.io/badge/Bitcoin-000?style=for-the-badge&logo=bitcoin&logoColor=white" /></a>
</p>
<hr />
<br />

## NFO:
Mozilla has provided few Settings on Options Page to select what kind of Data do you want to share with Mozilla and want to send to Mozilla Servers. <br />
You can turn on/off Options such as ```Allow Firefox to send technical and interaction data to Mozilla```, ```Allow Firefox to install and run studies``` and ```Allow Firefox to send Crash Reports to Mozilla``` Servers. <br />
You can change these settings using ```Privacy & Security``` Section. <br />
Even after you disable these Options, Firefox still collects and sends Data to Servers. 
<br />
<br />

## Disable Telemetry and Data Collection:
1. Open Firefox and type ```about:config``` in the Addressbar and press Enter. It'll show you a Warning Message, click on ```Accept the Risk and Continue``` Button
2. In the Search Bar, type each of the following Preferences and then set them to the Value provided to the right:
<br />
<br />

Preference | Value to change |
| --- | --- |
| browser.newtabpage.activity-stream.feeds.telemetry | false |
| browser.newtabpage.activity-stream.telemetry | false |
| browser.ping-centre.telemetry | false |
| datareporting.healthreport.service.enabled | false |
| datareporting.healthreport.uploadEnabled | false |
| datareporting.policy.dataSubmissionEnabled | false |
| datareporting.sessions.current.clean | true
| devtools.onboarding.telemetry.logged | false |
| toolkit.telemetry.archive.enabled | false |
| toolkit.telemetry.bhrPing.enabled | false |
| toolkit.telemetry.enabled | false |
| toolkit.telemetry.firstShutdownPing.enabled | false |
| toolkit.telemetry.hybridContent.enabled | false |
| toolkit.telemetry.newProfilePing.enabled | false |
| toolkit.telemetry.prompted | Number Value 2 |
| toolkit.telemetry.rejected | true
| toolkit.telemetry.reportingpolicy.firstRun | false |
| toolkit.telemetry.server | Delete URL |
| toolkit.telemetry.shutdownPingSender.enabled | false |
| toolkit.telemetry.unified | false |
| toolkit.telemetry.unifiedIsOptIn | false |
| toolkit.telemetry.updatePing.enabled | false |

## Extended attributes to set to false
Preference | Value to change |
| --- | --- |
| experiments.activeExperiment | false |
| experiments.enabled | false |
| experiments.supported | false |
| network.allow-experiments | false |

## Empty the values in the following entries
Preference  |
| --- |
| app.normandy.api_url |
| breakpad.reportURL |
| browser.contentblocking.report.manage_devices.url |
| browser.contentblocking.report.vpn-promo.url |
| browser.contentblocking.report.vpn.url |
| browser.ml.modelHubRootUrl |
| browser.newtabpage.activity-stream.discoverystream.contextualContent.fakespot.ctaUrl |
| browser.newtabpage.activity-stream.discoverystream.ohttp.relayURL |
| browser.partnerlink.attributionURL |
| browser.privatebrowsing.vpnpromourl |
| browser.region.network.url |
| browser.safebrowsing.provider.mozilla.gethashURL |
| browser.urlbar.merino.endpointURL |
| geo.provider.network.url |
| media.gmp-manager.chromium-update-url |
| signon.firefoxRelay.base_url |
| signon.firefoxRelay.manage_url |
| signon.management.page.breachAlertUrl |
| toolkit.shopping.ohttpConfigURL |
| toolkit.telemetry.dap.helper.url |
| toolkit.telemetry.dap.leader.url |
| webextensions.storage.sync.serverURL |
| identity.sync.tokenserver.uri |
| toolkit.telemetry.server |
| webextensions.storage.sync.serverURL |

## Servers to block
Blocking these will COMPLETELY block Mozilla services. Use at your own descretion.

    detectportal.firefox.com
    incoming.telemetry.mozilla.org
    tiles.services.mozilla.org
    services.addons.mozilla.org
    activity-stream-icons.services.mozilla.com
    aus5.mozilla.org
    blocklists.settings.services.mozilla.com
    ciscobinary.openh264.org
    content-signature.cdn.mozilla.net
    discovery.addons.mozilla.org
    download.cdn.mozilla.net
    firefox.settings.services.mozilla.com
    getpocket.cdn.mozilla.net
    img-getpocket.cdn.mozilla.net
    location.services.mozilla.com
    normandy.cdn.mozilla.net
    normandy.services.mozilla.com
    push.services.mozilla.com
    snippets.cdn.mozilla.net
    shavar.services.mozilla.com
    versioncheck-bg.addons.mozilla.org

