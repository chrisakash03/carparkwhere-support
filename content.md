
### Privacy Policy for CarParkWhere?
Effective date: September 26, 2025

This Privacy Policy explains how CarParkWhere? (“the App”, “we”, “us”) collects, uses, and shares information when you use the App.

#### What we collect
- Account information
  - Email and basic profile info from your chosen sign‑in method (Email/Password, Sign in with Apple, Google Sign‑In). Managed by Firebase Authentication.
- Location data
  - Car locations you explicitly save (address, timestamp, optional floor/lot/area/pillar, optional photo/thumbnail, and optional coordinates).
  - Optional home carpark geofencing (if enabled) for local reminders. Geofencing runs on-device; we do not continuously upload your live location.
- Notifications and device info
  - Push token (FCM), device identifier (IDFV), platform (iOS), and app version to deliver notifications reliably.
- Family sharing
  - Share codes, membership records (your user ID, share ID, joinedAt, access level), and car locations shared with approved family members.
- Photos
  - Optional photos you attach to a car location or a family group image. Stored in Firebase Storage.
- Network and diagnostics
  - Basic logs for reliability (e.g., errors, ad load status). No third‑party analytics SDKs are integrated beyond Firebase components used for core features.
- Advertising
  - Google AdMob may collect device and usage information to serve ads. We do not request tracking permission (IDFA). AdMob may use contextual signals and platform settings.

#### How we use your data
- Provide core features: save and retrieve your car locations, enable on-device proximity reminders, and share a saved location with your approved family members.
- Deliver notifications: send you and your family members relevant alerts (e.g., location updates).
- Maintain security and reliability: fraud prevention, troubleshooting, and product improvement.
- Serve ads: display interstitial ads after successful location updates.

#### Data sharing
- Family members you approve
  - Family members in your active share can view car locations shared within the group (not continuous background tracking).
- Service providers
  - Google Firebase (Authentication, Firestore, Cloud Functions, Cloud Messaging, Storage) and Google AdMob process data on our behalf to deliver the App’s functionality and ads.
  - Apple (MapKit/CLGeocoder) may process coordinates to return human‑readable addresses.
- Legal compliance
  - We may disclose information to comply with law, protect rights, or ensure safety.

#### Data retention
- Your car locations, images, and family memberships are retained until you delete them or request deletion.
- Push tokens and device info are retained while your account is active or until you sign out (sign out removes the stored push token from your user record).
- Logs are retained for a limited period for troubleshooting.

#### Your choices and controls
- Location permissions: grant “When In Use” or “Always” in iOS Settings. “Always” enables background/geofence reminders.
- Notifications: enable/disable in iOS Settings.
- Family sharing: generate a share code, join/revoke/leave shares from the App’s family sharing screens.
- Data deletion:
  - Delete specific car locations and associated images within the app UI (where available).
  - To request account/data deletion, contact support (see Contact Us). We will delete your account data stored in Firebase (Auth, Firestore, Storage) within a reasonable time.
- Advertising choices:
  - Manage personalized ads using your device settings and Google’s ad settings. We don’t sell personal information.

#### Security
- All traffic is encrypted in transit; Firebase encrypts data at rest.
- Firestore security rules restrict read/write of car locations to the owner and (for reads) members of the same family share.
- Note on images: images stored in Firebase Storage are available to authenticated users of the app; access requires the exact path/URL. Avoid uploading sensitive content.

#### International data transfers
- Data may be processed and stored by Google Cloud/Firebase in data centers across regions. Protections are applied per provider terms and applicable law.

#### Children’s privacy
- The App is not directed to children under 13 (or the equivalent age in your jurisdiction). Do not use the App if you are under the minimum age.

#### Changes to this policy
- We may update this policy from time to time. Material changes will be posted in the App or on our website.

#### Contact us
- Email: support@carparkwhere.app
- Include your sign‑in email and “Privacy Request” in the subject for data access/deletion requests.

---

### Frequently Asked Questions (FAQs)

- What does CarParkWhere? do
  - Helps you save where you parked, get reminders near your home carpark, and optionally share your latest saved car location with family.

- Do I need an account
  - Yes. Sign in with Email/Password, Sign in with Apple, or Google Sign‑In.

