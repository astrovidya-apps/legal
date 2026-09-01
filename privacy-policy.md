---
title: Privacy Policy
permalink: /privacy-policy/
---
# Privacy Policy

Last updated: 28 August 2026

AstroVidya ("the app", "we", "us") is an offline-first Vedic astrology app. This
policy explains what the app does with your information. It is written to be read,
not to be skimmed past.

The short version: we do not run a server, we do not have accounts, and we do not
collect your personal data. Everything you enter — your name, your birth details,
your charts — stays on your phone and is never sent anywhere. The one thing that
does leave your device is an advertising request to Google, described in section 4.
It carries no astrology data and nothing you typed into the app.

## 1. Who is responsible

AstroVidya is published by the developer identified on its Google Play listing.
Questions about this policy can be sent to astrovidya.support@gmail.com or to the
contact address on that listing.

## 2. What you give the app

To draw a birth chart the app asks for a name, date of birth, time of birth and
place of birth. To match two charts it asks for the same details for both people.

This information is stored only in the app's private storage on your device. It is
not uploaded to us, because there is nothing to upload it to: we operate no server
and no account system, and the astrology engine runs entirely on your phone.

The birth place you pick is matched against a list of cities that ships inside the
app. Choosing a city does not look anything up over the network and does not reveal
where you are — the app never requests your device's location, and holds no location
permission.

## 3. Your astrology data never leaves your device

Every feature — Kundli, Panchang, Muhurta, Matchmaking, Horoscope and Career Guidance
— is computed on your phone from the data you entered. Your name, birth date, birth
time, birth place, charts, matches and horoscopes are never transmitted anywhere.
There is no cloud sync, no backend, no third-party content service and no AI service.
Earlier versions included an optional AI chatbot that could send messages to a
third-party provider — that feature has been removed, and with it the only path by
which anything you typed could leave the device.

The app's only outbound network traffic is the advertising request described next.

## 4. Advertising

**This version of the app shows banner ads.** They are supplied by Google AdMob and
are shown to users who do not have Premium.

To fill an ad slot, the Google Mobile Ads library sends a request to Google that
includes your device's advertising ID, your IP address, general device information
(such as model, operating system version and screen size), which app is asking, and
whether you interacted with the ad. That is standard for mobile advertising, and it
is the only information about you that leaves this app.

**No astrology data is ever included in an ad request.** Your name, birth date, birth
time, birth place, charts and horoscopes are not sent to Google, are not used to
target ads, and are not shared with anyone.

