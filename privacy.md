# Privacy Policy — PAT (Personal Achievement Tracker)

**Last updated:** April 17, 2026

---

## The short version

PAT is a local-first app. Your achievements, scores, people, attachments, and profile information are stored on your iPhone only. We do not operate servers. We do not collect analytics. We do not track you. We cannot read your data because it never leaves your device (unless you opt in to the features described below).

---

## Who we are

PAT is developed by Munish Gandevia ("PAT", "we", "us", "our"). For questions about this policy, contact MunishGandevia@gmail.com.

---

## What PAT stores on your device

Everything you enter into PAT is stored locally on your iPhone using Apple's SwiftData framework. This includes:

- Achievement text, categories, and timestamps
- Dollar impact and time-saved values
- People and tag names you add
- Attachments (photos from your camera or photo library)
- Profile details you enter (name, role, next-review date, hourly rate)
- Weekly goals and impact targets
- In-app score history and milestones

This data is included in your iPhone's iCloud device backup if you have Apple's iCloud Backup enabled in iOS Settings. That backup is governed by Apple's privacy policy, not ours. We have no access to the backup or to its contents.

---

## What PAT does not collect

PAT does **not** collect:

- Your email, phone number, or any account identifier
- Any device identifier used for advertising or cross-app tracking
- Location data
- Usage analytics, screen views, or behavioral events
- Crash reports (unless you have opted into Apple's aggregated diagnostics in iOS Settings → Privacy & Security → Analytics & Improvements, in which case Apple — not we — receives the anonymized data)

PAT shows no advertising and integrates no advertising or analytics SDKs.

---

## Optional: on-device AI parsing (Apple Foundation Models)

PAT uses Apple's Foundation Models framework to parse the text of your achievements into categories, amounts, and names. This model runs **entirely on your iPhone**. No achievement text is transmitted to Apple or to us when this feature is in use.

---

## Optional: Claude Haiku AI parsing (PAT Pro)

If you purchase PAT Pro and enable Claude Haiku parsing in Settings, you will supply your own Anthropic API key. When this feature is enabled, the text of each achievement you log is sent from your device directly to Anthropic's API for parsing. We do not proxy, intercept, or store this data.

- Anthropic's handling of that data is governed by their privacy policy: https://www.anthropic.com/legal/privacy
- Your API key is stored locally on your device in the iOS Keychain
- You can disable this feature at any time in Settings → AI Parsing. When disabled, no data is sent to Anthropic.

---

## Optional: camera and photo library

If you choose to attach a photo to an achievement, PAT will request permission to access your camera or photo library. Selected images are stored locally alongside the associated achievement and are not uploaded anywhere. You can revoke these permissions at any time in iOS Settings → Privacy & Security.

---

## In-app purchases

PAT offers optional in-app purchases:

- **PAT Pro** — a one-time non-consumable purchase that unlocks premium features
- **Tip jar** — optional consumable purchases that support development

All purchases are processed by Apple through StoreKit. We receive only the anonymized purchase confirmation Apple provides (that a purchase was made, not by whom). Billing and payment data are governed by Apple's privacy policy: https://www.apple.com/legal/privacy/.

---

## Export and deletion

You control your data completely:

- **Export:** Settings → Data → Export produces a JSON or PDF copy of your achievements.
- **Delete:** Settings → Data → Reset permanently removes all PAT data from your device.
- **Uninstall:** removing PAT from your device deletes all local PAT data. Any iCloud device backup you have enabled may retain a copy until that backup is overwritten, per Apple's backup policies.

Because we do not hold your data on any server, there is nothing for us to delete on your behalf.

---

## Children's privacy

PAT carries a 4+ age rating but is designed for working professionals. We do not knowingly direct the app at children and do not collect data from anyone.

---

## Security

All your PAT data sits within the app's sandboxed storage on your device, protected by iOS's standard file-system encryption (tied to your device passcode). Your Anthropic API key, if provided, is stored in the iOS Keychain.

---

## Changes to this policy

If we make material changes, we will update the "Last updated" date above and, where meaningful, surface a notice in-app on your next launch.

---

## Contact

Questions, concerns, or requests: **MunishGandevia@gmail.com**

---

*PAT is an independent app. This policy describes the practices of the app itself. Apple's handling of App Store, StoreKit, and iCloud data is governed by Apple's published policies.*
