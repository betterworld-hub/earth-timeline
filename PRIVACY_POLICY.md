# Privacy Policy — Earth Timeline

**Last updated: 10-Aug-2026**
**Contact: betterworld.knowyourchild@gmail.com**

## The short version

Earth Timeline shows you where a place on Earth sat at different points in
geological history. It has no accounts, no sign-in, and no ads. We do not know
who you are, and we do not build a profile of you.

The app **never accesses your device's location**. It only knows the place name
you type into the search box.

## What the app does with what you type

When you search for a place, the text you type is sent to **Google's geocoding
service** (via Android's built-in `Geocoder`) to turn it into coordinates.
Those coordinates are then sent to the **GPlates Web Service**
(`gws.gplates.org`), operated by the EarthByte group at the University of
Sydney, to calculate where that point sat in the geological past.

- The search text and coordinates are used only to answer that request.
- They are **not stored** by Earth Timeline, on your device or anywhere else.
- They are **not included in analytics** — see below.
- Once you close the app or clear the search, they're gone.

Those two services are independent third parties with their own privacy
practices, which we don't control:

- Google (geocoding): https://policies.google.com/privacy
- GPlates / EarthByte (paleocoordinates): https://www.earthbyte.org

## Analytics

The app uses **Google Firebase Analytics** to understand how the app is used
in aggregate — for example, how many people try the timeline, and whether place
search works.

We deliberately **do not** send:

- the place you searched for, in any form
- the coordinates it resolved to, or anything derived from them such as your
  city, region or country
- your device's advertising identifier
- anything that identifies you as an individual or across apps

What we do send is limited to: that the app was opened; that an epoch was
selected, and which one; that a search happened, whether it succeeded, and how
long it took.

Firebase itself automatically collects some technical information such as an
app instance identifier, device model, OS version, and coarse region derived
from IP address. Google's handling of that data is covered by their privacy
policy: https://firebase.google.com/support/privacy

## What we never collect

- Device location (GPS, network, or otherwise). The app does not request
  location permission at all.
- Contacts, photos, files, microphone, camera, or calendar.
- Names, email addresses, phone numbers, or accounts.
- Any data from children specifically. The app is not directed at children.

## Data retention and deletion

Earth Timeline stores nothing about you on our side, so there is nothing to
delete on request. Search text lives only in memory while you're using the app.

If analytics is enabled and you want to opt out, you can uninstall the app, or
clear its data from Android Settings, which resets the anonymous analytics
instance identifier.

## Permissions the app requests

| Permission | Why |
|---|---|
| `INTERNET` | Look up place names and fetch paleocoordinates |
| `ACCESS_NETWORK_STATE` | Detect whether a lookup can be attempted |

That is the complete list. In particular, the app requests **no location
permission**.

## Changes

If this policy changes, the "Last updated" date above changes with it. Material
changes will be noted in the app's release notes.

## Contact

Questions about this policy: **betterworld.knowyourchild@gmail.com**