Google's handling of that data is governed by Google's Privacy Policy
(https://policies.google.com/privacy) and by "How Google uses information from sites
or apps that use our services" (https://policies.google.com/technologies/partner-sites).

**Asking you first.** Before the app makes its first ad request it checks, through
Google's User Messaging Platform, whether the law where you are requires that you be
given a choice about personalised advertising. Where it does, a form appears and no ad
is requested until you answer it. You may decline: ads still appear, they are simply not
personalised. Where no such requirement applies, no form is shown and nothing interrupts
you. If you were shown that form, **Settings → Ad privacy settings** inside the app lets
you change or withdraw your answer at any time; that entry stays hidden where it would
do nothing.

**Where the app is available.** AstroVidya is not offered on Google Play in the European
Economic Area or the United Kingdom.

You can limit this yourself. In **Android Settings → Privacy → Ads** you can reset
your advertising ID, or delete it entirely. Deleting it stops the app from receiving a
usable identifier — ads still appear, but they are not personalised.

Ads appear only on the main content screens. There are none during onboarding, none on
the birth-details form, none in Settings, and none on this document.

## 5. Payments

The app offers **Premium**, and the only thing it does is remove the ads described in
section 4. No astrology feature is locked behind it — Kundli, Panchang, Muhurta,
matchmaking, horoscopes, career guidance and PDF export are free for everyone.

Premium is sold as an **auto-renewing subscription**, monthly or yearly. It renews until
you cancel it, and you can cancel at any time in Google Play → Subscriptions. Cancelling
stops the next renewal; your access runs to the end of the period you have already paid for.

Payment, renewal and cancellation are handled entirely by Google Play. We never see,
receive or store your card details, and we run no payment system of our own. What stays on
your device is a single flag recording that a subscription is currently active — no payment
data and no billing history. "Restore Purchases" on the Premium screen asks Google Play
whether your account holds a subscription, which is what recovers it after a reinstall or
on a new device.

## 6. Analytics and tracking

**We run no analytics.** There is no crash-reporting library in the app, no third-party
tracker, and no profile of you is built by us. We receive no report of any kind about
how you use the app, because there is nowhere for such a report to go.

To be exact about what is inside the app package rather than only about what runs: the
advertising library described in section 4 ships with Google's app-measurement
components. The app explicitly switches them off — analytics collection is disabled,
advertising-ID collection by the measurement component is disabled, and measurement
initialisation is deferred. What remains is the ad request itself, and that is fully
described in section 4.

## 7. Permissions the app asks for, and why

This is the complete list. Some of these are not asked for by the app itself but are
merged in by the Google libraries it includes; they are listed here anyway, because a list
that leaves things out is not a list.

  - **Internet** — used to request the banner ads described in section 4. No app feature
    uses the network; every chart, panchang, match and horoscope is computed offline.
  - **Network state** — added by the Google Mobile Ads library, which checks whether a
    connection exists before trying to fetch an ad. It reveals whether you are online, not
    what you do online: it gives no access to your browsing, your traffic or its contents.
  - **Advertising ID (AD_ID)** — declared by the Google Mobile Ads library so that it can
    request ads. See section 4, including how to reset or delete that identifier.
  - **Ad Services (Topics, Attribution, Advertising ID)** — three permissions declared by
    the Google Mobile Ads library for Android's Privacy Sandbox, the system-level framework
    that is replacing cross-app tracking. They let the ad library ask Android for ad
    signals instead of gathering them itself. They give it no access to anything this app
    stores, and nothing described in section 3 is affected.
  - **Notifications** — only to deliver the daily horoscope, and only if you switch it on.
  - **Storage (Android 9 and below only)** — only to save a chart PDF you asked to export.
  - **Wake lock / foreground service** — added by Android's own WorkManager, which is what
    schedules the daily horoscope reminder. They let that one job finish once it starts.
    Nothing else runs in the background, and neither permission gives access to your data.
  - **Billing** — added by the Google Play Billing library described in section 5. It is
    used only if you choose to buy or restore Premium. The purchase itself is completed by
    Google Play; no payment details ever reach this app.

There is also one internal permission that Android generates for the app's own components
to talk to each other. It cannot be held by any other app and grants nothing.

The app requests **no location permission**, **no contacts**, **no camera** and **no
microphone**.

## 8. Children

The app is not directed at children under 13. We do not knowingly collect information
from children. As the app stores nothing on our side, there is nothing for us to
delete; a parent or guardian can remove all locally stored data by using the option in
section 9, by uninstalling the app, or by clearing its storage.

## 9. Your rights, and how to exercise them

Because the data you enter never leaves your device, you exercise your rights directly,
inside the app:

  - **See it** — it is shown to you in the app, and prefilled into the Kundli form.
  - **Correct it** — edit the birth details and regenerate the chart.
  - **Export it** — export any chart as a PDF from the chart screen.
  - **Delete it** — **Settings → Delete My Data** permanently erases your birth details,
    your saved chart and your preferences. It cannot be undone. A Premium entitlement, if
    you ever have one, lives with Google Play rather than with us, and "Restore Purchases"
    brings it back.

Uninstalling the app, or using Android's own "Clear storage" option, also removes
everything.

For the advertising identifier described in section 4, which is held by Android rather
than by us, use **Android Settings → Privacy → Ads** to reset or delete it.

If you are in a jurisdiction with statutory data rights, such as the GDPR or India's
Digital Personal Data Protection Act, this is how those rights are met.

## 10. Changes to this policy

If this policy changes, the updated version will ship with an app update and the date
at the top will change. Continuing to use the app after an update means you accept the
revised policy.

## 11. Astrology disclaimer

AstroVidya provides astrological information for personal interest and cultural
study. It is not advice, and it is not a substitute for professional medical, legal,
financial or psychological guidance. See the Terms of Service for the full disclaimer.
