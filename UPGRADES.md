## Client Upgrades:
- [ ] 01: Integrate Live Camera Preview Stream for the Client. 
#
- [ ] 02: Integrate a valid signing certificate to bypass Play Protect. 
#
- [ ] 03: Integrate persistence for the AhMyth payload.
#
- [ ] 04: Integrate real-time viewing of victim device screens.
#
- [ ] 05: Integrate screen recording for real time viewing of victim device screens.
#
- [ ] 06: Integrate USSD dialing and response view feature for the 
AhMyth client
#
- [ ] 07: Integrate screenshot for real time viewing of victim device screens.
#
- [ ] 08: Integrate proper storage access for the client.
#
- [ ] 09: Implement notification listening, a feature from L3MON.
#
## Server Upgrades:

- [ ] 01: Figure out a new hook method for the new Bind On Launch functions.
#
- [x] 02: Create a backup copy of AhMyth's `AndroidManifest.xml`
file, and store it in the newly created backup directory 
`Vault` in order to restore AhMyth's original manifest file back to 
it's original state after being edited with custom permissions.

- DONE!
#
- [ ] 03: Explore other, more discrete options for the 
URL payload masker.
#
- [x] 04: Integrate the function to Log apktool.jar and sign.jar 
errors to a text file for the GUI version of AhMyth.

- DONE!
#
- [ ] 05: Restyle the AhMyth Server using the following

      1. Glassmorphism 
      2. Icons next to Tab Names ✔️
      3. Dark Theme 
      4. Light Theme
      5. High Contrast Theme
      6. Settings Tab for UI Theme preferences
      7. Payload Options Tab for when other payload options have been built into AhMyth.

#
- [ ] 06: Integrate an EXE Builder for an AhMyth Windows client.
#
- [ ] 07: Explore the possibility of adding Browser Hook feature 
to control a range of devices by hooking their web browser - inspired by [beEF](https://GitHub.com/beefproject/beef)
#
- [ ] 08: Update *socket.io 2.4.2* to *socket.io 4.x* (after updating the client with *socket.io-client java 2.0.1*)
#
- [ ] 09: Hijack a legitimate APK and configure it to be built as a standalone
AhMyth payload.
#
- [ ] 10: Integrate APK obfuscation to avoid the payload being decompiled after deployment.
#
- [ ] 12: Add High contrast theme
#
- [ ] 13: Add Dark Theme
#
- [ ] 14: Add Settings Menu to switch between UI themes