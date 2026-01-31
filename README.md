# SniffHub — Social & Dating App with Event-Centered Discovery

## Overview
SniffHub is a production-ready native Android social discovery and dating application published on Google Play (10K+ downloads).
It combines the familiar swipe-based matchmaking experience of apps like Tinder and Bumble with a unique second mode called Hub Mode, where users connect through real-world events such as festivals, venues, trips, and social gatherings.

Unlike traditional dating apps focused only on profile browsing, SniffHub enables meaningful connections through shared communities, live event participation, and real-time interaction.

Built as a scalable mobile product, SniffHub integrates modern Android development practices, real-time communication, safety systems, cloud infrastructure, and monetization.


## 🚀 Core Features

### 🔐 Authentication & Onboarding
- Firebase Authentication (Google + Email login)
- Deep onboarding flow (13-step profile builder)
- Rich profile setup:
  - Personal info, interests, languages, job, hometown
  - Media upload (up to 6 images/videos)
  - Built-in image editor (crop, rotate, filters)

### 💘 Dating Mode (Swipe Discovery)
- Swipe-based matching (Like / Dislike / Super Like)
- Rewind last swipe
- Boost system (time-based visibility increase)
- Advanced filters:
  - Age & distance range
  - Interests, gender, hometown, looking-for options
- Premium gating:
  - Only premium subscribers can see who liked them.


### 🎉 Hub Mode — Event-Centered Social Discovery
- Discover nearby festivals, clubs, venues, and events
- Attend/leave events (premium access)
- Event feeds (Twitter-style posting system)
- Comments, likes, reporting
- Stage + timetable scheduling for large events
- Event attendee discovery + presence visibility
- Instagram-style attendee profiles with direct chat entry


### 💬 Real-Time Messaging & Communication
- Match-based + event-based chat system
- Rich messaging support:
  - Text, images, videos
  - Voice messages
  - GIFs + emoji support
- Message reactions
- Built-in message translation (multi-language chat)
- Report/block/delete match tools


### 📞 Audio & Video Calling
- Real-time audio/video calling via **Twilio Video (WebRTC)**
- Call invitations powered by Firebase Cloud Messaging (FCM)
- Dedicated call UI with accept/decline flow



### 👤 Profile & Account Management
- Profile completion indicator with onboarding progress tracking
- Full profile editor:
  - Update personal info, interests, and discovery preferences
  - Manage media gallery (add/remove/reorder images & videos)
- Profile preview system (Tinder-style card representation)

- Settings & account tools:
  - Notification controls (matches, chats, events)
  - Mode switching (Dating ↔ Hub Mode)
  - Account management: delete account, logout, support & feedback
  


### 🛡 Trust, Safety & Privacy
SniffHub includes production-grade safety systems designed for real-world social platforms:
- AI-based media moderation (human detection + NSFW/violence filtering)
- Identity verification with camera gesture challenge + verified badge
- Privacy-first controls:
  - Incognito browsing
  - Hide profile visibility
  - Freeze account mode
- Reporting and blocking across chats, event feeds, and user profiles

  
### 💳 Monetization & Premium System
Hybrid monetization model with subscriptions + consumables:
- Subscription tiers: Starter / Pro / Ultimate
- Premium access control:
  - Unlimited swipes
  - See who liked you
  - Attend events
  - Advanced filtering
- Consumable credit packs:
  - Boosts
  - Super Likes
  - Direct Messages
- Full integration with **Google Play Billing**
  

### 🔔 Notifications & Engagement
- Firebase Cloud Messaging (push notifications)
- Smart alerts for matches, chats, boosts, and event activity
- Event reminders and timetable-based notifications

  
### ⚙ App Monitoring & Production Hardening
- Firebase Remote Config for dynamic feature control
- Firebase Analytics + Crashlytics for monitoring and stability
- Play Integrity API + in-app update readiness for production release protection

  

## 🛠 Tech Stack

| Category            | Tools & Libraries |
|---------------------|------------------|
| Language            | Java |
| UI                  | XML + ViewBinding |
| Architecture        | Modular Activity + Fragment flows |
| Networking          | Retrofit2 + Gson |
| Backend             | AWS + Node.js APIs |
| Authentication      | Firebase Auth |
| Database / Storage  | Firestore + Firebase Storage |
| Notifications       | Firebase Cloud Messaging (FCM) |
| Analytics / Crash   | Firebase Analytics + Crashlytics |
| Media (Images)      | Glide + transformations |
| Media (Video)       | ExoPlayer (Media3) |
| Camera              | Camera2Capturer (Twilio Video) + Android camera flows |
| Image Editing       | Custom/native editor pipeline (crop/rotate/filters) |
| Maps & Places       | Google Maps SDK + Places API |
| Calls               | Twilio Video (WebRTC) |
| Payments            | Google Play Billing |
| Security            | Play Integrity API |
| Testing             | JUnit + Espresso |



## 👤 Role & Ownership

SniffHub was developed as a live commercial product where I served as:
  - **Lead and sole Android developer**
  - Owner of the full Android lifecycle:
    development → publishing → updates → maintenance
  - Contributor to backend feature updates and API enhancements



### ⚙ Engineering Highlights
- Built a fully custom swipe-card stack engine from scratch  
  (gesture + scroll + rewind animations in native Java)
- Real-time matchmaking + messaging infrastructure
- Scalable backend integration with AWS + Node.js APIs


  
## 📌 Status

SniffHub is live on Google Play and actively maintained with continuous feature updates, performance improvements, and production monitoring.


## Download

Download the app from Google Play: [SniffHub](https://play.google.com/store/apps/details?id=com.snifferapp.api&utm_source=website&utm_medium=social&utm_campaign=adsfordownloadandroidapp)

## 📸 Screenshots

<p align="center">
  <img alt="l" src="https://github.com/user-attachments/assets/93af43b8-fedf-4ffb-9fb4-173ffcf57075" width="30%">
   <img width="3%">
  <img alt="m" src="https://github.com/user-attachments/assets/d2eace73-32df-4d66-95f5-a29601f14d31" width="30%">
</p>


<p align="center">
  <img alt="l" src="https://github.com/user-attachments/assets/27afd963-1ddb-45ce-8cbd-f8d299452dc7" width="30%">
   <img width="3%">
  <img alt="m" src="https://github.com/user-attachments/assets/6c4d5339-7843-4fbf-9e4a-560482a6cc06" width="30%">
</p>
<p align="center">
  <img alt="l" src="https://github.com/user-attachments/assets/6d77e2da-7a0c-4cba-8a67-5636daa83deb" width="30%">
   <img width="3%">
  <img alt="m" src="https://github.com/user-attachments/assets/d05ce5e7-4840-46e1-ae97-9bc19293f9d4" width="30%">
</p>
<p align="center">
  <img alt="l" src="https://github.com/user-attachments/assets/011bbd9b-c3f3-40ec-9f7a-cc8b3e210953" width="30%">
</p>

<p align="center">
  <img alt="l" src="https://github.com/user-attachments/assets/029e2a45-de0f-4607-ab4d-0f6ab061070d" width="30%">
</p>


<p align="center">
  <img alt="l" src="https://github.com/user-attachments/assets/24b1da94-7f9e-48ba-acd5-2bc752ec4c06" width="30%">
</p>



