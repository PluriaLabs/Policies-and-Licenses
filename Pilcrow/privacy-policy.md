# Pilcrow Privacy Policy

**Effective:** [DATE — set when published]  ·  **Published by:** [LEGAL NAME OR COMPANY, e.g. PluriaLabs]  ·  **Contact:** [CONTACT EMAIL]

Pilcrow is a text editor for Mac and iPad. It keeps your writing on your device. This page says what the app does with your information, in plain terms.

## The short version

- Pilcrow has **no accounts, no advertising, no analytics and no tracking**. It does not collect data about you.
- Your documents stay on your device, in the files you open. We never receive them.
- The optional **AI assistant** is off until you set it up. When you use it, Pilcrow sends what you choose to the AI service **you** selected, using **your** account. That service, not us, receives and handles it. Details below.
- You can turn the assistant off, and remove everything it stores, whenever you like.

## What stays on your device

- **Your documents.** Pilcrow opens and saves files where you keep them, including folders such as iCloud Drive that you have chosen. Pilcrow does not copy them anywhere else. If you keep files in iCloud Drive, Apple handles syncing under Apple's own terms.
- **Recovery copies.** To protect your work after a crash, Pilcrow keeps a copy of unsaved text in its own private storage on your device. It is removed when you save or close the document.
- **Your library and settings.** Themes, syntax profiles, macros, style guides, backdrops and your preferences are stored on your device. By default the library is in Pilcrow's private storage; in Settings you can choose a folder for it instead. If you choose a folder in iCloud Drive, Apple syncs that folder under Apple's own terms, and Pilcrow does not see or handle that copy. Preferences, account keys and recovery copies are never moved to the folder you choose.
- **Recent files and folders.** Pilcrow remembers which files and folders you opened recently, as references stored on your device, so it can reopen them. You can turn this off or clear the list in Settings and in the File menu.
- **Writing statistics** such as word counts and session times are stored on your device for your own use. They are never sent anywhere.
- **Diagnostic information** is written to log files on your device. It is not sent to us or to anyone else.

## The AI assistant (optional)

The assistant, including its style review, works only after you add a connection in **Settings ▸ Assistant**. You can connect to a service on the internet (for example OpenAI, Anthropic or OpenRouter, or another service you type in) or to an AI model running on your own computer or local network.

**What is sent.** When you ask a question or run a review, Pilcrow sends the request to the address you configured. That request contains:

- your question or instruction;
- the part of your document you chose to share (your selection, the section you are in, the line around your cursor, a preview of the document, or the whole document);
- for a style review, the text being reviewed and the rules of the style guide you picked;
- the name of the AI model you chose, and your account key, so that the service can accept the request.

Separately, Pilcrow may ask a connected service for the list of models it offers, sending only your account key, so that it can tell you if your chosen model is no longer available.

Nothing is sent until you press Send or Review. Before the first send to a service, Pilcrow tells you where the text is going, what is sent and how to take it back, and asks you to confirm. You can see exactly what will be sent first with **Preview**.

**What is never sent.** Files whose names match your exclusion list (by default files such as `.env*`, `*.pem`, `*.key` and `secrets/`) and folders where you have turned the assistant off are never shared. Pilcrow does not send anything in the background: no document text, no usage information.

**Who receives it.** The company that runs the service you chose. Pilcrow's publisher does not receive, see, store or process these requests. Each service has its own privacy policy and its own rules on how long it keeps requests, who can read them, and whether it uses them to improve its models. These rules differ between services, and between account types and settings, and they can change. Before you connect, read the policy of the service you choose:

- OpenAI: https://openai.com/policies/privacy-policy/
- Anthropic: https://www.anthropic.com/legal/privacy
- OpenRouter (which passes requests on to the model provider you pick): https://openrouter.ai/privacy, and the policy of the model provider
- Any other service you add: its own policy

**Please do not send what you would not want a third party to see.** If a document contains confidential, personal or sensitive information, do not share it with an online service unless that service's terms are acceptable to you. Use a model on your own computer, or leave that text out, if you need it to stay private.

**Services on your own computer or network.** If you connect to a model on your own computer (such as Ollama or LM Studio), the request goes to that program and does not leave your computer. If you connect to a computer on your local network, the request travels over that network. Unless the address uses https, it is not encrypted, so Pilcrow asks you to confirm before it will do this. Pilcrow never sends unencrypted requests to addresses on the internet.

**Your account key.** The key for each service is stored in your device's Keychain. It is sent only to the service it belongs to, as proof of your account. It is never sent to anyone else, and we never see it.

**Conversation history.** The conversation and the review results stay in memory while the app is open. Pilcrow does not write them to disk, and they are gone when you quit. Pilcrow keeps no log of what was sent or received.

**Retention and deletion.** Pilcrow keeps nothing the assistant sends or receives. What a service keeps, and for how long, is decided by that service; to see or delete it, use that service's account tools or contact it.

**Turning it off.** In **Settings ▸ Assistant** you can remove a connection (which deletes its key from your Keychain), turn the assistant off for one folder, change the excluded files, or choose **Reset** to remove all connections and saved keys, the conversation and your privacy choices and turn the assistant off. To stop a service from using your account, you can also delete or rotate the key in that service's dashboard.

## Other network activity

- **Images from the internet.** A document can contain a picture that points to a web address. By default Pilcrow does **not** download it: Preview and PDF or image exports leave it out, so the site hosting it learns nothing. If you turn on **Load images from the internet** in Settings ▸ Images, Pilcrow fetches those pictures like a web browser does, and the site that hosts each one can see the request (your device's address and the time). You can turn it off again at any time. Pilcrow adds no tracking of its own to these requests.
- **Scripts in documents.** Pilcrow does not run scripts that a document contains, and a document cannot make Pilcrow contact a website other than for the pictures you allowed above.
- **Diagrams, equations and charts** are drawn on your device. Nothing is downloaded for them.
- Pilcrow does not check anything with its publisher and does not contact it.

## Children

Pilcrow is a general-purpose tool and is not directed to children. It does not knowingly collect information from anyone.

## Changes

If this policy changes, the new version will be posted at this address with a new effective date. If a change affects what the assistant sends, the app will tell you before you next use it.

## Contact

Questions about this policy: [CONTACT EMAIL].
