# AddonCyber

AddonCyber is a simple open-source browser extension to assist SOC teams, cybersecurity researchers and analysts in day-to-day threat inteligence and security operations. 

Using a browser, highlight the indicator: IP, URL, domain, file hash, CVE number, base64 encoded text, and opt to search various threat intel services for the IOC, search for a CVE, decode base64, etc

Made by [alterSec](https://altersec.com/) under Apache license. 
Any feedback and PR welcomed!

Current options:
  * [Talos Reputation](https://talosintelligence.com/)
  * [Virus Total](https://developers.virustotal.com/reference/search-1) - requires API key
  * [OTX](https://otx.alienvault.com/)
  * [Shodan](https://www.shodan.io/)
  * [Microsoft TI](https://ti.defender.microsoft.com/)
  * [CIRCL CVE](https://cve.circl.lu/cve/)
  * [CyberChef](https://gchq.github.io/CyberChef/)
  * [Twitter](https://twitter.com/);

NOTE: Some options may require authenticated access.
Services that require an API key (like VT) use the PHP script in the extra folder hosted by alterSec.
Users should host their own instance on public web server, configured with your specific VT API key.

## Screenshots

![Screenshot](screenshots/screenshot1.png?raw=true)
![Screenshot](screenshots/screenshot1.png?raw=true)

## Getting Started

Clone the github repo to a local folder and [Sideload extension in Edge](https://learn.microsoft.com/en-us/microsoft-edge/extensions-chromium/getting-started/extension-sideloading)

For Firefox installation you can go to:
about:debugging | Temporary Extensions | Load Temporary Add-on


## WIP/TBD

  * Add extension to stores
  * Integration with MISP instance, search IOC, add indicator to an event
  * In-context tooltip option, rather than open in a new tab
  * Can we improve the code and 
  * Any other useful services and ideas?

## References

  * Icon: https://icon-sets.iconify.design/tabler/virus-search/
  * Inspiration: https://github.com/401trg/warriormonk.git

© alterSec Ltd