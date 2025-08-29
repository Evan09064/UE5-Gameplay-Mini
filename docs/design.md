# Design notes (WIP)
- Character: grounded/air control, dash with cooldown & invulnerability frames (tunable), double-jump with coyote time.
- Interactables: pickup (ammo/health placeholder), interface `IUsable`.
- AI: Guard with perception (LOS check), states via BT: Patrol → Investigate(lastSeen) → Chase → Search.
- Debug: F1 HUD showing state/cooldowns; gizmos for LOS/lastSeen.
