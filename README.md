# VØRIX Ride for iPhone

## Download the app

**[Download VORIX-Ride.ipa](https://github.com/SpecB1111/apex-speed/raw/refs/heads/main/VORIX-Ride.ipa)**

This link always points to the latest successfully built app in this repository. Failed builds leave the previous installer available. See BUILD-INFO.json for its version and build details.

Save the IPA to Files on your iPhone. Keep AltServer running on your Windows PC, then open AltStore → My Apps → + and select the IPA. Choose **Keep App Extensions** for Dynamic Island. Install over the existing app using the same Apple Account; do not delete it first if you want to keep your history.

Features include GPS speed, automatic signal-quality adjustment, Dynamic Island, acceleration estimates, session history, and calibrated estimated phone lean. Calibrate while parked with the bike upright and the phone securely mounted. Lean readings run while the app is open and are not certified motorcycle lean measurements.

## Updates

The Xcode source project is in ApexSpeed.zip. Updating that archive on main automatically runs the Swift tests, builds the app and extension on a hosted Mac, then replaces VORIX-Ride.ipa here. You still install each update through AltStore; the installed app does not update itself.
