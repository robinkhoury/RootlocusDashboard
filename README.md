# Root Locus Lab

An interactive dashboard for learning the root locus method, built for ELEN 350: Control Systems.

**Live site:** open `index.html`, or visit the GitHub Pages link for this repository.

## Features
- Formula bar: type G(s) = K·N(s)/D(s) with slots for s^n, (s + a)^m and (s² + bs + c)^m
- Interactive s-plane: drag, add and erase poles and zeros; pan and zoom
- Gain slider with an animated K sweep and a live stability indicator
- Construction rules computed for your system: real-axis segments, asymptotes, breakaway/break-in points, jω crossings with a Routh array, and departure/arrival angles
- Guided build and quiz modes
- Angle/magnitude-condition probe
- Closed-loop step response (RK4) with %OS, Tp, Ts, Tr and steady-state error
- Design mode: %OS and Ts specs shaded on the s-plane, with the K that meets the ζ line

## Running it
No installation. Open `index.html` in any modern browser, or use the GitHub Pages site.
All math is implemented in plain JavaScript in this single file; the only external resource is Google Fonts.
