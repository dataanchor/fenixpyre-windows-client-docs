
## Why it Matters
Whitelisting ensures FenixPyre operates without interference from security tools, maintaining effective data encryption and compliance.

### Domain Whitelisting in Firewalls

Whitelisting domains allows SSL traffic for FenixPyre, ensuring secure communications.

#### Mandatory Domains

* apis.fenixpyre.com
* fenixshare.fenixpyre.com
* share.fenixpyre.com
* mtls.apis.fenixpyre.com
* admin.fenixpyre.com

#### Other Domains

* oauth.fenixpyre.com
* anchor-connector.fenixpyre.com  (Note: Fixed per vocabulary rules)
* And so on...

### Whitelisting FenixPyre Processes

Whitelist processes in the installation folder: **C:\Program Files\FenixPyre Client** or individually as listed.

## Next Steps / Related Topics
After whitelisting, proceed to [Install Windows Agent](/03-setup-&-installation/install-windows-agent) or review [Prerequisites](/03-setup-&-installation/prerequisites).