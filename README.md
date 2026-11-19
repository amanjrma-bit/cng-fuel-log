# Mofat CNG Log

Mofat CNG Log is the phone app for Mofat CNG station pump attendants: log each bus (arrival, pump in/out, pump, kg, odometer, km, route), record pump meter readings, and send Excel reports on WhatsApp.

**Open it:** https://amanjrma-bit.github.io/cng-fuel-log/

- Works offline after the first open. Data stays on each phone.
- Android: open in Chrome, tap **Install app** (or ⋮ → **Add to Home screen**).
- iPhone: open in Safari, tap **Share** → **Add to Home Screen**, then open **Mofat CNG Log** from the home screen.

## What's in it

- Log each bus: arrival, pump in/out, pump, KG (with a built-in calculator), odometer (KM worked out from the bus's last reading), route.
- Fleet list with each bus's morning and afternoon shift drivers and usual route; the form fills in the driver for the time of day and warns about bus numbers not on the list.
- KM per KG on every fill, plus Reports: month dashboard, buses, drivers, routes.
- Search any bus or driver across all dates.
- Pump meter readings for pumps 1–4 with the attendant at each pump, checked against the logged KG.
- Excel in the office master layout (one sheet per date, day and night shifts, Lake vs Mofat check, odometer column, pump attendants), with BUS SUMMARY and DRIVER SUMMARY sheets in the month file.
- English and Kiswahili. Mofat colours.

The link preview on WhatsApp uses `og-image.jpg`.

## Updating

Replace `index.html`, and change the version in `sw.js` (`CACHE`) and in `index.html` (`BUILD`) to the same new value, so installed phones fetch the new version and show the **Update** button.
