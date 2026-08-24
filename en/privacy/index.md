# ACNH Notes by Modong Privacy Policy

[한국어](/modongnote-site/privacy/)

Effective date: August 24, 2026

## 1. About this policy

- App: ACNH Notes by Modong (모동노트)
- Developer/operator: Jeonghun Lee
- Operating brand: GRID.DEV, an app development brand of ODD GRID
- Contact: modongnote@gmail.com

ACNH Notes by Modong processes information needed to provide island records, reference browsing, wishlists, turnip-price tools, visitor logs, and an island weather forecast helper.

ACNH Notes by Modong is an unofficial fan-made companion app. It is not affiliated with, endorsed, sponsored, or approved by Nintendo.

## 2. Information we process

| Category | Examples | Where it is processed | Purpose |
| --- | --- | --- | --- |
| Account information | Email address, Supabase user ID, sign-in provider ID, and a name or email supplied by a social sign-in provider | Supabase Auth | Registration, sign-in, session management, and account identification |
| Authentication information | Password authentication data and OAuth tokens or session data | Supabase Auth and on-device session storage | Authentication, automatic sign-in, and social sign-in completion |
| Profile and island information | Nickname, island name and suffix, native fruit, hemisphere, profile-icon preference, and weather seed | Supabase and on-device cache | Displaying and restoring your profile, reference filters, and weather calculations |
| Island residents | Villagers you select for your island | Supabase and on-device cache | Resident lists, filters, and aggregate villager statistics |
| Wishlist and collection progress | Saved reference IDs, categories, museum donations, and collection-state records | Supabase and on-device cache | Saving and restoring wishlist and collection progress |
| Turnip records | Price slots, prediction inputs, previous pattern, first-buy status, and history | Supabase and on-device cache | Turnip pattern estimates and record restoration |
| Visitor records | Dates, visiting characters, related flags, and notes | Supabase and on-device cache | Weekly visitor logs and restoration |
| Community posts | Post text, category, author ID, island snapshot, and post status | Supabase | Displaying, editing, closing, deleting, and moderating posts |
| Support inquiries | Inquiry type and message, optional reply email, app and OS details, status, and timestamps | Supabase | Customer support, status display, and email replies |
| Usage and analytics data | Screen views, feature interactions, ad-area load/failure/impression events, app-instance or device identifiers, and diagnostics | Firebase Analytics/Google Analytics | Understanding usage, reliability, retention, and ad performance |
| Villager statistics | Account, villager, and day-level view records, wishlist counts, and resident counts | Supabase and an on-device retry queue | Aggregate villager rankings and statistics |
| Advertising data | Advertising identifiers, IP-derived approximate location, product interactions, diagnostics, and device or account identifiers processed by Google Mobile Ads | Google AdMob/Google Mobile Ads SDK | Serving and measuring ads, security, and fraud prevention |
| Reference cache | Nookipedia API responses and translation cache | On-device SQLite or web storage | Faster reference browsing |

We do not ask for precise location, contacts, health information, financial information, or payment-card data as part of the app's own features. Advertising and analytics providers may nevertheless infer an approximate location from an IP address and process the SDK data described above.

## 3. On-device storage

ACNH Notes by Modong uses on-device storage for responsiveness and recovery:

- AsyncStorage stores sessions, profile cache, wishlist state, collection progress, turnip and visitor records, daily checklist state, dismissed notices, and ad-frequency information.
- SQLite or equivalent web storage caches external reference data, translations, and pending villager-statistics updates.

Some or all local information may be cleared when you sign out, switch accounts, delete your account, or uninstall the app. Device and operating-system behavior may affect when local copies are removed.

## 4. Services we use

| Service | Role | Information that may be processed |
| --- | --- | --- |
| Supabase | Authentication, database, storage, and server functions | Account information, saved app data, sessions, and operational settings |
| Kakao | Kakao sign-in and connection removal | Kakao account identifier and sign-in token |
| Google | Google sign-in, Google Mobile Ads, and Firebase Analytics | Google sign-in information, ad and analytics identifiers, interactions, diagnostics, and approximate location |
| Apple | Sign in with Apple | Apple account identifier and a name, email, or private relay email supplied by Apple |
| Nookipedia | Reference-data API | Request information and reference-data responses |

These providers process information under their own terms and privacy policies.

## 5. Advertising and analytics choices

The app may display ads using Google Mobile Ads. It requests standard, non-personalized ads by default. If you choose more relevant ads, the app uses Google's consent process where required and, on iOS, requests App Tracking Transparency permission when applicable. If consent or permission is unavailable, denied, or withdrawn, the app requests standard ads or pauses the ad request. No app feature requires personalized advertising.

You can review or change ad choices in the app under **My > Ad settings**. Device-level tracking permission can also be reviewed in iOS Settings.

Firebase Analytics processes screen views and selected feature and ad-area events. Accounts marked for analytics exclusion are excluded from app-initiated analytics events after that operational setting has been loaded.

## 6. Retention and deletion

Account-linked records are generally kept while your account remains active. The operational retention target for day-level villager view records is 30 days. Support inquiries are kept as needed to respond and operate support; the operational cleanup target is within 90 days after an inquiry is answered or closed.

When you complete in-app account deletion, the current server deletion process removes:

- your Supabase Auth account;
- wishlist and collection-progress records;
- turnip and visitor records;
- community posts;
- profile and island information;
- island residents and museum-donation records;
- support inquiries and day-level villager-view records; and
- reviewer/operator account flags associated with your account, if any.

Previously aggregated statistics or operational records may remain after direct user identifiers are removed or separated. Deleting your ACNH Notes by Modong account does not delete your account with Apple, Google, or Kakao. The app attempts to disconnect Kakao when applicable; if that attempt fails, you can review connected apps in your Kakao account settings. Other provider connections may also need to be reviewed in that provider's account settings.

To delete your account in the app, go to **My**, scroll to the bottom, choose **Delete account**, and confirm after the countdown. If you cannot sign in, see the [account deletion page](/modongnote-site/en/account-deletion/) or email modongnote@gmail.com.

## 7. Your choices and requests

You may ask to access, correct, or delete your information by emailing modongnote@gmail.com. Information editable in the app can be changed through the relevant profile or record screen. We may need to verify account ownership before completing an email request.

## 8. Children

The current release is not intended primarily for children. If the app's target audience changes, this policy and the applicable advertising and store settings will be reviewed.

## 9. Security

The app uses encrypted HTTPS connections for service communications, Supabase row-level security and authenticated sessions for server records, and account-aware local-cache handling. No method of transmission or storage can be guaranteed completely secure.

## 10. Reference data and attribution

Selected reference data is provided by or derived from [Nookipedia](https://nookipedia.com/). Some images are served through Nookipedia's [dodo.ac](https://dodo.ac/) CDN. This attribution identifies the source of reference material; it does not make a legal conclusion about separate rights in Nintendo-related content.

## 11. Changes

If this policy changes, notice may be provided through the app, store listing, or this page. The effective date at the top will be updated when a revised policy takes effect.