- Why does the app ask for “Always” location permission
  - “Always” allows geofencing to trigger reminders even when the app is in the background. If you only grant “When In Use,” background reminders may not work reliably.

- Does the app track me in real time
  - No. Geofencing is processed on-device. We only store car locations you explicitly save.

- What gets shared with my family
  - The latest saved car locations and any attached photo (if not a home location photo, depending on your use). No continuous live tracking.

- How do I start family sharing
  - Go to Settings → Family Sharing, generate a share code (valid for a limited time), and share it with family. They join using the code.

- How do I stop sharing or leave a family
  - In Family Sharing, revoke the share (owner) or choose to leave the family group (member). This prevents further access to your future locations.

- Can I delete my saved locations or images
  - Yes. Delete a location in the app to remove it and its associated images from your account. Family images can also be replaced or removed.

- Who can see my photos
  - Photos are stored in Firebase Storage and used by the app for your account and family features. They require authentication to access, but anyone with the exact URL and valid app authentication could access them. Avoid sensitive images.

- Why do I see ads
  - Ads help keep the app free. Interstitial ads appear after successful location updates. We use Google AdMob.

- Can I turn off personalized ads
  - Manage ad personalization in your device settings and Google ad settings. We don’t sell your personal information.

- What notification types does the app send
  - Reminders near your home carpark, and (optionally) family location update notifications.

- Notifications aren’t working—what should I check
  - Ensure notifications are enabled, grant “Always” location for background geofencing, and keep Background App Refresh on. Low Power Mode may reduce reliability.

- Does it work offline
  - Core features like viewing last saved info and local reminders can work offline. Syncing and sharing require an internet connection.

- What platforms are supported
  - iPhone running a recent iOS version (e.g., iOS 15+ recommended).

- How do I change my home carpark
  - Settings → Home Carpark → Change Home Carpark Location.

- How do I sign out
  - Settings → Account → Sign Out. This also unregisters your device’s push token.

- How do I request my data or delete my account
  - Email support@carparkwhere.app from your sign‑in email with “Data Request” or “Delete My Account.” We’ll verify and process promptly.

- Does the app use my address or coordinates for ads
  - We do not share your saved locations with AdMob. Ad networks may infer approximate location from IP. Manage ad preferences via your device settings.

- Is my data encrypted
  - Yes. Data is encrypted in transit; Firebase encrypts at rest. We also use Firestore rules to limit access to your data.

- What happens if I uninstall the app
  - Uninstalling won’t automatically delete your data. Sign in again to access it or contact us to request deletion.

- Can non-family users see my locations
  - No, except for any images accessible via exact URLs by authenticated users. Firestore rules restrict car location documents to you and your family share.

- Do you sell personal data
  - No.

- How long do you keep my data
  - Until you delete it or request deletion; diagnostic logs are kept for a limited period.

- How are addresses determined
  - We use Apple’s reverse geocoding (MapKit/CLGeocoder) to convert coordinates to a human‑readable address.

- How often are geofence reminders triggered
  - When you enter the defined region around your home carpark and permissions are granted. The radius and timing are tuned for reliability and battery life.

- Who do I contact for help
  - Email support@carparkwhere.app.

- Is this app for kids
  - No. It’s not directed to children under 13 (or the equivalent age in your region).

- Does the app run in the background
  - Only lightweight geofencing/monitoring for reminders if you enabled it. No continuous background uploading of your location.

- What if I use multiple devices
  - Your data syncs with your account. Push tokens are device-specific, so you may receive notifications on all signed‑in devices.

- I joined the wrong family—how do I fix it
  - Leave the family group in Settings → Family Sharing, then join the correct one with a new share code.

- Can I export my data
  - Email support@carparkwhere.app and we’ll help with a portable export where feasible.

- Why was my share code expired
  - Share codes expire after a limited time for security. Generate a new one from Family Sharing settings.

- Do you comply with GDPR/CCPA
  - We respect data subject rights. Contact us for access, rectification, deletion, or to exercise applicable rights.

- Can I block notifications from specific family updates
  - You can disable family notifications globally by leaving the family group or disabling app notifications in iOS Settings.

