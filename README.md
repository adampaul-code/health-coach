# Health Coach

A simple, calm, single-file web app to help you build better daily energy.

It focuses on the things that actually move the needle for you:
- Sleep quality and consistency
- Alcohol-free days
- Gut support through real food
- Your supplement stack (especially milk thistle)
- Steady nutrition without overcomplicating things

Everything lives in **one HTML file**. No accounts, no internet required after saving it, and all your data stays private on your device.

## How to Use

1. Download `index.html`
2. Open it in any browser (Chrome, Safari, Firefox, Edge)
3. It works completely offline

That's it.

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

- All data is stored locally in your browser using `localStorage`.
- Nothing is sent to any server.
- Close the tab or delete the file and your data is gone.
- You can export everything anytime.

## Resetting Your Data

Open the app and type this in the browser console (F12 → Console tab):

```js
localStorage.removeItem('hc_v4');
location.reload();
```

## Why This Version?

This is a refined hybrid that keeps things **quick to use every day** while still giving you useful insights. It has a calm dark interface, strong but not overwhelming personalisation, and makes it easy to see the connection between your habits (especially alcohol-free days and probiotic foods) and how you feel.

## Tech

- Single self-contained HTML file
- Tailwind CSS via CDN + custom dark theme
- No build step, no frameworks, no dependencies

Perfect for personal use or lightweight sharing.

---

Built to help you protect and improve your daily energy through small, consistent actions. Open it, log a few days, and see what the data shows you.
