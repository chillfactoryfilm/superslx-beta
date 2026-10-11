# SuperSLX beta switch

Every SuperSLX Beta copy reads `switch.json` at launch and every 6 hours. Set a round to `"off"` to end it:

```json
{ "beta-1": "off", "message": "Round one is over — thank you!" }
```

Off ends that round on every copy at its next check (projects are never deleted). A round not listed counts as on.
