# anwb.nl demo site

Replica of the ANWB brand website for an Amplitude platform demo. Single static page with hash routing, no build step.

- Amplitude project 884501 (Analytics, Session Replay, Web Experiment, Guides & Surveys via the Unified Script)
- Energy quote funnel, EV charging card, smart home bundle configurator, Wegenwacht plans, insurance quote
- The QR code on the energy page carries the Amplitude web device id so the app session can be linked
- Set `appUrl` in `window.ANWB_CONFIG` to your published app demo URL

Deploy: GitHub > Settings > Pages > Deploy from branch `main`, folder `/ (root)`.
