# Privacy Policy for Memorie

**Last updated: 20 September 2026**

Memorie is a place to keep the memories of a life — yours, or someone
you love. What you write down is yours. This page explains, in plain
language, exactly where it goes and where it doesn't.

The short version: **your memories live on your phone.** There is no
account, no sign-up, and no copy of your timeline on any server we run.
One feature, and only one, sends anything off your device, and you
choose when it happens.

---

## What Memorie stores, and where

Everything you capture is written to storage on your own device:

- the text you write, and the date and time of each memory
- photos you add, saved inside the app's own storage
- voice recordings, and the text they were transcribed into
- tags, and the recaps you have chosen to save
- the names and, if you set one, the birthdays of the people whose
  timelines you keep

**Videos are not copied.** When you add a video, Memorie stores only a
reference to the one already in your Photos library, and plays it from
there. The video never enters the app's storage, and deleting it from
Photos removes it from Memorie too.

None of this is uploaded, backed up to us, or synced anywhere. If your
phone backs itself up to iCloud, Memorie's data is included in that
backup under Apple's terms, not ours — we never see it.

## The one thing that leaves your device

When you tap **Write my recap**, Memorie sends the memories in the date
range you picked to be written up into a narrative. Nothing else in the
app makes a network request of any kind.

What is sent, for that range only:

- the date and time of each memory, and its kind (text, photo, voice, video)
- the text you wrote, and the transcript of any voice note
- any tags on those memories
- the first name and age of the person the timeline is about

**What is never sent:** your photographs, your videos, and the audio of
your voice recordings. Voice notes are transcribed **on your device** —
the recording itself never leaves it, and only the resulting text can be
included in a recap.

The request carries no name, email address or account, because Memorie
doesn't have any. It does carry a **per-install key**: a random
identifier your iPhone creates the first time you write a recap, which
proves the request came from the real Memorie app and not from someone
who found the address of our service and wanted to spend our credit on
it. It is not derived from you or your phone, it says nothing about
either, and deleting and reinstalling the app replaces it with a new
one.

### Who handles it

The request passes through a small service we run on **Cloudflare**,
which holds the credentials needed to reach the writing model. It stores
none of your memories. Cloudflare processes the request in transit and
may log ordinary technical information such as the originating IP
address, as any web service does.

Our service keeps two small things, and no memories: the per-install key
above with a count of recaps written by it, so the monthly limit and the
abuse limits can be enforced; and a short-lived count of requests per
internet address, which expires within hours. Neither is linked to a
person, and neither contains anything you wrote.

From there it goes to **Anthropic**, which generates the recap and
returns it. Anthropic may hold the request briefly for safety and abuse
monitoring under their own terms. Under Anthropic's Commercial Terms of
Service, *"Anthropic may not train models on Customer Content from
Services"* — your memories are not used to train AI models. Anthropic's
own privacy policy is at https://www.anthropic.com/legal/privacy.

The recap comes back, is shown to you, and is kept on your device only
if you tap **Save this recap**.

If you never use the recap feature, **nothing about you or your
memories ever leaves your phone.** You can also switch recaps off
entirely in **Settings → Recap usage**, which stops any request being
made at all.

## What Memorie does not do

- **No accounts.** No email, no password, no sign-in.
- **No advertising.** No ad networks, no ad identifiers.
- **No analytics or tracking.** We do not measure how you use the app,
  and there is no third-party analytics, crash-reporting, or attribution
  code in it.
- **No selling or sharing.** Your memories are not sold, rented, shared,
  or handed to data brokers. There is no circumstance in which we would.
- **No profiles.** We do not build a picture of you, because we have
  nothing to build one from.
- **No location.** Memorie never asks for or records your location.

## Permissions Memorie asks for

Each is requested only when you first use the feature that needs it, and
declining one simply disables that feature:

| Permission | Why |
|---|---|
| Camera | To take a photo as part of a memory. |
| Photo library | To add photos and videos you have already taken, and to play those videos back. |
| Microphone | To record a voice note. |
| Speech recognition | To transcribe voice notes on your device so they can be searched. |
| Notifications | To remind you of a memory from this day in a previous year. |

Notifications are created on your device and are never sent through any
server. Their text carries a count and a first name — for example
"3 memories of Noah from this day" — and never the content of a memory,
so nothing private appears on a lock screen someone else can see.

## Children

Memorie is a tool for an adult keeping a record. It is not directed at
children, and it has no social features, no messaging, no user accounts,
and no way for anyone to contact anyone through it.

Many people use Memorie to keep a timeline for a child. That
information is entered by you, stays on your device under your control,
and is subject to everything above — in particular, a child's
photographs and voice recordings never leave the device, and their
memories are only ever transmitted if you choose to generate a recap.

## Your control over your data

- **Delete a single memory.** Open it and delete it.
- **Delete a person's timeline.** *Settings → the person → Remove.* This
  deletes their memories, photos and recaps, and affects nobody else.
  (With only one person kept, use Delete everything below.)
- **Delete everything.** *Settings → Delete everything.*
- **Delete the app.** Removing Memorie from your device removes
  everything it stored, including the per-install key. Because we hold
  no memories of yours, there is nothing left for you to ask us to
  erase.

We keep your memories for as long as they are on your device, and no
longer — that decision is entirely yours, not ours.

## Security

Your memories are protected by your device's own encryption and
passcode, which is the same protection your photos and messages get. The
recap request travels over an encrypted (HTTPS) connection.

No system is perfect, and we would rather say so than promise otherwise.
What we can say is that the amount of your data we hold is zero, which
is the strongest protection available.

## Changes to this policy

If this policy changes, the date at the top will change with it, and any
change that affects what leaves your device will be described here
plainly rather than buried.

## Who we are

Memorie is made by Srinidhi Konappagari, an independent developer.
Requests to write a recap are processed in the United States by the
services named above.

## Contact

Questions about this policy, or about your data:

**reddysrinidhi70@gmail.com**
