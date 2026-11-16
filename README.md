# FoodBuddy Outer Space

> One-Slide Presentation Explanation — November 15, 2026

📲 **Download the TestFlight app** (iOS 27 required): [https://testflight.apple.com/join/nHgbM9jW](https://testflight.apple.com/join/nHgbM9jW)

## Overview

FoodBuddy Outer Space is a proposed personal health companion for astronauts on space missions. Its purpose is to help crew members record important health measurements, review trends, and, in a later development phase, receive evidence-informed guidance. The app is designed around offline operation, recognizing that connectivity and access to Earth-based assistance may be limited during space missions.

https://github.com/user-attachments/assets/6c91234a-40c5-432b-a12b-eafa3e8456ec

[Presentation slide 1](assets/foodbuddy-outer-space-slide.png)

[Presentation slide 2](assets/foodbuddy-outer-space-testflight.png)

## The Problem

Astronauts face health challenges during spaceflight, including changes related to microgravity, isolation, and the space environment. Monitoring health requires information from different instruments and daily records. A unified interface could make these measurements easier to capture and review over time.

## Eight Health Measurements

The dashboard organizes eight categories:

1. **Heart rate** — pulse in beats per minute.
2. **Blood pressure** — systolic and diastolic readings.
3. **Oxygen saturation (SpO2)** — estimated blood oxygen saturation.
4. **Respiratory rate** — breaths per minute.
5. **Body temperature** — measured temperature.
6. **Sleep** — duration and related sleep records.
7. **Nutrition** — food intake, calories, and nutrients where reliable information is available.
8. **Hydration** — logged fluid consumption.

These categories combine physiological measurements with daily behavior and intake records. Food and water logs indicate consumption, not a direct diagnosis of nutritional or hydration status.

## Phase 1: Health Monitoring

The first phase focuses on a usable monitoring foundation. Astronauts can enter measurements manually or capture displayed readings through the camera, with compatible device integration where available. The app stores records locally, shows the latest entries and historical trends, and offers reminders for scheduled measurements. A daily-completeness indicator shows which categories have entries; it does not mean that an astronaut has been medically cleared.

## Phase 2: Health Decision Assistant

The second phase builds on Phase 1 data. It is intended to evaluate measurements and trends using transparent, versioned rules and documented evidence from NASA research and appropriate clinical references. The interface would explain why a finding needs review, suggest an appropriate next step under approved protocols, and record follow-up actions. General Earth-based reference ranges are not automatically astronaut-specific medical thresholds. The proposed assistant is decision support, not an autonomous diagnosis or treatment system.

## How the App Works

1. **Measure** — The astronaut uses an appropriate medical device or records food, water, and sleep information.
2. **Capture** — The app imports a supported device reading, reads a device display using the camera, or accepts manual input.
3. **Confirm** — The astronaut reviews the values and corrects recognition errors.
4. **Record** — The app saves the reading with its timestamp, units, and source in local storage.
5. **Review** — The dashboard presents the current records, missing entries, and trends.
6. **Act (Phase 2)** — When supported by approved evaluation rules, the app explains a concern and provides documented follow-up guidance.

## Why Offline Matters

Local data capture, storage, and viewing allow the monitoring workflow to continue without an internet connection. Any offline evidence library and evaluation rules must be packaged and maintained with the app. The slide's offline-ready claim describes the intended design; it should be demonstrated and tested before being presented as a verified capability.

## Value for the NASA Space Apps Challenge

The challenge asks for software that helps astronauts gather health indicators, evaluate their health status, and act on findings. Phase 1 directly addresses gathering and visualization. Phase 2 extends that foundation toward evaluation and action. The two-phase approach makes the concept practical to build incrementally while keeping the larger challenge objective in view.

## Important Limitations

The presentation is a concept illustration, not evidence of clinical validation or deployment aboard the ISS. Numbers displayed on the mockup are examples, not actual astronaut records or approved NASA thresholds. The use of NASA research as a source of context does not imply NASA endorsement. Any clinical alerts or action guidance require validation and mission-appropriate medical oversight.

## Closing Message

FoodBuddy Outer Space brings vital signs, sleep, nutrition, and hydration into one offline-first interface. The initial product makes health information easier to record and understand; the next phase aims to turn those records into transparent, evidence-informed guidance for longer missions beyond Earth.

## Links

- [2026 NASA Space Apps Challenge](https://www.spaceappschallenge.org/2026/) — The Next Frontier, November 14–15, 2026
