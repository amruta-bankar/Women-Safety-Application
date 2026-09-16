🛡️ Personal Safety App

An Android application built with Java in Android Studio, designed to enhance personal safety — particularly for women — by giving users fast, discreet ways to call for help in an emergency.

The app's core feature is an SOS alert system that can be triggered by pressing the power button three times, even when the phone is locked. It calls the primary emergency contact, sends the user's live location to up to five registered contacts, and can sound a loud siren to deter attackers and attract attention.

Features
🚨 SOS Alert (Power Button Trigger) — Triple-press the power button to instantly call the primary emergency contact and SMS your live location to up to 5 saved contacts.
📢 Emergency Siren — A second triple-press (or a dedicated siren button) activates a loud alarm to attract attention and deter threats.
📍 Live Location Sharing — Uses the Fused Location Provider API to share accurate, real-time location with emergency contacts.
👮 Nearby Police Station Locator — Integrates Google Maps to find and display the nearest police stations.
📰 Women's Safety News Feed — Curated, safety-related news pulled from a News API to keep users informed.
📖 In-App Instructions / App Tour — A guided walkthrough so the app is easy to use, even under stress.
👥 Emergency Contact Management — Add, edit, and prioritize up to 5 emergency contacts.
⚡ Works with Minimal Connectivity — Built to remain functional and responsive under low-bandwidth conditions.

Tech Stack
Layer	Technology
Language	Java
IDE	Android Studio
Local Storage	SQLite
Cloud Storage / Auth	Firebase Realtime Database, Firebase Authentication
Maps & Location	Google Maps API, Fused Location Provider API
News	News API
UI	XML layouts, Material Design
Background Work	Android Services & Broadcast Receivers (power-button detection)
Testing	JUnit, Mockito, Espresso
Version Control	Git