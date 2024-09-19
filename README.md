# Aggressor-NTFY

Cobalt Strike beacon notifications using the [NTFY](https://ntfy.sh) app.

Runs in headless mode with [agscript](https://hstechdocs.helpsystems.com/manuals/cobaltstrike/current/userguide/content/topics_aggressor-scripts/as_intro3_headless-cobalt-strike.htm) to ensure consistent notification delivery.

![ntfy](https://github.com/user-attachments/assets/56b22263-2684-4369-ac62-41e73afae200)

## Instructions

1. Save `Aggressor-NTFY.cna` to your Cobalt Strike teamserver.
2. Run: `./agscript [cs-ip] [cs-port] NTFY [cs-password] Aggressor-NTFY.cna`
3. View generated subscription in Event Log: `/ntfy view` (or set with `/ntfy set`)
4. Add the subscription to your NTFY app (iOS, Android, Desktop).
5. Test with: `/ntfy test`
