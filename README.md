# Heart of Racing / AMR – ALMS Driver Debrief

Mobile-friendly post-event driver feedback form for Heart of Racing / Aston Martin Racing.

Current event version: **Paul Ricard 2026/27**

This is the ALMS version of the existing WEC driver-debrief app. It intentionally keeps the same visual design, mobile workflow, autosave behaviour, car-feedback checklist, balance controls and engineer-email workflow.

## Series

**Asian Le Mans Series (ALMS)**

## Current circuit

**Circuit Paul Ricard**

The supplied Paul Ricard track map is embedded directly inside `index.html`.

The balance debrief contains all numbered corners shown on the supplied map:

- T1
- T2
- T3
- T4
- T5
- T6
- T7
- T8
- T9
- T10
- T11
- T12
- T13
- T14
- T15

Each corner has the same four balance inputs as the WEC app:

- Brake
- Turn-in
- Mid-corner
- Exit

Scale:

`US5 ← Neutral → OS5`

## Files

- `index.html` – complete self-contained driver-debrief app
- `README.md` – repository / GitHub Pages instructions

No build process, server, npm package or app installation is required.

## GitHub Pages setup

1. Create a new GitHub repository, for example `HoR_ALMS_DriverDebrief`.
2. Upload `index.html` and `README.md` into the root of the repository.
3. Open **Settings → Pages**.
4. Under **Build and deployment**, select **Deploy from a branch**.
5. Select branch **main**.
6. Select folder **/(root)**.
7. Save.

GitHub Pages will publish the site automatically.

The address will normally be similar to:

`https://YOURUSERNAME.github.io/HoR_ALMS_DriverDebrief/`

## Driver workflow

1. Open the GitHub Pages link.
2. Select driver and car.
3. Complete the session feedback.
4. Tap through the large **OK / Issue / N/A** buttons in Car Feedback.
5. Add comments only where useful.
6. Complete the Paul Ricard T1–T15 balance sliders.
7. Complete the weekend conclusions.
8. Scroll to the bottom and press **Send to Engineers**.

## Email workflow

The same WEC email workflow is retained.

On mobile, **Send to Engineers** opens the default mail application.

On laptop/desktop, drivers can choose:

- Gmail Web
- Outlook Web
- Default Mail App
- Copy Full Email

The subject and engineer report are generated automatically from the completed form.

## Saved drafts

This ALMS Paul Ricard version uses its own browser storage key:

`hor_alms_paul_ricard_2026_27_driver_debrief_v1`

This means WEC / Monza / Barcelona / Fuji saved drafts will not populate the ALMS form.

The **Clear** button removes only the current ALMS Paul Ricard draft.

## Updating for another ALMS event

For the next event, replace `index.html` with the new event version and use a new event-specific local-storage key. GitHub Pages will redeploy automatically after the commit.
