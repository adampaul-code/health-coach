# Health Coach

A simple, calm, single-file web app to help you build better daily energy.

It focuses on the things that actually move the needle for you:
- Sleep quality and consistency
- Alcohol-free days
- Gut support through real food
- Your supplement stack (especially milk thistle)
- Steady nutrition without overcomplicating things

Everything lives in **one HTML file**. It now supports optional cloud sync via Supabase so your data is backed up and available across devices (phone + laptop).

## How to Use

1. Download `index.html`
2. Open it in any browser (Chrome, Safari, Firefox, Edge)
3. Sign in with email + password (you only need to do this once per device)
4. Start logging — your data will sync to the cloud

It also works offline and syncs when you're back online.

### Daily Flow (takes ~1–2 minutes)

- **Morning**: Rate your Energy, Sleep, and Gut feel (1–5), then set your priority for the day.
- **Nutrition tab**: 
  - See today’s meal suggestions with clear reasons why they help your energy.
  - Log water intake by tapping the glasses.
  - Check the Gut section for practical probiotic & prebiotic advice.
- **Supplements**: Quickly tick off what you’ve taken (Multivitamin, Omega-3, Milk thistle, Magnesium). See your 7-day consistency.
- **Evening**: Log whether the day was alcohol-free, note one thing that went well, and set tomorrow’s priority. Optional: view a personalised wind-down routine.
- **Trends**: See your patterns over time, including average probiotic foods logged.

## Key Features

- **Daily rotating meal plans** — Breakfast, lunch and dinner suggestions that rotate automatically, with explanations tied to energy, liver support, and gut health.
- **Probiotic foods checklist** — Track Live Greek yoghurt, Aged cheese, Kombucha, and Miso. Your progress also appears in the Trends view.
- **Water tracker** — Simple tap-to-log glasses (goal: 8 per day).
- **Sleep wind-down routine** — Customisable based on your target bedtime.
- **Trends & insights** — See what’s actually working (especially the impact of alcohol-free days and probiotic intake).
- **Export your data** — One-click copy of your logs to paste into Claude or another AI for deeper analysis.
- **Dark, calm interface** — Designed to feel good to use morning and evening.

## Your Core Principles (built into the app)

- Oily fish ~3× per week
- Colour on every plate
- Protein at every meal
- Liver-friendly choices (pairs well with milk thistle)
- Slow carbs for sustained energy
- Take supplements with fat for better absorption
- Alcohol is the biggest lever for energy and recovery
- Feed your gut daily with probiotic + prebiotic foods

## Privacy & Data

- Your data is stored in **Supabase** (secure cloud database) + a local copy on your device.
- You sign in with email + password (only needed once per device).
- Data syncs automatically across devices when you're online.
- You remain in full control — you can sign out or delete your account anytime.

## Resetting Your Data

To clear local data, open the browser console (F12) and run:

```js
localStorage.removeItem('hc_v5');
location.reload();
```

To fully delete your cloud data, sign in at [supabase.com](https://supabase.com) and delete your account or the data in the `health_data` table.

## Why This Version?

This version adds **Supabase cloud sync** so your data is safely backed up and available on all your devices. It keeps the calm interface and quick daily use while giving you reliable data persistence across phone and computer.

## Tech

- Single self-contained HTML file
- Uses Supabase for secure cloud data storage and cross-device sync
- Tailwind CSS via CDN + custom dark theme
- No build step required

Perfect for personal use with optional cloud sync.

---

Built to help you protect and improve your daily energy through small, consistent actions. Open it, log a few days, and see what the data shows you.
