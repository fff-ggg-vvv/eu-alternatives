# European Alternatives to US and Chinese Tech

A curated list of globally available European alternatives to dominant US and Chinese software, cloud and tech products, ordered from the biggest and most critical systems down to everyday apps.

- Only companies and projects **headquartered and owned in Europe** (EU, EEA, Switzerland, UK). No US, Chinese or Russian ownership.
- US and Chinese columns show the dominant products in each category. — means no dominant product from that country.
- Open source column: the strongest open-source option, from any country.
- Best option first in each row.
- 🆕 = launched or had a major release in 2025–2026.
- Flags show where the company is based. 🇪🇺 = pan-European consortium or community project.

Last research update: October 2026.

## Contents

1. [Infrastructure](#infrastructure)
2. [Platforms](#platforms)
3. [Artificial intelligence](#artificial-intelligence)
4. [Payments and finance](#payments-and-finance)
5. [Workplace and productivity](#workplace-and-productivity)
6. [Communication](#communication)
7. [Security and identity](#security-and-identity)
8. [Business software](#business-software)
9. [Development and design](#development-and-design)
10. [Consumer apps and media](#consumer-apps-and-media)
11. [Coming soon](#coming-soon)
12. [Not included](#not-included)

## Infrastructure

| Type | US product | Chinese product | EU alternative(s) | Open source |
|---|---|---|---|---|
| Semiconductors | Nvidia, Intel, Qualcomm | SMIC, HiSilicon (Huawei) | [ASML](https://www.asml.com) 🇳🇱 (lithography), [Infineon](https://www.infineon.com) 🇩🇪, [STMicroelectronics](https://www.st.com) 🇫🇷🇮🇹, [NXP](https://www.nxp.com) 🇳🇱 | [RISC-V](https://riscv.org) (open chip architecture), [OpenTitan](https://opentitan.org) |
| Telecom network equipment (4G/5G) | — | Huawei, ZTE | [Ericsson](https://www.ericsson.com) 🇸🇪, [Nokia](https://www.nokia.com) 🇫🇮 | [OpenAirInterface](https://openairinterface.org) 🇫🇷, [srsRAN](https://www.srslte.com) |
| Energy: solar inverters and home batteries | — | Huawei, Sungrow | [SMA Solar](https://www.sma.de) 🇩🇪, [Fronius](https://www.fronius.com) 🇦🇹 | [OpenEMS](https://openems.io) 🇩🇪 |
| Cloud (IaaS) | AWS, Microsoft Azure, Google Cloud | Alibaba Cloud, Huawei Cloud, Tencent Cloud | [OVHcloud](https://www.ovhcloud.com) 🇫🇷, [Scaleway](https://www.scaleway.com) 🇫🇷, [Hetzner](https://www.hetzner.com) 🇩🇪, [UpCloud](https://upcloud.com) 🇫🇮 | [OpenStack](https://www.openstack.org), [Apache CloudStack](https://cloudstack.apache.org) |
| Sovereign / government cloud | AWS GovCloud, Azure Government | — | [STACKIT](https://stackit.com) 🇩🇪, [IONOS Cloud](https://cloud.ionos.com) 🇩🇪, [SAP Sovereign Cloud](https://www.sap.com) 🇩🇪 🆕 | [Sovereign Cloud Stack](https://scs.community) 🇩🇪, [OpenStack](https://www.openstack.org) |
| AI / GPU cloud | AWS and Azure GPU, CoreWeave, Lambda | Alibaba Cloud | [Mistral Compute](https://mistral.ai/compute/) 🇫🇷 🆕, [Nscale](https://www.nscale.com) 🇬🇧 🆕, [T-Systems Industrial AI Cloud](https://www.telekom.com) 🇩🇪 🆕, [Verda](https://verda.com) 🇫🇮 | [Kubernetes](https://kubernetes.io), [Slurm](https://slurm.schedmd.com) |
| PaaS / managed Kubernetes | Heroku, GKE, EKS | — | [Clever Cloud](https://www.clever.cloud) 🇫🇷 🆕, [Scaleway Kapsule](https://www.scaleway.com) 🇫🇷 | [Kubernetes](https://kubernetes.io), [Coolify](https://coolify.io), [Dokku](https://dokku.com) |
| Object storage | Amazon S3 | — | [Hetzner Object Storage](https://www.hetzner.com/storage/object-storage) 🇩🇪, [Impossible Cloud](https://www.impossiblecloud.com) 🇩🇪, [Scaleway Object Storage](https://www.scaleway.com) 🇫🇷 | [Ceph](https://ceph.io), [Garage](https://garagehq.deuxfleurs.fr) 🇫🇷, [SeaweedFS](https://github.com/seaweedfs/seaweedfs) |
| CDN / edge | Cloudflare, Akamai, Amazon CloudFront | Alibaba Cloud CDN | [bunny.net](https://bunny.net) 🇸🇮 | [Varnish Cache](https://varnish-cache.org), [Apache Traffic Server](https://trafficserver.apache.org) |
| DDoS protection / WAF | Cloudflare, Akamai | — | [Myra Security](https://www.myrasecurity.com) 🇩🇪 | [CrowdSec](https://www.crowdsec.net) 🇫🇷, [OWASP Coraza](https://coraza.io) |
| Public DNS resolver | Google 8.8.8.8, Cloudflare 1.1.1.1 | — | [DNS4EU](https://www.joindns4.eu) 🇪🇺 🆕 | [Unbound](https://nlnetlabs.nl/projects/unbound/) 🇳🇱, [Knot Resolver](https://www.knot-resolver.cz) 🇨🇿 |
| Web hosting / VPS | GoDaddy, Bluehost, DigitalOcean | — | [Infomaniak](https://www.infomaniak.com) 🇨🇭, [Hostinger](https://www.hostinger.com) 🇱🇹, [netcup](https://www.netcup.com) 🇩🇪, [IONOS](https://www.ionos.com) 🇩🇪 | [YunoHost](https://yunohost.org) 🇫🇷, [Coolify](https://coolify.io) |
| Domain registrar | GoDaddy, Namecheap | — | [Netim](https://www.netim.com) 🇫🇷, [INWX](https://www.inwx.com) 🇩🇪, [OVHcloud Domains](https://www.ovhcloud.com/en/domains/) 🇫🇷 | — |

## Platforms

| Type | US product | Chinese product | EU alternative(s) | Open source |
|---|---|---|---|---|
| Desktop operating system | Windows, macOS | — | [openSUSE / SUSE Linux](https://www.opensuse.org) 🇩🇪, [Ubuntu](https://ubuntu.com) 🇬🇧, [KDE Linux](https://kde.org/linux) 🇩🇪 🆕 | [Debian](https://www.debian.org), [Fedora](https://fedoraproject.org), [Linux Mint](https://linuxmint.com) |
| Mobile operating system | Android (Google), iOS | HarmonyOS (Huawei) | [/e/OS](https://murena.com) 🇫🇷 🆕, [Sailfish OS](https://jolla.com) 🇫🇮, [Volla OS](https://volla.online) 🇩🇪 | [LineageOS](https://lineageos.org), [GrapheneOS](https://grapheneos.org), [postmarketOS](https://postmarketos.org) |
| Smartphone | iPhone, Google Pixel | Xiaomi, Huawei, Oppo, Vivo | [Fairphone](https://www.fairphone.com) 🇳🇱 🆕, [Jolla Phone](https://commerce.jolla.com) 🇫🇮 🆕, [Murena](https://murena.com) 🇫🇷 🆕, [SHIFTphone](https://www.shift.eco) 🇩🇪, [Volla Phone](https://volla.online) 🇩🇪 🆕, [Punkt](https://www.punkt.ch) 🇨🇭 🆕 | — |
| Laptops and PCs | Apple, Dell, HP | Lenovo, Huawei | [TUXEDO Computers](https://www.tuxedocomputers.com) 🇩🇪, [Schenker XMG](https://www.xmg.gg) 🇩🇪 | [coreboot](https://www.coreboot.org) (open firmware) |
| Home routers and Wi-Fi | — | TP-Link, Huawei | [FRITZ!Box](https://fritz.com) 🇩🇪, [MikroTik](https://mikrotik.com) 🇱🇻 | [OpenWrt](https://openwrt.org) |
| Search engine | Google Search, Bing | Baidu | [Ecosia](https://www.ecosia.org) 🇩🇪, [Qwant](https://www.qwant.com) 🇫🇷, [Mojeek](https://www.mojeek.com) 🇬🇧 | [SearXNG](https://docs.searxng.org), [YaCy](https://yacy.net) 🇩🇪 |
| Search index | Google and Bing indexes | — | [Staan](https://www.staan.ai) 🇫🇷🇩🇪 🆕, [Open Web Index](https://openwebsearch.eu) 🇪🇺 🆕 | [YaCy](https://yacy.net) 🇩🇪, [Common Crawl](https://commoncrawl.org) (open data) |
| Web browser | Chrome, Safari, Edge | Opera, UC Browser | [Vivaldi](https://vivaldi.com) 🇳🇴, [Ecosia Browser](https://www.ecosia.org/browser) 🇩🇪 🆕, [Mullvad Browser](https://mullvad.net/browser) 🇸🇪, [Waterfox](https://www.waterfox.net) 🇬🇧 | [Firefox](https://www.mozilla.org/firefox/), [LibreWolf](https://librewolf.net), [Chromium](https://www.chromium.org) |
| Drones | — | DJI | [Parrot](https://www.parrot.com) 🇫🇷, [Quantum Systems](https://quantum-systems.com) 🇩🇪 | [PX4](https://px4.io) 🇨🇭, [ArduPilot](https://ardupilot.org) |
| 3D printers | — | Bambu Lab, Creality | [Prusa Research](https://www.prusa3d.com) 🇨🇿 | [Klipper](https://www.klipper3d.org), [Voron](https://vorondesign.com), [PrusaSlicer](https://www.prusa3d.com/prusaslicer/) 🇨🇿 |

## Artificial intelligence

| Type | US product | Chinese product | EU alternative(s) | Open source |
|---|---|---|---|---|
| AI assistant / LLM | ChatGPT, Gemini, Claude | DeepSeek, Qwen, Doubao, Kimi | [Mistral Vibe (Le Chat)](https://chat.mistral.ai) 🇫🇷 🆕, [Lumo by Proton](https://lumo.proton.me) 🇨🇭 🆕, [Euria by Infomaniak](https://euria.infomaniak.com) 🇨🇭 🆕 | [Open WebUI](https://openwebui.com) + [Ollama](https://ollama.com) |
| Open-weight AI models | — | DeepSeek, Qwen | [Mistral](https://mistral.ai) 🇫🇷 | [EuroLLM](https://eurollm.io) 🇪🇺, [OLMo](https://allenai.org/olmo) |
| AI coding assistant | GitHub Copilot, Cursor, Claude Code | Trae (ByteDance), Qwen Code | [Mistral Vibe CLI + Devstral](https://mistral.ai/news/devstral-2-vibe-cli/) 🇫🇷 🆕, [JetBrains Junie](https://www.jetbrains.com/junie/) 🇨🇿 🆕 | [Aider](https://aider.chat), [Continue](https://www.continue.dev), [OpenCode](https://opencode.ai) |
| AI image generation | Midjourney, DALL-E | — | [FLUX by Black Forest Labs](https://bfl.ai) 🇩🇪 🆕 | [ComfyUI](https://www.comfy.org), [FLUX.1 [schnell]](https://github.com/black-forest-labs/flux) 🇩🇪 |
| AI video / avatars | HeyGen, Sora | Kling (Kuaishou), Hailuo (MiniMax) | [Synthesia](https://www.synthesia.io) 🇬🇧 | [LTX-Video](https://github.com/Lightricks/LTX-Video) |
| AI voice (speech-to-text, text-to-speech) | OpenAI Whisper and TTS | — | [Mistral Voxtral](https://mistral.ai) 🇫🇷 🆕, [Gradium](https://gradium.ai) 🇫🇷 🆕 | [Whisper](https://github.com/openai/whisper), [Piper](https://github.com/OHF-Voice/piper1-gpl), [Kyutai](https://kyutai.org) 🇫🇷 |
| Translation | Google Translate | Baidu Translate | [DeepL](https://www.deepl.com) 🇩🇪 🆕 | [LibreTranslate](https://libretranslate.com), [Firefox Translations](https://github.com/mozilla/translations) |

## Payments and finance

| Type | US product | Chinese product | EU alternative(s) | Open source |
|---|---|---|---|---|
| Payment network / wallet | Visa, Mastercard, PayPal, Apple Pay | Alipay, WeChat Pay, UnionPay | [Wero](https://wero-wallet.eu) 🇪🇺 🆕, [Bizum](https://www.bizum.es) 🇪🇸, [Vipps MobilePay](https://vippsmobilepay.com) 🇳🇴🇩🇰 | [GNU Taler](https://taler.net) 🇨🇭 |
| Payment processing | Stripe, PayPal Braintree, Square | — | [Adyen](https://www.adyen.com) 🇳🇱, [Mollie](https://www.mollie.com) 🇳🇱 🆕, [Viva](https://www.viva.com) 🇬🇷, [Unzer](https://www.unzer.com) 🇩🇪 | [Hyperswitch](https://hyperswitch.io), [BTCPay Server](https://btcpayserver.org) |
| Buy now, pay later | Affirm | — | [Klarna](https://www.klarna.com) 🇸🇪 | — |
| Digital bank | Chime, Cash App | — | [Revolut](https://www.revolut.com) 🇬🇧 🆕, [bunq](https://www.bunq.com) 🇳🇱 🆕, [N26](https://n26.com) 🇩🇪 | — |
| Business banking | Mercury, Brex | — | [Qonto](https://qonto.com) 🇫🇷 | — |

## Workplace and productivity

| Type | US product | Chinese product | EU alternative(s) | Open source |
|---|---|---|---|---|
| Workplace suite | Microsoft 365, Google Workspace | Lark / Feishu, DingTalk, WeCom | [openDesk](https://www.opendesk.eu) 🇩🇪, [Proton Workspace](https://proton.me/business) 🇨🇭 🆕, [Nextcloud Hub](https://nextcloud.com) 🇩🇪 🆕, [Infomaniak kSuite](https://www.infomaniak.com/ksuite) 🇨🇭, [Office EU](https://office.eu) 🇳🇱 🆕, [Twake Workplace](https://twake.app) 🇫🇷 🆕, [La Suite numérique](https://lasuite.numerique.gouv.fr) 🇫🇷 🆕 | [Nextcloud](https://nextcloud.com) 🇩🇪, [openDesk](https://www.opendesk.eu) 🇩🇪, [La Suite numérique](https://github.com/suitenumerique) 🇫🇷 |
| Office suite | Microsoft Office, Google Docs | WPS Office | [LibreOffice](https://www.libreoffice.org) 🇩🇪 🆕, [Euro-Office](https://github.com/Euro-Office) 🇪🇺 🆕, [Collabora Online](https://www.collaboraonline.com) 🇬🇧, [Proton Docs and Sheets](https://proton.me/drive) 🇨🇭 🆕 | [LibreOffice](https://www.libreoffice.org) 🇩🇪, [Collabora Online](https://www.collaboraonline.com) 🇬🇧, [Euro-Office](https://github.com/Euro-Office) 🇪🇺 |
| Email | Gmail, Outlook | — | [Proton Mail](https://proton.me/mail) 🇨🇭, [Tuta](https://tuta.com) 🇩🇪, [mailbox](https://mailbox.org) 🇩🇪 | [Thunderbird](https://www.thunderbird.net) (client), [Stalwart](https://stalw.art) (server) |
| Email server | Microsoft Exchange | — | [Open-Xchange (OX App Suite)](https://www.open-xchange.com) 🇩🇪 | [Stalwart](https://stalw.art), [mailcow](https://mailcow.email) 🇩🇪 |
| Cloud storage and sync | Google Drive, Dropbox, OneDrive, iCloud | — | [Proton Drive](https://proton.me/drive) 🇨🇭, [Tresorit](https://tresorit.com) 🇨🇭, [kDrive](https://www.infomaniak.com/kdrive) 🇨🇭, [pCloud](https://www.pcloud.com) 🇨🇭, [Filen](https://filen.io) 🇩🇪, [Internxt](https://internxt.com) 🇪🇸, [Koofr](https://koofr.eu) 🇸🇮 | [Nextcloud](https://nextcloud.com) 🇩🇪, [Seafile](https://www.seafile.com), [Syncthing](https://syncthing.net) |
| Calendar | Google Calendar, Outlook Calendar | — | [Proton Calendar](https://proton.me/calendar) 🇨🇭, [Tuta Calendar](https://tuta.com/calendar) 🇩🇪 | [Nextcloud Calendar](https://apps.nextcloud.com/apps/calendar) 🇩🇪, [Radicale](https://radicale.org) |
| Docs and wiki | Notion, Confluence | Lark Docs | [La Suite Docs](https://github.com/suitenumerique/docs) 🇫🇷🇩🇪 🆕, [XWiki](https://xwiki.com) 🇫🇷, [CryptPad](https://cryptpad.org) 🇫🇷 | [La Suite Docs](https://github.com/suitenumerique/docs) 🇫🇷🇩🇪, [Outline](https://www.getoutline.com), [BookStack](https://www.bookstackapp.com) |
| Project management | Jira, Asana, Trello, MS Project | — | [OpenProject](https://www.openproject.org) 🇩🇪, [MeisterTask](https://www.meistertask.com) 🇩🇪, [Stackfield](https://www.stackfield.com) 🇩🇪, [Taiga](https://taiga.io) 🇪🇸, [Businessmap](https://businessmap.io) 🇧🇬 | [OpenProject](https://www.openproject.org) 🇩🇪, [Taiga](https://taiga.io) 🇪🇸, [Kanboard](https://kanboard.org) |
| Forms and surveys | Google Forms, SurveyMonkey, Qualtrics | — | [Typeform](https://www.typeform.com) 🇪🇸, [Tally](https://tally.so) 🇧🇪, [Formbricks](https://formbricks.com) 🇩🇪 | [LimeSurvey](https://www.limesurvey.org) 🇩🇪, [Formbricks](https://formbricks.com) 🇩🇪 |
| Scheduling | Calendly, Doodle-style polls | — | [Doodle](https://doodle.com) 🇨🇭, [Zeeg](https://zeeg.me) 🇩🇪 | [Cal.com](https://cal.com), [Framadate](https://framadate.org) 🇫🇷 |

## Communication

| Type | US product | Chinese product | EU alternative(s) | Open source |
|---|---|---|---|---|
| Messenger | WhatsApp, iMessage, Signal | WeChat | [Threema](https://threema.com) 🇨🇭, [Olvid](https://www.olvid.io) 🇫🇷, [Element (Matrix)](https://element.io) 🇬🇧, [BirdyChat](https://www.birdy.chat) 🇱🇻 🆕 | [Signal](https://signal.org), [Element (Matrix)](https://element.io) 🇬🇧, [SimpleX](https://simplex.chat) |
| Team chat | Slack, Microsoft Teams | Lark, DingTalk | [Element Pro](https://element.io) 🇬🇧 🆕, [kChat](https://www.infomaniak.com/kchat) 🇨🇭, [Nextcloud Talk](https://nextcloud.com/talk) 🇩🇪, [Whaller](https://whaller.com) 🇫🇷 | [Element (Matrix)](https://element.io) 🇬🇧, [Zulip](https://zulip.com), [Mattermost](https://mattermost.com) |
| Video conferencing | Zoom, Microsoft Teams, Google Meet | Tencent Meeting (VooV) | [Proton Meet](https://proton.me/meet) 🇨🇭 🆕, [Whereby](https://whereby.com) 🇳🇴, [eyeson](https://www.eyeson.com) 🇦🇹 | [Jitsi Meet](https://jitsi.org), [BigBlueButton](https://bigbluebutton.org) |
| Social network (microblogging) | X (Twitter), Threads | Weibo | [Mastodon](https://joinmastodon.org) 🇩🇪, [W Social](https://wsocial.eu) 🇸🇪 🆕, [Eurosky](https://eurosky.social) 🇳🇱 🆕 | [Mastodon](https://joinmastodon.org) 🇩🇪 |
| Social network (photos, friends) | Instagram, Facebook | Xiaohongshu (RedNote) | [Monnett](https://monnett.social) 🇱🇺 🆕, [eYou](https://eyou.eu) 🇭🇷 🆕 | [Pixelfed](https://pixelfed.org), [Friendica](https://friendi.ca) |
| Short video | — | TikTok, Kwai | [Dailymotion](https://www.dailymotion.com) 🇫🇷 | [Loops](https://joinloops.org), [PeerTube](https://joinpeertube.org) 🇫🇷 |

## Security and identity

| Type | US product | Chinese product | EU alternative(s) | Open source |
|---|---|---|---|---|
| Endpoint security / antivirus | Microsoft Defender, CrowdStrike, Norton | — | [ESET](https://www.eset.com) 🇸🇰, [Bitdefender](https://www.bitdefender.com) 🇷🇴, [WithSecure](https://www.withsecure.com) 🇫🇮, [G DATA](https://www.gdata.de) 🇩🇪, [F-Secure](https://www.f-secure.com) 🇫🇮, [TEHTRIS](https://tehtris.com) 🇫🇷 | [Wazuh](https://wazuh.com), [ClamAV](https://www.clamav.net) |
| Identity and single sign-on | Okta, Auth0, Microsoft Entra ID | — | [cidaas](https://www.cidaas.com) 🇩🇪, [Zitadel](https://zitadel.com) 🇨🇭, [Univention Nubus](https://www.univention.com) 🇩🇪, [Bare.ID](https://bare.id) 🇩🇪, [Cloud-IAM](https://www.cloud-iam.com) 🇫🇷 | [Keycloak](https://www.keycloak.org), [Zitadel](https://zitadel.com) 🇨🇭, [Authentik](https://goauthentik.io) |
| Password manager | 1Password, LastPass, Bitwarden | — | [Proton Pass](https://proton.me/pass) 🇨🇭, [Passbolt](https://www.passbolt.com) 🇱🇺, [NordPass](https://nordpass.com) 🇱🇹, [heylogin](https://www.heylogin.com) 🇩🇪, [Uniqkey](https://www.uniqkey.eu) 🇩🇰 | [Bitwarden](https://bitwarden.com) / [Vaultwarden](https://github.com/dani-garcia/vaultwarden), [KeePassXC](https://keepassxc.org), [Passbolt](https://www.passbolt.com) 🇱🇺 |
| Backup | Veeam, Backblaze | — | [Acronis](https://www.acronis.com) 🇨🇭, [Keepit](https://www.keepit.com) 🇩🇰, [Proxmox Backup Server](https://www.proxmox.com) 🇦🇹, [Bareos](https://www.bareos.com) 🇩🇪, [Xopero](https://xopero.com) 🇵🇱 | [BorgBackup](https://www.borgbackup.org), [restic](https://restic.net), [Bareos](https://www.bareos.com) 🇩🇪 |
| VPN | ExpressVPN, IPVanish | — | [Proton VPN](https://protonvpn.com) 🇨🇭, [Mullvad](https://mullvad.net) 🇸🇪 | [WireGuard](https://www.wireguard.com), [OpenVPN](https://openvpn.net), [NetBird](https://netbird.io) 🇩🇪 |
| Two-factor authenticator | Google Authenticator, Authy | — | [Proton Authenticator](https://proton.me/authenticator) 🇨🇭 🆕 | [Aegis](https://getaegis.app) 🇳🇱, [Ente Auth](https://ente.io/auth/) |

## Business software

| Type | US product | Chinese product | EU alternative(s) | Open source |
|---|---|---|---|---|
| ERP | Oracle NetSuite, Microsoft Dynamics | — | [SAP](https://www.sap.com) 🇩🇪, [Odoo](https://www.odoo.com) 🇧🇪, [Exact](https://www.exact.com) 🇳🇱, [weclapp](https://www.weclapp.com) 🇩🇪, [Xentral](https://xentral.com) 🇩🇪 | [Odoo Community](https://github.com/odoo/odoo) 🇧🇪, [ERPNext](https://erpnext.com), [Dolibarr](https://www.dolibarr.org) 🇫🇷 |
| CRM | Salesforce, HubSpot | — | [Attio](https://attio.com) 🇬🇧, [SuperOffice](https://www.superoffice.com) 🇳🇴, [folk](https://www.folk.app) 🇫🇷, [Odoo CRM](https://www.odoo.com/app/crm) 🇧🇪 | [Twenty](https://twenty.com), [EspoCRM](https://www.espocrm.com), [SuiteCRM](https://suitecrm.com) 🇬🇧 |
| Accounting and invoicing | QuickBooks, Bill.com | — | [Pennylane](https://www.pennylane.com) 🇫🇷 🆕, [Lexware Office](https://office.lexware.de) 🇩🇪, [sevDesk](https://sevdesk.de) 🇩🇪, [Sellsy](https://www.sellsy.com) 🇫🇷 | [Akaunting](https://akaunting.com), [Invoice Ninja](https://invoiceninja.com), [GnuCash](https://www.gnucash.org) |
| HR and payroll | Workday, BambooHR, Gusto | — | [Personio](https://www.personio.com) 🇩🇪, [Factorial](https://factorialhr.com) 🇪🇸, [PayFit](https://payfit.com) 🇫🇷 | [OrangeHRM](https://www.orangehrm.com), [Frappe HR](https://frappe.io/hr) |
| E-commerce platform | Shopify | — | [Shopware](https://www.shopware.com) 🇩🇪, [PrestaShop](https://prestashop.com) 🇫🇷 | [PrestaShop](https://prestashop.com) 🇫🇷, [Shopware Community Edition](https://github.com/shopware/shopware) 🇩🇪, [Sylius](https://sylius.com) 🇵🇱 |
| Email marketing | Mailchimp | — | [Brevo](https://www.brevo.com) 🇫🇷 🆕, [MailerLite](https://www.mailerlite.com) 🇱🇹, [CleverReach](https://www.cleverreach.com) 🇩🇪, [GetResponse](https://www.getresponse.com) 🇵🇱 | [listmonk](https://listmonk.app), [Mautic](https://www.mautic.org) |
| Customer support | Zendesk, Intercom, Front | — | [Zammad](https://zammad.com) 🇩🇪, [Crisp](https://crisp.chat) 🇫🇷, [Trengo](https://trengo.com) 🇳🇱 | [Zammad](https://zammad.org) 🇩🇪, [Chatwoot](https://www.chatwoot.com), [FreeScout](https://freescout.net) |
| Web analytics | Google Analytics | — | [Piwik PRO](https://piwik.pro) 🇵🇱, [Plausible](https://plausible.io) 🇪🇪, [Simple Analytics](https://www.simpleanalytics.com) 🇳🇱, [Pirsch](https://pirsch.io) 🇩🇪 | [Matomo](https://matomo.org), [Plausible CE](https://github.com/plausible/analytics) 🇪🇪, [Umami](https://umami.is) |
| Product and UX analytics | FullStory, Mixpanel, Amplitude | — | [Contentsquare](https://contentsquare.com) 🇫🇷, [OpenPanel](https://openpanel.dev) 🇸🇪 | [PostHog](https://posthog.com), [OpenPanel](https://openpanel.dev) |
| E-signature | DocuSign, Adobe Sign | — | [Yousign / Youtrust](https://www.youtrust.com) 🇫🇷 🆕, [Skribble](https://www.skribble.com) 🇨🇭, [Signaturit](https://www.signaturit.com) 🇪🇸 | [DocuSeal](https://www.docuseal.com), [Documenso](https://documenso.com) 🇩🇪 |
| Website builder | Webflow, Squarespace, Wix | — | [Framer](https://www.framer.com) 🇳🇱, [Jimdo](https://www.jimdo.com) 🇩🇪 | [WordPress](https://wordpress.org), [Grav](https://getgrav.org) |
| Workflow automation | Zapier, Make | — | [n8n](https://n8n.io) 🇩🇪 🆕 | [n8n](https://n8n.io) 🇩🇪 (fair-code), [Node-RED](https://nodered.org), [Activepieces](https://www.activepieces.com) |
| Paid newsletter / memberships | Substack, Patreon | — | [Steady](https://steady.page) 🇩🇪 | [Ghost](https://ghost.org) |

## Development and design

| Type | US product | Chinese product | EU alternative(s) | Open source |
|---|---|---|---|---|
| Code hosting | GitHub, GitLab, Bitbucket | Gitee | [Codeberg](https://codeberg.org) 🇩🇪 🆕, [Forgejo](https://forgejo.org) 🇩🇪 (self-hosted) | [Forgejo](https://forgejo.org) 🇩🇪, [Gitea](https://about.gitea.com), [GitLab CE](https://about.gitlab.com/install/?version=ce) |
| CI/CD | GitHub Actions, CircleCI, Bitrise | — | [Woodpecker CI](https://woodpecker-ci.org) 🇪🇺, [Codemagic](https://codemagic.io) 🇬🇧 | [Woodpecker CI](https://woodpecker-ci.org), [Forgejo Actions](https://forgejo.org/docs/latest/user/actions/), [Jenkins](https://www.jenkins.io) |
| AI app builder | Bolt.new, Replit, v0 | — | [Lovable](https://lovable.dev) 🇸🇪 🆕 | [bolt.diy](https://github.com/stackblitz-labs/bolt.diy), [Dyad](https://www.dyad.sh) |
| UI / UX design | Figma | — | [Penpot](https://penpot.app) 🇪🇸 🆕 | [Penpot](https://penpot.app) 🇪🇸 |
| Vector database | Pinecone | — | [Qdrant](https://qdrant.tech) 🇩🇪, [Weaviate](https://weaviate.io) 🇳🇱 | [Qdrant](https://qdrant.tech) 🇩🇪, [Weaviate](https://weaviate.io) 🇳🇱, [pgvector](https://github.com/pgvector/pgvector) |
| Monitoring and error tracking | Datadog, New Relic, Sentry | — | [AppSignal](https://www.appsignal.com) 🇳🇱, [Bugsink](https://www.bugsink.com) 🇳🇱 | [Grafana](https://grafana.com) + [Prometheus](https://prometheus.io), [GlitchTip](https://glitchtip.com) |
| IDE | Visual Studio, VS Code | — | [JetBrains IDEs](https://www.jetbrains.com) 🇨🇿 | [VSCodium](https://vscodium.com), [Eclipse](https://eclipseide.org), [Zed](https://zed.dev) |

## Consumer apps and media

| Type | US product | Chinese product | EU alternative(s) | Open source |
|---|---|---|---|---|
| Maps and navigation | Google Maps, Apple Maps, Waze | Baidu Maps, Amap | [HERE WeGo](https://wego.here.com) 🇳🇱, [TomTom](https://www.tomtom.com) 🇳🇱, [CoMaps](https://www.comaps.app) 🇪🇺 🆕, [Komoot](https://www.komoot.com) 🇩🇪 | [OpenStreetMap](https://www.openstreetmap.org), [CoMaps](https://www.comaps.app), [OsmAnd](https://osmand.net) 🇳🇱 |
| Music streaming | Apple Music, Amazon Music, YouTube Music | QQ Music, NetEase Cloud Music | [Spotify](https://www.spotify.com) 🇸🇪, [Deezer](https://www.deezer.com) 🇫🇷, [Qobuz](https://www.qobuz.com) 🇫🇷 | [Navidrome](https://www.navidrome.org), [Jellyfin](https://jellyfin.org), [Funkwhale](https://www.funkwhale.audio) |
| Video hosting | YouTube, Vimeo | Bilibili, iQIYI | [Dailymotion](https://www.dailymotion.com) 🇫🇷, [PeerTube](https://joinpeertube.org) 🇫🇷 🆕, [Bunny Stream](https://bunny.net/stream/) 🇸🇮 | [PeerTube](https://joinpeertube.org) 🇫🇷 |
| Video editing app | — | CapCut | [Kdenlive](https://kdenlive.org) 🇪🇺, [Lightworks](https://lwks.com) 🇬🇧 | [Kdenlive](https://kdenlive.org), [Shotcut](https://shotcut.org), [OpenShot](https://www.openshot.org) |
| Podcast hosting | Libsyn, Buzzsprout | — | [Acast](https://www.acast.com) 🇸🇪, [Ausha](https://www.ausha.co) 🇫🇷, [Podigee](https://www.podigee.com) 🇩🇪 | [Castopod](https://castopod.org) 🇫🇷 |
| Audiobooks and e-books | Audible, Kindle Unlimited | — | [Storytel](https://www.storytel.com) 🇸🇪, [BookBeat](https://www.bookbeat.com) 🇸🇪 | [Audiobookshelf](https://www.audiobookshelf.org), [Calibre](https://calibre-ebook.com) |
| E-reader | Amazon Kindle | — | [PocketBook](https://pocketbook.de) 🇨🇭 | [KOReader](https://koreader.rocks) |
| Ride-hailing | Uber, Lyft | DiDi | [Bolt](https://bolt.eu) 🇪🇪, [Heetch](https://www.heetch.com) 🇫🇷 | — |
| Food delivery | Uber Eats, DoorDash | Keeta (Meituan) | [Delivery Hero (Glovo, foodora, foodpanda)](https://www.deliveryhero.com) 🇩🇪 | — |
| Online marketplace | Amazon, eBay | — | [Allegro](https://allegro.pl) 🇵🇱, [Bol](https://www.bol.com) 🇳🇱, [Zalando](https://www.zalando.com) 🇩🇪, [Vinted](https://www.vinted.com) 🇱🇹 | — |
| Discount online marketplace | — | Temu, Shein, AliExpress | [Allegro](https://allegro.pl) 🇵🇱, [Vinted](https://www.vinted.com) 🇱🇹, [Zalando](https://www.zalando.com) 🇩🇪 | — |
| Refurbished electronics | Amazon Renewed | — | [Back Market](https://www.backmarket.com) 🇫🇷, [Swappie](https://swappie.com) 🇫🇮 | — |

## Coming soon

Announced or in progress, not yet usable by everyone.

| Project | What it replaces | Status |
|---|---|---|
| [European Network for Payments](https://newsroom.kbc.com/bancomat-bizum-epiwero-sibs-mb-way-and-vipps-mobilepay-announce-the-creation-of-a-european-interoperability-entity-to-connect-their-respective-solution) 🇪🇺 | Visa, Mastercard | Wero, Bizum, Bancomat, MB WAY and Vipps MobilePay joined in Sept 2026 (~130M users, 13 countries). Shop payments expected around 2027. |
| [Digital euro](https://www.ecb.europa.eu/euro/digital_euro) 🇪🇺 | Visa, Mastercard rails | European Parliament approved its position in June 2026. Possible issuance by 2029. |
| [EU AI Gigafactories](https://eurohpc-ju.europa.eu) 🇪🇺 | US hyperscaler AI compute | Selection call closes Nov 2026, awards expected early 2027. |
| [EU OS](https://eu-os.eu) 🇪🇺 | Windows in public administration | Community proof of concept for a public-sector Linux desktop. |
| [Tuta Drive](https://tuta.com) 🇩🇪 | Google Drive | Closed beta since April 2026. |

## Not included

Often suggested as "European", but left out on purpose:

- **Startpage**: owned by System1 (US).
- **Opera**: Chinese-owned.
- **Pipedrive**: owned by Vista Equity (US) since 2020.
- **Jitsi**: owned by 8x8 (US).
- **OnlyOffice**: Russian roots. Use Euro-Office (a European fork) instead.
- **Aleph Alpha**: merging into Cohere (Canada), 2026.
- **Exoscale**: majority owner is América Móvil (Mexico).
- **Hornetsecurity**: acquired by Proofpoint (US) in Dec 2025.
- **Wolt, Deliveroo**: owned by DoorDash (US). **FreeNow**: owned by Lyft (US).
- **Matomo**: company based in New Zealand.
- **GitLab, Mattermost, Bitwarden, Signal, Brave, Thunderbird**: US organizations.
- **S3NS, Bleu, Delos Cloud, Workspace by STACKIT**: European operators running US hyperscaler software.

## Contributing

Pull requests are welcome. Only European-owned, actively maintained, publicly available products, please. Add a source that shows where the company is based and who owns it.

## License

[CC0 1.0 Universal](LICENSE)
