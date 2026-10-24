# Pilcrow Privacy Policy

*Other languages (AI translations; this English version is the clearest statement of the policy):* [Español](privacy-policy.es.md) · [Français](privacy-policy.fr.md) · [Deutsch](privacy-policy.de.md) · [Italiano](privacy-policy.it.md) · [Português (Brasil)](privacy-policy.pt-BR.md) · [Nederlands](privacy-policy.nl.md) · [Русский](privacy-policy.ru.md) · [日本語](privacy-policy.ja.md) · [한국어](privacy-policy.ko.md) · [简体中文](privacy-policy.zh-Hans.md)

**Effective:** October 20, 2026

**Publisher:** PluriaLabs

**Privacy contact:** support@plurialabs.com

Pilcrow is a text editor for Mac and iPad. It is designed to keep your writing under your control and to work without an account, advertising, analytics or tracking.

This policy explains how the Pilcrow app handles information. It also explains what PluriaLabs receives if you contact us directly. It does not govern Apple, an AI service you choose, a website you visit, or another third-party service. Those parties apply their own terms and privacy policies.

## The short version

- Pilcrow does not require or provide a Pilcrow account.
- Pilcrow contains no advertising, analytics SDK, tracking SDK or PluriaLabs-operated telemetry service.
- Your documents and Pilcrow settings are stored locally or in a storage location you choose. PluriaLabs does not receive them.
- The optional Assistant is off until you configure it. At your direction, Pilcrow can transmit material directly from your device to an AI service or other endpoint you choose. PluriaLabs does not receive or retain a copy.
- Loading a remote image or opening a link contacts the relevant third party. Remote images are disabled by default.
- PluriaLabs does not receive your documents or feature-usage history from Pilcrow. We may receive information you deliberately send us, such as in a support email, and limited distribution, purchase or diagnostic information that Apple makes available.

## Information stored by Pilcrow

Pilcrow stores the following information on your device or in a storage location you select:

- **Documents.** Pilcrow opens and saves files where you keep them. PluriaLabs does not receive a copy.
- **Recovery data.** To help recover work after a crash or interruption, Pilcrow temporarily keeps unsaved text in the app's private storage. Pilcrow removes its recovery copy after the document is saved or closed normally. Copies may remain temporarily in device, filesystem or cloud backups controlled by you or your storage provider.
- **Library items and settings.** Themes, syntax profiles, macros, style guides, backdrops and preferences are stored locally. By default, library items are kept in Pilcrow's private app storage. You may instead choose another folder, including a folder that a storage provider synchronizes.
- **Recent items.** Pilcrow can remember references to recently opened files and folders so that you can reopen them. You can disable this feature or clear the list in Settings or the File menu.
- **Writing statistics.** Information such as word counts and session times is calculated and stored for your use. Pilcrow does not transmit these statistics to PluriaLabs.
- **Diagnostic log.** Pilcrow keeps a short log on your device of problems it meets. While you have turned on **Record diagnostic log** in Settings, it also records more detail about what the app is doing. The log is designed to leave out your document text and file names, and you can read it in the app and clear it at any time. Pilcrow does not send it to PluriaLabs automatically. A report leaves your device only if you choose to save, share or send it, and you choose which extra information (device and system details, Pilcrow settings, speed and memory figures, recent actions) it includes. If you report a problem on GitHub, what you post there is public. Where Pilcrow offers it, you can send a report to PluriaLabs support, which receives the copy you send.
- **Assistant credentials.** Credentials for services you configure are stored using the system Keychain. Your operating-system, iCloud Keychain and backup settings may affect whether Keychain items are synchronized or backed up by Apple.

Pilcrow does not intentionally use document content, local settings, recent-item references, writing statistics or Assistant credentials for advertising, profiling or analytics.

### Storage providers and backups

If you save a document or library folder in iCloud Drive or another synchronized location, that provider receives and processes the files in order to store and synchronize them. Pilcrow enables your chosen storage location but PluriaLabs does not receive the provider's copy. The provider's privacy policy and your account settings govern its processing.

Deleting information in Pilcrow or from your device does not necessarily delete copies retained in backups, version history, recently deleted folders or another provider's systems. Manage those copies through the applicable device or provider controls.

## Optional Assistant

The Assistant, including style review, is disabled until you add a connection in **Settings ▸ Assistant**. You may connect it to an online AI service, a custom endpoint, software running on your device, or a service on your local network.

### Your choice and permission

Pilcrow sends Assistant content only after you take an action such as **Send** or **Review**. Before the first content submission to a remote service, Pilcrow identifies the configured destination, describes the material that will be transmitted and asks for your permission. A preview lets you inspect the document material and user instructions selected for submission.

You can decline and continue using Pilcrow without the Assistant. You can later revoke permission for future submissions by removing the connection, disabling the Assistant for a folder, or resetting the Assistant. Revoking permission does not retrieve information already received by a service; use that service's controls to request access or deletion where available.

