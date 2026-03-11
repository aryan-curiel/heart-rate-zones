# Heart Rate Zones

A single-page interactive calculator that computes personalized heart rate training zones using the **Karvonen Formula**.

**Live:** https://aryan-curiel.github.io/heart-rate-zones/

## What it does

Enter your age, resting heart rate, and fitness level to get your five training zones with exact BPM ranges:

| Zone | Name | Intensity |
|------|------|-----------|
| Z1 | Recovery / Active Rest | 50–65% HRR |
| Z2 | Aerobic Base / Fat Burn | 65–75% HRR |
| Z3 | Aerobic Tempo | 75–84% HRR |
| Z4 | Lactate Threshold | 84–93% HRR |
| Z5 | VO₂ Max / Neuromuscular | 93–100% HRR |

Each zone includes:
- When to use it
- How it should feel
- Training tips tailored to your fitness level
- Primary fuel source (fat vs. carbs ratio)

A **quick-reference table** and **level-specific training tips** (Beginner → Elite Athlete) are shown below the zone cards.

## Formula

Target HR = RHR + (HRR × % intensity)

Where **HRR** (Heart Rate Reserve) = Max HR − Resting HR, and Max HR is estimated as `220 − age`.

## Features

- Bilingual — English and Spanish
- Fitness levels: Beginner, Intermediate, Advanced, Athlete
- Input validation with inline error messages
- Animated flash feedback on recalculation
- Dark UI, fully responsive

## Usage

No build step. Open `src/index.html` directly in a browser, or visit the live GitHub Pages link above.
