# DocStock

> *A reminder a day keeps Doc at bay.*

DocStock is a web-based application that helps people manage their prescribed medication schedules. Users enter their medications and dosing schedules, and the app organizes everything into an easy-to-follow plan — sending reminders when doses are due, letting users log what they've taken, and tracking how much medicine is left.

Built by **Team Pearl**.

---

## The Problem

Many people who take medications regularly struggle to manage their schedules — remembering doses, tracking whether a dose was taken, and knowing when supply is running low. These difficulties lead to missed, delayed, or duplicated doses.

The scale of the problem:

- About **1 in 5** new prescriptions in the U.S. are never filled. (CDC)
- Roughly **50%** of filled prescriptions are taken incorrectly with respect to timing, dosage, frequency, or duration.
- Nonadherence drives an estimated **$100–$300 billion** in annual U.S. health care costs.

## The Solution

DocStock centralizes prescription management in one dashboard reachable from any device with a browser. Users input their medications once, and the app handles scheduling, reminders, adherence tracking, and supply monitoring — reducing the manual steps involved in staying on top of a medication regimen.

## Features

**What DocStock does:**

- Centralizes every prescription in one dashboard reachable from any device
- Schedules doses and sends reminders so doses aren't missed, mistimed, or doubled
- Alerts users before refills run out to prevent gaps in treatment
- Screens for drug interactions by checking each new medication against the user's active list
- Tracks adherence and exports a provider-ready report to bring to appointments
- Supports caregiver access and multiple profiles under one account

**What DocStock does *not* do:**

- Automatically order refills for low medications
- Give medical advice or replace healthcare professionals
- Log symptoms, mood, or health metrics (blood pressure, glucose, etc.)
- Integrate directly with pharmacies to pull prescriptions automatically
- Function as a native mobile app (DocStock is web-based)

## How It Compares

| Feature | DocStock | Medisafe | MyTherapy | Round Health |
|---|:---:|:---:|:---:|:---:|
| Dose reminder & scheduling | ✔ | ✔ | ✔ | ✔ |
| Prescription refill alert | ✔ | ✔ | ✔ | ✔ |
| Drug interaction warning | ✔ | ✔ | — | — |
| Caregiver / family sharing | ✔ | ✔ | ✔ | ✔ |
| Exportable adherence report | ✔ | Partial | ✔ | — |
| Symptom / health metric logging | — | — | ✔ | — |
| Multiple user profiles | ✔ | ✔ | ✔ | ✔ |
| Web-based (browser, not app-only) | ✔ | — | — | — |
| Free / no paywall | Partial | Partial | ✔ | Partial |

## Architecture

Major functional components:

- **Account Management** — authentication, user profiles, caregiver support
- **Medication Management** — scheduling, tracking, notifications
- **Backend** — business logic and database (users, medications, schedules, history, supply data)

## Tech Stack

- **IDE:** Visual Studio Code
- **Version Control:** Git & GitHub
- **CI/CD:** Automated testing and deployment

## Team Pearl

- Isaiah Gamble
- Julia Hairston
- Anson Cheng
- Shannon Stinnette
- Jessica Fischer
- Ab Aljazaeri
- Matthew Richards

## Disclaimer

DocStock is a scheduling and reminder tool. It does not provide medical advice and is not a substitute for guidance from a licensed healthcare professional. Always verify medication instructions with your doctor or pharmacist.

## References

1. Centers for Disease Control and Prevention, "CDC Grand Rounds: Improving medication adherence for chronic disease management — Innovations and opportunities," *MMWR*, vol. 66, no. 45, pp. 1248–1251, Nov. 2017.
2. Medisafe, "App Features," medisafeapp.com.
3. MyTherapy, "MyTherapy: Medication Reminder & Pill Tracker," mytherapyapp.com.
