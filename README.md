# Privacy Policy & Terms — Image Simple Viewer

**Effective date:** 14 May 2026
**App:** Image Simple Viewer (Microsoft Store)
**Publisher / data controller:** Rodrigo G. de Queiroz

---

## The short answer

**The Image Simple Viewer app does not collect, store, send, or share any personal data of its own.**
The app's code runs entirely on your device. It contains no analytics, no tracking, no advertising, and no user accounts.

Because the app is distributed through the Microsoft Store, Windows and the Store collect their own platform-level diagnostics (such as crash reports, install counts) independently of the app. That is governed by **Microsoft's** privacy practices, not by mine. Details are in the *Microsoft Store and Windows platform telemetry* section below.

If that is all you wanted to know, you can stop reading here.

---

## What the app does on your device

Image Simple Viewer is a minimalist image viewer for Windows. To do this, the app:

- Opens image files (jpg, jpeg, png, bmp, gif, tif, tiff, ico, svg) that you choose, either via the file picker, by drag-and-drop, by file-type association in Windows Explorer, or by command-line argument.
- Reads the folder containing the current image so you can press **Next** / **Previous** to navigate to other images in the same folder.
- Keeps a permission token to the most recent folder you opened in the Windows **FutureAccessList**, so navigation keeps working across app sessions.
- Saves two local preferences in Windows app storage: whether to show the full file path overlay, and whether to hide the mouse pointer while viewing.
- Loads the chosen image into memory so it can be displayed, zoomed, rotated, and (if you choose) copied to the clipboard.

All of this happens locally on your computer. None of this information leaves your device.

## What the app does NOT do

The app's own code:

- does **not** send any information to me or to any third party,
- does **not** include any analytics, telemetry, crash-reporting, or tracking SDKs,
- does **not** use cookies,
- does **not** show advertising,
- does **not** require an account, a login, or a subscription,
- does **not** ask for your name, email, address, phone number, payment details, or any other personal information,
- does **not** access your camera, microphone, contacts, calendar, messages, or location, and
- does **not** modify, rename, move, or delete your image files — it only reads them. (The **Copy** menu item copies the current image to the Windows clipboard at your request; **Edit** opens the file in another app via the Windows app picker, also at your request.)

This list refers to **the app's code**. See the next section for what Windows and the Microsoft Store do at the platform level, which is outside the app's control.

## Microsoft Store and Windows platform telemetry

Because the app is distributed through the Microsoft Store and runs on Windows, the platform itself may collect some information independently of the app:

- **Windows Error Reporting (WER):** if the app crashes, Windows can send a crash dump to Microsoft. Whether and how much is sent is controlled by your **Windows diagnostic data setting** (Settings → Privacy & security → Diagnostics & feedback), not by the app.
- **Microsoft Store metrics:** installs, uninstalls, app launches, and session counts may be recorded by the Store and by Windows.
- **Partner Center reports:** as the publisher, I receive **aggregated, non-identifying reports** in Microsoft Partner Center — for example "N installs in country X this week" or "N crashes of build Y". I do not receive your name, account, IP address, or any data that identifies you individually, and I never receive the contents of your images.

None of the above is collected, sent, or stored by the app's code — it is collected by Windows and by the Microsoft Store. It is governed by Microsoft's own privacy practices, not by this policy. To review or change it, see:

- Microsoft Privacy Statement: https://privacy.microsoft.com/privacystatement
- Windows diagnostic data controls: Settings → Privacy & security → Diagnostics & feedback
- Microsoft Store privacy: https://privacy.microsoft.com/

## Why the app asks for "broad file system access"

Image Simple Viewer asks Windows for **broad file system access** so it can open image files from wherever you keep them — your **Pictures** folder, **Desktop**, **Downloads**, an external drive, a network share, etc. Without this permission, the app could only read files inside its own private folder, which is not useful for an image viewer.

This permission is used **only** to read the files you choose and the folder that contains them (for next/previous navigation). The app does not scan your disk, index your files, build a thumbnail database, or read anything you have not opened in the app yourself. You can revoke this permission at any time in Windows Settings → Privacy & security → File system.

## Files you open with the app

When you open an image, that file stays on your device. The app reads it, decodes it, and displays it. The app never writes to your image files. The clipboard copy feature copies the in-memory image to the Windows clipboard at your explicit request.

## Children's privacy

The app is not directed to children under 13 (or under 16 in the EU/UK). Because the app does not collect any data at all, it is not possible for it to knowingly collect information from children. The app contains no advertising, no in-app purchases, and no online features.

## Your rights

Because the app does not collect or process any personal data, most data-subject rights (access, correction, deletion, portability, objection, restriction) do not apply in practice — there is nothing about you for me to access, correct, delete, port, restrict, or share.

For completeness, the rights granted to you by the laws below would otherwise apply:

- **EU residents:** General Data Protection Regulation (GDPR) — Regulation (EU) 2016/679.
- **German residents:** in addition to the GDPR, the Federal Data Protection Act (*Bundesdatenschutzgesetz*, BDSG) of 2018.
- **UK residents:** UK GDPR and the Data Protection Act 2018.
- **California residents:** California Consumer Privacy Act and California Privacy Rights Act (CCPA/CPRA). I do not sell or share personal information, because I do not collect any.
- **Brazilian residents:** Lei Geral de Proteção de Dados Pessoais (LGPD) — Lei nº 13.709/2018.
- **Canadian residents:** Personal Information Protection and Electronic Documents Act (PIPEDA).
- **Other jurisdictions:** equivalent local laws.

