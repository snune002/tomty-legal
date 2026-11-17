---
title: "Tomty Tester Privacy Policy"
---

# Tomty Tester Privacy Policy

**Version 2**


**Last updated:** November 5, 2026

## In short

- The app keeps your lists, Meals plan, reminders and store choices on your phone. Some related data leaves your
  phone as section 3 explains.
- Some data must leave your phone for a feature to work. For example, your voice goes to a speech-to-text service,
  and your location goes through our server to Apple Maps or Google Maps when you search for stores. In the United
  States, the stores you pick can also be looked up in our server's copy of Overture's open map data (clause 3.13).
- We do not sell your data. The app has no advertising or analytics tracking of its own. On Android, Google's map
  software sends Google some data about how the map is used (clause 3.11, "The maps in the app").
- If you agree, we use the words of your voice commands (never the audio) to develop our own model, keep them up to
  12 months, and remove them when you withdraw or clear your history (clause 3.20).
- For every piece of data, the sections below say what it is, why we keep or send it, who receives it and how long
  it lasts.
- You can control location, microphone and notification access in your phone's Settings. Section 7, "Your
  choices," explains these controls and what deleting the app removes.

The full policy starts at clause 1.1 and governs. This summary helps you find the relevant details.

## 1. About this policy

1.1 This policy is provided by Hari, the developer of Tomty ("we", "us" or "our"). It covers the whole Tomty
app ("the app"), on iPhone and on Android.

1.2 "Our servers" means the servers that run the app's online features. "Our hosting provider" means Google Cloud,
which runs our servers and stores the app's content.

1.3 This policy sits beside the Tomty Tester Terms at https://snune002.github.io/tomty-legal/terms. The Tester Terms cover your use of the
test build: the daily and weekly limits, pausing, your agreement to send your data to the outside services named
here, changes and stopping. This policy is the full account of the data the app uses.

## 2. Data kept on your phone

2.1 **Your lists.**

- *What:* your lists and their names. For each item, the app keeps its name, amount, category and whether you
  checked it off, and, for an item that Meals added, which Meals plan and ingredient it came from. It also keeps
  each list's shopping date, shopping time and reminder times.
- *Why and how it is used:* so the app can show and organize your lists. When you use voice, it sends some list
  contents as clauses 3.1, "Turning your voice into text", and 3.2, "Understanding what you said", explain.
- *How long:* until you change them, delete them, or delete the app. There are two exceptions: the recovery copy in
  clause 2.10, "Copies of damaged data", and an old copy of your lists from a very early test version of the app.
  If your phone still has that old copy when the app first opens the current version, the app keeps it, only to
  read, until you delete the app. If you installed the current version as a new app, there is no old copy.

2.2 **Categories the app has learned.**

- *What:* the category the app has learned for an item name, for example that "basil" goes in Produce. It keeps
  up to 1,000 of these.
- *Why and how it is used:* so the next item with that name goes into the same category without asking again.
- *How long:* until you delete the app. When the app has 1,000, it removes the one it saved or updated longest
  ago to make room.

2.3 **Your voice recordings.**

- *What:* each time you use the microphone, the app saves your recording as a file in its own temporary storage
  (its cache) on your phone. It is never saved to your phone's photo or file library.
- *Why and how it is used:* to turn your voice into text, as clause 3.1, "Turning your voice into text", explains.
  If a recording ends on its own while you are away from a list or the app is in the background, the app keeps it
  as a pending voice capture (clause 2.4, "Pending voice captures").
- *How long:* a pending voice capture's recording is deleted with the capture (clause 2.4). Speech you add to a
  pending voice capture is deleted once it has been turned into text, or when that fails. Other recordings stay in
  the app's temporary storage until your phone clears that storage, for example when it needs space, or until you
  delete the app.

2.4 **Pending voice captures.**

- *What:* a pending voice capture holds your recording, the text of what you said, the app's interpretation and
  any changes you make during review.
- *Why and how it is used:* so you can play it back, review it and then add it to your lists or throw it away.
- *How long:* a capture expires 24 hours after it was made. The clock starts again when you add more speech to it,
  and when you add it to your lists; after you add it, the app keeps it until it expires so you can undo that step.
  The app deletes an expired capture, with its recording, the next time it checks, for example when the app starts
  or comes back to the front, but not while you have it open for review. If you throw a capture away, the app
  deletes it at its next check after both of these: 5 seconds have passed, and you can no longer undo that step.
  To limit their number and size, the app may remove some captures sooner, but never one you have open, or one
  still waiting to be added that you changed during review.

