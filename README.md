# website
first website test

We need to generate a new updated prompt for the presentation, reflecting the change from ESP32 to Arduino Uno for the hardware.

The user's request is: "regenerate the new updated prompt"

So we need to produce a revised version of the earlier slide preparation prompt, incorporating the Arduino Uno change.

I'll re-write the entire prompt but with the hardware update. Also ensure it's comprehensive, with all slides, tailored for Arduino Uno.

Let's craft the response.

Here is the fully updated prompt for your Tulia Tag presentation slide deck, reflecting the hardware switch to Arduino Uno.

📊 Tulia Tag – Investor / Stakeholder Presentation Prompt
🎯 Overall Goal
Convince the audience (investors, partners, judges) that Tulia Tag is a high‑growth, scalable, and essential IoT solution for asset security in Kenya and beyond.

🎨 Visual Style
Dark theme primary, with brand colours (#1e88e5 blue, #004d40 teal, hints of amber for alerts)

Clean, minimal slides with no more than 5 bullet points each

Use icons (react-icons Fi set) and simple diagrams

Professional, modern font (system sans‑serif)

Every slide should have a clear single message

🧩 Slides Outline (13 slides)
Slide 1: Title Slide
Title: Tulia Tag – Your Bag. Your Code. Your Control.

Subtitle: Smart, Real‑Time GPS Tracking for What Matters Most

Presenter Name: Cassie / Your Name

Date & Event

Visual: App logo (briefcase icon) + map pin animation background

Slide 2: The Problem
Heading: The Pain of Losing Valuables

Bullets:

Over 60% of Kenyans have experienced theft or misplacement of a valuable item

Existing solutions are expensive (KES 15,000+ for vehicle trackers) or limited (Bluetooth trackers have 30m range)

No real‑time community‑assisted recovery system exists for personal items

Visual: Infographic showing a lost bag with a question mark

Slide 3: Our Solution – Tulia Tag
Heading: A Revolutionary GPS Tracker + Community Rescue Network

Image: Phone with app dashboard + physical tracker device

Key points:

Compact, cellular‑based tracker (no phone needed)

Real‑time location on a live map (Mapbox / OpenStreetMap)

Lost Mode generates a public tracking link – helpers can pin the exact location

Built‑in buzzer and sighting reports

Slide 4: How It Works (User Journey)
Heading: From Panic to Peace of Mind in 4 Steps

Diagram steps:

Attach Tulia Tag to any bag/item
If lost, tap "Activate Lost Mode" in the app
Share the generated link with community / security
Helpers view live map, ring buzzer, or report sighting → Owner notified instantly
Visual: Simple flow diagram with icons

Slide 5: Key Features (App Screenshots)
Heading: Powerful Dashboard & Realtime Tracking

Show 3‑4 screenshots or GIFs:

Device dashboard with status cards (battery, last seen)

Live map with animated pulsing marker

Lost Mode active with code and “Share Link” button

Helper public view with “I See This Bag” and “Ring Buzzer” buttons

Caption: Fully functional mobile‑first web app (PWA), works on any smartphone

Slide 6: Technology Stack
Heading: Modern, Scalable Architecture

Architecture diagram:

Frontend: React + Vite + Tailwind CSS + Capacitor (APK)

Backend: Supabase (Auth, DB, Realtime) + Render Gateway (Node.js)

Hardware: Arduino Uno + GPS (NEO‑6M) + GSM (SIM800L)

Key attributes: Offline fallback, dark mode, community‑driven recovery

Slide 7: The Physical Tracker (Hardware) ✨ Updated
Heading: Affordable, Accessible GPS Device

Image: Arduino Uno prototype photo / 3D render with labelled modules

Specs:

Controller: Arduino Uno R3 (ATmega328P) – widely available and easy to prototype

GPS Module: NEO‑6M (2.5m accuracy)

GSM/GPRS Module: SIM800L (works with any Kenyan SIM)

Power: 9V battery or USB power bank; 2000mAh lasts ~48h

Data Transmission: Sends location to Render cloud via HTTP POST every 60 seconds

Estimated Build Cost: KES 2,500 – 3,500

Future Plans: Migration to Arduino Nano or custom PCB for a smaller, wearable form factor

Visual: Annotated photo of connected components

Slide 8: Business Model
Heading: Double Revenue Stream for Sustainable Growth

Revenue:

Hardware sale: KES 4,500 – 5,500 (one‑time, competitive with AirTag but superior tech)

Monthly subscription: KES 500 (data + cloud + community features)

B2B Add‑ons:

Cold‑chain monitoring (temperature sensor) – KES 15,000+

Insurance partnership (premium discount for tagged assets) – recurring revenue share

Visual: Simple table or chart

Slide 9: Market Opportunity
Heading: A Growing Market with Urgent Need

Stats:

SSA GPS tracking market: $210M (2023) → $519M (2033)

Kenya’s e‑commerce & logistics boom → increased demand for asset security

50M+ mobile connections in Kenya – every phone is a potential helper

Visual: Map of Kenya with glowing target areas (Nairobi, Mombasa, etc.)

Slide 10: Competitive Advantage
Heading: Why Tulia Tag Wins

Comparison table:

Tulia Tag vs Apple AirTag vs Samsung SmartTag vs Traditional Vehicle Trackers

Columns: Real‑time GPS | No‑phone needed | Community recovery | Monthly cost

Winning points: Only solution that combines real‑time GPS + community rescue + low cost

Slide 11: Traction & Milestones
Heading: From Idea to Working MVP

Timeline:

✅ Fully functional web app with auth, devices, lost mode, helper view

✅ Arduino‑based hardware prototype sending live data

✅ Deployed backend on Render, database on Supabase

🔜 First 50 beta users

🔜 Insurance pilot with XYZ company

Visual: Milestone timeline graphic

Slide 12: Roadmap & The Ask
Heading: Scaling Beyond MVP

Next 6‑12 months:

Native Android/iOS APK via Capacitor

Push notifications (helper sighting → owner alert)

Fleet management dashboard for corporate clients

Move from Arduino Uno to custom PCB for mass production

Insurance pilot with 2 Kenyan underwriters

Visual: Timeline with phases

Slide 13: Thank You & Q&A
Contact: Name, email, phone, GitHub repo link

QR code linking to the deployed app (or GitHub)

Tagline: "Tulia Tag – Your bag. Your code. Your control."


