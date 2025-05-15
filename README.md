# Privacy Policy for Fusion App

**Last Updated:** May 15, 2025

## 1. Introduction

Welcome to Fusion App ("Fusion," "the App"). This Privacy Policy explains how Fusion handles information, including personal data, in connection with the operation of the App. Fusion is committed to protecting user privacy and complying with data protection laws. **This policy provides all information required by the EU General Data Protection Regulation (GDPR)** and other applicable privacy laws. It also describes how Fusion meets Apple App Store privacy rules (such as Apple’s Privacy “Nutrition Label” system). Please read this policy carefully.

## 2. Data Controller / Contact Information

**Data Controller:** *Marian Marian* (individual developer of Fusion)
**Contact Email:** [diffusiocreatio@gmail.com](mailto:diffusiocreatio@gmail.com)

For any privacy inquiries or requests, please use the email address above.  
A physical postal address is **not published**. GDPR Article 13 (1)(a) requires the *contact details* of the controller but **does not mandate a postal address**; the European Data Protection Board’s *Transparency Guidelines* (WP260 rev.01, para 35) state that an electronic address is sufficient where it enables data subjects to exercise their rights.  
Disclosing a private residence would violate the GDPR data-minimisation principle (Art. 5 (1)(c)) and could create disproportionate security risks contrary to Art. 32. The email channel offered here allows prompt, documented communication and therefore fully satisfies the Regulation’s accessibility requirement (Art. 12 (1)).  
*If a competent supervisory authority formally determines that a physical address is indispensable, the developer will furnish it confidentially to that authority without delay.*

## 3. Information Fusion Handles

Fusion is designed to minimise direct collection of personal data. However, to provide its services, Fusion handles the following information:

* **Information for Third-Party Service Integration:**
 - *User-Provided Credentials:* To connect with services like Trakt, TMDB, MDBList, or OpenRouter at the user’s request, Fusion may require API keys or authentication tokens. This information is provided explicitly by the user.
 - *Storage:* Trakt OAuth tokens are stored securely in the device’s Keychain. API keys or tokens for TMDB, MDBList, and OpenRouter are stored in the app’s local storage (UserDefaults) on the user’s device.

* **iCloud Sync Data:**
 - If the user enables iCloud Sync, certain app data and settings (e.g. Trakt catalog lists, addon configurations, general preferences) are synced via the user’s private iCloud account using Apple’s `NSUbiquitousKeyValueStore`. This data is subject to Apple’s iCloud terms and privacy policy, and Fusion cannot access or control the data in the user’s iCloud account beyond facilitating the sync.

* **Addon-Related Information:**
 - When users install and use third-party addons (plugins) from user-provided URLs, Fusion interacts with the addon’s specified server endpoint **at the user’s direction**. For example, Fusion may send content identifiers (like IMDb or TMDB IDs) or user-initiated queries (search terms, filter selections) to the addon’s URL as configured by the user. This happens only as a result of the user installing/configuring an addon. *(Note: addons are provided by third parties; users should review any privacy information from the addon provider, as Fusion does not control addon services.)*

> **Addon providers are independent “data controllers.” No joint-controller arrangements exist between the developer and addon authors.**

* **Non-Personally Identifiable Information:**
 - Fusion may handle non-personally identifiable information related to app configuration and preferences (e.g. UI settings), stored locally on the device (and optionally synced via iCloud, per the user’s settings).

* **Crash and Diagnostic Reports:**
 - If the app crashes or encounters an error, the device may generate a crash report. With the user’s consent (for instance, if you have enabled iOS analytics sharing or are using TestFlight for beta testing), these reports are sent to Apple and made available to the developer. Crash reports contain technical details about the incident (such as error codes, function names, app version, device model, and iOS version) but **do not include personal data**. Apple anonymizes crash logs by removing any user-identifying information before forwarding them to us. We use crash diagnostics exclusively to debug issues and improve the app’s stability and performance.

> **No tracking or advertising:** Fusion **does not** collect or transmit any user data for analytics, profiling, advertising, or marketing purposes. There are **no** third-party trackers, ad SDKs, or analytics tools integrated in the app. The only data transmissions are those **explicitly initiated by the user** for the app’s functionality as described above.

> **No cookies or similar tracking technologies are set or used by Fusion.**

## 4. Legal Basis for Processing

Fusion processes personal data under the legal bases defined in GDPR Article 6, as applicable:

* **Consent (GDPR Art. 6(1)(a)):** Processing based on the user’s consent:
 - Storing and using third-party API keys or authentication tokens that the user explicitly provides for connecting their accounts.
 - Syncing data via iCloud, when the user actively enables iCloud Sync in the app.
 - Using and transmitting addon-related data when the user chooses to install and use a specific addon (the user’s actions imply consent to that addon’s data usage).

* **Contract Performance (GDPR Art. 6(1)(b)):** Processing necessary to fulfill the app services requested by the user:
 - Sending requests and data to third-party services (Trakt, TMDB, MDBList, OpenRouter, etc.) that the user has connected, in order to retrieve or sync content as part of Fusion’s core functionality.
 - Handling the user’s queries, commands, and configuration choices within the app to deliver the expected features (for example, playing a trailer via a linked service, or applying a filter in an addon).

* **Legitimate Interests (GDPR Art. 6(1)(f)):** Processing based on the legitimate interests of the controller, balanced against user rights:
 - Storing basic app configuration and state data locally on the device to maintain functionality and a smooth user experience (e.g. remembering user settings, login tokens) without repeatedly asking for information.
 - Implementing security measures to protect user-provided credentials (e.g. using Keychain for tokens) and to prevent unauthorized access.
 - Receiving and analyzing anonymized crash reports (if a user opts to share them) to improve the app’s quality and reliability. This diagnostic processing is minimal and does not override users’ privacy rights, and it helps ensure the app runs safely and efficiently.

Our reliance on these bases is in accordance with GDPR requirements. We only pursue **legitimate interests** that are necessary for the app’s proper functioning and security, and we have assessed that these do not override your fundamental rights and freedoms. Where consent is required, you have the right to withdraw consent at any time (see Section 8 below), and where contract performance is the basis, the processing is limited to what is needed to deliver the requested features.

**Provision of Data & Consequences (Art. 13 (2)(e))**
All personal data is *optional*. If you decline to enter third-party credentials, those integrations will not function, but **offline-only features of Fusion remain available**.

## 5. How Fusion Uses Information

We use the information described above strictly to operate and provide the app’s functionality, and not for any secondary purpose:

* **To Provide App Functionality:** Fusion uses the data you provide (API keys, tokens, etc.) and your settings to enable the features you request – for example, connecting to your third-party accounts, retrieving and displaying content via addons, or syncing your preferences across devices (if iCloud sync is enabled).

* **Local Storage of Data:** Authentication tokens and API keys are stored on your device (locally) as described in Section 3, so that you do not need to log in or re-enter them every time. This local storage allows persistent connections to third-party services while keeping credentials secure on your device.

* **Diagnostics and Improvements:** If we receive crash reports or error logs (as explained in Section 3), we use them solely to diagnose technical issues and improve Fusion’s stability. These reports are not used for any profiling or marketing – they are examined only to fix bugs and enhance the user experience.

## 6. Data Sharing and Disclosure

Fusion does **not** share or send your personal information to any external parties except in the limited scenarios described below, which typically occur under your direction. In particular, Fusion (the app or its developer) does not sell or trade personal data, and does not disclose your information for advertising or marketing purposes.

