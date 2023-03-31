## <div align="center"><ins>Stability Updates</ins></div>

- [ ] 01: Merge Client Upgrades from [@HiddenPirates](https://github.com/HiddenPirates)
#
- [ ] 02: Fix the App List feature in [@HiddenPirates](https://github.com/HiddenPirates) client work so that AhMyth users are successfully able to view a list of the Victims installed apps from the victims lab
#
- [ ] 03. Stabilise the SMS feature by adding the ability to view sent SMS's in an `Outbox SMS` sub-tab next to a separate `Inbox SMS` sub-tab when using the Victims Lab's SMS feature, a small example of this can be seen below.
```
|--| SMS | <== Main Tab
|----| Send an SMS || SMS List | <== Sub Tab
|---------------------| Inbox || Outbox | <== two seperate sub-tabs for inbox and outbox messages once the sms list sub-tab is clicked 
```
#
- [ ] 04: Implement the `REQUEST_IGNORE_BATTERY_OPTIMISATION` manifest permission in such a way where it wont be replaced when using the `Custom Permissions` feature.
#
- [ ] 05: Add *Zipalign* for 32bit linux based operating systems as well as the JavaScript code to execute it before signing.
#
- [x] 06: write a JavaScript function with `fs.readdir` so AhMyth is able to read an Apk folder and determine how many `"smali_classes**"` folders we have present in order to create a new one for the AhMyth payload files to be copied into instead of copying them to the same smali folder containing the path to the Launcher Activity.
- Done ✅ 
#
- [ ] 07: Build an Android Client Manager with Victims Lab access so users can at least have some sort of AhMyth functionality on Android
