# Safely App - Secure APK Distribution

> **Download Here:** https://safely-apk.netlify.app/
> **PIN:** 2026

This repository contains the secure, interactive landing page designed for distributing the **Safely App** Android package (APK) directly to authorized users.

## 🔒 Core Features

* **Secure PIN Obfuscation:** Access to the direct APK download link is protected behind a native Base64 frontend authentication system to prevent casual inspection or unauthorized hotlinking.
* **Smooth UX Transitions:** Upon entering the correct PIN, the instruction texts and input fields smoothly fade out and shrink vertically, keeping the container dimensions anchored.
* **Animated Download Action:** Features a sleek CSS slide-up and fade-in entry animation (`slideUpFadeIn`) that brings the download CTA button dynamically into focus.
* **Smart Device Detection:** Dynamically evaluates the user's platform (iOS, macOS, Windows) using user-agent parsing and displays a persistent real-time warning layout to guide non-Android users.
* **Blink Indicator:** Employs fluid CSS keyframe blinking (`It's right where you got this link.`) for essential user onboarding.

## 🛠️ Built With
* **HTML5:** Clean semantic markup structure.
* **CSS3:** Keyframe animations, cubic-bezier transitions, and dark-mode container layout.
* **Vanilla JavaScript:** Clean DOM manipulation, native string encoding (`btoa`), and device platform evaluation.