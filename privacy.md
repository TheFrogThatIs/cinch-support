---
title: Cinch — Privacy Policy
---

# Privacy Policy for Cinch

**Last updated: 10 October 2026**

Cinch is a card game that runs on your device. It has no accounts, no sign-in, no
advertising, and no social features. This policy describes the small amount of data the
app does send, and the larger amount it deliberately does not.

## The short version

- **The names you type never leave your device.** Not to us, not to anyone.
- There is **no account** and we never ask for your name, email, phone number, contacts,
  photos, or location.
- The app sends **anonymous diagnostic and gameplay statistics** so we can tell whether it
  is working and whether the game is any good.
- **Nothing is sold, shared with data brokers, or used for advertising or tracking.**

## What the app collects

The app uses three services from Expo (EAS Insights, EAS Observe and EAS Update) for
updates, performance and crash diagnostics, and **PostHog** for gameplay statistics.
Together they send the following.

### Installation identifiers

Two random identifiers are created on your device. One is shared by the Expo services, and
the other by the gameplay statistics sent to PostHog. Each is sent with its own data, so
that events from one installation can be grouped together.

Both are generated on your device and neither is derived from your name, your Apple
account, or any hardware identifier. Neither is an advertising identifier, and the app
does not copy one into the other. Deleting and reinstalling the app creates new ones.

We are naming them plainly because they are persistent identifiers, even though they
identify an installation rather than a person.

### Gameplay statistics

Anonymous facts about how games go, such as: a game was started or finished, what was bid,
which suit was trump, whether the bid was made or set, how many points and tricks were
taken, and the stage a game was at if it was abandoned.

**These never include the cards in anyone's hand, a record of the moves played, or any
name.** Where something needs summarising, it is reduced to a single number or label on
your device first, and only that summary is sent.

They are sent with the app's version and the kind of device and operating system it is
running on, so that a problem on one kind of phone can be told apart from a problem with
the game. They are **not** sent with your language, your time zone, or any location. The
service is configured not to work out a location from your internet address, and to
discard that address when the statistics arrive.

### Performance and crash diagnostics

How long the app takes to start and to become usable, which screen was involved, and — if
the app crashed the last time you used it — the error message from that crash.

Crash information consists of a technical error message only. No game state, no hand, and
no name is attached to it.

## What the app never collects

- **Player names.** They are typed by you, stored only on your device, and no part of the
  app is permitted to transmit them. This is enforced by an automated test in our source
  code, not merely by intention.
- Your contacts, photos, files, microphone, camera, or location. The app requests no such
  permissions.
- Any contact information, because there is nothing in the app that asks for it.
- Purchase or financial information. The app contains no purchases.

## What we do not do with it

The data is used only to keep the app working and to understand how the game is played. It
is **not** sold, **not** shared with data brokers or advertisers, **not** used to build a
profile of you, and **not** combined with data from other apps or websites. There is no
advertising and no third-party tracking of any kind.

## The web version

The web version of Cinch sends **nothing at all**. The services described above do not
function in a browser build; their calls succeed and discard their arguments.

## Playing offline

Cinch is fully playable with no network connection. If the app cannot reach the internet,
it simply carries on.

## Children

Cinch is rated 4+ and is suitable for all ages. It collects no personal information from
anyone, including children. There is no chat, no user-generated content, and no way for
users to contact each other through the app.

## Data processing and retention

The data described above is transmitted to and stored by our service providers:

- **Expo** (Expo Application Services): updates, performance and crash diagnostics. See
  <https://expo.dev/privacy>.
- **PostHog**, on its United States cloud: gameplay statistics. PostHog is configured never
  to build a profile of a person. See <https://posthog.com/privacy>.

## Changes

If this policy changes, the date at the top will change with it, and the current version
will always be available at this address.

## Contact

Questions about this policy or about the app: **cinchcardgame@gmail.com**