* **Third-Party Services (User-Initiated):** When you choose to connect Fusion to an external service (such as Trakt, TMDB, MDBList, OpenRouter, etc.), you are instructing the app to communicate with that service. In doing so, Fusion will transmit the necessary data (e.g. your API token and the specific request or query) to the third-party service **only** to fulfill the functionality you selected. For example, if you sync your watchlist with Trakt, Fusion sends your Trakt token and request to Trakt’s API to fetch your list. These third-party services act as separate data controllers for any personal data you send to them. **Please review the privacy policy of each service you connect** for details on how they handle your data. For convenience, here are links to those policies:
 - Apple Privacy Policy [https://www.apple.com/legal/privacy/](https://www.apple.com/legal/privacy/)
 - Trakt Privacy [https://trakt.tv/privacy](https://trakt.tv/privacy)
 - TMDB Privacy [https://www.themoviedb.org/privacy-policy](https://www.themoviedb.org/privacy-policy)
 - OpenRouter Privacy [https://openrouter.ai/privacy](https://openrouter.ai/privacy)

* **Addons (User-Initiated):** Similarly, if you install a third-party addon in Fusion, the app will send requests to the addon’s designated server or API as needed to provide that addon’s functionality. This means any query you perform through an addon (such as searching for a title) will be sent to the addon’s backend service. This happens only because you installed and used the addon. **Fusion’s developer has no control over third-party addon providers.** The privacy and security of data handled by an addon’s service are the responsibility of that addon’s developer or provider. By installing an addon, you are effectively consenting to send data to that addon’s service. We strongly advise users to only use addons from sources they trust and to consult any available privacy information from the addon provider. *(For example, if an addon is meant to retrieve information from a certain website, any data you input will be sent to that website according to the addon’s design.)*

* **Apple iCloud (User-Enabled Sync):** If you enable iCloud Sync in Fusion, certain data (as listed in Section 3) will be transmitted to and stored in your personal iCloud account under Apple’s infrastructure. This is considered “sharing” with a third-party in the sense that Apple will process and store that data on your behalf. However, this iCloud data is not accessible to the Fusion developer. It is managed by Apple pursuant to Apple’s iCloud terms. You can control it via your device’s iCloud settings. (Disabling iCloud Sync in the app or via device settings will stop this data syncing.)

> Apple (TestFlight/diagnostics, iCloud) acts as an **independent data controller**. Fusion currently uses **no processors** within the meaning of GDPR Art. 28.

* **Diagnostic Data to Apple (User-Enabled):** As noted, if you participate in app beta testing via TestFlight or have opted to share analytics with app developers, crash and usage diagnostics are sent to Apple and then to us. This is a form of data sharing with Apple acting as an intermediary. The information shared is limited to technical crash data (no personal user content) and is used only for support and improvement purposes (see Section 3, “Crash and Diagnostic Reports”). Apple may also aggregate usage statistics (e.g. how often the app is opened) which are provided to us in a way that does not identify individual users.

* **Legal Requirements:** Fusion (the developer) may disclose information if **required by law** or if we in good faith believe such action is necessary to: comply with a legal obligation or lawful request (for example, a court order or a request from law enforcement or data protection authorities); protect and defend the rights or property of the developer; or act in urgent circumstances to protect the personal safety of Fusion users or the public. We will only do so to the minimum extent necessary and in accordance with applicable laws. If we receive any government or third-party request for user data, our policy is to review it carefully and object to overly broad or unlawful requests.

Aside from the situations above, **no personal data leaves your device** or is disclosed to any other party. Fusion does not use any external analytics or advertising networks, so no data is sent to such parties. The developer of Fusion has access only to information you provide directly (for example, if you email for support) and to the limited diagnostics described.

## 7. Data Retention

We aim to retain personal data only for as long as necessary to fulfill the purposes for which you provided it, and no longer. Because Fusion primarily stores data on your own device (and iCloud, if enabled by you), you have control over how long it is kept:

* **Locally Stored Credentials:** API keys and authentication tokens that you enter into Fusion (for services like Trakt, etc.) remain stored on **your device** until you remove them. You can remove a service’s credentials at any time via Fusion’s settings (for example, by logging out of a connected service). If you uninstall the app from your device, all locally stored tokens and data are deleted as part of the app’s data sandbox.

* **iCloud Synced Data:** Any data you choose to sync via iCloud is subject to your Apple iCloud account’s retention and deletion policies. For example, if you sync an item (like a list or setting) and later delete it within the app, that deletion will sync to iCloud as well. If you disable iCloud Sync for Fusion or sign out of iCloud on your device, the app will no longer update that data in iCloud (existing data may remain in your iCloud storage until you delete it via your device or iCloud settings). You may also delete Fusion’s iCloud data by deleting the app and choosing to remove its data in iCloud (as prompted by iOS), or via the iCloud storage management settings.

* **Server Storage:** Fusion **does not** have its own servers storing user personal data. We do not centrally log or store any of the personal information that might be handled (such as tokens or lists) – all such data resides either on your device or in your iCloud. The developer does not have a database of user information.

* **Third-Party Services Data:** If you connect to third-party services (Trakt, etc.), any data stored with those services (e.g. your watchlist on Trakt’s servers) will be retained by them according to their policies. Fusion does not duplicate or ingest that data into any storage under the developer’s control.

In summary, Fusion itself retains personal data locally for as long as you use the app (unless you remove it sooner). If you withdraw consent or disconnect a service, the related data is removed from the app. We encourage you to manage the data in the app (and iCloud, if used) to your comfort. If you have any questions about deleting or exporting data, feel free to contact us.

## 8. User Rights

As a user of Fusion and as a data subject under the GDPR (and equivalent laws), you have certain rights regarding your personal data. We respect and uphold these rights. Subject to conditions and applicable law, your rights include:

* **Right to Access:** You have the right to request a copy of the personal data that we (as controller) hold about you. In Fusion’s case, most personal data is stored on your own device, and you can view it directly (for example, you can see any saved API keys or tokens in the app’s settings). If you require a structured summary of any personal data we might have (e.g. if you emailed support with personal info), you can contact us to request this.

* **Right to Rectification:** If you believe that any personal data we process is inaccurate or incomplete, you have the right to request correction. For Fusion, this is typically under your control (for instance, you can update any credentials or settings you entered). If you need assistance correcting any information, please let us know.

* **Right to Erasure (Right to be Forgotten):** You have the right to request that we delete personal data we hold about you. In the context of Fusion, most data (such as service tokens or synced content) can be erased by you (e.g. by removing the API token from the app, which deletes it from local storage, or uninstalling the app entirely). If you request, we will also delete any personal data that we might have outside the app (for example, if you contacted us by email and want that correspondence deleted, we will comply unless retention is required by law).

* **Right to Restrict Processing:** You have the right to ask us to restrict (pause) the processing of your personal data in certain circumstances – for example, if you contest the data’s accuracy or have objected to processing (pending resolution). Given that Fusion’s processing is mostly user-directed and local, this right would typically apply if you have an ongoing issue under review. We will honor any valid request to restrict processing.

* **Right to Data Portability:** You have the right to obtain your personal data in a commonly used, machine-readable format, and to have that data transmitted to another controller where feasible. For Fusion, virtually all your data is either stored on your device or with the third-party services you connect (Trakt, etc.), so data portability can be achieved by accessing those directly. If needed, we can assist in exporting any relevant data that we control.

* **Right to Object to Processing:** You have the right to object to certain processing of your data, especially if we are processing it under a legitimate interest basis or for direct marketing. Fusion does not perform any direct marketing, and we only process data for the app’s functionality and security. If you object to any processing (for example, if you no longer want crash data shared), you can disable that sharing (by opting out of analytics on your device or leaving the TestFlight beta) or contact us with your objection and we will accommodate it.

* **Right to Withdraw Consent:** Where we rely on your consent for processing, you have the right to withdraw that consent at any time. This will not affect the lawfulness of processing already carried out, but it means we will stop the processing going forward. In practice, you can withdraw consent by, for example, disabling iCloud Sync (to stop that data processing), disconnecting a third-party service (to stop sending data to it), or uninstalling an addon. You can also simply revoke a permission (for instance, remove an API key) and Fusion will no longer process that data.

* **Right to Lodge a Complaint:** If you believe your data protection rights have been violated, you have the right to file a complaint with a Data Protection Supervisory Authority (DPA). You may do so in the EU Member State where you reside, where you work, or where the issue occurred. A directory of supervisory authorities and their contact details is available from the European Data Protection Board (EDPB). We encourage you to contact us first to resolve any issue, but you are always free to approach the authorities directly.

**Supervisory Authority Contact (Art. 13 (2)(d))**
You may lodge a complaint with any EU supervisory authority. A directory is maintained by the European Data Protection Board: [https://edpb.europa.eu/about-edpb/about-edpb/members\_en](https://edpb.europa.eu/about-edpb/about-edpb/members_en).
For convenience, you may also contact the Berlin Commissioner for Data Protection (BlnBDI), Alt-Moabit 59-61, 10555 Berlin, Germany, [https://www.datenschutz-berlin.de](https://www.datenschutz-berlin.de).

To exercise any of these rights, you can usually take action directly within Fusion (for example, remove data or change settings) or you can contact us at **[diffusiocreatio@gmail.com](mailto:diffusiocreatio@gmail.com)** with your request. We may need to verify your identity to process certain requests (to ensure we don’t give your data to someone else), and some requests (like access or deletion) can be subject to certain legal exceptions. We will respond to inquiries or rights requests as soon as possible and at most within the timeframe required by law (generally one month under GDPR).

**No Automated Decisions:** Fusion does **not** engage in any form of automated decision-making, including profiling, that produces legal or similarly significant effects on you (per GDPR Article 22). In other words, we are not using algorithms to make decisions about you without human involvement, and we do not profile users in any way.

## 9. Data Security

Fusion takes reasonable and appropriate measures to protect the information it handles, keeping in mind the state of the art, implementation costs, and the nature of the data. We strive to follow industry best practices for security:

* **Secure Storage:** Sensitive credentials (like your Trakt OAuth token) are stored in the Apple iOS **Keychain**, which is an encrypted secure storage mechanism on your device. Other preferences and data are stored in the app’s sandboxed storage or in your iCloud key-value store – inaccessible to other apps – and benefit from Apple’s device encryption. Fusion does *not* store any of your passwords in plain text or in an insecure manner.

* **Encrypted Connections:** Whenever Fusion communicates with third-party services, it uses HTTPS (TLS) connections. For example, API calls to `api.trakt.tv`, `mdblist.com`, or other services are made over encrypted channels to prevent eavesdropping. (Connections to addon endpoints will also use HTTPS if the addon URL begins with `https://`; users are advised to only use addons that support HTTPS for security.) This helps ensure that data in transit cannot be easily intercepted.

* **Least Privilege & Token Use:** Fusion uses authentication tokens (provided by you) to access third-party APIs rather than storing your usernames/passwords for those services. In many cases (e.g. Trakt), these tokens can be limited or revoked by you on the third-party service side at any time. Fusion does not have access to more data than necessary – for instance, it only retrieves information from third-party services in direct response to your actions.

* **Developer Practices:** As a developer, I follow secure coding practices to avoid common vulnerabilities. There is no code in Fusion that transmits your data to any server other than the services you configure. We also keep the app up-to-date with Apple’s security frameworks and review any third-party libraries for compliance and security.

Despite all measures, please note that **no method of transmission or storage is 100% secure**. The security of data can also depend on factors outside our control – for example, a weakness in a third-party service or someone having physical access to your device. **You** as the user also play a role in security: we encourage you to use a secure device passcode, keep your iOS updated, and not share any sensitive tokens or personal data with untrusted addons or services. If you suspect any security issue in Fusion, please contact us immediately.

## 10. International Data Transfers

Fusion is developed and offered from within the European Union. The app itself does not send your personal data to any country outside the European Economic Area (EEA) in the course of its normal operation. In general, all personal data remains on your device or in your private iCloud storage (which is hosted on Apple’s servers, primarily in the EU or as configured by Apple). The developer does not operate any external servers receiving personal data.

However, when **you connect to third-party services or use addons**, Fusion will transmit data over the internet to those external services, and those services might be located in other jurisdictions. This means **international data transfers can occur only as a result of your own integration choices**:

* For example, if you connect Fusion to Trakt, your data (e.g. your show watchlist requests, your Trakt auth token) will be sent to Trakt’s servers. Trakt is a U.S.-based service, so personal data you send (such as viewing history tied to your account) will be processed in the United States. Similarly, other third-party APIs or addon servers may be outside the EU.

These transfers of data are **necessary to provide the functionality you have requested** – e.g. contacting a U.S. service to get your data at your behest. We ensure that such transmissions occur securely (via HTTPS) and only with your initiation.

**Legal basis for transfers:** When personal data is transferred to a third country that does not have an EU adequacy decision (such as the U.S.), we rely on the derogations permitted by GDPR for such specific, user-requested transfers. In particular, the transfer is **explicitly consented to by you** when you activate the third-party integration, or it is necessary for the performance of the contract/service that you have requested (within the meaning of GDPR Article 49). GDPR Recital 111 acknowledges that a data subject’s explicit consent or the necessity in relation to a contract can justify such occasional data transfers. By choosing to link Fusion with a third-party service, you are deemed to have given such consent for the related data to travel to the service’s country as needed to perform the integration.

We will always limit the data shared to only what is required for the feature. (For instance, if an addon needs a movie ID to fetch information, we send only that ID and not any unnecessary personal info about you.)

Where possible, we favor services that have adopted appropriate safeguards (like standard contractual clauses or participation in frameworks like the EU–US Data Privacy Framework, if applicable). However, ultimately the data you send through Fusion to an external service will be subject to that service’s policies. **We advise you to review the privacy policy of each third-party service or addon you use** to understand how they handle international data transfers and what protections they have in place. If you have questions or require more information about data transfer mechanisms for a given integration, feel free to contact us.

## 11. App Store and Platform Compliance

Fusion is distributed via Apple’s App Store, and we adhere to all of Apple’s privacy requirements and guidelines for apps:

* **App Privacy “Nutrition Label”:** On Fusion’s App Store product page, you can find an *App Privacy* section (often referred to as a privacy nutrition label) which summarizes the app’s data practices. This label is based on our submissions to Apple about what data the app collects and how it is used. Apple **requires all apps** to provide this disclosure for transparency, in addition to having a full privacy policy available. Fusion’s label reflects that the app **does not collect personal data** for its own purposes, and only handles user-provided data for the functionality described in this policy.

* **Privacy Manifest Declaration:** Fusion includes an Apple *Privacy Manifest* file in its app bundle. Apple introduced privacy manifests for apps and SDKs to explicitly declare the types of data the app uses and the reasons (purposes) for that usage. We have listed all data types accessed by Fusion or any third-party libraries it uses, along with the allowed reasons (such as “user authentication” or “app functionality”). This manifest is required by Apple’s App Store policies as of 2024 and helps Apple verify that the app only uses sensitive APIs for justified purposes. By complying with this, we ensure additional transparency and that our stated practices are enforceable at the platform level.

* **TestFlight & Crash Reports:** Fusion may be distributed for beta testing via Apple’s TestFlight. When you use the TestFlight version (or if you have enabled sharing of analytics/crash data in iOS for the App Store version), Apple automatically collects crash reports and usage statistics and shares them with us through their secure system. Importantly, these **crash reports do **not** include any personal data** or content from you. Apple strips out identifiers and personal details from diagnostic logs to protect user privacy. The crash reports we see typically contain anonymized device and software information and the technical details of the crash (e.g., stack traces). We use this information under our legitimate interest in improving the app’s reliability, solely to fix bugs or compatibility issues. We do **not** receive anything that identifies you individually. Participation in TestFlight or analytics sharing is optional and can be controlled by you (you can opt out of sharing iPhone Analytics with app developers in iOS settings at any time).

* **iCloud Integration:** As noted, Fusion uses Apple’s iCloud service for syncing data if you (the user) enable it. This integration is fully in accordance with Apple’s guidelines: the app declares its use of iCloud in its App Store privacy disclosures, and all iCloud-stored data is tied to your Apple ID and protected by Apple’s security measures. The Fusion app’s developer never sees your iCloud contents. You have granular control over iCloud syncing (you can enable/disable it for Fusion via the app or in your device’s iCloud settings). Using iCloud sync is completely optional – it exists for your convenience to sync your own data across your devices. If you prefer not to use it, the app will function with local-only storage.

These steps demonstrate Fusion’s commitment to transparency and privacy on the App Store platform. We keep our App Store submission information up-to-date to reflect the app’s current behavior. If any new version of Fusion were to introduce a change in data practices, we would update the App Privacy label and this Policy accordingly (subject to App Store review) so that users are informed. Our goal is to meet or exceed both legal requirements and Apple’s policies in order to protect our users.

## 12. Children’s Privacy

Fusion is **not intended for children** under the age of 16 (or the relevant age of consent in your jurisdiction if higher). We do not knowingly collect personal information from children. The app’s content is generally oriented towards media and utilities for general audiences, and there is no feature directed specifically at children.

If you are a parent or guardian and believe that a child under the relevant age has provided personal data to us (for example, by contacting support via email), please contact us immediately at [diffusiocreatio@gmail.com](mailto:diffusiocreatio@gmail.com). We will take prompt steps to delete the information and terminate any child’s use of the app if necessary. Because Fusion does not directly collect user data, it is unlikely to have any child’s personal data unless a child actively emailed or communicated with the developer, but we will investigate and address any report of such data.

Users under the age of 16 (or applicable age) should not use Fusion to connect to services or provide personal data without parental consent. By using the app, you represent that you are at least the age of digital consent in your country, or that you have obtained proper parental/guardian consent to use the app.

## 13. Changes to This Privacy Policy

We may update this Privacy Policy from time to time to reflect changes in the app’s features, legal requirements, or other developments. If we make material changes (especially any changes in what data we collect or how we use it), we will notify users through appropriate means. This may include an in-app notification or a note in the App Store release notes, in addition to updating this document.

The “Last Updated” date at the top of this Policy indicates when the latest revisions were made. Prior versions of the Policy will be archived or available upon request so you can see what has changed. We encourage you to review the Privacy Policy periodically to stay informed about how Fusion protects your information.

Continued use of the App after any changes to this Policy will be considered acceptance of the updated terms. If you do not agree with a Policy update, you should discontinue use of the app and/or disable any features (like service integrations) that concern you, and you may contact us to address any specific issues.

---

*Thank you for reading our Privacy Policy.* We are committed to safeguarding your data and privacy rights. If you have any questions or concerns about this Policy or Fusion’s data practices, please contact us at **[diffusiocreatio@gmail.com](mailto:diffusiocreatio@gmail.com)**. We will be happy to assist you.
