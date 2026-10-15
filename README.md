# SuperSLX beta switch

Every SuperSLX Beta copy reads `switch.json` at launch and every 6 hours. Set a round to `"off"` to end it:

```json
{ "beta-1": "off", "message": "The beta round is over.", "demoUrl": "https://superslx.com" }
```

Off ends that round on every copy at its next check (projects are never deleted). A round not listed counts as on.

The ended screen reads "This beta has ended", thanks the tester, shows `message`, and has a **Get the SuperSLX demo** button. `demoUrl` (optional, https only) is where that button goes — point it at the demo page once it exists. A copy remembers the last good `demoUrl` even offline; with none ever set the button opens `https://superslx.com`.
