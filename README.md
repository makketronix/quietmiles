# Quiet Miles

A privacy-first running and walking tracker for Android. No accounts, no ads, no analytics: your runs stay on your phone.

<img src="docs/screenshot.png" alt="Quiet Miles during a run: time, distance, pace, speed and calories, an interval workout banner, and history charts" width="320" align="right">

Quiet Miles is one screen. Press **Go**, run, press **End**. It measures time, distance, pace, speed and calories from GPS, coaches you through pace limits and interval workouts with sounds and vibration, and charts your history. Nothing is sent to a server.

<br clear="right">

## Note: The Demo version does not hvae coaching

## Features

### Tracking
- **Live stats:** elapsed time, distance, current pace, speed and calories.
- **Accurate distance:** inaccurate GPS readings, jitter and impossible jumps are filtered out.
- **Works with the screen off:** lock your phone and put it in your pocket. A notification shows while a run is recording, and nothing is lost while the screen is off.
- **Run controls:** Go, Pause, Continue, Lap and End. Movement while paused doesn't count.
- **Auto lap:** a lap every 1 km or 1 mile, timed to the exact moment you cross it.
- **Screen stays awake** during a run, if you want to watch it.

### Coaching
- **Pace limit:** tap the pace card to set a limit, either "faster than" or "slower than". You get urgent beeps when you cross it, reminders while you stay over, and a chime once you're back within it.
- **Interval workouts:** build workouts like *3:00 @ 5:30/km, 1:00 @ 7:00/km × 5*. A beep marks each new interval, and distinct "too fast" and "too slow" sounds tell you when you drift off target. A banner shows the current interval, the time left and whether you're on pace.
- **No false alarms:** brief GPS wobbles don't set off alerts, and each new interval gives you a few seconds to settle into the pace.
- **Sounds and vibration** work with the screen locked, and briefly lower your music like navigation prompts do.

### You and your units
- **Age and weight** are set with odometer-style rolling digit wheels (drag, flick or tap). They're used to estimate calories.
- **Units:** tap the distance or speed card to switch between km and miles, and tap the weight unit to switch between kg and lb.

### History
- **Every run is saved** with its date, duration, distance, calories and laps.
- **Charts** of distance and time for your recent sessions, with totals and tap-for-details.
- **Table view** of all your sessions.
- **Clear data** deletes all history, after a confirmation.

### Map (optional)
- **Off by default.** Turning on **Show map** first explains what it means for your privacy, and only loads the map if you agree.
- **Map:** [OpenFreeMap](https://openfreemap.org) (free, no tracking cookies) shows your position and route.
- **Your choice is remembered**, and turning the map off stops it completely.

## Privacy

- **No accounts:** no sign-in, no ads, no analytics, no crash reporting, no tracking.
- **Your data stays on your phone:** run history and settings are stored only on your device. They are not backed up to the cloud or copied to other devices.
- **Your route is not stored:** GPS is only used to measure distance, and only the totals are saved.
- **No Google Play services:** location comes straight from your phone's GPS.
- **The map is the only thing that uses the internet,** and only if you turn it on. Because the map downloads the area around you, OpenFreeMap could infer your approximate location from those requests.

The full privacy policy and open-source licenses are available inside the app, at the bottom of the screen.

## Tips

- **Tracking stops while the phone is locked?** Some phones (notably Xiaomi, Huawei and some Samsung models) stop apps in the background to save battery. Exempt Quiet Miles from battery optimization in your phone's settings.
- **Calories are an estimate** based on your speed, weight and age, not a medical measurement.

## Credits

Built with [Leaflet](https://leafletjs.com), [MapLibre](https://maplibre.org) and [Capacitor](https://capacitorjs.com). Map data © [OpenStreetMap](https://www.openstreetmap.org/copyright) contributors, served by [OpenFreeMap](https://openfreemap.org).
