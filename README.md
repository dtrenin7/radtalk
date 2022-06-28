# Radtalk: RADio TALKing Messaging application for Android

Allows you to send secure messages and voice through your bluetooth walkie-talkie.

## Installing and running

This is a standalone app. All contacts, message threads are strored in local encrypted database.
You must make password for your db on the first run.

## What works:

* One-on-one conversations and group chats.
* Channels with unlimited number of read-only subscribers.
* Unread message counters.
* Push notifications and in-app presence notifications.
* Message status notifications: message delivery to server; received and read notifications; typing notifications.
* Markdown-style formatting of text, e.g. \*styled\* &rarr; **styled**. Implemented as spannable.
* Replying and forwarding messages.
* Trusted account badges: verified account, staff, etc.
* Form messages suitable for chatbots.
* Attachments and inline images, voice messages.
* Muting/un-muting conversations and other granular permission management.
* Integration with Android's stock Contacts.
* Invite contacts to the app by SMS or email.
* Transport Level Security - https/wss.
* Offline mode.

## Not done yet:

* ...

## Dependencies

### SDK:

* [Jackson](https://github.com/FasterXML/jackson) for JSON serialization.
* [Java-WebSocket](https://github.com/TooTallNate/Java-WebSocket/) for websocket support.

SDK contains no Android-specific dependencies.

### Application

* [Picasso](https://square.github.io/picasso/) for image downloading and caching.
* Standard Android dependencies.

## Other

Demo avatars and some other graphics are from https://www.pexels.com/ under [CC0 license](https://www.pexels.com/photo-license/).

Background patterns from http://subtlepatterns.com/, commercial and non-commercial use allowed with attribution.

The [`contacts.vcf`](./contacts.vcf) contains a list of contacts which can be used for testing. Push it to your emulator using command
```
adb push contacts.vcf /sdcard/contacts.vcf`
```

## Translations

The app is currently available in the following languages:
* English
* Chinese (simplified)
* Chinese (traditional)
* French
* German
* Korean
* Russian
* Spanish
