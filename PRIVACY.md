# Island privacy policy

_Last updated: 8 November 2026_

Island is a Windows app sold by **Almost Intelligent** through Whop. This policy explains what
Island does with your information. In short: almost everything stays on your PC.

## What stays on your PC

Island keeps these only in `%APPDATA%\Island` on your computer, and never sends them anywhere:

- your settings, timers and recent apps list;
- what's playing, your volume, battery level, and which apps use your microphone or camera;
- screenshot previews (Island only shows them; it doesn't upload them);
- a diagnostics log (`island.log`), which you can choose to send us when asking for help.

## What Island sends: the licence check

When Island starts, and a few times a day while it runs, it checks that your licence is valid.
It sends our licence server:

- **your licence key**, and
- **an anonymous ID for your PC**: a one-way scrambled form (SHA-256) of Windows' machine ID.
  It identifies "the same PC" for the one-PC-per-key rule, but can't be turned back into
  anything about you or your computer.

The licence server runs on **Cloudflare Workers**. It asks **Whop** whether your key belongs to an
active Island membership, and stores the anonymous PC ID on that membership so the key works on
one PC at a time. Like any web service, Cloudflare records basic request details (such as the
time, IP address and approximate location) in logs that are kept for a few days for running and
debugging the service.

Island sends nothing else: no analytics, no tracking, no ads, and nothing about what you play,
open or do.

## Payments and your account

Purchases, billing and your Whop account are handled by Whop under
[Whop's privacy policy](https://whop.com/privacy/). We see what Whop shows sellers, such as your
Whop username, email and membership status, and use it only to provide Island and support.

## Your choices

- Uninstalling Island removes the app. To remove your local data too, delete `%APPDATA%\Island`.
- **Settings → Licence → Remove** clears your licence from the PC and the PC ID from your
  membership.
- To ask about or delete information connected to your membership, message us through
  [Island's Whop page](https://whop.com/almost-intelligent/island-c0/).

## Changes

If this policy changes, the new version will be posted here with a new date.
