# Awesome N8N MSP Nodes [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of [n8n](https://n8n.io) nodes useful for Managed Service Providers (MSPs).  
> Inspired by [Awesome Selfhosted](https://github.com/awesome-selfhosted/awesome-selfhosted).

---

## Contents

- [Awesome N8N MSP Nodes ](#awesome-n8n-msp-nodes-)
  - [Contents](#contents)
  - [Accounting Platforms](#accounting-platforms)
  - [Alerting](#alerting)
    - [Monitoring \& Uptime](#monitoring--uptime)
    - [On-Call \& Incident Response](#on-call--incident-response)
  - [Backup \& DR](#backup--dr)
  - [Communication](#communication)
    - [Chat \& Collaboration](#chat--collaboration)
    - [Transactional Email](#transactional-email)
    - [SMS \& Voice](#sms--voice)
  - [CRM \& Marketing](#crm--marketing)
  - [Distributors](#distributors)
  - [Documentation](#documentation)
  - [Infrastructure \& Edge Services](#infrastructure--edge-services)
  - [Microsoft Management](#microsoft-management)
  - [Payment Platforms](#payment-platforms)
  - [PSA Tools](#psa-tools)
  - [Quoting \& Proposals](#quoting--proposals)
  - [RMM Tools](#rmm-tools)
  - [Security](#security)
    - [Endpoint Protection](#endpoint-protection)
    - [Network \& DNS Security](#network--dns-security)
    - [Password Management \& Access](#password-management--access)
    - [SaaS \& Cloud Security Monitoring](#saas--cloud-security-monitoring)
    - [Security Awareness \& Training](#security-awareness--training)
    - [Vulnerability \& Risk Management](#vulnerability--risk-management)
  - [Utilities](#utilities)
  - [Miscellaneous](#miscellaneous)
  - [Contributing](#contributing)
  - [License](#license)

---

## Accounting Platforms
- [QuickBooks Node](https://github.com/n8n-io/n8n/tree/master/packages/nodes-base/nodes/QuickBooks) - [QuickBooks](https://quickbooks.intuit.com/) accounting automation for invoices, expenses, and payments. *(by [n8n.io](https://github.com/n8n-io))*
- [Sage Intacct Node](https://www.npmjs.com/package/@avantguardllc/n8n-nodes-sageintacct) - [Sage Intacct](https://www.sage.com/en-us/sage-intacct/) finance and accounting automation. *(by [@avantguardllc](https://www.npmjs.com/~avantguardllc))*
- [Xero Node](https://github.com/n8n-io/n8n/tree/master/packages/nodes-base/nodes/Xero) - [Xero](https://www.xero.com/) accounting automation and invoice management. *(by [n8n.io](https://github.com/n8n-io))*

---

## Alerting

### Monitoring & Uptime
- [UptimeRobot Node](https://github.com/n8n-io/n8n/tree/master/packages/nodes-base/nodes/UptimeRobot) - [UptimeRobot](https://uptimerobot.com/) uptime and website monitoring automation. *(by [n8n.io](https://github.com/n8n-io))*

### On-Call & Incident Response
- [PagerDuty Node](https://github.com/n8n-io/n8n/tree/master/packages/nodes-base/nodes/PagerDuty) - [PagerDuty](https://www.pagerduty.com/) incident management and on-call alert automation. *(by [n8n.io](https://github.com/n8n-io))*

---

## Backup & DR
- [Cove Data Protection Node](https://www.npmjs.com/package/n8n-nodes-cove) - [N-able Cove](https://www.n-able.com/products/cove-data-protection/backup) server, workstation, and cloud account backups. *(by [@redanthrax](https://github.com/redanthrax))*
- [Druva MSP Node](https://github.com/msoukhomlinov/n8n-nodes-druva-msp) - [Druva MSP](https://www.druva.com/) cloud backup and data protection automation. *(by [msoukhomlinov](https://github.com/msoukhomlinov))*

---

## Communication

### Chat & Collaboration
- [Discord Node](https://github.com/n8n-io/n8n/tree/master/packages/nodes-base/nodes/Discord) - [Discord](https://discord.com/) chat automation and alerts for MSP teams. *(by [n8n.io](https://github.com/n8n-io))*
- [Microsoft Teams Node](https://docs.n8n.io/integrations/builtin/app-nodes/n8n-nodes-base.microsoftteams/) - [Microsoft Teams](https://www.microsoft.com/microsoft-teams) chat, meetings, and collaboration automation. *(by [n8n.io](https://github.com/n8n-io))*
- [Slack Node](https://github.com/n8n-io/n8n/tree/master/packages/nodes-base/nodes/Slack) - [Slack](https://slack.com/) internal chat and MSP notification automation. *(by [n8n.io](https://github.com/n8n-io))*

### Transactional Email
- [Acumbamail Node](https://www.npmjs.com/package/@avantguardllc/n8n-nodes-acumbamail) - [Acumbamail](https://acumbamail.com/) email and SMS campaign automation. *(by [@avantguardllc](https://www.npmjs.com/~avantguardllc))*
- [EmailIt Node](https://www.npmjs.com/package/@avantguardllc/n8n-nodes-emailit) - [EmailIt](https://emailit.io/) transactional and marketing email integration. *(by [@avantguardllc](https://www.npmjs.com/~avantguardllc))*
- [Maileroo Node](https://www.npmjs.com/package/@avantguardllc/n8n-nodes-maileroo) - [Maileroo](https://maileroo.com/) transactional email delivery automation. *(by [@avantguardllc](https://www.npmjs.com/~avantguardllc))*
- [Mailgun Node](https://github.com/n8n-io/n8n/tree/master/packages/nodes-base/nodes/Mailgun) - [Mailgun](https://www.mailgun.com/) transactional and marketing email automation. *(by [n8n.io](https://github.com/n8n-io))*
- [SendGrid Node](https://github.com/n8n-io/n8n/tree/master/packages/nodes-base/nodes/SendGrid) - [SendGrid](https://sendgrid.com/) transactional and marketing email delivery. *(by [n8n.io](https://github.com/n8n-io))*

### SMS & Voice
- [ClerkChat Node](https://www.npmjs.com/package/@avantguardllc/n8n-nodes-clerkchat) - [ClerkChat](https://clerk.chat/) two-way SMS and chat automation. *(by [@avantguardllc](https://www.npmjs.com/~avantguardllc))*
- [NetSapiens Node](https://www.npmjs.com/package/n8n-nodes-netsapiens) - [NetSapiens](https://www.netsapiens.com/) VoIP phone switch/PBX used by many MSPs and also by service providers to MSPs. *(by [@dszp](https://david.szpunar.com))*
- [Twilio Node](https://github.com/n8n-io/n8n/tree/master/packages/nodes-base/nodes/Twilio) - [Twilio](https://www.twilio.com/) SMS, call, and communication automation. *(by [n8n.io](https://github.com/n8n-io))*

---

## CRM & Marketing
- [HighLevel Node](https://github.com/n8n-io/n8n/tree/master/packages/nodes-base/nodes/HighLevel) - [HighLevel (Growably)](https://www.gohighlevel.com/) marketing and CRM automation platform. *(by [n8n.io](https://github.com/n8n-io))*
- [HubSpot Node](https://github.com/n8n-io/n8n/tree/master/packages/nodes-base/nodes/Hubspot) - [HubSpot](https://www.hubspot.com/) CRM, leads, and marketing automation. *(by [n8n.io](https://github.com/n8n-io))*

---

## Distributors
- [Pax8 Node](https://www.npmjs.com/package/@avantguardllc/n8n-nodes-pax8) - [Pax8](https://www.pax8.com/) cloud distributor API integration. *(by [@avantguardllc](https://www.npmjs.com/~avantguardllc))*
- [Sherweb Node](https://www.npmjs.com/package/@n8layer/n8n-nodes-sherweb) - [Sherweb](https://www.sherweb.com/) cloud distributor API integration. *(by [@n8layer](https://www.npmjs.com/~n8layer))*

---

## Documentation
- [Hudu Node (@avantguardllc)](https://www.npmjs.com/package/@avantguardllc/n8n-nodes-hudu) - [Hudu](https://www.hudu.com/) IT documentation platform integration. *(by [@avantguardllc](https://www.npmjs.com/~avantguardllc))*
- [Hudu Node (msoukhomlinov)](https://github.com/msoukhomlinov/n8n-nodes-hudu) - [Hudu](https://www.hudu.com/) IT documentation platform automation. *(by [msoukhomlinov](https://github.com/msoukhomlinov))*
- [IT Glue Node](https://www.npmjs.com/package/n8n-nodes-itglue) - [IT Glue](https://www.itglue.com/) documentation automation with access to all IT Glue objects and flexible assets. *(by [n8n Community](https://www.npmjs.com/~n8n))*

---

## Infrastructure & Edge Services
- [Cloudflare Node (Automations Project)](https://www.npmjs.com/package/n8n-nodes-cloudflare) - Comprehensive [Cloudflare](https://www.cloudflare.com/) node with 100+ API operations supported across Core Infrastructure, Developer Platform, Security, Media, Analytics, and Networking categories. *(by [Nskha Automations Project](https://github.com/Automations-Project))*
- [Cloudflare Node (n8n.io)](https://github.com/n8n-io/n8n/tree/master/packages/nodes-base/nodes/Cloudflare) - [Cloudflare](https://www.cloudflare.com/) DNS, firewall, and edge network automation. *(by [n8n.io](https://github.com/n8n-io))*

---

## Microsoft Management
- [CIPP Node (@avantguardllc)](https://www.npmjs.com/package/@avantguardllc/n8n-nodes-cipp) - [CIPP](https://cipp.app/) Microsoft 365 management and automation. *(by [@avantguardllc](https://www.npmjs.com/~avantguardllc))*
- [CIPP Node (davejlong)](https://github.com/davejlong/n8n-nodes-cipp) - [CIPP](https://cipp.app/) automation with strong support for user and licensing operations. *(by [davejlong](https://github.com/davejlong))*
- [CIPP Node (n8layer)](https://www.npmjs.com/package/@n8layer/n8n-nodes-cipp) - Automate [CIPP](https://cipp.app) with extended Microsoft 365 management options. *(by [n8layer](https://www.npmjs.com/~n8layer))*
- [Microsoft SharePoint Node](https://github.com/msoukhomlinov/n8n-nodes-microsoft-sharepoint) - [SharePoint](https://www.microsoft.com/microsoft-365/sharepoint) site and document automation. *(by [msoukhomlinov](https://github.com/msoukhomlinov))*

---

## Payment Platforms
- [FlexPoint Node](https://www.npmjs.com/package/@avantguardllc/n8n-nodes-flexpoint) - [FlexPoint](https://www.flexpoint.com/) eCommerce and payment platform integration. *(by [@avantguardllc](https://www.npmjs.com/~avantguardllc))*
- [Stripe Node](https://github.com/n8n-io/n8n/tree/master/packages/nodes-base/nodes/Stripe) - [Stripe](https://stripe.com/) payment processing and invoicing automation. *(by [n8n.io](https://github.com/n8n-io))*

---

## PSA Tools
- [Autotask Node](https://github.com/msoukhomlinov/n8n-nodes-autotask) - [Autotask](https://www.datto.com/autotask-psa/) PSA ticketing, time, invoicing, and project integration with webhook listener registration. *(by [msoukhomlinov](https://github.com/msoukhomlinov))*
- [ConnectWise PSA Node](https://mspcopilot.io/n8n-nodes/connectwise-psa) - [ConnectWise PSA](https://www.connectwise.com/platform/psa) PSA integration *(by [@j0dan](https://mspcopilot.io))*
- [HaloPSA Node](https://www.npmjs.com/package/@avantguardllc/n8n-nodes-halopsa) - [HaloPSA](https://halopsa.com/) professional services automation. *(by [@avantguardllc](https://www.npmjs.com/~avantguardllc))*
- [ServiceNow Node](https://github.com/n8n-io/n8n/tree/master/packages/nodes-base/nodes/ServiceNow) - [ServiceNow](https://www.servicenow.com/) service management and workflow automation. *(by [n8n.io](https://github.com/n8n-io))*

---

## Quoting & Proposals
- [ConnectWise CPQ (Sell) Node](https://github.com/msoukhomlinov/n8n-nodes-connectwise-cpq) - [ConnectWise CPQ](https://www.connectwise.com/platform/sell) quoting and proposal automation for MSP sales workflows. *(by [msoukhomlinov](https://github.com/msoukhomlinov))*
- [TurboDocx Node](https://www.npmjs.com/package/@turbodocx/n8n-nodes-turbodocx) - [TurboDocx](https://www.turbodocx.com) single and bulk e-signature and templating tool. *(by [@turbodocx](https://github.com/turbodocx/))*

---

## RMM Tools
- [Auvik Node](https://www.npmjs.com/package/n8n-nodes-auvik) - [Auvik](https://www.auvik.com/) Network device management and mapping (node is mostly read-only in initial release). *(by [msoukhomlinov](https://github.com/msoukhomlinov))*
- [ImmyBot Node](https://www.npmjs.com/package/@n8layer/n8n-nodes-immybot) - [ImmyBot](https://www.immy.bot/) RMM automation and integrations. *(by [n8layer](https://www.npmjs.com/~n8layer))*
- [NinjaOne Node](https://www.npmjs.com/package/@avantguardllc/n8n-nodes-ninjaone) - [NinjaOne](https://www.ninjaone.com/) RMM automation and integrations. *(by [@avantguardllc](https://www.npmjs.com/~avantguardllc))*
- [SyncroMSP Node](https://github.com/n8n-io/n8n/tree/master/packages/nodes-base/nodes/SyncroMSP) - [SyncroMSP](https://syncromsp.com/) PSA and RMM platform automation. *(by [n8n.io](https://github.com/n8n-io))*

---

## Security

### Endpoint Protection
- [Huntress Node](https://www.npmjs.com/package/@n8layer/n8n-nodes-huntress) - [Huntress](https://huntress.io/) endpoint protection and threat response. *(by [@n8layer](https://www.npmjs.com/~n8layer))*
- [SentinelOne Node](https://www.npmjs.com/package/@avantguardllc/n8n-nodes-sentinelone) - [SentinelOne](https://www.sentinelone.com/) endpoint protection and threat response. *(by [@avantguardllc](https://www.npmjs.com/~avantguardllc))*

### Network & DNS Security
- [DefensX Node](https://www.npmjs.com/package/n8n-nodes-defensx) - [DefensX](https://www.defensx.com/) DNS and endpoint security, and content filtering, and remote access. *(by [@dszp](https://david.szpunar.com))*
- [DNSFilter Node](https://www.npmjs.com/package/@avantguardllc/n8n-nodes-dnsfilter) - [DNSFilter](https://www.dnsfilter.com/) DNS security and policy management. *(by [@avantguardllc](https://www.npmjs.com/~avantguardllc))*
- [UniFi Site Manager](https://mspcopilot.io/n8n-nodes/unifi-sitemanager) - [UniFi Site Manager API](https://developer.ui.com/site-manager-api/gettingstarted) This is for the UI.com cloud site manager. *(by [j0dan](https://mspcopilot.io))*
- [Zorus Node](https://www.npmjs.com/package/@n8layer/n8n-nodes-zorus) - [Zorus](https://www.zorus.com/) DNS security and policy management. *(by [@n8layer](https://www.npmjs.com/~n8layer))*


### Password Management & Access
- [1Password Node](https://www.npmjs.com/package/@n8layer/n8n-nodes-1password) - [1Password](https://1password.com/) password manager and vault automation. *(by [@n8layer](https://www.npmjs.com/~n8layer))*
- [Bitwarden Node](https://github.com/n8n-io/n8n/tree/master/packages/nodes-base/nodes/Bitwarden) - [Bitwarden](https://bitwarden.com/) password manager automation. *(by [n8n.io](https://github.com/n8n-io))*

### SaaS & Cloud Security Monitoring
- [SaaS Alerts Node](https://www.npmjs.com/package/@avantguardllc/n8n-nodes-saasalerts) - [SaaS Alerts](https://www.saasalerts.com/) SaaS security monitoring for MSPs. *(by [@avantguardllc](https://www.npmjs.com/~avantguardllc))*

### Security Awareness & Training
- [Phin Node](https://www.npmjs.com/package/@avantguardllc/n8n-nodes-phin) - [Phin Security](https://phinsec.io/) security awareness training automation. *(by [@avantguardllc](https://www.npmjs.com/~avantguardllc))*

### Vulnerability & Risk Management
- [ConnectSecure Node](https://www.npmjs.com/package/@avantguardllc/n8n-nodes-connectsecure) - [ConnectSecure](https://connectsecure.com/) vulnerability scanner automation. *(by [@avantguardllc](https://www.npmjs.com/~avantguardllc))*
- [SecurityScorecard Node](https://github.com/n8n-io/n8n/tree/master/packages/nodes-base/nodes/SecurityScorecard) - [SecurityScorecard](https://securityscorecard.com/) cybersecurity ratings and risk analysis automation. *(by [n8n.io](https://github.com/n8n-io))*

---

## Utilities
- [OpenAPI Node](https://www.npmjs.com/package/@avantguardllc/n8n-openapi-node) - Convert [OpenAPI](https://www.openapis.org/) specs into n8n nodes. *(by [@avantguardllc](https://www.npmjs.com/~avantguardllc))*
- [PXL Node](https://www.npmjs.com/package/@avantguardllc/n8n-nodes-pxl) - [PXL](https://pxl.to/) link shortener and tracking automation. *(by [@avantguardllc](https://www.npmjs.com/~avantguardllc))*
- [WebhookSite Node](https://www.npmjs.com/package/@avantguardllc/n8n-nodes-webhooksite) - [Webhook.site](https://webhook.site/) webhook testing and inspection. *(by [@avantguardllc](https://www.npmjs.com/~avantguardllc))*

---

## Miscellaneous
- [Printix Node](https://www.npmjs.com/package/@n8layer/n8n-nodes-printix-cloud-print) - [Tungsten Printix](https://printix.net/) cloud printing automation. *(by [@n8layer](https://www.npmjs.com/~n8layer))*

---

## Contributing

Contributions are welcome! Please read the [Contributing Guidelines](CONTRIBUTING.md) before submitting a pull request.

---

## License

[![MIT License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)

This project is licensed under the MIT License.
