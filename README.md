# TXON_01: Zingo Habit Tracker (Low-Fidelity Wireframes)

**TXON UI/UX Design Internship, Week 1**  
**Task:** Mobile App User Flow & Low-Fidelity Wireframes  
**Intern:** Zia Prasad

## Figma file

[View the Zingo wireframes in Figma](https://www.figma.com/design/qUSiKLaSMcLuPlimcjSbmY/TXON_01-Zingo-Wireframes?node-id=12-243&t=L6jWSGPM4DKtiHTK-1)

## Project idea

**Zingo** is a habit tracker with a friendly fox buddy. Users pick a few habits, check them off each day, and see their streak grow. The fox cheers them on, and a few side characters appear in specific moments (for example, a bunny that reminds users that rest days count).

The goal of this week is to plan structure, layout and flow only, so the wireframes are grayscale with placeholder boxes for the mascot and icons. Colors, illustrations and the component library come in Weeks 2 and 4.

## User persona

**Aarya, 19, college student**

- **Goal:** build a simple daily routine (drink water, read, exercise) without feeling overwhelmed.
- **Frustrations:** forgets habits after a few days, finds most trackers boring, feels guilty after a missed day.
- **Motivations:** quick wins, visible progress, friendly encouragement instead of pressure.
- **Behavior:** uses her phone one-handed, mostly in the morning and at night.

> "I start strong, but I lose motivation after a week."

Persona visual: [`persona/Zingo_Persona.webp`](persona/Zingo_Persona.webp).

## Task flow

**Onboarding** → **Home** → **Action** → **Confirmation**

1. Open app (Welcome)
2. Choose habits
3. Set reminder
4. Home (today's habits)
5. Tap a habit to complete it
6. Confirmation ("Great job! +10 XP")
7. Back to Home, then Progress, Rewards or Profile from the tab bar

Flow visual: [`flow/Zingo_Task_Flow.webp`](flow/Zingo_Task_Flow.webp).

## Screens

| # | Screen | Purpose |
|---|--------|---------|
| 01 | Welcome | Introduces the app and Zingo, with one clear action |
| 02 | Choose habits | Lets users pick a few habits quickly (step 2 of 3) |
| 03 | Set reminder | Finishes onboarding with a daily reminder time (step 3 of 3) |
| 04 | Home | Shows today's habits, streak and progress in one place |
| 05 | Complete a habit | Instant feedback after a check-off (progress bar and +10 XP) |
| 06 | Confirmation | Full-screen celebration that reinforces the habit loop |
| 07 | Progress | Weekly streak, chart and stats to show momentum |
| 08 | Rewards | XP, badges and items to unlock with XP |
| 09 | Profile | Stats and settings |
| 10 | Add habit | Bottom sheet for creating a new habit |
| 11 | Missed day | Gentle recovery screen: "Never miss twice" |

The screen exports will be added under `/screens` when they are available.

## Design decisions

- **Low fidelity on purpose:** grayscale only, boxes with an X for the mascot and images, so the focus stays on layout, spacing and content hierarchy.
- **Consistent navigation:** the bottom tab bar (Home, Stats, Rewards, Profile) sits in the same place on every main screen, and primary buttons keep the same size and position.
- **One clear action per screen:** each screen has one primary button or tap target.
- **Thumb-friendly:** main actions sit in the lower part of the screen, and tap targets are designed at 44px or larger on a 390x844 frame.
- **Progress indicators:** onboarding shows "Step 1 of 3" to "Step 3 of 3" so users know how long setup takes.
- **No-guilt tone:** a missed day shows a sleepy Zingo with an encouraging message and a streak freeze option, because Aarya feels guilty after a miss.
- **One mascot, a few side characters:** Zingo appears on the main screens, and side characters only where they add meaning.

## Tools

Figma, FigJam, GitHub

## Files included so far

- `persona/Zingo_Persona.webp` — persona visual.
- `flow/Zingo_Task_Flow.webp` — user-flow diagram.
- `docs/Zingo_Persona_and_Task_Flow.pdf` — combined two-page PDF of the persona and task flow.

The `/screens` PNG exports are not included yet and will be added later.

## What's next

- **Week 2:** mini UI style guide and reusable component kit
- **Week 4:** high-fidelity version and clickable prototype of these screens
