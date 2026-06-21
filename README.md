# Kerangka Khotbah Kristen

**Android app for building and managing sermon outlines** — built and maintained solo since 2017.

![Platform](https://img.shields.io/badge/platform-Android-3DDC84) ![Installs](https://img.shields.io/badge/installs-100K%2B-blue) ![Status](https://img.shields.io/badge/status-actively%20maintained-success)

> 📌 **Note:** This is a closed-source, published production app. This repository serves as a case study and portfolio overview — full source code is private to protect the product and its users. Happy to walk through the architecture and code in an interview.

---

## 📱 Screenshots

https://play.google.com/store/apps/details?id=net.yogaapps.kerangkakhotbahkristen

---

## Overview

Kerangka Khotbah Kristen helps pastors, preachers, and Bible study leaders in Indonesia create, organize, and access sermon outlines (*kerangka khotbah*) directly from their phone. It was my first published Android app and remains the flagship product in my independent app portfolio — **100,000+ installs** with daily active usage from the Indonesian Christian community.

## The Problem

Many preachers prepare sermons using scattered notes, printed material, or generic note apps that aren't built for the structure of a sermon (text reference, outline points, illustrations, application). There was no lightweight, purpose-built Android app for this audience in Bahasa Indonesia.

## What I Built

- A structured sermon-outline builder tailored to common Indonesian homiletic formats
- A searchable library of saved outlines, organized for fast access before/during a service
- A content pipeline for publishing new sermon outlines and sermon plans on a regular cadence
- A **WordPress backend** (REST API) powering content management and delivery to the app

## My Role

Sole developer and maintainer end-to-end since January 2017:

- Designed the app architecture and UI/UX from scratch
- Built and ship the cross-platform client with **Flutter**
- Set up and manage the **WordPress backend**, using its REST API to serve sermon content to the app
- Handle the full release cycle: new features, bug fixes, Play Store releases
- Maintain a daily content pipeline for new sermon material, publishing through WordPress

## Tech Stack

| Layer | Technology |
|---|---|
| Mobile | Flutter |
| Backend | WordPress (REST API) |
| Distribution | Google Play Store |

## Impact

- 🚀 **100,000+ installs** on Google Play, organic growth, no paid acquisition
- 🔁 9+ years of continuous maintenance and iteration based on user feedback
- 🧩 Became the foundation for a second app in the same portfolio, *Renungan Keluarga Kristen*, reusing the same Flutter + WordPress content pipeline

## Why the Source Is Private

This app is an active production product serving a real user base, so the full codebase isn't public to avoid unauthorized copies or rebranding. This README is meant to give a transparent look at the problem, decisions, and impact — if you'd like to see actual code, I'm glad to share a private repo or walk through it live.

---

📩 Contact: watashiyoga@gmail.com · [Portfolio](https://www.yogaadicandra.com) · [LinkedIn](https://www.linkedin.com/in/yogaadic)
