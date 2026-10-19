# switchwise-privacy

The privacy policy and support pages for **Switchwise** (`com.cucerenco.switchwise`), one set for both the iPhone and the Android app, served by GitHub Pages from `main` at the repository root.

| Page | URL | Used as |
|---|---|---|
| `index.html` | `https://maxe34.github.io/switchwise-privacy/` | the privacy policy URL in App Store Connect, Google Play Console and the game's Settings |
| `support.html` | `https://maxe34.github.io/switchwise-privacy/support.html` | the support URL in App Store Connect and the game's Settings |

`SettingsScreen.PrivacyPolicyUrl` and `SupportUrl` in the Switchwise repo point here. If these URLs ever move, those constants and the store fields move with them: a policy link that 404s is a review rejection.

The policy describes what the game actually does: progress on the device (and the player's iCloud on iPhone), no analytics of its own, AdMob ads behind Google's consent form, Game Center sign-in on iPhone with no scores sent, purchases through Apple and Google Play. When the game changes any of that (leaderboards, a new ad type, analytics, an Android cloud save), the text here is part of the change, and the effective date moves.
