# Polylogue Privacy Policy

**Effective:** when Polylogue is first released

**Publisher:** PluriaLabs

**Privacy contact:** support@plurialabs.com

Polylogue is a Mastodon app for iPhone, iPad and Mac that helps you read and reply across languages. It is designed to work without a Polylogue account, advertising, analytics or tracking.

This policy explains how the Polylogue app handles information. It also explains what PluriaLabs receives if you contact us directly. It does not govern Apple, your Mastodon server or any other server, an AI service you choose, a website you visit, or another third-party service. Those parties apply their own terms and privacy policies.

## The short version

- Polylogue does not require or provide a Polylogue account. You sign in to a Mastodon server you choose.
- Polylogue contains no advertising, analytics SDK, tracking SDK or PluriaLabs-operated telemetry service.
- What you read and write travels between your device and your Mastodon server. PluriaLabs does not receive it.
- Translation uses Apple's Translation framework on your device by default.
- AI translation is off until you turn it on with your own API key. It then sends text of public and quiet public posts and replies directly to the service you chose. PluriaLabs does not receive it.
- Every Polylogue feature is free. Optional support and roadmap voting are planned and are not in the app yet.

## Your Mastodon server

To sign in, Polylogue registers itself with the server you enter and opens that server's sign-in page in your web browser. You enter your password there; Polylogue never receives it. The server gives Polylogue an access token with permission to read, write, follow and receive push notifications for your account. Polylogue stores the token and the server address in the Keychain on that device only.

Everything you do in Polylogue, such as posting, uploading media, voting in polls, searching, following, blocking, reporting and editing your profile, is sent to your server. Your server processes it under its own rules and privacy policy, and may share public and addressed content with other servers in the network. Deleting a post asks your server to delete it; copies held by other servers or people may remain.

If you forward a report, the moderators of the other account's server receive it too.

Signing out removes the token from your device. To withdraw Polylogue's access on the server as well, remove it from the authorized apps in your Mastodon account settings.

## Other network connections

Showing a timeline means loading avatars, images, video and link previews from the addresses your server supplies, which may be on other servers. Opening a news article in Polylogue loads that website inside the app, and the site may set cookies or collect information as it would in a browser. Opening a link or sharing a post hands it to the app or browser you choose.

Any host that is contacted can see ordinary connection information such as your IP address, the time and the address requested.

## Translation

**Apple Translation and text recognition.** Posts are translated, and text in images is recognized, on your device using Apple's frameworks. Apple may download language resources to your device under [Apple's Privacy Policy](https://www.apple.com/legal/privacy/).

**Optional AI translation.** If you turn it on in **Preferences** and save an API key, Polylogue can send text to OpenAI, Anthropic, Google Gemini or an OpenAI-compatible HTTPS endpoint that you enter. Depending on your settings and what you do, a request may contain:

- the text of a public or quiet public post, which may have been written by someone else;
- text recognized in an image from such a post (the text, not the image);
- the text of a public or quiet public reply you are writing, when you ask for a translated preview or ask for it to be shortened (the addresses at the start of the reply are left out);
- the source and target language names and the instructions Polylogue supplies;
- the model name and technical settings, and your API key for that service; and
- ordinary network information such as your IP address.

Polylogue does not send followers-only or direct posts to an AI service. Content warnings can be added to public posts; a warning does not by itself stop a public post's text from being sent.

Polylogue asks you to confirm the first time a post, recognized image text or a reply is sent to a service. It asks again for a different service or a different custom endpoint, and does not ask again for one you have confirmed. If you turn on automatic AI translation or put AI before Apple Translation, posts may be sent as they appear on screen without further prompts. Polylogue may also request the service's list of models, using your key.

The service you choose is an independent recipient. It may keep requests, process them in other countries or use them as its terms allow, and may charge you. Review its policy before using it:

- [OpenAI Privacy Policy](https://openai.com/policies/privacy-policy/)
- [Anthropic Privacy Policy](https://www.anthropic.com/legal/privacy)
- [Google Privacy Policy](https://policies.google.com/privacy)
- for any other endpoint, the operator's terms and privacy information

## Information stored on your device

- **Credentials.** Your Mastodon token and any AI API keys are stored in the Keychain, on that device only.
- **Settings.** Preferences such as reading language, translation choices, AI service, model and endpoint.
- **Drafts.** Unfinished post and reply text, and your original text for replies you published in translation.
- **Translation caches.** Recent translations and text recognized in images, which may include text from private posts translated on your device.

Signing out does not erase drafts, translation caches, settings or AI keys. You can clear the translation cache and remove each API key in **Preferences**. Deleting the app removes its stored files; Keychain items and device backups are handled by Apple's systems and your settings.

## Supporting Polylogue and roadmap voting

These features are planned and are **not in the current app**. When they are added, they are intended to work as they do in Pilcrow:

- Every feature stays free. You may subscribe monthly for three voting credits, or buy single credits. Apple processes every purchase; Polylogue does not receive your payment-card details or Apple Account password.
- Your credit list is kept on your device and, if you use iCloud, in your private iCloud database, which PluriaLabs cannot read.
- A vote is recorded in a public iCloud (CloudKit) database that PluriaLabs operates. It holds the roadmap item and round, the credit used, a random identifier, an anonymous identifier CloudKit assigns for this app, and the time. It holds no name, email address, Mastodon account or post. Other users may be able to see vote records.

We will update this policy before these features become available.

## Apple services and diagnostics

Apple processes App Store downloads, updates, purchases, device backups and other Apple services under [Apple's Privacy Policy](https://www.apple.com/legal/privacy/). Apple may provide PluriaLabs with sales reporting and, if you have enabled sharing with app developers, crash or performance diagnostics. We use this only to distribute the app, understand crashes and improve reliability.

## Information you send to PluriaLabs

If you email us or otherwise contact us, we receive what you choose to provide, such as your email address, name, message and attachments. We use it to respond, provide support, investigate reliability or security problems, keep appropriate records and comply with legal obligations, and keep it only as long as reasonably necessary. Our email and infrastructure providers may process it on our behalf, possibly in other countries, with safeguards where law requires them. We do not sell it, share it for cross-context behavioral advertising or use it to train an AI model.

## Your choices and privacy rights

You can choose your server, leave AI translation off, remove API keys, clear the translation cache, sign out and revoke access on your server.

Privacy laws may give you rights over personal information PluriaLabs holds about you, including access, correction, deletion, objection, restriction and portability. To make a request, email support@plurialabs.com. Because we do not receive your posts, account data or AI requests, contact your Mastodon server or AI service about information they hold. You may also complain to the data-protection authority where you live. PluriaLabs will not discriminate against you for exercising a privacy right.

## Children

Polylogue is not directed to children, and PluriaLabs does not knowingly collect personal information from children through the app. Mastodon servers show content written by others and set their own minimum ages, as do AI services. If you believe a child sent personal information directly to PluriaLabs, contact support@plurialabs.com.

## Security

Polylogue limits what reaches PluriaLabs by connecting your device directly to the services you choose. No storage or transmission method is completely secure. Protect your device, your Mastodon account and your API keys, and keep system software current.

## Changes to this policy

We may update this policy to reflect changes in Polylogue, law or third-party services. The current version will be posted at this address with a revised effective date.

## Contact

**PluriaLabs**

**Email:** support@plurialabs.com
