# Privacy Policy for SyncVia

Last updated: 9 November 2026

SyncVia is an app for shared planning, booking and resource overview
for families and small groups.

This privacy policy applies to SyncVia on Android and iOS.

## Information We Collect

SyncVia may collect and process the following information:

- Name, email address and account information used for login
- User ID used to identify the user account inside the app
- Family or group information, including the invite code
- Booking information, such as selected resource, date, time, purpose
  and user name
- Subscription status and purchase information from Google Play,
  Apple App Store and RevenueCat
- Push notification identifiers: a Firebase Cloud Messaging (FCM)
  registration token, the app platform (Android or iOS), a language
  preference for notification text, and timestamps. These identifiers
  are associated with the signed-in user ID. SyncVia does not use them
  for advertising.
- Technical data needed for authentication, security and app
  functionality

## How We Use Information

We use the information to:

- Let users create and manage a family or group
- Let users create, view and manage bookings
- Let a family administrator approve or decline new members and, if
  that family has turned it on, new bookings
- Manage access to Free, Premium, Premium Plus, Business and Business
  Plus features
- Process and verify subscriptions through Google Play, Apple App
  Store and RevenueCat
- Deliver push notifications about bookings and membership requests
- Provide account, booking and resource functionality
- Provide support if users contact us

## Push Notifications

When you are signed in, the published apps ask the operating system
for permission to show notifications and then try to obtain an FCM
token through Google Firebase, including if you decline permission to
display alerts. Permission to show notifications and the processing of
a notification identifier are therefore separate. Declining or later
turning off alerts stops or limits lock-screen and banner
notifications on the device. It does not by itself stop SyncVia from
requesting or storing a token. On iPhone this also uses Apple Push
Notification service (APNs).

SyncVia stores the token, platform, language and a timestamp in
Firebase Cloud Firestore, linked to your user ID. Other family members
cannot read these tokens. SyncVia’s server functions use the stored
tokens to send notifications.

Lock-screen and notification banner text is generic, for example “New
booking in your group”, “A booking needs approval”, “Your booking was
approved” or “Your membership was approved”. It does not include a
person’s name, email address, booking purpose or the name of a car or
other resource.

A hidden data payload may include the group ID and an internal booking
or request ID so that opening the notification can show the right
screen. That payload is processed by Firebase Cloud Messaging and, on
iPhone, APNs. It is not shown on the lock screen.

Approval and rejection notices are sent only to the person they
concern. Notices about a new booking in the group are separate and are
sent only if a family administrator has turned on “Notify all on new
booking”. SyncVia does not turn that setting on for every group.

You can turn off notifications in the device settings for SyncVia. A
family administrator can also turn group booking alerts on or off in
SyncVia settings. Turning off notifications in the system settings
stops the device from showing alerts; it does not by itself delete a
stored token.

The current device token is removed when you sign out or switch
account, when Firebase rejects the token, or when you delete your
account. A token that has not been refreshed for 90 days is also
removed the next time SyncVia tries to send a notification to that
device. Tokens without a timestamp are kept until one of the other
events above.

## Data Storage

User data may be stored using Firebase services, including Firebase
Authentication and Cloud Firestore.

Subscription and purchase status may be processed by RevenueCat,
Google Play and Apple App Store.

Push delivery may be processed by Firebase Cloud Messaging and Apple
Push Notification service.

## Third-Party Services

SyncVia may use third-party services, including:

- Firebase
- Firebase Cloud Messaging
- Google Play services
- Apple App Store services
- Apple Push Notification service (via Firebase on iOS)
- RevenueCat

These services may process data according to their own privacy
policies.

## Data Sharing

SyncVia does not sell personal data.

SyncVia does not use personal data for third-party advertising or
tracking.

Data may be processed by third-party service providers only when
needed to operate the app, provide subscriptions, authentication,
database storage, push delivery or technical functionality.

## Data Deletion

Users can delete their account inside the app where account deletion
is available.

When an account is deleted, the Firebase Authentication account and
the user’s profile document are deleted. Stored push tokens for that
user, the token ownership index for those tokens, and notification
delivery records that target that user ID are deleted. The user is
removed from the family or group.

Bookings and trips that user created may be kept for the group’s
history and statistics. The displayed name is replaced with “Deleted
user” (stored as “Slettet bruker”). These identifiers are removed from
those records: email address, member user ID, creator ID (`createdBy`),
and any matching approver or rejecter ID. The same creator ID is also
removed from cars or other resources that user created. Other booking
details are kept as free text or operational data: resource name, date,
time and purpose. Those fields are not rewritten.

Notification delivery records that are keyed by booking ID are kept
for 30 days and then deleted automatically. They may contain a
notification type, status, booking ID and hashes of device tokens used
to record delivery. Records that target a user ID are also deleted
when that account is deleted.

If you are the only member and the family owner, the family and its
bookings are deleted instead of anonymized. Owners with other members,
and the last remaining admin, must transfer that role before they can
delete their account.

Users may also contact the developer for questions about data
deletion.

Subscription cancellation must be handled through Google Play
subscriptions or Apple App Store subscriptions, depending on where the
subscription was purchased.

## Children

SyncVia is intended for general family and group use. The app does not
knowingly collect more personal information than needed to provide the
service.

## Security

We take reasonable measures to protect user data and use Firebase and
platform services for authentication and storage.

## Changes

This privacy policy may be updated from time to time. The latest
version will be available at the privacy policy URL provided for the
app.

## Contact

For questions or data deletion requests, contact:

support@syncvia.no