### Information included in a request

Depending on the action you choose, an Assistant request may contain:

- your question, instruction or other text entered for the Assistant;
- the document material you selected, such as a selection, the current section, text around the cursor, a document preview or the whole document;
- for style review, the text being reviewed and the selected style-guide rules;
- instructions Pilcrow supplies to make the requested Assistant feature work;
- the model name and technical request settings;
- the credential for the configured service, normally sent in an authentication header; and
- ordinary network information visible to the recipient, such as your IP address, request time, destination URL and protocol headers.

Pilcrow may separately request a connected service's model list. That request does not include document content or an Assistant conversation, but it may include the configured credential and ordinary network information.

The preview is intended to show the document material and user instructions selected for transmission. It may not display authentication headers, Pilcrow's functional instructions, request formatting or ordinary network metadata.

### Excluded files and folders

Pilcrow blocks Assistant actions initiated from files and folders that match your configured exclusions. The default exclusions include sensitive-looking paths such as `.env*`, `*.pem`, `*.key` and `secrets/`. You may change the exclusions or disable the Assistant for a folder.

Exclusions are a safety aid, not a substitute for reviewing a request. They cannot recognize every kind of confidential information, prevent you from copying excluded material into a non-excluded file or prompt, or control information already sent to a service. Check the preview before submitting sensitive material.

### Who receives Assistant information

The operator of the endpoint you configured receives the request. It is an independent recipient selected by you, not an Assistant service provider selected by PluriaLabs. PluriaLabs does not operate an Assistant proxy and does not receive, inspect or retain a copy of the request or response.

An online service may retain requests and responses, allow personnel or subprocessors to access them, process them in another country, or use them to enforce policies or improve services or models. Its practices may depend on your account type, contract and settings and may change over time. Pilcrow and PluriaLabs cannot control or guarantee the privacy, security, availability or deletion practices of a service you choose.

Review the terms and data controls that apply to your account before connecting a service:

- [OpenAI Privacy Policy](https://openai.com/policies/privacy-policy/)
- [Anthropic Privacy Policy](https://www.anthropic.com/legal/privacy)
- [OpenRouter Privacy Policy](https://openrouter.ai/privacy/)
- for any other endpoint, the operator's terms and privacy information

OpenRouter and similar routing services may transmit a request to a separate model provider. In that case, both the routing service and the selected model provider may process the request under their respective terms.

Do not send confidential, personal, regulated or otherwise sensitive information unless you are authorized to do so and the destination's terms, security and data controls meet your needs. A service running under your control may be more appropriate for sensitive material.

### Local and custom endpoints

If the configured address is a loopback address for software such as Ollama or LM Studio, Pilcrow sends its request to that software on your device. That software is separate from Pilcrow and may have its own storage, logging, extension or network behavior.

If you connect to another device on your local network, the request travels over that network. An `http` connection is not encrypted in transit. Pilcrow warns you before using an unencrypted connection. Prefer `https` unless you control and trust the device and network.

A custom endpoint is supplied and controlled by you. Pilcrow cannot verify who operates it, where it ultimately routes information, whether its certificate or domain remains under the same control, or what it does with requests. Confirm the complete address before saving or using a custom connection.

### Credentials, history and deletion

Pilcrow retrieves a credential from Keychain when it needs to authenticate a request to its configured endpoint. PluriaLabs does not receive the credential. Removing a connection or resetting the Assistant instructs Pilcrow to delete the corresponding Keychain item. You should also revoke or rotate the credential through the service if you no longer want it to authorize access.

Assistant conversations and review results are held for the active app session. Pilcrow does not intentionally save them as a persistent conversation history. They are discarded when the app quits or when you reset the Assistant. As with other application memory, the operating system may manage temporary memory, crash state and device backups independently of Pilcrow.

Resetting the Assistant removes its saved connections, associated Keychain credentials, in-session conversation and review results, and Assistant privacy choices from Pilcrow. It does not delete information already received by an external service.

## Other network activity

### Remote images

A document may refer to an image on the internet. Pilcrow does not load remote images by default, including in Preview and PDF or image export. If you enable **Load images from the internet** in **Settings ▸ Editing ▸ Images**, Pilcrow requests those images when needed.

The image host and any redirect destination may receive your IP address, the date and time, the complete requested URL and its query string, protocol headers and other ordinary connection information. A document author can use a unique image URL to learn that the document was opened. Pilcrow does not add an advertising or tracking identifier to the request, but it cannot prevent the host from logging or analyzing the request. Disable remote images when reading untrusted or sensitive documents.

### Links and document content

Opening a link in a document sends the destination to your selected browser or system handler. The destination and your browser then govern the resulting network activity.

Pilcrow does not execute scripts embedded in a document. Diagrams, equations and charts provided by Pilcrow are rendered locally. Apart from content you deliberately send through the Assistant, remote images you enable, and links you choose to open, Pilcrow does not intentionally cause document content to contact a remote destination.

### Connections to PluriaLabs

Pilcrow has no PluriaLabs-operated analytics, advertising, tracking, document-sync or Assistant proxy service. It does not send your documents, writing statistics, local logs or feature-usage history to PluriaLabs. A diagnostic report reaches PluriaLabs only if you choose to send it to us.

## Apple services, purchases and diagnostics

Apple processes App Store downloads, purchases, receipts, updates, iCloud activity, device backups and other Apple services under [Apple's Privacy Policy](https://www.apple.com/legal/privacy/). Pilcrow does not receive your Apple Account password or payment-card details.

Apple may provide PluriaLabs with sales, transaction or subscription reporting associated with distribution of the app. Apple may also provide crash or performance diagnostics if you have enabled sharing diagnostics with app developers. Pilcrow does not use this information for advertising or tracking. PluriaLabs uses information made available by Apple only to administer distribution, verify or support a purchase, understand crashes, maintain security and improve reliability. The information available and its retention are governed in part by Apple's systems and your Apple settings.

## Information you send to PluriaLabs

If you email PluriaLabs or otherwise contact us, we receive the information you choose to provide. This may include your email address, name, message, attachments, diagnostic logs, purchase information and any document excerpt you include.

We use this information to respond to you, provide requested support, investigate reliability or security problems, maintain appropriate business records and comply with legal obligations. Depending on the request, this processing is necessary to provide the support you requested, to perform or prepare to perform a contract, to comply with law, or for our legitimate interests in supporting and securing Pilcrow.

Support email is not end-to-end encrypted by default. Do not send an account credential, an entire sensitive document or other information that is unnecessary for the request.

We retain support correspondence only as long as reasonably necessary for these purposes, including follow-up, security, dispute resolution, recordkeeping and legal requirements. Our email and infrastructure providers may process it on our behalf. We select providers whose commitments require them to protect information consistently with their agreements and applicable law. We do not sell support information, share it for cross-context behavioral advertising, or use it to train an AI model.

Providing information for support is voluntary, but we may be unable to answer or investigate a request without enough information to understand it and contact you. PluriaLabs does not use support information to make decisions about you based solely on automated processing.

PluriaLabs and its email or infrastructure providers may process support information in countries other than yours. Where applicable law requires a transfer mechanism or other safeguard for an international transfer, we use one provided by law or by the relevant service provider.

## Your choices and privacy rights

You can control most information described in this policy directly:

- choose where documents and library items are stored;
- disable or clear recent items;
- choose whether to include local logs or other attachments in a support request;
- leave the Assistant disabled, review each submission, manage exclusions, remove individual connections or reset the Assistant;
- revoke service credentials with the service that issued them;
- disable remote images; and
- manage iCloud, Keychain, backup, App Store and diagnostic-sharing choices in Apple settings.

Privacy laws may also give you rights over personal information PluriaLabs holds about you, including rights to request access, correction or deletion, to object to or restrict certain processing, or to receive a portable copy. These rights vary by location and may be subject to exceptions. To make a request, email support@plurialabs.com. We may need enough information to verify the request and locate the relevant correspondence.

Where PluriaLabs relies on your consent to process information, you may withdraw that consent for future processing. Withdrawal does not affect processing that was lawful before the withdrawal.

Because PluriaLabs does not receive your locally stored documents or Assistant exchanges, we cannot access, export, correct or delete those copies for you. Contact the applicable storage or AI provider about information in its systems.

You may also complain to the data-protection or privacy authority where you live. PluriaLabs will not discriminate against you for exercising an applicable privacy right.

## Children

Pilcrow is a general-purpose writing tool and is not directed to children. PluriaLabs does not knowingly collect personal information from children through the app.

Online AI services and other third parties set their own minimum ages and parental-consent requirements. A parent, guardian or school responsible for a minor should review those requirements before allowing the minor to configure or use an online service through Pilcrow. If you believe a child sent personal information directly to PluriaLabs, contact support@plurialabs.com so that we can review and, where appropriate, delete it.

## Security

Pilcrow limits information sent to PluriaLabs by keeping its core editor functions local. No storage or transmission method is completely secure, however. Protect your device, storage-provider account and AI credentials; use strong access controls; keep system software current; and review destinations before transmitting sensitive material.

## Changes to this policy

We may update this policy to reflect changes in Pilcrow, law or third-party services. The current version will be posted at the same location with a revised effective date. Earlier versions remain available through the public version history of this policy repository.

If a change materially affects information transmitted by the Assistant or another optional network feature, Pilcrow will provide notice before the feature next transmits that information and will request new permission when required.

## Contact

Questions, privacy requests and concerns about this policy may be sent to:

**PluriaLabs**

**Email:** support@plurialabs.com
