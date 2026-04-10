# Akkio's Consume Helper

A buff and consumable tracking addon for Turtle WoW (WoW 1.12).

Now allows for buffs to be applied even if already active.

Keep in mind that timers will only show if the buff is applied through the addon. Applying buffs from bags or actionbars will not show any timer.

## Buff Status Bar

- **Configurable icon bar** — track any combination of buffs and consumables at a glance
- **Color-coded status** — icons turn red when missing
- **Countdown timers** — remaining duration displayed on each active consumable
- **One-click actions** — use a consumable, apply a weapon enchant, or request a buff from the group

## Shopping List

- **Stock tracking** — bags, bank, and mailbox
- **Color-coded status** — green (stocked), orange (bags low but bank/mail covers it), red (genuinely short) - editable thresholds
- **Crafting materials** — shown in the tooltip of each item

## Slash Commands

| Command | Action |
|---|---|
| `/act` or `/ach` | Open Select Buffs tab |
| `/actsettings` or `/achsettings` | Open Settings tab |
| `/actbuffstatus` or `/achbuffstatus` | Force refresh buff bar |
| `/actreset` or `/achreset` | Reset all settings to defaults |
| `/actwelcome` or `/achwelcome` | Show welcome screen |

## Installation

> If you previously had Akkio's Consume Helper installed, remove `Akkio_Consume_Helper.lua` and `Akkio_Consume_Helper.lua.bak` from:  
> `WTF/Account/<YOUR_ACC_NAME>/<YOUR_SERVER>/<YOUR_CHAR_NAME>/SavedVariables/`

1. Extract to `Interface/AddOns/`
2. Rename folder to `Akkio_Consume_Helper`
3. Restart the game
4. Click the minimap button or type `/act` or `/ach` to open the addon

---

*Created by Akkio for Turtle WoW 1.12*
