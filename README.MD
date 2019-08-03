# Source Round Timer (Redux, Updated)

- This is an update of the [old tf2 round timer plugin](https://forums.alliedmods.net/showthread.php?p=1769674).
- Now *really* fully compatible with other source games.
- Fixed the classic annoying bug that made the timer disappear from the hud after a few rounds.

## cvars:
- cvar: `sm_roundtimer_enabled`: Enable Round Timer.
- cvar: `sm_roundtimer_time`: Round timer time.
- cvar: `sm_roundtimer_hud`: Enable displaying timer in hud.
- cvar: `sm_roundtimer_center`: Enable displaying timer in center text.
- cvar: `sm_roundtimer_yhud`: X hud position.
- cvar: `sm_roundtimer_xhud`: Y hud position.
- cvar: `sm_roundtimer_commands`: Command to execute when the timer ends, example: `"sm_say The round time has ended!; sm_slay @red;"`.
