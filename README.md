# Time-Meridian

A personal time toolkit that lives entirely in your browser — a local clock, a world clock, alarms, a stopwatch, and a timer, all in one page, styled after a brass-and-navy instrument panel.

There's no sign-up, no server, and no app store. Time-Meridian is a single HTML file: open it in a browser and it works. Your accent color, background, sounds, and alarms are remembered on your own device via the browser's local storage — nothing is ever sent anywhere.

## Features

- **Clock** — an analog + digital view of your device's local time.
- **World Clock** — add the cities you care about and see their current time at a glance.
- **Alarm** — set alarms with custom repeat days and snooze length.
- **Stopwatch** — time yourself down to the hundredth of a second, with lap tracking.
- **Timer** — a countdown timer, including an **Exam Timer** mode that schedules itself to start automatically at a time you choose.
- **Appearance** — customize the accent color, set a background photo, and adjust the size of each section.
- **Custom sounds** — upload your own sound files for alarms, the stopwatch, and the timer.
- **Installable** — add it to your phone or computer's home screen/dock as its own app (PWA).

## Getting Started

Time-Meridian doesn't need a build step, a server, or any dependencies. Just open `index.html` in a browser:

```bash
git clone https://github.com/<your-username>/<your-repo>.git
cd <your-repo>
open index.html   # or just double-click the file
```

To host it on the web (for example with GitHub Pages), commit `index.html` and enable Pages on the repository — no build process required.

## Installing as an App

Once the page is live on the web, it can be installed like a native app:

- **iPhone / iPad (Safari):** Share button → *Add to Home Screen*.
- **Android (Chrome):** ⋮ menu → *Install app* (or *Add to Home screen*).
- **Mac / Windows (Chrome/Edge):** Click the install icon in the address bar, or the browser menu → *Install Time-Meridian*.

## Privacy

Time-Meridian is a self-contained, offline-first web page. It doesn't connect to any server, collect any data, or require an account. Settings and alarms are stored only in your browser's local storage on your own device.

## Tech

A single `index.html` file containing all HTML, CSS, and JavaScript — no frameworks, no build tools, no external requests at runtime.