- Will you add account deletion in‑app
  - It’s planned. Until then, email support@carparkwhere.app to delete your account and data.

- How big can my photos be
  - Photos are optimized and thumbnailed before upload to reduce size and improve performance.

- I changed phones; do I need to do anything
  - Sign in on the new phone. Push notifications will re-register automatically.

- Why does the app ask for notification permission
  - To send you reminders and family update alerts.

- How can I reduce ad frequency
  - Ads only show after successful location updates. Reducing rapid updates will reduce ad impressions.

- Does the app support dark mode and accessibility
  - Yes, the UI supports dark mode and dynamic type.

- How can I report a bug
  - Email support@carparkwhere.app with steps to reproduce and screenshots if possible.

- I forgot to save my location—can the app recover it
  - The app doesn’t auto‑save locations continuously. Save a location when you park for best results.

- My home carpark changed—do I need to redo permissions
  - Usually no. Update your home carpark in Settings; ensure “Always” location permission remains granted if you want background reminders.

- Are there in‑app purchases
  - Not at this time.

- Do you support Apple Watch or widgets
  - Not currently; we’re evaluating future enhancements.

- How do I restore default settings
  - Toggle off features you don’t need in Settings. Contact support if you need help.

- Will my family see my home address
  - They can see whatever car location you save and choose to share. Manage sharing as needed.

- Do you log my exact movements
  - No. Only the locations you save and geofence events needed for reminders are used.

- Where is my data stored
  - Google Firebase (Google Cloud) data centers. Exact region may vary.

- What happens when I sign out
  - Your push token is unregistered from your user record, and you’ll stop receiving notifications until you sign back in.

- Can I use the app without location services
  - You can still save manual details, but location-based features and reminders will be limited.

- Is there a way to test notifications
  - Ensure permissions are granted, then enter/exit the geofenced area or use any built‑in debug options when available.

- Can I change my sign‑in method later
  - You can add additional providers to the same Firebase account if supported. Contact support for assistance.

- How do I change my email address
  - Manage via your sign‑in provider (Apple/Google) or contact support for help with email/password accounts.

- What if I get too many notifications
  - Adjust notification settings in iOS or disable the related feature in the app’s Settings.

- I got a “permission denied” error
  - Likely due to Firestore security rules or missing membership. Rejoin the family group or check you’re signed in with the correct account.

- I can’t see my family’s photo on a home location
  - Family image overlay is not applied to home locations by design.

- Are URLs to images secret
  - They’re unguessable but not a guarantee of privacy. Treat them like shareable links; avoid sensitive content.

- Can I request a feature
  - Yes please—email us! chrisakashh@gmail.com

- How do I report inappropriate use in a family group
  - Revoke the share or leave the group and contact support with details.

- Do you support multiple cars
  - We are currently working on supporting multiple cars 

- Will you add premium/ads removal
  - Possibly in the future. Let us know your interest.

- Can I import/export family members
  - Not currently. Use share codes to add members.

- Why do I need internet for family sharing
  - Sharing and syncing use Firebase (cloud). Local reminders do not require internet.

- What happens if I deny “Always” permission
  - You’ll still be able to save locations, but background reminders may not trigger.

- How big is the geofence
  - Tuned for reliability and battery life; exact radius may vary by device and configuration.

- Does the app support iPad or Mac
  - The app targets iPhone; other platforms are not officially supported at this time.

- Is Sign in with Apple private relay supported
  - Yes; Apple may provide a private relay email. We respect that.

- Can I link with multiple families
  - The app is designed for a single active family share at a time.

- How quickly do changes sync
  - Usually near real‑time, depending on connectivity.

- I need a copy of your privacy policy
  - This document serves as the current privacy policy.

- Contact
  - support@carparkwhere.app

- Accessibility
  - We support Dynamic Type and dark mode. Contact us with specific needs.

- Data portability
  - We will assist with reasonable export requests via support@carparkwhere.app.

- Is this legal advice
  - No. This policy is informational; consult your legal counsel for compliance guidance.


- Drafted a tailored privacy policy and a comprehensive FAQ set based on the app’s Firebase Auth, Firestore, FCM, family sharing, geofencing, and AdMob integrations.