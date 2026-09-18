# Privacy Policy — MyPickup

**Effective 18 September 2026**

MyPickup (`com.yapps.mypickup`) is an Android app by y-apps that watches incoming SMS for
package-pickup messages and lists your waiting parcels.

**We collect nothing.** There is no account, no sign-in, no analytics, no advertising, no crash
reporting, and no server belonging to us. Your messages are read and matched on your phone.

## What the app reads

| Data | Why | Where it goes |
|---|---|---|
| SMS messages in your inbox | To find pickup notices and pull out the tracking number, code and pickup point | Stays on your device |
| Pickup details extracted from them | To show your parcel list, notifications and home-screen widget | Stays on your device |
| Your supplier rules and app settings | To know which messages are pickups | Stays on your device |
| A Todoist API token, only if you enter one | To create tasks in **your** Todoist account | Stays on your device; used only to call Todoist |

SMS access is **optional**. "Monitor SMS" is off when you install the app, and the SMS permission
is requested only if you switch it on. With it off, the app never reads your inbox — you paste a
message in by hand and it works exactly the same.

The app never reads messages that do not match one of your rules, and it does not read call logs,
contacts, photos, location, or any identifier about you or your device.

## The only data that leaves your phone

If — and only if — you connect a Todoist account by entering your own API token, MyPickup sends
each **matched** pickup message to Todoist as a task: the pickup code, the supplier name, and the
text of that message as the task description.

- This happens only for messages that matched one of your rules. Unmatched messages are never sent.
- It goes to `api.todoist.com` over HTTPS, and nowhere else.
- It goes into **your own** Todoist account, under your own token. We never see it.
- Disconnect Todoist in Settings and it stops immediately.

Todoist is operated by Doist Ltd. and its handling of that data is governed by their privacy
policy: https://todoist.com/privacy

`api.todoist.com` is the only internet address the app contacts, for any reason.

## Exporting your rules

Rules → ⋮ → **Export rules** writes a file to a location you pick. That file includes the example
message saved with each rule, which is real SMS text and may contain your name, an address or a
tracking link. The app warns you before writing it. Where that file then goes is up to you.

## Storage, retention and deletion

Everything is kept in the app's private storage on your device, which other apps cannot read.
Cloud backup and device-to-device transfer are switched off for this app, so nothing is copied to
Google Drive or a new phone.

Delete a package in the app to remove it. **Uninstalling MyPickup deletes all of it** — messages,
parcels, rules, settings and the Todoist token. We hold no copy, so there is nothing for you to
request from us. Tasks already created in Todoist live in your Todoist account; delete them there.

The Todoist token is stored in the app's private storage. It is not additionally encrypted, so
treat a rooted or compromised device as able to read it, and revoke the token in Todoist if you
are concerned.

## Children

MyPickup is not directed at children and collects no data from anyone.

## Changes

If this policy changes, the new version will be posted on this page with a new effective date.

## Contact

yonka2003@gmail.com
