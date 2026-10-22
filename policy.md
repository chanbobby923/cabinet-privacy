# Cabinet privacy policy

**Effective and last updated: 23 October 2026.**

Cabinet is provided by Pathex Limited (“Pathex”, “we”, “us”). This policy explains how we handle information when you use the Cabinet iOS app and contact us about it. It does not describe every feature or service on the separate Pathex website.

Contact us about privacy or support at **info@pathex.io**. Our website is [www.pathex.io](https://www.pathex.io/).

## What Cabinet handles

**Your saved material.** You choose screenshots, images, videos, audio, documents, links and text to save. Cabinet can derive searchable text, notes, summaries, Wiki pages, source references and conversation history from that material. Your library is stored in an account-specific area on your device. Signing in does not automatically upload your whole library or make it public. Device backups and exports you create can contain separate copies.

**Account information.** When you create or use an account, our authentication service handles your email address, account identifier, sign-in credentials and session information. If you sign in through Apple or Google, the information we receive depends on that provider and your choices, and can include your name, email address and provider account identifier.

**Preferences and personal context.** Cabinet stores settings, processing permissions, reminders and any personal background you choose to enter. Personal background is used for supported on-device personalization; it is excluded from Cabinet’s cloud AI request context.

**Service information.** Online requests involve technical information such as network addresses, request times, processing results and usage counts. Account, security, quota and access records help us operate and protect the service. Where App Store purchases are available, we can receive transaction and entitlement identifiers and purchase status from Apple; we do not receive your payment-card number.

**Support communications.** If you email us, we receive your contact details and the information you choose to send. Please avoid sending passwords or unnecessary sensitive material.

## On-device processing and online services

Cabinet uses local storage and supported Apple frameworks for activities such as text recognition and on-device writing. Available processing depends on your device, permissions and the material you save. Some features use online services:

- **Automatic saved-item summaries:** when Additional cloud processing is enabled, and on-device summary generation is unavailable or cannot finish, eligible extracted text can be sent through our authenticated service to Microsoft Azure OpenAI to create and check a summary. Without that permission, summary generation stays on device. Original image and video files are not sent by that summary path.
- **Optional cloud writing and extraction:** when enabled in Settings → AI & processing, eligible text can be sent through our backend to the configured AI service. Sending eligible images, audio or video requires the separate media permission. Image-context processing can include a second support check of the same image.
- **Ask Cabinet:** when cloud processing and the Wiki-excerpt permission are enabled, eligible published Wiki passages, your question, source-reference metadata and a limited recent conversation context are sent to the AI service. Ask does not use a web search or secretly attach your entire library. Your own writing can be included when it is part of the eligible Wiki context.
- **Optional semantic search:** when enabled, search questions and eligible extracted text and notes can be sent to the embedding service. The resulting search index stays on your device; this search path does not upload original images or videos.
- **Speech recognition:** Cabinet attempts local transcription of saved video speech. With the required iOS Speech Recognition authorization, audio may be sent to Apple automatically when on-device transcription is unavailable or cannot finish. This Apple speech path is separate from Cabinet’s optional cloud-processing switch.
- **Optional online Reel transcription:** when its separate fallback permission is enabled, an eligible Instagram Reel link can be sent through our backend to Supadata after public video acquisition or Apple reading cannot supply the needed text. Supadata retrieves and processes the referenced content; Cabinet sends the link rather than a movie file on this path.

Sensitive, locked or otherwise ineligible material is excluded from relevant online processing paths by the app’s access rules. Those safeguards do not make Cabinet a separate encrypted vault. Online services process readable information, and we do not describe cloud AI processing as end-to-end encrypted or guarantee that providers retain no data. AI output can be incomplete or wrong; you can check its saved references.

## Who processes information

We use **Supabase** for account authentication, authenticated backend functions and service records, including usage and optional analytics. **Microsoft Azure OpenAI** processes eligible AI requests. **Supadata** processes Reel links and retrieved content when its fallback is enabled. **Apple** handles relevant operating-system services, Apple sign-in, speech recognition and App Store transactions; **Google** handles Google sign-in when you choose it. Email and hosting providers process communications and technical data needed to deliver their services. This public policy and support page is hosted on GitHub Pages; GitHub may process connection information such as IP addresses when you visit it, under its own privacy statement.

Fetching a saved link or opening its original source also connects to that source’s website or app. Those services have their own privacy practices. We may disclose information where legally required or reasonably necessary to protect people, investigate abuse or protect the service. We do not sell Cabinet library content or use it for advertising profiles. We do not use it to train our own general-purpose AI model. Providers’ handling of submitted information is subject to the applicable service arrangements and their data-protection terms.

Further information: [Supabase](https://supabase.com/privacy), [Microsoft Azure AI](https://learn.microsoft.com/en-us/azure/foundry/responsible-ai/openai/data-privacy), [Supadata](https://supadata.ai/legal/privacy), [Apple](https://www.apple.com/legal/privacy/), [Google](https://policies.google.com/privacy), and [GitHub](https://docs.github.com/en/site-policy/privacy-policies/github-general-privacy-statement).

## Usage analytics

After the in-app disclosure is acknowledged, Cabinet can send feature activity under an account identifier. You can turn off **Share usage analytics** in Settings → Privacy & security. This clears queued optional events and stops future optional collection; it does not disable necessary service metering, authentication or security records.

Optional events contain categories of feature activity, outcomes, source-platform/media types, counts, durations, identifiers and app/OS versions. They do not contain your saved text, images, transcripts, source URLs, filenames, search terms, chats or personal background. These identifiers can link events to an account; we do not describe them as anonymous. Account-linked events are available to authorized operators through protected reporting tools.

## Retention and deletion

Your device library remains until you remove its contents or delete the local library. Signing out leaves the account’s local library on that device. Ordinary item and Wiki deletion moves content to **Recently Deleted** for 30 days. After that period, restoration is disabled and permanent removal runs when Cabinet next performs cleanup. The app cannot guarantee physical cleanup while it is closed. Whole-library deletion is a separate permanent action. Copies you exported, backed up or shared are independent and are not recalled.

Queued optional analytics expire after seven days. Detailed analytics events, processing-operation records and provider-call records are retained for 90 days; session records and aggregate reporting are retained for 13 months under the current retention jobs. Deleting a cloud account removes its linked optional analytics. Aggregated or unlinked operational records can remain.

We keep account and necessary service records while needed to provide the service, maintain security, administer access, resolve disputes or meet applicable obligations. Support correspondence is retained while needed to handle the request and related obligations. Provider logs, backups, abuse monitoring and any required financial records have separate retention schedules; an app deletion or a request to Pathex does not instantly erase every provider-held copy.

Use **Settings → Account & support → Delete cloud account data** to request cloud-account deletion. The app confirms successful completion or reports a failure that can be retried. This does not erase the on-device library; delete that separately in the library settings if desired. Signing out or uninstalling alone does not request cloud-account deletion. Deleting a Cabinet account does not cancel an Apple subscription; manage subscriptions with Apple.

## Your choices and rights

You can manage supported processing permissions in Cabinet, turn off optional analytics, clear local search or chat history, remove saved material, export supported library data and request account deletion. You can manage Photos, Speech Recognition, notification and other iOS permissions in device Settings. App lock uses the device’s Face ID or passcode mechanism; Cabinet receives an authentication result, not your facial biometric template.

Turning a permission off affects future eligible processing; it cannot recall information already sent. If cloud-summary permission is withdrawn while a request is running, Cabinet discards the returned summary. Apple speech behavior is described separately above: the optional-cloud switch is not a universal offline switch.

Depending on applicable law, you may have rights to access, correct, delete or receive a copy of personal information, restrict or object to processing, withdraw consent, or complain to a data-protection authority. Contact **info@pathex.io** to make a request. We may need information to verify your identity before acting; do not email your password.

## Security, international processing and children

We use authenticated access, transport encryption for configured online requests and account-scoped controls. No storage or transmission method is completely secure. App lock is an access gate rather than a separate end-to-end encrypted storage service.

Our providers may process information outside your country, where legal protections may differ. Contact us for information about relevant processing locations and safeguards.

Cabinet is not designed or marketed specifically to children. If you believe a child has provided personal information without permission required by applicable law, contact us so we can investigate and handle the information appropriately.

## Changes and contact

We may update this policy as Cabinet or its processing arrangements change. The published policy will identify its effective or updated date, and material changes will receive appropriate notice. For questions or privacy requests, email **info@pathex.io** or visit [Pathex’s contact page](https://www.pathex.io/#contact).