2.5 **Your reminders.**

- *What:* when you set reminders for a list, the app saves which lists have reminders, when each reminder is due
  and the identifier your phone gives it. It also saves when a list's reminder last went off, when you last opened
  that list, the last 50 reminders you opened, whether you allow notifications and whether the app has already
  asked you. Your phone's notification system holds each scheduled reminder: its title and text, which name the
  list, which list it is for, and when it is due.
- *Why and how it is used:* so the app can schedule, change and cancel reminders as your lists change, mark a list
  whose reminder went off until you open it, and avoid handling the same opened reminder twice.
- *How long:* a reminder stays scheduled until it goes off or the app cancels it, for example when you change or
  clear the list's time. The app removes these records when they are no longer needed, for example when a list is
  deleted, and all of them when you delete the app. Damaged records can leave a recovery copy (clause 2.10,
  "Copies of damaged data").

2.6 **Your store choices.**

- *What:* when you choose a store branch, including in Meals, the app saves a branch record on your phone: the map
  service, the branch's place identifier (the map service's code for that branch), its position, when the position
  was found and when you chose the branch. A record from Apple Maps also holds the branch's name and address. A
  record from Google Maps does not; the app asks our servers for them again when a screen needs them (clause 3.3,
  "Store searches and maps"). In the United States, a record can also hold the store's details from Overture's open
  map data: its Overture identifier, name, address, position and kind of store (clause 3.13, "Overture's open
  data"). The app also saves each list's name, which branch to use by default for a store, which store and branch
  you chose for each kind of specialty store, and, for a list made from Meals, which store and kinds of specialty
  store the list serves.
- *Why and how it is used:* so your lists show where you shop, and so Meals can offer the same stores the next time
  you add a week to your lists.
- *How long:* a list's name, and the store details saved for a list made from Meals, stay until you change them or
  delete the list. Branch records, with their Overture details, stay until you delete the app, even after you delete
  the list or choose a different branch; undoing the step that saved one can remove it. Your other choices stay
  until you change them or delete the app. The name, address and position in a record from Apple Maps, and the
  position in a record from Google Maps, each expires 30 days after it was found. That is Google's limit for
  keeping map positions, which the app also applies to Apple Maps content. The app clears expired content while it
  runs, or the next time it runs. The Overture details do not expire. Damaged data can leave a recovery copy
  (clause 2.10, "Copies of damaged data").

2.7 **Your Meals data.**

- *What:* your week plan (the dish and servings for each day), favorites, saved recipes, the last 10 recipes you
  viewed, and your Meals preferences: diet, ingredients to avoid, household size, cooking days, weekly budget and
  moods. While you choose where and when to shop, the app also keeps your unfinished shopping choices in its memory.
- *Why and how it is used:* so the app can plan your week, filter dishes and remember your choices. It stays on your
  phone and is not sent to us.
- *How long:* until you change it or delete the app. The unfinished shopping choices are dropped when you close the
  shopping screens or the app closes; tapping Add to List saves them with your lists (clause 2.6, "Your store
  choices").

2.8 **Your device identifier and sign-in credentials.**

- *What:* the app creates a random code for your device when it is first set up. We call this your device
  identifier. Our servers also give the app sign-in credentials, which the app uses to access them. The app keeps
  both in your phone's secure storage, called the keychain on iPhone. Our database holds neither your name nor your
  email: the enrollment code we emailed you is the only link between your sign-up email and your device (clauses
  3.8, "Signing in", and 3.18, "The tester sign-up form").
- *Why and how it is used:* so our servers know a request comes from the app (clause 3.8, "Signing in").
- *How long:* until the app replaces or deletes them. On iPhone, the keychain can keep them even after you delete
  the app (clause 7.4, "Deleting the app").

2.9 **Small app settings.** The app also saves a few settings on your phone, such as whether you have already seen
the map's help and whether you allow notifications. They stay until you delete the app.

2.10 **Copies of damaged data.**

- *What:* if the app finds your lists, your pending voice captures or your reminder records damaged and cannot read
  them, it saves a copy of that damaged data on your phone before it carries on without it. The copy can hold
  anything that data held.
- *Why and how it is used:* so that damaged data is not lost for good. The app does not restore your data from the
  copy or send it anywhere.
- *How long:* the app keeps one copy for each of the three kinds of data; a newer copy replaces the older one. From
  a copy of your lists that can still be read, the app removes the names, addresses and positions from Apple Maps
  and Google Maps in its saved store branches, and keeps the copy until you delete the app. If it cannot be read at
  all, the app deletes the copy 30 days after saving it, or the next time the app runs after that. A copy of your
  pending voice captures or of your reminder records stays until you delete the app.

2.11 **Content saved on your phone.**

- *What:* copies of the content the app has downloaded (clause 3.6, "Content"), kept in the app's own
  cache on your phone, not in your photo library.
- *Why and how it is used:* so content shows quickly and is not downloaded again.
- *How long:* until your phone clears the cache, or until the app removes content that is no longer part of the
  app's recipes, for example content an update has replaced. Removing a recipe from your week or your favorites does not delete its content.

2.12 **Your last store search, on your phone.**

- *What:* the spot you searched from, your US state, which map service answered, when the search ran, and the
  well-known grocery chains' branches found near it: our name for each chain, the map service's place identifier,
  its position and when it was found. It never keeps the store's own name or address from the map service.
- *Why and how it is used:* when you open store suggestions again in the same state, with the same map service,
  within 10 miles of that spot and within 30 days, the app shows those chains straight away instead of searching
  for them again. The saved search stays on your phone and is never sent to us.
- *How long:* the app keeps only your latest area; a complete search somewhere new replaces it. After 30 days
  (Google's limit for keeping map positions), the saved search is no longer used, and the app deletes it then or
  the next time it runs.

## 3. Data that leaves your phone

3.1 **Turning your voice into text.**

- *What:* your recording goes from your phone, through our servers, to Deepgram, our speech-to-text service. The
  app also sends up to 100 words or phrases to help Deepgram recognize what you say. These are your list names,
  phrases made of "in" and a list name, a few fixed words such as "double" and "twice", and the names of the items
  on your lists that are not archived. Deepgram does not receive your device identifier or your sign-in
  credentials.
- *Why and how it is used:* Deepgram turns your recording into text. These words and phrases help Deepgram
  recognize your speech, for example by distinguishing "milk in Target" from "milking target". We do not store your
  recording (clause 3.14, "Your recording on our server").
- *How long:* Deepgram handles recordings and these words and phrases under its own terms and privacy policy. We
  take part in Deepgram's model-improvement program and do not opt out of it when we send recordings. Under that
  program, Deepgram may keep small parts of recordings to improve its voice models and provide customer support.
  Deepgram says it does not share this data with others without permission from its customers, such as us, and
  does not use it for advertising. Deepgram explains the program at
  https://developers.deepgram.com/docs/the-deepgram-model-improvement-partnership-program.

3.2 **Understanding what you said.**

- *What:* the app sends our servers the text of what you said and your list names. It also sends the items on the
  list you are speaking to. When you are not on a list, it sends the items on all your lists that are not archived
  instead. For each item, it sends what the app keeps about that item, such as its name, amount, category, whether
  you marked it as already at home and whether Meals added it. When you answer a question from our servers, the app
  also sends your answer, the details of that question and the items our servers suggested before.

  Our servers may send Cerebras or OpenAI the text of what you said, your list names, each item's name, the list
  it is on and whether you marked it as already at home. When you have answered a question, they may also send the
  question, your answer and the names of the items suggested before. When an item needs a category, the app sends
  the item's name through our servers to Cerebras.
- *Why and how it is used:* we use this data to turn what you said into changes to your lists, such as "add milk
  to Costco", and to pick categories for items.
- *How long:* our servers use this data to answer the request and do not save it. If our server needs to ask you
  a question, it sends the question and related details back to your phone. You have 5 minutes to respond using
  those details. Our servers' log lines do not name the items on your lists or repeat what you said (clause 3.10,
  "Our hosting provider's logs"). Cerebras and OpenAI handle what they receive under their own terms and privacy
  policies.

3.3 **Store searches and maps.**

- *What:* when you open the Maps tab, search for stores or ask for the closest branch, the app reads your
  location, with your permission. To search for stores, it sends our servers your location, or the place you
  search from, with any store name, store department (such as "pharmacy") or address you type. Our server asks
  Apple Maps (on iPhone) or Google Maps (on Android) for stores near you, or finds the address you typed and
  searches around it. When a screen needs a branch's name, address or position that the app no longer holds, the
  app sends our servers the branch's place identifier to get them again.

  In Meals, "Choose where to shop" also searches for nearby grocery stores and for well-known grocery chains,
  choosing which chain names to send from your state when your phone has worked it out (clause 3.4, "City, state
  and country from your position"). When your week needs ingredients from a specialty store, such as a store that
  sells foods from a particular country or cuisine, the app also searches for that kind of store. This search goes
  through our servers to Apple Maps on iPhone and Google Maps on Android. On iPhone in the United States, the app
  can also send Apple Maps a few more searches for that kind of store, and ask our servers for stores of that kind
  in Overture's open data (clause 3.13, "Overture's open data"). The app can also ask our servers whether they can
  be reached; that check sends no location, search text or sign-in credential.
- *Why and how it is used:* to find stores near you and show where they are, and to tell you when the app cannot
  reach the internet.
- *How long:* the app normally keeps your current location only in memory while it is open. Store search results
  are kept only in the app's memory, for a short time or while you are choosing a store, apart from the chains'
  branches in clause 2.12, "Your last store search, on your phone". The positions of the store branches you choose
  follow clause 2.6, "Your store choices". Our servers pass each search to the map service without saving it, and
  no log records your location or search text (clause 3.10, "Our hosting provider's logs"). Apple and Google handle
  the searches they receive under their own privacy policies.

3.4 **City, state and country from your position.**

- *What:* your phone's own location service turns your position, rounded to about 100 meters, and the position of
  the main store you pick in "Choose where to shop", into a city, state and country, without going through our
  servers. On iPhone this is Apple's service; on Android it is the location service built into your phone.
- *Why and how it is used:* so "Choose where to shop" can search for the well-known grocery chains in your state,
  and so the app uses the store features of your country, for example Overture's US store data (clause 3.13,
  "Overture's open data"). The app also uses the city when it shows store addresses.
- *How long:* the app keeps it only in its memory and never saves it. It is lost when the app closes, or, for a
  store you picked, when you close the shopping screens. On iPhone, Apple handles the request under its own terms;
  on Android, the location service built into your phone does.

3.5 **Directions.** When you ask for directions, the app opens the navigation app you choose: Apple Maps, Google
Maps or Uber. It hands that app the position of each store on your route, and for Uber also the store's name. It
does not put your own location in the link; Uber finds your pickup point itself. That app then handles your trip
under its own terms.

3.6 **Content.**

- *What:* when the app needs Meals content it does not have yet, it asks our servers for it by a code in the
  request's web address: for the dishes in your planned week, the dishes on the screens you open and the dishes you
  tap. These codes can relate to what you plan or browse. Your plan and settings themselves are not uploaded. Our
  servers send the content from our storage service, Google Cloud Storage, and receive your phone's internet
  address, the time and which content you asked for.
- *Why and how it is used:* to show the content. Each device can download up to 50 MB of content a day, until
  midnight UTC, which keeps its cost within a limit.
- *How long:* the daily size count is kept for 30 days (clause 3.15, "Usage counters and blocks"). Our hosting
  provider's network log shows which content was requested (clause 3.10, "Our hosting provider's logs"). Google
  Cloud Storage handles the underlying storage under its own terms.

3.7 **Meals and AI.** Meals itself sends nothing to an AI service. It has no analytics or advertising tracking, and
it has no way to share a recipe or your plan with another app. Once Meals adds items to a shopping list, those items
become ordinary list data and follow the voice-processing rules in clauses 3.1, "Turning your voice into text", and
3.2, "Understanding what you said".

3.8 **Signing in.**

- *What:* when you first open the app, you enter a one-time set-up code from us, and the app sends that code and
  your device identifier to our servers. After that, the app signs in to our servers with a sign-in credential it
  keeps in your phone's secure storage, and renews it from time to time while you use the app, including when the app comes back to the front. On iPhone, Apple's
  App Attest also checks that it is the genuine app (clause 3.17, "Checking that the app is the real app").
- *Why and how it is used:* so our servers accept requests only from the app. We keep a record of your device (its
  device identifier, when it was first set up and when it last signed in), with the set-up code it used and the
  sign-in credentials we gave it.
- *How long:* the app replaces its credentials each time it signs in again (clause 2.8, "Your device identifier and
  sign-in credentials"). Your device record stays until you delete it (clause 3.19, "Deleting your device data") or
  until 60 days pass without a successful sign-in, when we delete it automatically. Credentials that have run out
  are deleted sooner.

3.9 **Error reports.**

- *What:* the app's own code on your phone sends no error reports. On Android, Google's map software can send
  Google crash reports about its own code (clause 3.11, "The maps in the app"). When one of our servers runs into an
  error while it handles a request, it can send an error report to Sentry, our error-report service. A report holds
  technical details: the error, where in our code it happened, which server and version sent it, the time, the kind
  of request, and technical labels that come with a request, such as the name and version of the software that
  sent it.
- *Why and how it is used:* so we can find and fix errors in our servers. Before a report leaves our servers, it is
  scrubbed of your sign-in credential, your internet address, the content of the request (such as what you said or
  the dishes asked for), your location and your search text. Sentry stores the reports in the United States and
  handles them under its own terms and privacy policy.
- *How long:* Sentry keeps each error report for up to 90 days. Sentry also keeps backups and deletes each backup
  90 days after it was made, so a copy can remain in a backup after the report's normal retention period ends.
<!-- plan T.6: section 3.9 is true only once the S.1 scrub fix and the no-request-counts fix (2026-10-19) are deployed to production -->

3.10 **Our hosting provider's logs.**

- *What:* our hosting provider, Google Cloud, keeps technical logs of the requests that reach our servers: the time,
  the type of request and its result, your phone's internet address, the name and version of the software that
  sent it, and the web address. The web address can show which content or store the app asked about. The logs
  never contain what you said, your location or your searches. Google Cloud also keeps the log lines our servers write: the type of request and its result, with
  your device identifier or internet address for some requests. They do not contain what you said, your location or
  your searches.
- *Why and how it is used:* the logs are part of how our hosting provider runs our servers. We use them to run the
  service and find problems.
- *How long:* 30 days. Google Cloud then deletes them.
<!-- plan T.6 (B3): facts re-found 2026-10-26 for the Google Cloud host (Cloud Run request log fields per Google's LogEntry reference — the web address keeps its query string, the request body is not recorded; Cloud Logging _Default bucket, 30 days — map-provider Task 8.1 report). Hari's ruling M39 (2026-10-26, map-provider Task 8.3): store searches are POST with the fields in the JSON body; the GET forms were removed on 2026-11-02 (build 31). Confirm the retention setting before publishing. -->

3.11 **The maps in the app.**

- *What:* maps appear on the Maps tab and on the store and shopping screens, including small maps that load by
  themselves in their List views. When a map loads, map software from Apple on iPhone or Google on Android requests
  the area shown from Apple or Google. If you allow location and the app has your position, the map software can
  also use it to show your position on the map. On Android, Google says its map software can also collect: your
  phone's internet address; details about your phone, such as its model and system version, and about the map
  software; a code that Google uses to count the users of its map software; crash reports about its own code; and
  how the map is moved and zoomed. Google describes only the newest version of its map software on that page. The
  version in our app may differ, so this is Google's description, not something we have checked in our app.
- *Why and how it is used:* so the app can show stores and your route on a map. We do not receive this data.
  On Android, Google says it uses what its map software collects to maintain and improve Google services, to make
  the map software more stable, to understand how the software is used, and to count its daily users.
- *How long:* Apple and Google handle this data under their own privacy policies. Apple's is at
  https://www.apple.com/legal/privacy/. Google describes what its map software collects at
  https://developers.google.com/maps/documentation/android-sdk/play-data-disclosure.

3.12 **Searching an online store.**

- *What:* in Meals, you can have ingredients added to a list for an online store. The app offers Walmart, Amazon,
  Instacart, Kroger, Target and Weee! as online stores. Each item on that list has a search button. When you tap the button, the app opens that store's website, or its app if your
  phone opens the link there, with the item's name as the search. The link holds only the item's name. The store
  receives that search and your phone's internet address, as with any website you open.
- *Why and how it is used:* so you can find and buy the item from that store.
- *How long:* the store handles the search under its own terms and privacy policy. We do not receive it.

3.13 **Overture's open data.**

- *What:* for stores in the United States, the app also uses store data from Overture Maps Foundation, which
  publishes open map data. Our servers keep their own copy of Overture's data for US stores. When you, or the place
  you search from, are in the United States and you pick a store, the app may send our servers that store's name,
  its position and, when it has one, its street address. On iPhone, a specialty-store search in the United States
  also sends our servers the place you search from, which can be your location, the kind of store your week needs
  and any store department you name in your search. When the app shows a saved store with Overture details,
  wherever you are, it can send our servers that store's Overture identifier to get newer details.
- *Why and how it is used:* our servers look the store you picked, or stores of that kind near the place you search
  from, up in their copy of Overture's data and send back Overture's details. The app uses those details to name
  and show the stores you pick, and on iPhone to add nearby stores of the kind your week needs. Overture itself
  receives nothing from you or the app, and nothing you send is added to our copy.
- *How long:* our servers use what you send to answer the request, and then forget it. They do not write it to
  their logs, keep it or put it in error reports. The Overture details of a store you pick are saved on your phone
  with that store (clause 2.6, "Your store choices").

3.14 **Your recording on our server.**

- *What:* the recording of a voice command passes through our servers on its way to Deepgram (clause 3.1).
- *Why and how it is used:* so our servers can check the recording's length against your daily and weekly voice
  allowance.
- *How long:* audio passes through and is not stored. Our servers hold it in memory for the length of the request
  and then forget it. Our logs and error reports never contain audio or the words you said. We keep the words of
  each voice command, and what the app did with them, for 30 days to fix mistakes; you can clear them in Profile.
  For each command, we keep the time you recorded it, the words Deepgram heard and what the app did with each item:
  the item, the list it ended up on, whether it was added, removed or changed, whether it waited on a card for your
  confirmation, and whether the command ended in a question you answered or left unanswered. Saved history is
  linked to your device record. Clearing history or deleting your device data removes it; inactive-device cleanup
  also removes it. Deletion runs hourly, so a record may remain for up to one hour beyond 30 days. History can be
  incomplete: recording limits or processing failures can leave a command or its result missing. Saved results
  describe what was applied at the time; later Undo actions are not included. You can see and clear this history
  in Profile.

3.15 **Usage counters and blocks.**

- *What:* our servers count, for each device and each day, how much of the costly features the device used:
  seconds of voice, the size of downloaded content, the number of typed-sorting, parsing, store-search and store-data
  requests, and how many voice commands were saved to history each day. For 24 hours they also keep a record of
  each request for one of these features, allowed or refused: which feature, how much was asked for and the answer.
  They also count all testers together. If a device is blocked, they keep a block record.
- *Why and how it is used:* to apply the daily and weekly limits in the Tester Terms (section 3, "Daily and weekly
  limits"), to keep costs under a ceiling, and to stop misuse. We may pause or block a device that uses far more
  than normal or misuses the app. A block stops voice processing, automatic item sorting, store searches,
  store-data lookups and dish-photo downloads. You can still manage your agreement and delete your device data.
- *How long:* daily and weekly counters and the small records of voice reservations (status, seconds and times,
  with no audio and no words) are kept for 30 days. The all-testers totals carry no link to a device. An automatic
  block record is kept until 30 days after the block ends. A manual block record is kept until we lift the block,
  plus 30 days. Deleting your device data does not remove a block record, the all-testers totals or the reservation
  records.

3.16 **Your agreement records.**

- *What:* when you enroll, you tick one box that agrees to the Tester Terms and this policy, and to your voice and
  lists being processed by the artificial intelligence services listed here: Deepgram (clause 3.1, "Turning your
  voice into text") and Cerebras and OpenAI (clause 3.2, "Understanding what you said"). The app records that agreement, the
  documents' version number, a fingerprint (hash) of each document's text, and the time. Each time you agree again
  after a material change, or withdraw, the app adds another record. Records are added and never edited.
- *Why and how it is used:* to show which version you agreed to, and to ask you to agree again when we make a
  material change.
- *How long:* the records are kept with your device record and removed when you delete your device data or when
  the device record is cleaned up after 60 days without use.

3.17 **Checking that the app is the real app.**

- *What:* on iPhone, when you enroll and when the app renews its sign-in, the app uses Apple's App Attest service,
  and Apple confirms that it is the genuine Tomty app on a genuine Apple device. Our servers keep a record of the
  app's App Attest key with your device record.
- *Why and how it is used:* to check the app installation. App Attest identifies the app installation, not you.
  Apple takes part in the check and handles its side under its own terms.
- *How long:* the key record is kept with your device record and removed with it.

3.18 **The tester sign-up form.**

- *What:* to sign up, you give your email address in a Google Form. The form holds the email address and your
  agreement to be a tester. We use the email address to send you your enrollment code.
- *Why and how it is used:* so we can invite you. The email addresses stay in the form. They are never put in our
  database.
- *How long:* Google keeps the form's answers under its own terms. We keep email addresses in the form only.

3.19 **Deleting your device data.**

- *What:* in Profile, "Stop using Tomty's online services" withdraws your agreement, and "Delete my device
  data" deletes what our servers hold about your device: the device record, its sign-in credentials and keys, your
  agreement records, the device's counters, its admission records and its voice command history. Then the app
  deletes its local data, including your lists and recordings, but keeps its device identifier so existing blocks
  still apply. It returns to the enrollment code screen.
- *What deletion never removes:* the all-testers totals and the reservation records (neither is linked to your
  device), any block record (clause 3.15), and a scrambled fingerprint made from your code and your device identifier, which
  holds no other data about you and stops that device using the same code again. We keep that fingerprint only until the
  code expires. The codes we issue to testers last 30 days. You need a new code from us to come back.
- *Cleaning up:* any device with no successful sign-in for 60 days is deleted automatically in the same way.
- *Backups:* our database's backups age out on Cloud SQL's backup retention. A deleted record can stay in a
  backup until the backup expires.
- *If your sign-in has failed for good:* the code screen offers a support ID. Email it to us so we can find and
  delete the matching record. If your phone has lost its original device identifier, the new support ID cannot
  locate the old record; the 60-day inactive cleanup removes it instead.

3.20 **Developing our own model.**

- *What:* the words of your voice commands (the text Deepgram heard, never the audio) and the time you said them.
  Nothing else from your history: not your lists, your items or what the app did with them.
- *Why:* we are building our own model to understand voice commands, so the app can work with less reliance on
  outside AI services. Your words help us test and improve it.
- *When:* only if you agree to this version of the policy, and only for commands you say after you agree.
- *How:* within the 30 days we keep your history (clause 3.14), we copy those words to a separate, access-restricted
  development copy controlled by us. Before the copy is made, your device identifier is replaced with a scrambled
  code. The words themselves are not edited, so anything you say, such as a name, stays in the text; please don't
  say anything you wouldn't want stored.
- *How long:* for as long as we are developing our model. We intend to limit this to 12 months from the date each
  command is copied.
- *Your choice:* withdrawing your agreement, clearing your voice history in Profile, or deleting your device data
  (clause 3.19) removes your commands from that copy at our next copy run. A model that has already learned from
  data cannot unlearn it.
- *Who else sees it:* no one outside us. When we check our model against the app, those words may pass again
  through the voice-understanding services named in clause 3.2.

## 4. Who we share data with

4.1 The services below receive data as described in section 3. Those clauses explain the purposes, retention
periods and provider policies that apply.

- **Deepgram** turns your voice into text (clause 3.1, "Turning your voice into text").
- **Cerebras and OpenAI** help our server understand what you said and pick categories for items (clause 3.2,
  "Understanding what you said").
- **Apple Maps Server API, Google Places API and Google Geocoding API** find stores and addresses and give their
  names, addresses and positions (clause 3.3, "Store searches and maps").
- **Overture Maps Foundation** publishes the open store data that our server keeps a copy of. Overture receives no
  data from you or the app (clause 3.13, "Overture's open data").
- **Apple and Google** receive requests for the map areas shown in the app (clause 3.11, "The maps in the app").
- **Your phone's location service** (Apple's on iPhone; the one built into your phone on Android) turns your
  position into a city, state and country (clause 3.4, "City, state and country from your position").
- **Apple** also takes part when the app checks that it is the genuine app (clause 3.17, "Checking that the app is
  the real app").
- **Google Forms** holds the email address you give to sign up as a tester (clause 3.18, "The tester sign-up
  form").
- **Google Cloud**, our hosting provider, runs our servers, keeps their logs, stores our sign-in records and our
  copy of Overture's data, and, through Google Cloud Storage, stores and delivers the app's content (clauses 3.6,
  "Content", 3.8, "Signing in", 3.10, "Our hosting provider's logs", and 3.13, "Overture's open data").
- **Sentry** receives error reports from our servers (clause 3.9, "Error reports").
- **Apple Maps, Google Maps and Uber** receive your route only when you open one of them for directions (clause
  3.5, "Directions").
- **The online stores in clause 3.12** receive an item's name when you tap its search button (clause 3.12,
  "Searching an online store").

4.2 Each of these services has its own terms and privacy policy, which govern what it does with the data it
receives. The Google Privacy Policy is at https://policies.google.com/privacy.

4.3 Store logos in the app are pictures built into the app. The app does not download store logos from the
internet.

## 5. Where data is stored

5.1 The app keeps the data described in section 2 on your phone. Some of that data also goes to the services
described in section 3.

5.2 Our servers, the database that holds our sign-in records, and our copy of Overture's data run with our hosting
provider in Oregon, United States. The database's backups are stored in the United States and age out on Cloud SQL's backup retention (clause 3.19,
"Deleting your device data"). When our servers handle a
request, the data in it, such as what you said or a store search, is processed there.

5.3 Our hosting provider stores all the logs from our servers, and its network log, in its logging service in
Oregon, United States. Logs written before we made this change on 26 October 2026, including earlier that day, stay
in Google's worldwide location, which can be any of Google's data centers, until Google deletes them under the same
30-day retention.

5.4 The app's content is stored with our hosting provider in Oregon, United States.

5.5 Sentry stores error reports in the United States.

5.6 Other services store the data they receive under their own terms.

## 6. What we don't do

6.1 We do not sell your data to anyone.

6.2 The app has no advertising or analytics tracking of its own. On Android, Google's map software sends Google
data about how the map is used, as clause 3.11, "The maps in the app", explains.

6.3 We do not use your recordings, your lists or your items to train AI models. If you agree, we use the words of
your voice commands to develop our own model, as clause 3.20, "Developing our own model", explains. Clause 3.1,
"Turning your voice into text", says what Deepgram may do under its own terms.

6.4 We never send the items on your lists to Apple Maps or Google Maps. Apple and Google receive only what clauses
3.3, "Store searches and maps", 3.4, "City, state and country from your position", 3.5, "Directions", and 3.11, "The maps in
the app", describe.

6.5 Meals itself sends nothing to an AI service. Once Meals adds items to a shopping list, those items follow the
voice-processing rules in clauses 3.1, "Turning your voice into text", and 3.2, "Understanding what you said".

## 7. Your choices

7.1 **Location.** The app asks for your location only while you are using it, never in the background. On
Android, just before your phone asks, the app shows one line that says why: "Tomty uses your location to show
stores near you. Store results come from Google Maps." You can refuse, or turn it off at any time in your phone's
Settings. With location off, you can still search for stores by name or address.

7.2 **Microphone.** The app asks for the microphone the first time you use voice. You can turn it off at any time
in your phone's Settings. Without it, you can still type items into your lists.

7.3 **Notifications.** The app asks before it sends reminders. You can turn notifications off at any time in your
phone's Settings. The app then cannot remind you about a shopping trip.

7.4 **Deleting the app.** Deleting the app removes the data it keeps in its own storage on your phone. This
includes:

- lists, recordings and pending voice captures;
- Meals data and downloaded content;
- store choices and app settings;
- copies of damaged data (clause 2.10, "Copies of damaged data");
- the old copy of your lists, if your phone has one (clause 2.1, "Your lists").

Deleting the app does not remove:

- on iPhone, your device identifier and sign-in credentials in the keychain, which iPhone can keep after the app
  is deleted;
- your device's record on our servers (clause 3.8, "Signing in");
- the logs and reports that our hosting provider and Sentry keep for the times in clauses 3.9, "Error reports",
  and 3.10, "Our hosting provider's logs";
- what other services in section 4, "Who we share data with", received, which they keep under their own terms.

7.5 **Stopping and deleting.** In Profile, "Stop using Tomty's online services" withdraws your agreement. Voice,
typed sorting, store search, maps and content downloads stop until you agree again. "Clear voice history" removes your
saved command history without stopping these services. "Delete my device data" removes the records listed in
clause 3.19 and clears the app's local data, except its device identifier. You need a new enrollment code to
return.

To ask about the records we keep about your device, email us at tomty.app.feedback@gmail.com.

## 8. Children's privacy

8.1 Tomty is for people 18 or older. It is not directed at children, and we do not knowingly collect data from
children.

## 9. Changes to this policy

9.1 We may change this policy as the app changes. Each version shows its "Last updated" date at the top of this
page.

9.2 A material change affects how we collect, use or share your data, or otherwise changes your rights or what you
agree to. If we make a material change to the Tester Terms or this policy, the app tells you when it next connects to our servers. You must agree to the updated documents before using online features again. The app adds a record of the documents' version you accepted and the time (clause 3.16, "Your agreement
records"). Section 7 of the Tester Terms, "Changes to these Terms," explains this process.
<!-- true only with CONSENT_REQUIRED=1 (tester-launch plan Part F, task 5, step 2); 3.15 and Tester Terms 3 only with LIMITS_ENFORCED=1 and
GATE_ENABLED=1 (the same task, steps 1 and 3). -->

9.3 A minor change does not change your rights or what you agree to. Examples include clearer wording, corrected
typos and corrected clause references. We update the text and its "Last updated" date. You do not need to agree
again.

## 10. Contact

Questions about this policy or your data: tomty.app.feedback@gmail.com