If you believe you have personal data with me that should be removed, contact me (see below) and I will look into it.

## Cookies, local storage, and tracking technologies

The app is a Windows desktop application, not a website. It does **not** use HTTP cookies, browser local storage, IndexedDB, fingerprinting, beacons, pixels, session replay, or any equivalent tracking mechanism. There is no built-in browser surface that could load third-party trackers.

For convenience, the app does keep a small amount of state in the standard Windows app-data area:

- two boolean preferences (**show full path in title overlay**, **hide mouse pointer while viewing**),
- a Windows FutureAccessList token pointing at the most recently opened folder, so next/previous navigation keeps working after the app restarts.

This state stays on your device, is readable only by your Windows user account and this app, and is removed when you uninstall the app.

## "Do Not Sell or Share My Personal Information" (CCPA/CPRA)

Under California law, residents have the right to ask businesses to stop selling or sharing their personal information. **Image Simple Viewer does not sell or share any personal information, because it does not collect any.** There is therefore nothing to opt out of.

If you are a California resident and still want to submit a "Do Not Sell or Share" request for the record, please do so by opening a GitHub issue (see *Contact* below). The response will confirm that no such data exists.

## Data protection contact (GDPR Article 27 / Article 37)

I am a single independent developer publishing this app on the Microsoft Store. Under GDPR Articles 37 and 38, a formal Data Protection Officer (DPO) is only required when an organisation's core activities consist of large-scale processing of personal data or special-category data — which does not apply here, since the app processes **no personal data at all**.

For any data-protection matter you would normally raise with a DPO (right of access, erasure, objection, complaint, etc.), please contact me directly through the channel listed under *Contact* below. I act as the controller and as the contact point for these matters.

If you are in the EU and remain unsatisfied with my response, you have the right to lodge a complaint with your national supervisory authority. In Germany this is the *Bundesbeauftragte für den Datenschutz und die Informationsfreiheit* (BfDI) or your relevant state authority (*Landesdatenschutzbeauftragter*).

## Security

Because no data is collected or transmitted, there is no server, account, or database to protect. The data on your device is protected by the same Windows account, disk encryption (if you enable BitLocker), and Microsoft Store sandboxing that apply to any other Microsoft Store app.

## Third parties

The app does not embed or link to any third-party service, SDK, or analytics provider. The only network activity associated with the app comes from Windows and the Microsoft Store themselves (app updates, platform diagnostics) — see *Microsoft Store and Windows platform telemetry* above. This activity is handled by Microsoft, not by the app's code, and is governed by Microsoft's privacy practices.

## "As-is" disclaimer and limitation of liability

Image Simple Viewer is provided **free of charge** and **as-is**, without any warranty of any kind, express or implied, including but not limited to warranties of merchantability, fitness for a particular purpose, and non-infringement. To the maximum extent permitted by applicable law, the publisher shall not be liable for any direct, indirect, incidental, consequential, special, or exemplary damages arising out of or in connection with the use of, or inability to use, the app — including but not limited to loss of data, loss of image files, or any other loss — even if advised of the possibility of such damages.

Some jurisdictions do not allow the exclusion of certain warranties or the limitation of liability for consequential damages, so some of the above limitations may not apply to you. In those jurisdictions, liability is limited to the maximum extent permitted by law.

## Changes to this policy

If this policy changes, the new version will be published at the same GitHub URL and the **Effective date** above will be updated. Because the app does not connect to me, you should check this page if you want to see the latest version. Material changes will be noted at the top of the page for a reasonable period.

## Governing law and place of residence

The publisher resides in **Germany**. This policy and any non-contractual obligations arising out of or in connection with it are governed by the laws of the Federal Republic of Germany, without regard to its conflict-of-laws rules. The GDPR and the German *Bundesdatenschutzgesetz* (BDSG) apply directly.

Nothing in this policy limits or removes any rights you have under mandatory local consumer-protection or data-protection law in your country of residence. Where such mandatory local law gives you stronger rights than German law, those local rights still apply to you.

## Contact

The simplest way to reach me about this policy or about anything related to the app is to open a **public GitHub issue** in this policy repository:

- https://github.com/rodrigogq/win-app-image-simple-viewer-license/issues

Please do not include any sensitive personal information in a public issue. If you need a private channel for a data-protection request, mention that in the issue and I will reply with a way to continue privately.

---

## Terms of use

Image Simple Viewer is **proprietary software**. The source code is **not publicly distributed**; only the compiled application on the Microsoft Store is provided.

You are granted a non-exclusive, non-transferable, revocable right to install and use the app for personal or business purposes, subject to the *"As-is" disclaimer and limitation of liability* above and to the Microsoft Store standard application licence terms (which Microsoft displays to you at install time).

You may **not**:
- decompile, reverse-engineer, disassemble, or otherwise attempt to derive the source code, except to the extent expressly permitted by applicable mandatory law;
- redistribute, sublicense, rent, lease, or resell the app;
- remove or alter any copyright, trademark, or other proprietary notices.

All rights not expressly granted to you are reserved by the publisher.

---

© Rodrigo G. de Queiroz. All rights reserved.
